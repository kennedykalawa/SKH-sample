# SokoHub Code Guide 🚀

Welcome to the SokoHub codebase! This document explains how the website is structured and how to maintain the code in the "SokoHub way."

## 1. Project Structure
- `index.html`: The main landing page.
- `products.html`, `About.html`, `Contact us.html`: Core informational pages.
- `Register.html`, `sellers.page.html`, `delivery.html`: Onboarding and registration.
- `main.css`: The unified stylesheet for the entire website.
- `main.js`: The main JavaScript file for interactivity.
- `sokohubimg/`: Directory containing all image assets.
- `Login&Signup/`: Dedicated folder for authentication pages.

## 2. CSS Conventions (`-flex` suffix)
We follow a specific naming convention to ensure our code is easy to read and focused on Flexbox layouts.
- **Layout Wrappers**: Always end with `-flex` (e.g., `.nav-menu-flex`, `.hero-flex`, `.grid-flex`).
- **Components**: Smaller parts also use the suffix for consistency (e.g., `.btn-up-flex`, `.card-info-flex`).
- **Variables**: We use CSS variables for colors and shadows to make global changes easy.
  - `--primary-color`: The SokoHub LimeGreen (#32cd32).
  - `--accent-color`: The SokoHub Gold (#d8860b).

## 3. JavaScript Features
The `main.js` file handles:
- **Mobile Menu**: Automatically toggles the navigation links on small screens.
- **Form Validation**: Checks if "required" fields are filled before submitting.
- **Sticky Header**: Makes the navbar slightly smaller and transparent when you scroll down.
- **Smooth Scroll**: Animates transitions when clicking links that point to sections on the same page.

## 4. How to Add a New Page
1. Create a new `.html` file.
2. Link `main.css` in the `<head>`.
3. Copy the standard `<header class="header-flex">` structure.
4. Add your content inside a `<main class="container">`.
5. Link `main.js` at the bottom of the `<body>`.
6. Add the standardized footer.

Happy Coding!
