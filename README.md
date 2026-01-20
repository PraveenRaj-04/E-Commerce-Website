# 👗 Online Dress Shopping Website

An interactive e-commerce platform designed for online dress shopping with full shopping workflow including authentication, product selection, wallet system, crypto payments, and payment receipt generation. The website is fully front-end based and uses **Local Storage** to persist user data across pages.

---

## 🚀 Features

### 🧑‍💻 User Account System
- Login page
- Signup page
- Local Storage authentication (no backend needed)
- Session handling via Local Storage

### 🛍️ Product & Shopping Workflow
- Product listing on **index.html**
- Add to Cart Functionality
- Buy Now option
- Quantity updates
- Discount/offers support

### 💼 Wallet System
- Pre-loaded wallet balance
- Deduct balance during purchase
- Shows remaining balance after transaction
- Stored using Local Storage

### 💳 Multiple Payment Methods
- Crypto payment (simulated)
- Wallet payment
- INR payment
- Payment confirmation
- Payment receipt page

### 📄 Receipt & Confirmation
- Receipt displays:
  ✔ Product name  
  ✔ Size  
  ✔ Quantity  
  ✔ Price  
  ✔ Total amount  
  ✔ Payment method  
- Thank You page after checkout

### 📞 Contact & Support
- Contact page for user queries
- Form submission stored locally

---

## 🧱 Project File Structure

```
📂 PROJECT ROOT
 ├── index.html
 ├── login.html
 ├── signup.html
 ├── buy-now.html
 ├── wallet.html
 ├── add-to-cart.html
 ├── crypto-payment.html
 ├── payment.html
 ├── payment-receipt.html
 ├── thank-you.html
 ├── contact.html
 ├── style.css
 ├── script.js
 └── assets (images/icons)
```

---

## 🛠️ Tech Stack Used

| Layer | Technology |
|-------|------------|
| Frontend | HTML, CSS, JavaScript |
| Storage | Local Storage (Browser API) |
| Payment Simulation | Wallet + Crypto + INR |
| Deployment | Browser Based |

---

## 🗂️ Local Storage Usage

The project uses `localStorage` for:

✔ User Login Data  
✔ Wallet Balance Data  
✔ Cart Items  
✔ Purchased Item Details  
✔ Authentication Status  
✔ Payment Method Chosen  
✔ Receipt Data  

Example usage:

```js
localStorage.setItem("walletBalance", 5000);
localStorage.getItem("walletBalance");
```

---

## 🛒 Shopping Flow Diagram

```
index → add-to-cart → buy-now → payment → receipt → thank-you
```

---

## 🔐 Authentication Flow

```
signup → login → index (session active)
```

---

## 💼 Wallet Flow

```
wallet → buy-now → payment deduction → receipt → updated wallet balance
```

---

## 🪙 Crypto Payment Flow

```
buy-now → crypto-payment → simulate success → receipt
```

---

## 🧩 Step-by-Step Running Instructions

1. Download or clone repo
2. Open `index.html` in browser
3. Signup a new user
4. Login with the created account
5. Browse products & Add to Cart
6. Click Buy Now
7. Choose payment method:
   - Wallet
   - Crypto
   - INR
8. Complete payment
9. View Payment Receipt
10. Redirected to Thank You page

---

## 📷 Screenshots (Optional section)

_Add here:_
- Home Page
- Product Page
- Login & Signup
- Cart Page
- Wallet Page
- Payment Page
- Receipt Page
- Thank You Page

---

## 🎯 Future Scope / Improvements

- Backend and database integration
- Razorpay/Crypto real payment gateway
- Admin Dashboard for product management
- Order history tracking
- Email invoice system
- Multi-user support

---

## 🙌 Credits

Developed by: **Praveen Raj**  
Location: India  
Status: Mini Project (E-commerce Frontend)

---

## 📄 License

This project is free to use for educational purposes.
