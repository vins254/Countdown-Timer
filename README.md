# Countdown Timer ⏳

A simple, elegant, and responsive countdown timer built with Vanilla JavaScript, HTML, and CSS. This project counts down to New Year's Day (January 1, 2027), providing a real-time display of days, hours, minutes, and seconds.

## 🚀 Live Demo
Check out the live application here: [Countdown Timer Demo](https://vins254.github.io/Countdown-Timer/)

## 🛠️ Tech Stack
- **HTML5**: Semantic structure for the timer elements.
- **CSS3**: Custom styling, including Google Fonts (Poppins), Flexbox for responsiveness, and background image integration.
- **JavaScript (Vanilla)**: Core logic for time calculation and dynamic DOM manipulation.

## ⚙️ How It Works
The application functions by calculating the time remaining until a specified target date (New Year's Day 2027).

1. **Time Calculation**: The script captures the current date and compares it with the target date to determine the total remaining time in milliseconds.
2. **Unit Conversion**: It converts the total milliseconds into seconds, minutes, hours, and days using mathematical operations.
3. **Dynamic Updates**: Using `setInterval`, the `countdown` function is invoked every 1000ms (1 second), ensuring the UI reflects the time passing in real-time.
4. **Formatting**: A helper function ensures that any value below 10 is prepended with a "0" for a consistent double-digit display (e.g., `09` instead of `9`).

## ✨ Features
- **Real-time Countdown**: Updates every second without page refreshes.
- **Responsive Design**: Adapts beautifully to various screen sizes.
- **Clean UI**: Minimalist aesthetic with a bold focus on the countdown numbers.
- **Custom Font**: Integrated with Google Fonts' "Poppins" for a modern feel.

## 📂 Project Structure
- `index.html`: The entry point and UI structure.
- `style.css`: All visual styles and layouts.
- `script.js`: The engine behind the timer logic.
- `background_image.jpg`: High-quality background image for the app.

---
Developed by [vins254](https://github.com/vins254)
