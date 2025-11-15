# ROVI - Fashion Website

**Discover and Find Your Own Fashion**

A complete fashion e-commerce website built with HTML, CSS, and JavaScript. Features a modern, elegant design with full admin panel for content management.

## Features

### User Features
- **Homepage** - Beautiful hero section with customizable content
- **Product Catalog** - Browse products by category with filtering
- **Product Details** - Detailed product pages with add to cart functionality
- **Shopping Cart** - Full cart management with quantity updates
- **Checkout** - Complete checkout process with order creation
- **About & Contact** - Informational pages

### Admin Features
- **Dashboard** - Analytics overview with charts showing:
  - Total Revenue
  - Total Orders
  - Pending Orders
  - Total Products
  - Sales trends (last 6 months)
  - Order status distribution
- **Product Management** - Add, edit, and delete products
- **Order Tracking** - View and manage orders with status updates
- **Content Management** - Customize:
  - Hero section (image, title, description)
  - About section text
  - Brand showcase logos

## File Structure

```
rovi/
├── user/                  # User-facing pages
│   ├── index.html        # Homepage
│   ├── products.html     # Product catalog
│   ├── product-detail.html
│   ├── cart.html
│   ├── checkout.html
│   ├── about.html
│   └── contact.html
├── admin/                 # Admin panel
│   ├── index.html        # Dashboard
│   ├── products.html     # Product management
│   ├── orders.html       # Order tracking
│   └── content.html      # Content management
├── assets/
│   ├── css/
│   │   └── style.css    # Main stylesheet
│   └── js/
│       └── data.js       # Data management (localStorage)
├── photos/               # Image assets
│   ├── hero.jpg
│   ├── heronobg.png
│   └── Kretya Studio.jpg
└── README.md
```

## Getting Started

1. **Open the Website**
   - Navigate to `user/index.html` in your browser to view the homepage
   - Navigate to `admin/index.html` to access the admin panel

2. **Admin Access**
   - No login required (for demo purposes)
   - Access admin panel at `admin/index.html`

3. **Data Storage**
   - All data is stored in browser localStorage
   - Data persists between sessions
   - To reset: Clear browser localStorage

## Usage Guide

### For Users

1. **Browse Products**
   - Visit the Products page
   - Use category filters to find items
   - Click on any product to view details

2. **Shopping**
   - Add products to cart from product detail pages
   - View cart and adjust quantities
   - Proceed to checkout to place orders

### For Admins

1. **Dashboard**
   - View real-time analytics and statistics
   - Monitor sales trends and order statuses

2. **Manage Products**
   - Click "Add New Product" to create products
   - Edit existing products
   - Delete products as needed
   - Upload images by placing them in `photos/` folder and using relative paths

3. **Track Orders**
   - View all customer orders
   - Update order status (Pending, Processing, Completed, Cancelled)
   - View detailed order information

4. **Customize Content**
   - Update hero section image, title, and description
   - Edit about page content
   - Manage brand showcase logos
   - All changes reflect immediately on the user site

## Image Management

To add custom images:

1. Place image files in the `photos/` folder
2. In admin panel, use relative paths like:
   - `../photos/your-image.jpg`
   - `../photos/your-image.png`
3. The system will preview images before saving

## Design Features

- **Modern UI** - Clean, elegant design inspired by luxury fashion brands
- **Responsive** - Works on desktop, tablet, and mobile devices
- **Typography** - Playfair Display (serif) for headings, Poppins (sans-serif) for body
- **Color Scheme** - Brown/beige tones with elegant accents
- **Animations** - Smooth transitions and hover effects

## Technologies Used

- **HTML5** - Semantic structure
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript** - Interactivity and data management
- **Chart.js** - Analytics charts (via CDN)
- **Google Fonts** - Typography
- **localStorage** - Client-side data persistence

## Browser Compatibility

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## Notes

- This is a front-end only application using localStorage for data storage
- No backend server required
- Data is stored locally in the browser
- Perfect for demonstrations and prototypes
- Can be extended with a backend API for production use

## Customization

All styling can be customized in `assets/css/style.css`:
- Color scheme (CSS variables in `:root`)
- Typography
- Layout and spacing
- Component styles

## Support

For issues or questions, refer to the code comments or modify the files as needed.

---

**ROVI** - Discover and Find Your Own Fashion

