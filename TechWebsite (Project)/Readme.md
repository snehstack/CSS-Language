# 🛍️ Digi Tech — Modern E-Commerce Website

A modern and responsive **electronics e-commerce website** built using **HTML5 and CSS3**. Digi Tech provides a clean, attractive, and user-friendly interface for browsing technology products such as smartphones, smartwatches, cameras, accessories, and speakers.

The project focuses on **responsive web design, modern UI, CSS Grid, Flexbox, product filtering, promotional banners, hover effects, and mobile-friendly layouts**.
---

## 📸 Screenshots

### 🖥️ Desktop View

![Digi Tech Desktop](Assets/screenshots/desktop.png)

### 💻 Tablet View

![Digi Tech Tablet](Assets/screenshots/tablet.png)

### 📱 Mobile View

![Digi Tech Mobile](Assets/screenshots/mobile.png)

---

## 🎥 Video Demo

### Website Walkthrough

[![Digi Tech Website Demo](Assets/screenshots/video-thumbnail.png)](https://your-video-link.com)

> 🎬 The video demonstrates the website layout, navigation, promotional banners, product filtering, product cards, hover effects, and responsive design.

---

## ✨ Features

### 🧭 Navigation Header

* Digi Tech brand logo
* Search bar
* User profile icon
* Wishlist icon
* Shopping bag/cart icon
* Item counters
* Product navigation menu
* Shop, About, Contact and Blog links
* Special discount offer

The header contains the main branding, search functionality, account actions, navigation, and promotional offer area.

---

### 🎯 Hero & Promotional Banners

The website includes attractive promotional banners for different products:

* 🍎 Apple HomePod 2nd Gen
* ⌚ Apple Watch
* 📷 Samsung Gear Camera
* 🎧 Beats Studio Buds
* 📸 Hero Camera

Each banner includes product information, images, and a **Shop Now** call-to-action.

---

## 🛒 Trending Products

The website contains a **Trending Products** section with category-based filtering.

### Product Categories

* 🛍️ All
* 📱 Mobile
* ⌚ Watch
* 📷 Camera
* 🎧 Accessories
* 🔊 Speaker

The category filter is implemented using **HTML radio buttons and CSS selectors**, so JavaScript is not required for the basic filtering functionality.

---

## 📦 Products

| Category       | Product           | Price |
| -------------- | ----------------- | ----: |
| 📱 Mobile      | Galaxy S26 Ultra  |  $999 |
| 📱 Mobile      | iPhone 16 Pro     | $1199 |
| ⌚ Watch        | Apple Watch Ultra |  $699 |
| ⌚ Watch        | Galaxy Watch 6    |  $499 |
| 📷 Camera      | Canon DSLR        |  $850 |
| 📷 Camera      | Sony Alpha        |  $950 |
| 🎧 Accessories | Wireless Charger  |   $49 |
| 🎧 Accessories | Power Bank        |   $79 |
| 🔊 Speaker     | Apple HomePod     |  $299 |
| 🔊 Speaker     | JBL Charge 5      |  $199 |

Each product card contains an image, stock status, product name, price, rating, and an **Order Now** button.

---

## 📱 Responsive Design

Digi Tech is designed to work across desktop, tablet, and mobile devices.

### Responsive Breakpoints

| Screen Width | Layout                             |
| ------------ | ---------------------------------- |
| `1200px`     | Adjusted banner and product layout |
| `992px`      | Tablet-style layout                |
| `768px`      | Smaller tablet/mobile layout       |
| `576px`      | Mobile layout                      |
| `480px`      | Small mobile layout                |

### Product Grid

```text
Desktop        → 5 columns
≤ 1200px       → 4 columns
≤ 992px        → 3 columns
≤ 768px        → 2 columns
≤ 576px        → 1 column
```

The responsive CSS adjusts the navigation, banners, product grid, typography, spacing, images, and footer according to the screen size.

---

## 🎨 Design

The website uses a modern electronics-store design featuring:

* Clean white background
* Dark footer
* Blue primary color
* Gradient promotional banners
* Rounded corners
* Product cards
* Box shadows
* Hover animations
* Responsive typography
* Font Awesome icons

### Primary Color

```css
#2d2bb6
```

---

## 🛠️ Technologies Used

### HTML5

Used for:

* Website structure
* Header
* Navigation
* Banner sections
* Product section
* Footer
* Semantic page organization

### CSS3

Used for:

* Flexbox
* CSS Grid
* Media queries
* Gradients
* Transitions
* Hover effects
* Responsive layouts
* Product filtering
* Styling and animations

### Font Awesome

Used for icons such as:

* 🔍 Search
* 👤 User
* ❤️ Wishlist
* 🛍️ Shopping bag
* ⭐ Rating
* 📍 Location
* 📞 Phone
* ✉️ Email
* Social media icons

Font Awesome is loaded through its CDN in the project.

---

## 📂 Project Structure

```text
Digi-Tech/
│
├── index.html
│
├── css/
│   ├── style.css
│   └── media.css
│
├── Assets/
│   ├── image/
│   │   ├── Apple-HomePod.webp
│   │   ├── Apple-Watch.png
│   │   ├── Samsung-Gear-Camera.png
│   │   ├── Beats-Studio-Buds.png
│   │   ├── Hero-Camera.png
│   │   ├── mobile-1.png
│   │   ├── mobile-2.webp
│   │   ├── watch-1.png
│   │   ├── watch-2.jpeg
│   │   ├── camera-1.png
│   │   ├── camera-2.png
│   │   ├── accessories-1.png
│   │   ├── accessories-2.png
│   │   ├── speaker-1.png
│   │   └── speaker-2.png
│   │
│   └── screenshots/
│       ├── desktop.png
│       ├── tablet.png
│       ├── mobile.png
│       └── video-thumbnail.png
│
└── README.md
```

The HTML references separate stylesheet files and product/banner assets from the `Assets/image` directory.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/digi-tech.git
```

### 2. Open the Project

```bash
cd digi-tech
```

### 3. Run the Website

Open `index.html` in your browser.

For development, you can use **VS Code + Live Server**.

---

## 🎯 CSS Product Filtering

One of the main features of the project is the CSS-only product filtering system.

The project uses hidden radio buttons:

```html
<input type="radio" name="filter" id="all-products" checked hidden>
<input type="radio" name="filter" id="mobile-products" hidden>
<input type="radio" name="filter" id="watch-products" hidden>
<input type="radio" name="filter" id="camera-products" hidden>
```

Category labels are connected to these inputs:

```html
<label for="all-products">All</label>
<label for="mobile-products">Mobile</label>
<label for="watch-products">Watch</label>
<label for="camera-products">Camera</label>
```

CSS selectors then control which products are visible.

**No JavaScript is required for this filtering system.**

---

## 💡 Project Highlights

* ✅ Modern e-commerce UI
* ✅ Fully responsive design
* ✅ CSS Grid
* ✅ CSS Flexbox
* ✅ CSS-only product filtering
* ✅ Product cards
* ✅ Promotional banners
* ✅ Hover animations
* ✅ Responsive navigation
* ✅ Mobile-friendly layout
* ✅ Font Awesome icons
* ✅ Clean and organized CSS
* ✅ No JavaScript required

---

## 🔮 Future Improvements

The following features can be added in future versions:

* [ ] Functional search bar
* [ ] JavaScript shopping cart
* [ ] Wishlist functionality
* [ ] Product details page
* [ ] Product sorting
* [ ] Price filtering
* [ ] User authentication
* [ ] Checkout page
* [ ] Payment gateway
* [ ] Backend integration
* [ ] Database integration
* [ ] Product API
* [ ] Dark mode
* [ ] Admin dashboard
* [ ] User reviews and ratings

---

## 📚 What I Learned

Through this project, I practiced and improved my knowledge of:

* HTML5
* CSS3
* CSS Grid
* Flexbox
* Media Queries
* Responsive Web Design
* CSS Selectors
* CSS Transitions
* Hover Effects
* Product Card Design
* Navigation Design
* E-Commerce UI Design
* CSS-only Filtering
* Website Structure
* Mobile-first considerations

---

## 👨‍💻 Author

### Sneh Patel

**Frontend / Full Stack Developer**

Designed and developed with ❤️ using **HTML5 & CSS3**.

---

## 📬 Contact

📍 **Location:** Surat, Gujarat, India
📞 **Phone:** +91 98765 43210
📧 **Email:** [digitech@gmail.com](mailto:digitech@gmail.com)

---

## 📄 License

This project is created for **learning, practice, and portfolio purposes**.

You are free to use and modify the code for educational and personal projects.

---

## ⭐ Support

If you like this project, please consider giving the repository a ⭐ **Star** on GitHub.

---

**Made with ❤️ by Sneh Patel**
