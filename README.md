# Freyr - Premium Hoodies E-Commerce Website

A modern, responsive e-commerce website for selling premium hoodies.

## Features

- 🛍️ **Product Catalog**: Browse through a collection of premium hoodies
- 🛒 **Shopping Cart**: Add items to cart, update quantities, and remove items
- 📱 **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- 🎨 **Modern UI/UX**: Beautiful, clean interface with smooth animations
- ⚡ **Fast & Lightweight**: Pure HTML, CSS, and JavaScript - no frameworks required

## Getting Started

1. **Open** `index.html` in your web browser
2. That's it! No build process or dependencies required.

## File Structure

```
freyr-website/
├── index.html      # Main HTML structure
├── styles.css      # All styling and responsive design
├── script.js       # Cart functionality and interactivity
└── README.md       # This file
```

## Features in Detail

### Product Display
- Grid layout showcasing all available hoodies
- Product cards with images, descriptions, and prices
- Hover effects for better user interaction

### Shopping Cart
- Sidebar cart that slides in from the right
- Add/remove items
- Update quantities
- Real-time total calculation
- Empty cart state handling

### Design Highlights
- Modern color scheme with gold accents
- Smooth animations and transitions
- Professional typography using Inter font
- Sticky navigation header
- Hero section with call-to-action

## Customization

### Adding Products
Edit the `products` array in `script.js`:

```javascript
const products = [
    {
        id: 1,
        name: "Your Product Name",
        description: "Product description",
        price: 59.99,
        image: "👕"
    },
    // Add more products...
];
```

### Changing Colors
Modify the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #1a1a1a;
    --accent-color: #d4af37;
    /* ... */
}
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Future Enhancements

Potential features to add:
- Product detail pages
- User authentication
- Payment integration
- Product search and filtering
- Customer reviews
- Wishlist functionality

## License

This project is open source and available for personal and commercial use.

---

Built with ❤️ for Freyr

