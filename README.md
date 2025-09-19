# Amazon Clone

A fully functional e-commerce website that replicates the core features of Amazon's shopping experience. Built with vanilla JavaScript, HTML5, and CSS3, this project demonstrates modern web development practices and responsive design principles.

## Features

### Core Shopping Experience
- **Product Catalog**: Browse through a comprehensive collection of products across multiple categories
- **Advanced Search**: Real-time search functionality with keyword filtering
- **Product Details**: Detailed product information including ratings, pricing, and descriptions
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### Shopping Cart Management
- **Add to Cart**: Seamless product addition with quantity selection
- **Cart Updates**: Real-time cart quantity updates and price calculations
- **Item Management**: Update quantities, remove items, and manage your cart
- **Persistent Storage**: Cart data persists across browser sessions

### Checkout & Orders
- **Flexible Shipping**: Multiple delivery options with varying costs and timeframes
- **Order Summary**: Comprehensive pricing breakdown including taxes and shipping
- **Order Processing**: Complete checkout flow with order placement
- **Order History**: Track and review past purchases

### Additional Features
- **Buy Again**: Quick reordering from order history
- **Mobile Navigation**: Hamburger menu for mobile users
- **Visual Feedback**: Interactive elements with hover effects and loading states
- **Date Calculations**: Dynamic delivery date calculations using Day.js

## Live Demo

Experience the live application: **[Amazon Clone Live](https://ecommerce-website-nine-hazel.vercel.app/)**

## Project Structure

```
Amazon-Clone/
├── index.html              # Main homepage
├── cart.html               # Shopping cart/checkout page
├── orders.html             # Order history page
├── scripts/
│   ├── main.js             # Homepage functionality & product rendering
│   ├── cart.js             # Cart page logic & checkout flow
│   ├── checkout.js         # Shopping cart class & core functionality
│   ├── orders.js           # Order history management
│   └── products.js         # Product data & product class
├── styles/
│   ├── style.css           # Global styles & header/navigation
│   ├── main.css            # Homepage product grid & responsive design
│   ├── cart.css            # Shopping cart & checkout styling
│   └── orders.css          # Order history page styling
├── images/
│   ├── products/           # Product images
│   └── [other icons]       # UI icons & logos
└── README.md               # Project documentation
```

## Technologies Used

### Frontend Technologies
- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Flexbox, Grid, and responsive design
- **Vanilla JavaScript (ES6+)**: Core functionality with classes and modules
- **Local Storage API**: Data persistence
- **Day.js**: Date manipulation and formatting

### Development Practices
- **Modular Architecture**: ES6 modules for code organization
- **Object-Oriented Programming**: Classes for better code structure
- **Responsive Design**: Mobile-first approach
- **Event-Driven Programming**: Dynamic user interactions

## Installation & Setup

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional but recommended)

### Local Development Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/amazon-clone.git
   cd amazon-clone
   ```

2. **Option A: Using Live Server (Recommended)**
   
   If you have VS Code with Live Server extension:
   - Open the project folder in VS Code
   - Right-click on `index.html`
   - Select "Open with Live Server"
   - The application will open at `http://127.0.0.1:5500`

3. **Option B: Using Python HTTP Server**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   ```
   Then visit `http://localhost:8000`

4. **Option C: Using Node.js HTTP Server**
   ```bash
   # Install globally
   npm install -g http-server
   
   # Start server
   http-server
   ```
   Then visit `http://localhost:8080`

5. **Option D: Direct File Access**
   - Simply double-click `index.html`
   - **Note**: Some features may not work due to CORS restrictions

### Deployment

This project is deployed on **Vercel** and is accessible at:
**[https://ecommerce-website-nine-hazel.vercel.app/](https://ecommerce-website-nine-hazel.vercel.app/)**

To deploy your own version:

1. **Fork this repository**
2. **Connect to Vercel**:
   - Visit [vercel.com](https://vercel.com)
   - Import your forked repository
   - Deploy with default settings
3. **Alternative deployment platforms**:
   - **Netlify**: Drag and drop the project folder
   - **GitHub Pages**: Enable in repository settings
   - **Firebase Hosting**: Use Firebase CLI

## Usage Guide

### Homepage Navigation
1. **Browse Products**: Scroll through the product grid
2. **Search**: Use the search bar to find specific items
3. **Add to Cart**: Select quantity and click "Add to Cart"
4. **Mobile Menu**: Tap the hamburger menu on mobile devices

### Shopping Cart
1. **View Cart**: Click the cart icon to access your cart
2. **Update Quantities**: Use the "Update" link to modify item quantities
3. **Remove Items**: Click "Delete" to remove items from cart
4. **Select Shipping**: Choose from multiple delivery options
5. **Place Order**: Review summary and place your order

### Order Management
1. **View Orders**: Access order history from the navigation
2. **Reorder**: Use "Buy it again" for quick reordering
3. **Track Details**: Review order dates, totals, and delivery information



##  Quick Links

-  **[Live Demo](https://ecommerce-website-nine-hazel.vercel.app/)**
-  **[GitHub Repository](https://github.com/your-username/amazon-clone)**
-  **[Report Issues](https://github.com/your-username/amazon-clone/issues)**
-  **[Discussions](https://github.com/your-username/amazon-clone/discussions)**

