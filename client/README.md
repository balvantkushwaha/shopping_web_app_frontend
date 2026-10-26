# BLACK STUDIO - Premium Men's Fashion E-commerce

## Setup Instructions

### 1. Install dependencies
\`\`\`bash
npm install
\`\`\`

### 2. Run development server
\`\`\`bash
npm run dev
\`\`\`

### 3. Build for production
\`\`\`bash
npm run build
\`\`\`

## Features

- ✅ Modern responsive design
- ✅ Product listing with filters
- ✅ Search functionality
- ✅ Shopping cart
- ✅ Wishlist
- ✅ Checkout with OTP verification
- ✅ Admin panel
- ✅ Mobile-friendly bottom navigation
- ✅ Product details with size/color selection
- ✅ Category-wise product display
- ✅ Hero slider
- ✅ Product sliders

## Admin Access

- Admin Mobile: XXXXXXXXXX
- OTP: XXXX

## Tech Stack

- React 18
- Redux Toolkit
- React Router v6
- CSS Modules
- Swiper.js
- Lucide Icons

## Folder Structure

<pre>
src/
├── assets/          # Images, icons, CSS files
├── components/      # Reusable components
│   ├── common/      # Buttons, loaders, modals
│   ├── layout/      # Navbar, Footer, Sidebar
│   └── products/    # ProductCard, ProductList
├── pages/           # Home, Login, Register, Cart
├── data/            # Dummy data
├── redux/           # State management
│   └── slices/      # Auth, Cart, Product
├── routes/          # Routing configuration
├── services/        # API calls
├── App.jsx          # Main app component
├── main.jsx         # Entry point
└── index.css        # Global styles
</pre>

## Future Backend Integration

The code is structured to easily integrate with a backend API:

1. Replace dummy data in `/data` with API calls
2. Update Redux slices for async actions
3. Add API service layer in `/services`
4. Implement JWT authentication
5. Connect to MongoDB

## License

Private - All rights reserved
