# 📚 BookWorm - Interactive Reading & Notes Companion

![Demo](https://img.shields.io/badge/Demo-Available-blue) 
![License](https://img.shields.io/badge/License-MIT-green)

A modern web app for reading text files with immersive theming, note-taking, and search capabilities. Built with pure HTML/CSS/JS.

## 🌟 Features
- **File Upload**: Drag-and-drop or browse `.txt` files.
- **Interactive Theming**: 4 themes (Classic, Sci-Fi, Romance, Mystery) with 3D card flips.
- **Notes System**: Highlight text and attach notes (saved in localStorage).
- **Search**: Highlight matches and navigate through results.
- **Dark Mode**: Toggleable dark theme.
- **Parallax Effects**: Dynamic background layers that react to mouse movement.
- **Progress Bar**: Tracks scroll position.
- **Responsive Design**: Works on mobile and desktop.

## 🛠 Technologies
- **HTML5**: Semantic structure and file handling.
- **CSS3**: Variables, animations, 3D transforms, and responsive design.
- **JavaScript**: File API, DOM manipulation, localStorage.
- **Google Fonts**: `Inter`, `Merriweather`, `Space Mono`, `Pacifico`.
  
# Bookworm Project Overview

## 🖥 Usage

### Uploading Text
- Click the upload zone or drag a `.txt` file into it.
- The text will display in the reader area with paragraph formatting.

### Theming
- Click theme cards to switch styles.
- Themes affect:
  - Font family (serif, monospace, cursive).
  - Color schemes (gradients for light/dark modes).

### Notes
- **Highlight text:** Select text to create a highlight.
- **Add notes:** A form appears to save notes linked to the highlight.
- **View/Delete notes:** All notes appear in the sidebar. Click 🗑️ to delete.

### Search
- Type in the search bar to highlight matches.
- Press Enter to cycle through results.

### Dark Mode
- Toggle the 🌙/☀️ button to switch themes.

---
# Theming System

| Theme   | Font Family  | Primary Colors      |
|---------|--------------|---------------------|
| Classic | Merriweather | Slate Gray Gradient |
| Sci-Fi  | Space Mono   | Blue Gradient       |
| Romance | Pacifico     | Pink/Red Gradient   |
| Mystery | Merriweather | Purple Gradient     |
