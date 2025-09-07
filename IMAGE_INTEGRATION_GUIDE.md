# Image Integration Guide for UzOPay

## 📁 Directory Structure Created

```
uzopay/
├── public/
│   ├── images/
│   │   ├── hero/           # Hero section images (robot, backgrounds)
│   │   ├── features/       # Feature icons and illustrations
│   │   ├── testimonials/   # Customer photos and avatars
│   │   ├── logos/          # Company logos and brand assets
│   │   └── README.md       # Image usage instructions
│   └── index.html
└── src/
    └── components/
        ├── Hero.js         # Updated with image integration example
        └── ImageExample.js # Complete usage examples
```

## 🖼️ How to Add Images

### Step 1: Add Your Images
Place your images in the appropriate folders:
- **Robot image**: `/public/images/hero/uzopay-robot.png`
- **Feature icons**: `/public/images/features/icon-name.svg`
- **Customer photos**: `/public/images/testimonials/customer-name.jpg`
- **Logos**: `/public/images/logos/company-logo.svg`

### Step 2: Use Images in Components

#### Method 1: Direct Path (Recommended)
```jsx
<img 
  src="/images/hero/uzopay-robot.png" 
  alt="UzOPay Robot" 
  className="w-full max-w-md h-auto"
/>
```

#### Method 2: Dynamic Path
```jsx
const imagePath = `${process.env.PUBLIC_URL}/images/hero/robot.png`;
<img src={imagePath} alt="Robot" />
```

#### Method 3: With Error Handling
```jsx
<img 
  src="/images/hero/uzopay-robot.png" 
  alt="UzOPay Robot" 
  className="w-full max-w-md h-auto"
  onError={(e) => {
    e.target.style.display = 'none';
    e.target.nextSibling.style.display = 'block';
  }}
/>
<div style={{ display: 'none' }}>Fallback content</div>
```

## 🎯 Current Hero Component Setup

Your Hero component is now ready to display a robot image. Simply:

1. **Add your robot image** to `/public/images/hero/uzopay-robot.png`
2. **The component will automatically display it**
3. **If image doesn't exist**, it shows a placeholder with instructions

## 📝 Example Usage in Other Components

### Feature Icons
```jsx
// In Features.js
<img 
  src="/images/features/security-icon.svg" 
  alt="Security Feature" 
  className="w-12 h-12"
/>
```

### Customer Testimonials
```jsx
// In Testimonials.js
<img 
  src="/images/testimonials/sarah-johnson.jpg" 
  alt="Sarah Johnson" 
  className="w-16 h-16 rounded-full object-cover"
/>
```

### Company Logos
```jsx
// In Header.js or Footer.js
<img 
  src="/images/logos/uzopay-logo.svg" 
  alt="UzOPay Logo" 
  className="h-8 w-auto"
/>
```

## 🚀 Quick Start

1. **Add your robot image**:
   ```
   Place your robot image at: /public/images/hero/uzopay-robot.png
   ```

2. **Test the application**:
   ```bash
   npm start
   ```

3. **The Hero section will show your robot image** automatically!

## 📋 Image Optimization Tips

- **Format**: Use PNG for photos, SVG for icons
- **Size**: Compress images for web (use tools like TinyPNG)
- **Naming**: Use descriptive names with hyphens
- **Alt text**: Always include meaningful alt attributes

## 🔧 Troubleshooting

### Image Not Showing?
1. Check the file path is correct
2. Ensure image is in `/public/images/` folder
3. Verify the file name matches exactly
4. Check browser console for 404 errors

### Need Different Image Sizes?
Create responsive images:
```jsx
<picture>
  <source media="(min-width: 768px)" srcSet="/images/hero/robot-desktop.png" />
  <source media="(min-width: 480px)" srcSet="/images/hero/robot-tablet.png" />
  <img src="/images/hero/robot-mobile.png" alt="Robot" />
</picture>
```

## 📞 Next Steps

1. Add your robot image to `/public/images/hero/uzopay-robot.png`
2. Replace placeholder images in other components as needed
3. Optimize images for web performance
4. Test on different devices and screen sizes
