# 🔐 Secure Password Generator

Welcome to the **Secure Password Generator** — a minimalist, responsive, and fully interactive web application built using HTML, CSS, and JavaScript. It lets users create highly secure passwords based on customizable criteria including length, character types, and more.

This project features real-time password strength analysis, light/dark theme toggling with persistence, and instant copy-to-clipboard functionality. Whether you're building a new account or upgrading old credentials, this tool offers simplicity, utility, and speed.

---

## 📚 Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [UI Overview](#ui-overview)
- [Code Structure](#code-structure)
- [How It Works](#how-it-works)
- [Customization Guide](#customization-guide)

---

## 🚀 Features

| Feature                     | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| 🎛 Password Settings       | Users can select password length and which character types to include.     |
| 📋 Copy Button             | One-click button to copy the password to the clipboard.                     |
| 📊 Strength Indicator      | Visual strength bar (Weak, Medium, Strong) based on password content.       |
| 🌙 Theme Toggle            | Switch between light and dark modes, stored in `localStorage`.             |
| 🧠 Intelligent Generation  | Uses JavaScript to combine selected character types securely.               |
| 🧩 Fully Responsive        | Scales perfectly from desktop to mobile devices.                            |
| 🔐 Readonly Output         | Password field is non-editable to prevent accidental changes.               |
--
## 🛠 Tech Stack

This project is built using:

- **HTML5**: Structure and layout
- **CSS3**: Styling and light/dark theme support
- **Vanilla JavaScript (ES6+)**: Password logic, event handling, UI interactivity

All code is written without frameworks or libraries to keep it lightweight and beginner-friendly.

---

## 🖥️ UI Overview

### Light Mode:
- Clean white background
- Clear form elements with modern blue buttons

### Dark Mode:
- Sleek dark background
- Text and buttons adapted for contrast and accessibility

**Layout Includes:**
- A toggle button to change theme
- Input field to display generated password
- Checkboxes for character types
- Strength bar and strength text
- Button to generate password
- Copy button for instant use

---

## 🧱 Code Structure

Everything is self-contained in a single `index.html` file:

---
## 🔎 How It Works

### 1. 🛠 Password Construction

javascript

let allChars = "";

if (hasUpper) allChars += "ABCDEFGHIJKLMNOPQRSTUVWXYZ";

if (hasLower) allChars += "abcdefghijklmnopqrstuvwxyz";

if (hasNumber) allChars += "0123456789";

if (hasSymbol) allChars += "!@#$%^&*()_+[]{}|;:,.<>?";

for (let i = 0; i < length; i++) {
    password += allChars[Math.floor(Math.random() * allChars.length)];
}

---
## ⚙️ Customization Guide

Here’s how to tweak or enhance different aspects of the password generator:

| What You Want to Change         | Where to Change It                   |
|---------------------------------|--------------------------------------|
| **Default password length**     | In the HTML: `<input value="12">`   |
| **Min/Max password length**     | In the HTML: `<input min="4" max="20">` |
| **Symbols used**                | In JavaScript: `const symbols = "!@#$%^&*()_+[]{}|;:,.<>?";` |
| **Theme colors**                | CSS section under `.light-mode` and `body` |
| **Button styles**               | CSS class `.btn` inside `<style>` block |
| **Default theme (light/dark)**  | Modify this JS check: `if (localStorage.getItem("theme") === "light")` |
| **Strength thresholds**         | Edit `checkStrength()` logic in JS |
| **Alert copy feedback**         | Replace `alert("Password Copied!")` with a custom toast/snackbar |
| **Font & Typography**           | Change `font-family` in CSS for `body` |
| **Add favicon**                 | Use `<link rel="icon" href="favicon.ico">` inside `<head>` |

> 💡 Want to go further? Consider splitting your code into `style.css` and `script.js` files for cleaner organization, especially if you plan to scale this project.

---
