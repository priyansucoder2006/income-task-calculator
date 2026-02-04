# 💸 Income Tax Calculator

A simple, clean, and beginner‑friendly **Income Tax Calculator** built using **HTML, CSS, and JavaScript**. This project calculates total tax based on income slabs and instantly displays the result without reloading the page.

Perfect for learning **DOM manipulation**, **event handling**, and **basic business logic in JavaScript**.

---

## ✨ Features

* 📥 User-friendly income input
* 🧮 Automatic tax calculation based on slabs
* ⚡ Instant result using JavaScript (no page reload)
* 🎨 Clean and responsive UI with CSS
* 🧹 Form resets automatically after submission

---

## 🛠️ Tech Stack

* **HTML5** – Structure of the application
* **CSS3** – Styling and layout
* **JavaScript (Vanilla)** – Logic, DOM manipulation, and event handling

---

## 📊 Tax Slabs Logic

| Income Range          | Tax Rate |
| --------------------- | -------- |
| Up to 1,200,000       | 0%       |
| 1,200,001 – 1,600,000 | 15%      |
| 1,600,001 – 2,000,000 | 20%      |
| 2,000,001 – 2,400,000 | 25%      |
| Above 2,400,000       | 30%      |

Tax is calculated progressively based on these slabs.

---

## 🚀 How It Works

1. User enters their annual income
2. Form submission is intercepted using `preventDefault()`
3. JavaScript calculates tax based on predefined slabs
4. Total tax is displayed instantly on the page
5. Form resets for the next calculation

---

## 📂 Project Structure

```
├── index.html
└── script.js
```

---

## 🧠 Key JavaScript Concepts Used

* `addEventListener()`
* `preventDefault()`
* DOM selection & manipulation
* Conditional logic (`if / else if`)
* Form handling

---

## 🌱 Future Improvements

* 💱 Currency formatting
* 📈 Tax breakdown per slab
* 🌓 Dark mode
* 📱 Improved mobile responsiveness
* ✅ Input validation messages

---

## 📸 Preview

*Add a screenshot or GIF of your project here for extra polish.*

---

## 🤝 Contributing

Feel free to fork this repository and submit pull requests. Suggestions and improvements are always welcome!

---

## 📄 License

This project is open-source and available under the **MIT License**.

---

### ⭐ If you found this helpful, give it a star and keep building amazing things!

Happy coding 🚀
