🍔 Burger Website

A modern, fully responsive single-page restaurant website built using HTML, Tailwind CSS, JavaScript, Swiper.js, and ScrollReveal animations. The website showcases sections like Home, About, Menu, Categories, Promotions, Reviews, and Contact.

🚀 Features
✅ Fully Responsive UI

Designed with Tailwind CSS utility classes ensuring smooth experience on mobile, tablet, and desktop.

✅ Modern Animations

Uses ScrollReveal for smooth scroll animations & CSS animations for floating elements.

✅ Interactive Menu Filter

Menu items can be filtered by category:
All | Food | Snack | Beverage

✅ Mobile Navigation Menu

Includes a hamburger menu with open/close toggle for smaller screens.

✅ Reusable Components

Includes styled buttons, cards, category sections, promo sections, and contact form.

✅ Swiper.js Integration

Used to implement sliders (if present in your extended version).

🛠️ Technologies Used
Technology	Purpose
HTML5	Structure
Tailwind CSS	Styling & responsiveness
JavaScript (ES6)	Menu toggle, filtering, animations
Font Awesome	Icons
Remix Icons	Extra icons
Swiper.js	Sliders
ScrollReveal	On-scroll animations

📁 Folder Structure
project-folder/
│── index.html
│── output.css        # Compiled Tailwind CSS file
│── main.js           # JavaScript interactions
│── tailwind.config.js
│── package.json
│── img/
│   ├── home-image.png
│   ├── burger-1.png
│   ├── promo-1.png
│   └── ...etc

🧩 How to Run the Project Locally
1️⃣ Install Tailwind (if you're using npm)
npm install

2️⃣ Build Tailwind CSS
npx tailwindcss -i ./src/input.css -o ./output.css --watch

3️⃣ Start Project

Just open:

index.html


in your browser.

🌐 Deployment

This project can be deployed on:

Vercel




Important: Make sure output.css is placed in the root folder and correctly linked:

<link rel="stylesheet" href="./output.css" />
