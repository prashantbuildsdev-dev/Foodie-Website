# 🛒 Food Cart Website

A responsive and interactive **Food Cart Website** built using **HTML, CSS, and JavaScript**.
The website provides a smooth shopping experience with product cards, a dynamic shopping cart, quantity management, image slider, and responsive mobile navigation.

## 🚀 Live Demo

🔗 **Live Demo:** https://prashantbuildsdev-dev.github.io/Foodie-Website/

## 💼 LinkedIn

🔗 **LinkedIn:** https://www.linkedin.com/in/%20prashant-kumar-4a9bb7352%20Vanity%20URL%20name

## 📌 Features

* 🛍️ Product listing with dynamic product cards
* ➕ Add products to cart
* 🚫 Prevents duplicate products from being added
* ➕ Increase product quantity
* ➖ Decrease product quantity
* 🗑️ Remove product from cart
* 💰 Automatically calculates cart total
* 🔢 Displays total number of items in cart
* 🖼️ Swiper image/product slider
* 📱 Responsive mobile navigation menu
* 🍔 Hamburger menu for mobile devices
* ✨ Interactive cart sidebar
* 📦 Products loaded dynamically from `products.json`
* 📱 Responsive design for different screen sizes

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript
* Swiper.js
* Font Awesome
* JSON

## 📂 Project Structure

```text
Food-Cart/
│
├── index.html
├── style.css
├── script.js
├── products.json
│
├── images/
│   └── product images
│
└── README.md
```

## ⚙️ How It Works

### 1. Product Loading

Products are stored inside `products.json` and loaded dynamically using JavaScript's `fetch()` method.

```javascript
fetch('products.json')
  .then(response => response.json())
  .then(data => {
      productList = data;
      showCards();
  });
```

### 2. Add to Cart

When the user clicks **Add to Cart**, the selected product is added to the cart.

The application also checks whether the product is already present in the cart to prevent duplicate entries.

### 3. Quantity Management

Users can increase or decrease the quantity of products using the **+** and **−** buttons.

The item price is automatically updated according to the selected quantity.

### 4. Cart Total

The website automatically calculates:

* Total quantity of products
* Total cart price

```javascript
cartTotal.textContent = `$${totalPrice.toFixed(2)}`;
cartValue.textContent = totalQuantity;
```

### 5. Responsive Navigation

A hamburger menu is provided for mobile devices.
Clicking the hamburger icon opens and closes the mobile navigation menu.

### 6. Swiper Slider

The website uses **Swiper.js** to create a smooth and interactive product/image slider.

```javascript
var swiper = new Swiper(".mySwiper", {
    loop: true,
    navigation: {
        nextEl: "#next",
        prevEl: "#prev",
    },
});
```

## 🎯 Main JavaScript Functionality

The project uses JavaScript to handle:

* Product rendering
* Shopping cart functionality
* Quantity updates
* Price calculation
* Product removal
* Mobile menu
* Cart sidebar
* Swiper navigation
* Dynamic JSON data

## 💡 What I Learned

While building this project, I practiced:

* DOM manipulation
* JavaScript event listeners
* Arrays and objects
* `fetch()` API
* JSON data handling
* Dynamic HTML creation
* Cart management logic
* Responsive navigation
* Working with third-party JavaScript libraries
* Basic frontend project structure

## 🔮 Future Improvements

Some features that can be added in the future:

* 🔐 User authentication
* 💳 Online payment integration
* ❤️ Wishlist functionality
* 🔎 Product search
* 🏷️ Product categories and filters
* 💾 LocalStorage cart persistence
* 📦 Order tracking
* 🌐 Backend integration

## 👨‍💻 Author

**Prashant Singh**

B.Tech CSE Student | C++ & DSA | HTML | CSS | JavaScript | MERN Stack Developer



## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
