# UzoPay - React.js Payment Platform

A modern, responsive payment platform built with React.js and Tailwind CSS. This project replicates a professional payment solution interface with clean design, accessibility features, and responsive layouts.

## 🚀 Features

- **Modern React Architecture**: Built with functional components and React hooks
- **Responsive Design**: Mobile-first approach with Tailwind CSS breakpoints
- **Accessibility**: WCAG compliant with semantic HTML and ARIA attributes
- **Interactive Components**: Hover, focus, and active states throughout
- **Reusable Components**: Modular component structure for easy maintenance
- **Performance Optimized**: Optimized for fast loading and smooth interactions

## 🛠️ Tech Stack

- **React.js 18** - Modern React with hooks
- **Tailwind CSS 3** - Utility-first CSS framework
- **PostCSS** - CSS processing
- **Autoprefixer** - CSS vendor prefixing

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd uzopay
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000` to view the application.

## 🏗️ Project Structure

```
uzopay/
├── public/
│   └── index.html          # HTML template
├── src/
│   ├── components/         # React components
│   │   ├── Header.js      # Navigation header
│   │   ├── Hero.js        # Hero section
│   │   ├── Features.js    # Features showcase
│   │   ├── Stats.js       # Statistics section
│   │   ├── Testimonials.js # Customer testimonials
│   │   ├── CTA.js         # Call-to-action section
│   │   └── Footer.js      # Footer component
│   ├── App.js             # Main application component
│   ├── index.js           # Application entry point
│   └── index.css          # Global styles and Tailwind imports
├── package.json           # Dependencies and scripts
├── tailwind.config.js     # Tailwind CSS configuration
├── postcss.config.js      # PostCSS configuration
└── README.md              # Project documentation
```

## 🎨 Components Overview

### Header
- Responsive navigation with mobile menu
- Logo and brand identity
- Call-to-action buttons
- Accessible keyboard navigation

### Hero
- Eye-catching headline with gradient text
- Call-to-action buttons with icons
- Trust indicators and company logos
- Mock dashboard visualization

### Features
- Grid layout showcasing key features
- Icon-based feature cards
- Hover effects and animations
- Responsive breakpoints

### Stats
- Impressive statistics display
- Gradient background
- Trust badges and compliance indicators
- Animated counters (ready for implementation)

### Testimonials
- Customer testimonial carousel
- Navigation controls and indicators
- Customer photos and ratings
- Smooth transitions

### CTA (Call-to-Action)
- Conversion-focused design
- Multiple action buttons
- Trust indicators
- Feature highlights

### Footer
- Comprehensive link organization
- Social media links
- Newsletter signup
- Legal and compliance links

## 🎯 Key Features

### Responsive Design
- **Mobile First**: Optimized for mobile devices
- **Breakpoints**: 
  - `xs`: 475px
  - `sm`: 640px
  - `md`: 768px
  - `lg`: 1024px
  - `xl`: 1280px
  - `2xl`: 1536px

### Accessibility
- **Semantic HTML**: Proper use of HTML5 semantic elements
- **ARIA Labels**: Screen reader support
- **Keyboard Navigation**: Full keyboard accessibility
- **Focus Management**: Visible focus indicators
- **Color Contrast**: WCAG compliant color schemes

### Performance
- **Optimized Images**: Placeholder images with proper sizing
- **CSS Optimization**: Tailwind CSS purging
- **Component Structure**: Efficient React component architecture

## 🎨 Design System

### Colors
- **Primary**: Blue gradient palette
- **Secondary**: Gray scale palette
- **Accent**: Success, warning, error states
- **Neutral**: Background and text colors

### Typography
- **Font Family**: Inter (Google Fonts)
- **Weights**: 300, 400, 500, 600, 700, 800
- **Scales**: Responsive typography scales

### Spacing
- **Consistent**: 4px base unit system
- **Responsive**: Adaptive spacing across breakpoints

## 🔧 Customization

### Adding New Components
1. Create component file in `src/components/`
2. Import and use in `App.js`
3. Follow existing component patterns

### Styling Modifications
1. Update `tailwind.config.js` for theme changes
2. Modify `src/index.css` for custom utilities
3. Use Tailwind classes in components

### Adding API Integration
- Components are structured for easy API integration
- State management ready for data fetching
- Placeholder content can be replaced with real data

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🚀 Deployment

### Build for Production
```bash
npm run build
```

### Deploy to Netlify
1. Connect your repository to Netlify
2. Set build command: `npm run build`
3. Set publish directory: `build`

### Deploy to Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run: `vercel`
3. Follow the prompts

## 📄 License

This project is licensed under the MIT License.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📞 Support

For questions or support, please contact the development team.

---

**Built with ❤️ using React.js and Tailwind CSS**
