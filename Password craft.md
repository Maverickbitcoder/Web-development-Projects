# 🔐 PassCraft – Password Pattern Builder

**PassCraft** is a creative, visual password generator that lets users design secure, memorable passwords using colors, shapes, rhythm, and a grid-based pattern. Unlike traditional password tools, PassCraft empowers users to build passwords that reflect their preferences while ensuring security through complexity and character diversity.

Built entirely with **HTML**, **CSS**, and **JavaScript**, it requires no frameworks or external dependencies.

---

## 🚀 Features

- 🎨 Select a **favorite color** via palette, HEX, or RGB sliders
- 🔷 Choose a **shape** like circle, square, triangle, heart, etc.
- 🔢 Set a **rhythm level** to animate bars and influence password variation
- 🔲 Create a **pattern** by dragging across a 3x3 grid
- 🔐 Auto-generate passwords from your unique selections
- 📋 **Copy to clipboard** instantly
- 📊 Password **strength meter** and detailed analysis
- 🧠 Memorability through visual and emotional cues
- 💡 Helpful tooltips and multi-tabbed layout (*Create*, *Preview*, *About*)
- 🖥 Fully responsive design with animated feedback
- 💯 No server, no tracking, no storage — all in-browser

---

## 🛠 Tech Stack

| Layer        | Technology             |
|--------------|------------------------|
| Markup       | HTML5                  |
| Styling      | CSS3 with Custom Properties (Variables) |
| Interactivity| JavaScript (ES6+)      |
| UI Patterns  | Flexbox, CSS Grid, Transitions, Animations |
| Storage      | None – stateless and secure |

---

## 🛠 Tech Stack
| Layer        | Technology             |
|--------------|------------------------|
| Markup       | HTML5                  |
| Styling      | CSS3 with Custom Properties (Variables) |
| Interactivity| JavaScript (ES6+)      |
| UI Patterns  | Flexbox, CSS Grid, Transitions, Animations |
| Storage      | None – stateless and secure |

---

## 🧠 How It Works

PassCraft uses a combination of visual inputs and user preferences to build passwords that are both **secure** and **memorable**.

### 1. 🖌 Color Input
Choose a color using:
- Native color picker
- Pre-set palette
- Manual HEX code
- RGB sliders

The color’s HEX values are converted to characters and added to the password.

### 2. 🔷 Shape Selector
Pick a shape that represents you. Each shape injects a unique symbol into the password (e.g., `@`, `^`, `&`, `*`).

### 3. 🥁 Rhythm Level
Adjust a slider from 1 to 5. This sets the rhythm level and animates visual rhythm bars. The number is embedded into the password.

### 4. 🧩 Pattern Grid
Drag across a 3×3 grid. Each cell has a symbol (letters, numbers, or special chars). The sequence becomes part of the password’s body.

### 5. 🔐 Password Generation
The password is built using:
- Color → character pair (HEX → ASCII)
- Shape → symbol (e.g., `@`, `#`, `*`)
- Rhythm → single digit (e.g., `3`)
- Pattern → series of selected grid symbols
- Safety fallback to ensure special characters and digits

### 6. 📊 Strength & Analysis
After generation:
- A strength bar updates based on entropy scoring
- A breakdown lists character types, password length, and feedback

---

## ⚙️ Customization Options

| Element                 | How to Modify                                      |
|-------------------------|----------------------------------------------------|
| Default color           | Change `value` in `#standard-color-picker`         |
| Pattern symbols         | Edit `gridSymbols` array in JavaScript             |
| Shape character rules   | Modify `generatePasswordFromPattern()` function    |
| Rhythm intensity range  | Tweak `min` and `max` in `#rhythm-slider`          |
| Strength calculation    | Tune logic in `calculatePasswordStrength()`        |
| Copy-to-clipboard UI    | Customize tooltip or notifications in JS           |
| Theme & branding        | Adjust CSS variables under `:root` selector        |
| Grid layout             | Change grid structure in `createGrid()` function   |
| Password fallback logic | Add/modify conditions in generation function       |

---

## 🔐 Security Benefits

- **Fully client-side**: No backend, no API calls, nothing is transmitted.
- **User-controlled entropy**: Visual cues like shape, rhythm, and color add real randomness.
- **Compositional enforcement**: Ensures character diversity (upper, lower, digit, special).
- **Pattern complexity**: Grid paths increase uniqueness with each use.
- **No storage**: Data isn’t saved locally or remotely — session-only.
- **Fallback-safe**: Password generator fills in missing char types if needed.

  
## 📂 Project Structure

```text
📁 root/
 ┣ 📜 index.html        ← Contains all HTML, CSS, and JS
 ┗ 📜 README.md         ← This documentation file## 🛠 Tech Stack
