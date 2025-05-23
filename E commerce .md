# 🛍️ Modern E-Commerce Website

A visually modern, responsive, and fully interactive **e-commerce website** built using **HTML**, **Tailwind CSS**, and **JavaScript**. This project features a dynamic product catalog, animated hero sections, filtering by categories, dark mode support, and more.

## 📌 Features

- 🌟 **Hero Section** with a call to action and smooth scroll navigation
- 🎯 **Category Filtering** for products (Clothing, Accessories, Electronics)
- 🛒 **Add to Cart** functionality with animated feedback
- 🌙 **Dark Mode Toggle** using CSS variables
- 🖼️ **Product Carousel** for featured items
- 🔍 **Responsive Search Bar**
- 📱 **Mobile-Optimized Layout** with collapsible menu
- ⚡ **Loading Spinner** for initial page load
- 🎨 **Modern UI** with gradients, animations, and hover effects
- 💬 **Quick View** tooltips for detailed product info

---

## 🚀 Tech Stack

| Technology     | Purpose                        |
|----------------|--------------------------------|
| HTML5          | Structure of the website       |
| Tailwind CSS   | Utility-first responsive design |
| JavaScript     | Dynamic behaviors & interactivity |
| Remix Icons    | Icon set used across the UI    |
| Google Fonts   | Custom typography (Pacifico)   |

---

## 📖 Code Overview

### 1. `index.html`
- Contains the entire layout: header, hero, product grid, carousel, and footer.
- Elements are divided into semantic sections: `#home`, `#featured`, `#products`, `#collections`, `#contact`.

### 2. **Tailwind CSS**
- Tailwind is used via CDN (`tailwindcss.com`) with custom theme configurations (e.g., colors, border radius).
- Utility classes make responsive design effortless.

### 3. **JavaScript Features**
- **Menu & Search Toggle**: Enables mobile menu and search bar interactions.
- **Add to Cart**: Adds products dynamically using `data-id`, `data-name`, `data-price`, and `data-image`.
- **Dark Mode Toggle**: Toggles a class (`dark-mode`) on the `body` using CSS variables.
- **Carousel Logic**: Translates the `carousel-track` on navigation.
- **Quick View Popups**: Extracts detailed info from `data-` attributes.
- **Animations**: Includes fade-in effects, bounce scroll indicators, and toast notifications.

---

## 🛠️ Customization

- ✏️ Change product data inside the `.product-card` sections.
- 🎨 Customize your theme colors via the Tailwind config object.
- 🧠 Add backend integration for:
  - Persistent cart (via `localStorage`, Firebase, etc.)
  - Checkout functionality
  - User authentication

---

## 🧩 Future Improvements

- [ ] Add payment gateway integration (e.g., Stripe)
- [ ] Implement user login/signup
- [ ] Add product search autocomplete
- [ ] Optimize images using `srcset`
- [ ] Add filters (price, brand, rating)

---

## 🤝 Contribution

1. Fork the repository 🍴
2. Clone your forked repo:
   ```bash
   git clone https://github.com/your-username/modern-ecommerce.git
