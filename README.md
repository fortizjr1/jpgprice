# Parking Fee Calculator 🚗💸

A sleek, mobile-first web application for calculating parking fees. Features a modern dark UI, touch-optimized controls, and real-time calculation logic.

![Dark Mode UI](https://via.placeholder.com/800x400?text=Parking+Fee+Calculator+Dark+UI)

## ✨ Features

- **Dark Mode UI**: Professional, eye-friendly dark theme with slate and indigo accents.
- **Mobile First Design**: Fully responsive layout with optimized touch targets (54px+), safe-area insets for notched devices, and native app-like feel.
- **Real-time Calculation**: Fees are updated instantly as you select dates and times.
- **Smart Logic**:
  - **Grace Period**: First 15 minutes are free.
  - **Standard Rate**: $5 for the first hour (after grace period).
  - **Hourly Rate**: $2 per additional 30-minute block.
  - **Daily Max**: Capped at $35 per 24 hours.
- **Offline Capable**: Built with vanilla HTML/CSS/JS, no external dependencies required for core logic.

## 📱 How to Use

1. **Select Entry Date**: Tap the date input to choose when the vehicle entered.
2. **Select Entry Time**: Use the custom dropdowns for Hour, Minute, and AM/PM.
3. **View Fee**: The total fee is displayed instantly above the reset button.
4. **Reset**: Tap "RESET CALCULATOR" to clear the form and start over.

## 🛠️ Technologies

- **HTML5**: Semantic structure.
- **CSS3**: Custom properties (variables), Flexbox, CSS Grid, and responsive media queries.
- **JavaScript (ES6+)**: Date manipulation and fee calculation logic.
- **Fonts**: [Poppins](https://fonts.google.com/specimen/Poppins) via Google Fonts.
- **Icons**: [FontAwesome 6](https://fontawesome.com/).

## 🚀 Installation

Simply clone the repository and open `index.html` in your browser.

```bash
git clone https://github.com/aristotle-malichetty/parking-fee-calculator.git
cd parking-fee-calculator
# Open index.html
```

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---
*Based on the original logic by [aristotle-malichetty](https://github.com/aristotle-malichetty).*
