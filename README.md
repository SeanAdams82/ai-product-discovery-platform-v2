# AI Product Discovery Hub

Discover the best deals across multiple platforms with AI-powered product analysis and price comparison

## Features

- 🛍️ Modern, responsive e-commerce storefront
- 🔍 Advanced search and filtering
- 💰 Price comparison across multiple retailers
- 📱 Mobile-first responsive design
- ⚡ Fast loading and optimized performance
- 🏷️ Affiliate marketing ready
- 📊 Analytics tracking ready
- 🌍 Worldwide legal compliance

## Deployment

This website is ready to deploy on:

### GitHub Pages
1. Go to your repository settings
2. Navigate to "Pages" section
3. Select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Your site will be available at: `https://SeanAdams82.github.io/ai-product-discovery-platform-v2/`

### Netlify
1. Connect your GitHub repository to Netlify
2. Build settings: Leave empty (static site)
3. Publish directory: `/` (root)
4. Deploy automatically on push

### Vercel
1. Import your GitHub repository to Vercel
2. Framework Preset: "Other"
3. Build and Output Settings: Leave default
4. Deploy automatically on push

## Customization

### Colors
Update the CSS custom properties in `styles.css`:
```css
:root {
    --primary-color: #3b82f6;
    --secondary-color: #64748b;
    --accent-color: #f59e0b;
}
```

### Products
Modify the `sampleProducts` array in `script.js` to add your own products.

### Affiliate Links
Update the `trackClick` function in `script.js` to redirect to your affiliate links.

## Legal Compliance

This website includes:
- Affiliate marketing disclaimer
- Privacy policy placeholder
- Terms of service placeholder
- Cookie policy placeholder

⚠️ **Important**: Update all legal pages with your specific terms and comply with local regulations (GDPR, CCPA, etc.).

## File Structure

```
/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── package.json        # Project metadata
└── README.md          # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Optimized images with lazy loading
- Minimal dependencies
- CSS Grid and Flexbox for layouts
- Mobile-first responsive design

## License

MIT License - feel free to use this for your projects!

---

**Affiliate Disclaimer**: This website contains affiliate links. We may earn a commission if you make a purchase through these links at no additional cost to you. All prices and availability are subject to change.