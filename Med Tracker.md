# MedTracker Pro 💊

A modern medication reminder and adherence tracking web application with intuitive UI, statistics, and calendar view.

## Features ✨

- **Medication Management**
  - Add medications with dosage, frequency, and instructions
  - Custom time scheduling for medications
  - Start/End date configuration
  - Delete medications

- **Smart Reminders**
  - Browser notifications for upcoming doses
  - Customizable snooze duration (5-30 minutes)
  - Automatic schedule generation

- **Tracking & Analytics**
  - Real-time adherence statistics
  - Progress visualization
  - Medication history log
  - CSV export functionality

- **Interactive Calendar**
  - Monthly medication schedule view
  - Color-coded adherence indicators
  - Today's schedule overview

- **User Preferences**
  - Notification enable/disable
  - Data persistence using localStorage
  - Full data reset option

## Technologies Used 🛠️

- **Frontend**
  - HTML5 Semantic Markup
  - CSS3 with Custom Properties (CSS Variables)
  - Modern CSS Features (Grid, Flexbox, Animations)
  - Vanilla JavaScript (ES6+)

- **Browser APIs**
  - Web Notifications API
  - localStorage for data persistence
  - Date and Time manipulation

## 📋 Key Functionality Overview

### ✅ Medication Management
- **Smart Form Validation**
  - Real-time input validation with error notifications
  - Dynamic frequency selector (shows custom time input when "Custom" selected)
  - Date range validation (end date cannot be before start date)

### ✅ Interactive Dashboard
- Real-time medication list updates
- 3D pill visualization animations
- Status badges with color-coded indicators (Taken/Missed/Postponed)

### ⏰ Dose Tracking System & Smart Reminders
- Browser notification system with permission handling
- Snooze functionality (5/10/15/30 minute options)
- Automatic dose status detection (compares actual vs scheduled time)

### 📈 Advanced Analytics
- Adherence rate calculation algorithm
- 7-day streak tracking system
- Interactive progress bar with gradient animation
- CSV export with proper data formatting

### 🗓️ Calendar System
- Dynamic month navigation using date objects
- Smart day classification (Today / Has Medication / Has Missed)
- Responsive grid layout for all screen sizes

---
### 🎨 CSS Highlights

#### Theme System
- 15+ CSS custom properties for theming
- HSL color space for dynamic alpha adjustments
- Sophisticated shadow system with layered elevations

#### Advanced Techniques
- 3D transforms for logo and pill elements
- Keyframe animations (float, shimmer, fadeIn)
- Mobile-first responsive design
- CSS grid for calendar layout

---

## 🧠 JavaScript Core

### Data Management
- `localStorage` wrapper with JSON serialization
- Medication schema validation system
- History log versioning for data integrity

### Time Management
- Time parser for custom medication schedules
- Timezone-aware date calculations
- Intelligent medication scheduling algorithm

---

## 🌐 Browser Support

| Feature              | Chrome | Firefox | Safari | Edge | Mobile |
|----------------------|--------|---------|--------|------|--------|
| Core Functionality   | 89+    | 78+     | 14+    | 89+  | 15+    |
| Web Notifications    | ✔️     | ✔️      | △\*     | ✔️    | △      |
| CSS Grid             | 66+    | 61+     | 12+    | 79+  | 12.2+  |
| CSS Variables        | 66+    | 60+     | 12+    | 79+  | 12.2+  |
| localStorage         | 4+     | 3.5+    | 4+     | 10+  | 8+     |

\* Safari requires HTTPS for notifications.

---

## 🧪 Coding Standards

- **CSS:** Follow BEM naming convention  
- **JavaScript:** ES6+ with JSDoc comments  
- **Commits:** Use [Conventional Commits](https://www.conventionalcommits.org/)  
- **Testing:** Manual testing matrix required  

---

## ✅ Test Cases Checklist

- [ ] Add medication flow  
- [ ] Cross-browser date parsing  
- [ ] Notification permission handling  

---

## 📥 Pull Request Requirements

- Include **before/after screenshots** for any UI changes  
- Update `localStorage` version if schema changes  
- Add or update **documentation** for new features  
- Verify **mobile responsiveness** across major devices  

---

### 📚 Resources Used

- **Notification System:** Inspired by [MDN Web Docs – Notification API](https://developer.mozilla.org/en-US/docs/Web/API/Notifications_API)  
- **CSS Animations:** Techniques from [Animista](https://animista.net/)  
- **Color System:** Based on [Open Color](https://yeun.github.io/open-color/)  
- **UI Patterns:** Adapted from [Material Design Guidelines](https://m3.material.io/)

---

> **End Note**  
> MedTracker Pro is built with care to make medication tracking intuitive, smart, and user-friendly.  
> Thank you for checking out the project — your support, feedback, and contributions help make it even better! 💙
