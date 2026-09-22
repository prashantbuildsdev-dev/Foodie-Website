# 🛒 Responsive Shopping Cart Website

A modern and responsive shopping website built using **HTML, CSS, and JavaScript**.
This project includes a dynamic product section, responsive navigation, Swiper slider, and a fully functional shopping cart.
LIVE DEMO : https://prashantbuildsdev-dev.github.io/Foodie-Website/
## 🚀 Features

* 📱 Fully Responsive Design
* 🛍️ Dynamic Product Cards
* 🛒 Add to Cart Functionality
* ➕ Increase Product Quantity
* ➖ Decrease Product Quantity
* 💰 Automatic Cart Total Calculation
* 🔢 Automatic Cart Item Count
* ❌ Remove Product from Cart
* 📊 Dynamic Product Data using `products.json`
* 🍔 Responsive Hamburger Menu
* 🔄 Swiper.js Image/Product Slider
* ✨ Smooth Cart Item Removal Animation
* 🚫 Prevents Duplicate Products in Cart

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript**
* **Swiper.js**
* **Font Awesome**
* **JSON**

## 📂 Project Structure

```text
responsive-shopping-cart/
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

Products are stored in a `products.json` file and loaded dynamically using JavaScript:

```javascript
fetch('products.json')
```

The product information is then displayed as product cards on the webpage.

### 2. Add to Cart

When the user clicks **Add to Cart**, the selected product is added to the cart.

The project also checks whether the product is already in the cart to prevent duplicate items.

### 3. Quantity Management

Users can increase or decrease the quantity of a product using the **+** and **−** buttons.

The product price is automatically updated according to the selected quantity.

### 4. Cart Total

The website automatically calculates:

* Total quantity of products
* Total price of products

```javascript
updateTotals();
```

### 5. Responsive Navigation

A hamburger menu is included for smaller screens, making the website easier to use on mobile devices.

## 📸 Project Preview

Add your project screenshots here:

```markdown
![Project Screenshot](images/screenshot.png)
```

## ▶️ How to Run

1. Clone this repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

2. Open the project folder.

3. Run the project using **VS Code Live Server** or another local server.

4. Open the website in your browser.

> **Note:** Since the project loads `products.json` using `fetch()`, running it through a local server such as Live Server is recommended instead of directly opening `index.html`.

## 🎯 What I Learned

While building this project, I practiced:

* DOM Manipulation
* JavaScript Events
* Arrays and Objects
* `find()` and `filter()` methods
* Fetch API
* JSON Data Handling
* Dynamic HTML Creation
* Event Listeners
* Responsive Navigation
* Shopping Cart Logic
* Price and Quantity Calculations
* Swiper.js Integration

## 🔮 Future Improvements

* User Login & Registration
* Product Search
* Category Filtering
* Product Details Page
* Wishlist Functionality
* LocalStorage Cart
* Checkout Page
* Backend Integration
* Database Integration
* Online Payment Integration

## 👨‍💻 Author

**Prashant Kumar**

B.Tech CSE Student | Frontend Developer | Learning DSA & MERN Stack Development | Backend Development

---

LinkedIn: https://www.linkedin.com/in/%20prashant-kumar-4a9bb7352%20Vanity%20URL%20name


⭐ If you like this project, consider giving it a **star** on GitHub!
