# Artisan Woods - E-Commerce Website

A clean, inviting, and highly functional multi-product e-commerce website built with traditional HTML and CSS, focused on selling handcrafted woodworking items with extensibility for other product categories.

## 🎨 Design Aesthetic

### Color Palette
- **Primary Backgrounds**: Soft warm off-whites (#FAF8F5), light creams, subtle greys (#F2F2F2)
- **Primary Text**: Rich dark browns (#3A2A1A), deep charcoal (#333333)
- **Accent Colors**: 
  - Muted Ochre/Mustard (#B8860B) - Primary accent
  - Deep Sage Green (#6B8E23) - Secondary accent
  - Terracotta/Burnt Orange (#C85A3B) - Warning/special elements
- **Secondary Text**: Medium warm grey (#888888)

### Typography
- **Headings**: Montserrat (clean, modern sans-serif)
- **Body Text**: Open Sans (highly readable sans-serif)
- **Line Height**: 1.6em to 1.8em for optimal readability

### Visual Principles
- **Craftsmanship & Quality**: Highlighting handmade nature
- **Warmth & Authenticity**: Natural materials aesthetic
- **Clarity & Ease of Use**: Intuitive navigation
- **Timeless Appeal**: Classic, enduring design

## 📁 Project Structure

```
ecom/
├── index.html              # Homepage
├── shop.html              # Product catalog with filtering
├── product.html           # Product detail page
├── about.html             # Company story and values
├── css/
│   ├── styles.css         # Main stylesheet
│   ├── shop.css          # Shop-specific styles
│   └── product.css       # Product page styles
└── images/               # Product and content images
    ├── hero-woodwork.jpg
    ├── category-*.jpg
    ├── product-*.jpg
    └── team-*.jpg
```

## 🏠 Page Overview

### Homepage (index.html)
- **Hero Section**: Full-width showcase with compelling headline
- **Featured Categories**: 4 product categories (Woodwork, Pottery, Textiles, Metalwork)
- **New Arrivals**: Product carousel with ratings and quick actions
- **About Snippet**: Brief company introduction
- **Testimonials**: Customer reviews
- **Newsletter Signup**: Email collection

### Shop Page (shop.html)
- **Sidebar Filters**: Categories, price range, materials, availability
- **Product Grid**: Responsive grid with hover effects
- **Product Cards**: Images, ratings, prices, quick actions
- **View Toggle**: Grid/list view options
- **Sorting**: Multiple sort options
- **Pagination**: Clean page navigation

### Product Detail (product.html)
- **Image Gallery**: Main image with thumbnail navigation
- **Product Information**: Title, rating, price, description
- **Product Options**: Size and finish selection
- **Add to Cart**: Quantity selector and purchase buttons
- **Tabbed Content**: Description, specifications, care, reviews
- **Related Products**: Suggested items

### About Page (about.html)
- **Company Story**: Heritage and values
- **Process Overview**: 4-step crafting process
- **Team Profiles**: Key artisan introductions
- **Value Propositions**: Quality commitments

## 🛠 Technical Features

### CSS Architecture
- **Mobile-First Responsive Design**: Breakpoints at 480px, 768px, 1024px
- **CSS Grid & Flexbox**: Modern layout techniques
- **Custom Properties**: Consistent color and spacing system
- **Semantic HTML5**: Accessible markup structure
- **No External Frameworks**: Pure HTML/CSS implementation

### Interactive Elements
- **Dropdown Navigation**: Hover-activated category menus
- **Product Image Gallery**: JavaScript-powered image switching
- **Tabbed Content**: Dynamic tab navigation
- **Quantity Controls**: Increment/decrement buttons
- **Filter Checkboxes**: Product filtering interface
- **Responsive Navigation**: Mobile-friendly menu system

### Performance Optimizations
- **Optimized Images**: Responsive image sizing
- **CSS Transitions**: Smooth hover effects
- **Minimal JavaScript**: Essential functionality only
- **Efficient Selectors**: Performance-conscious CSS

## 🎯 Key Design Features

### Product Cards
- High-quality product images
- Star ratings with review counts
- Hover effects revealing quick actions
- Consistent pricing display
- Category badges and product status indicators

### Navigation
- Sticky header with search and cart icons
- Dropdown menus for product categories
- Breadcrumb navigation
- Clear visual hierarchy

### Forms & Interactions
- Newsletter signup with validation styling
- Product option selection (size, finish)
- Quantity selectors with +/- buttons
- Review and rating displays

### Responsive Design
- **Desktop (1024px+)**: Full sidebar, multi-column grids
- **Tablet (768px-1024px)**: Adapted layouts, compressed navigation
- **Mobile (480px-768px)**: Single column, stacked elements
- **Small Mobile (<480px)**: Minimal UI, essential features only

## 🌱 Extensibility

### Adding New Product Categories
1. Add category to navigation dropdown menus
2. Create category-specific filter options
3. Add category badges and styling
4. Update product cards with new category data attributes

### Customization Options
- **Color Scheme**: Modify CSS custom properties
- **Typography**: Update font imports and font-family declarations
- **Layout**: Adjust grid template columns and gap properties
- **Imagery**: Replace placeholder images with actual product photos

## 📱 Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- CSS Grid and Flexbox support required
- JavaScript ES6+ for interactive features
- Responsive design for all screen sizes

## 🚀 Getting Started

1. **Setup**: Place all files in a web server directory
2. **Images**: Add product images to the `/images` folder
3. **Content**: Update product information in HTML files
4. **Styling**: Customize colors and fonts in CSS files
5. **Testing**: Verify responsive behavior across devices

## 📈 Future Enhancements

- Shopping cart functionality
- User authentication
- Product search with autocomplete
- Wishlist management
- Order tracking
- Custom product configurator
- Advanced filtering (price range sliders)
- Product zoom functionality
- Customer review submission

---

**Note**: This is a static HTML/CSS implementation. For full e-commerce functionality, integrate with a backend system for cart management, payment processing, and order fulfillment.
