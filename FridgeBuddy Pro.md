# 🧊 FridgeBuddy Pro

FridgeBuddy Pro is a single-page web application designed to help users track leftover ingredients in their fridge and generate recipe suggestions accordingly. It features a clean, responsive UI and is implemented using only HTML, CSS, and JavaScript — all contained in a single HTML file.

---

## 🚀 Features

### ✅ Ingredient Tracking
- Users can enter the items they currently have in their fridge.
- Inputs are flexible — add single or multiple ingredients separated by commas.

### 🧠 Smart Recipe Suggestions
- Based on entered items, FridgeBuddy Pro dynamically matches available recipes.
- Matches are case-insensitive and support partial keyword detection.

### 🍲 Recipe Display
- Matching recipes are displayed with:
  - Title
  - Description
  - List of required ingredients
- Recipes that match at least one of the entered ingredients are shown.

### 🎨 Sleek User Interface
- Clean and responsive design built with modern CSS.
- Minimalist layout with focus on usability.
- Works seamlessly on desktop and mobile browsers.

---

## 🛠️ Technologies Used

| Tech         | Purpose                          |
|--------------|----------------------------------|
| HTML5        | Structure of the application     |
| CSS3         | Styling and responsive design    |
| JavaScript   | Logic for input handling and dynamic recipe filtering |

---

## 📂 File Structure

Since this is a single HTML file project, the structure is self-contained:

### Sections Inside the File:
1. `<head>`:
   - Includes metadata and embedded `<style>` tag for CSS.
2. `<body>`:
   - Main app container with title, description, input field, and results section.
3. `<script>`:
   - Contains an array of recipes and the filtering logic.

---

## 🧪 How It Works

### 1. User Input
Users type in ingredients like:
chicken, garlic, tomato
### 2. Matching Logic
The script:
- Splits input into keywords.
- Loops through each predefined recipe.
- Checks if any input keyword matches the recipe ingredients (partial and case-insensitive match).
- Displays matching recipes in the results section.

### 3. Output Display
Recipes are shown with structured info:
- Recipe name
- Description
- Ingredients used

---

## 📸 Screenshots

_Include screenshots here if needed_

---

## 🧾 Sample Recipes Included

- **Garlic Chicken Stir Fry**
- **Tomato Basil Pasta**
- **Vegetable Fried Rice**
- **Avocado Toast**
- **Mango Smoothie**
- **Spaghetti Carbonara**
- **Grilled Cheese Sandwich**
- **Fruit Salad**
- **Omelette**
- **Pancakes**

Each recipe has a name, a short description, and a list of ingredients used for filtering.

---

## 💡 Future Enhancements

- [ ] Allow users to add their own recipes and persist them using localStorage.
- [ ] Filter recipes by dietary preferences (vegetarian, gluten-free, etc.).
- [ ] Enable sorting by number of matched ingredients.
- [ ] Add image thumbnails to each recipe.
- [ ] Support saving ingredient lists across sessions.

---

## 📦 Installation & Usage

### Option 1: Open Locally
1. Download the `FridgeBuddy Pro.html` file.
2. Open it in any modern browser (Chrome, Firefox, Edge, etc.).

### Option 2: Deploy Online
1. Upload the HTML file to GitHub Pages, Netlify, or Vercel.
2. Share the public link for anyone to access.

---

## 🤝 Contributing

Pull requests and feedback are welcome! If you have ideas for improving the matching algorithm or UI, feel free to fork the project and suggest changes.

---

## 📄 License

This project is open-source and free to use for personal or educational purposes. No license specified — add one if desired.


