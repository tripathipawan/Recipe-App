# 🍽️ Recipe App

A clean, responsive web application that lets users discover recipes from around the world in real time — powered by an external recipe API and built with vanilla HTML, CSS, and JavaScript.

---

## 📌 Overview

Recipe App is a front-end web application designed to help users search for recipes instantly. By entering a dish name or keyword into the search bar, the app fetches live data from an external API and displays matching recipes in a visually appealing card layout. Users can then click on any recipe card to view its full details — including ingredients and preparation instructions — inside a smooth overlay panel.

The project demonstrates real-world skills in API integration, DOM manipulation, responsive design, and UI/UX thinking — all without any framework or library dependency.

---

## ✨ Features

- **Live Recipe Search** — Users can type any dish name or keyword and hit the Search button to fetch matching recipes in real time from the API.
- **Recipe Cards Display** — Matching results are rendered as dynamic cards, each showing the meal's image and name in a clean grid layout.
- **Detailed Recipe View** — Clicking on a recipe opens a detailed overlay panel that shows the full recipe information including ingredients and cooking instructions.
- **Close Button on Detail Panel** — The detail overlay includes a dedicated close button (using a Font Awesome × icon) so users can go back to the search results without refreshing the page.
- **Font Awesome Icons** — Integrated Font Awesome (v6.6.0) for iconography, keeping the UI polished and lightweight.
- **Fully Responsive Design** — The layout adapts seamlessly across desktop, tablet, and mobile screen sizes using CSS media queries, ensuring a smooth experience on any device.
- **No Framework Dependency** — Built entirely with vanilla HTML, CSS, and JavaScript — no React, no Vue, no dependencies to install.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and semantic markup |
| CSS3 | Styling, layout, and responsive design via media queries |
| JavaScript (ES6+) | API calls, DOM manipulation, and interactivity |
| External Recipe API | Fetches real-time recipe data based on user search input |
| Font Awesome v6.6.0 | UI icons (search, close button) |

---

## 📁 Project Structure

```
Recipe-App/
├── Index.html      # Main HTML file — app structure and layout
├── Style.css       # All styling including responsive media queries
├── Script.js       # JavaScript logic — API calls, DOM rendering, event handling
└── README.md       # Project documentation
```

---

## 🚀 Getting Started

No installation or build step required. Just follow these steps:

**1. Clone the repository**
```bash
git clone https://github.com/tripathipawan/Recipe-App.git
```

**2. Navigate into the project folder**
```bash
cd Recipe-App
```

**3. Open the app**

Open `Index.html` directly in your browser, or use the Live Server extension in VS Code for a better development experience.

```bash
# With VS Code Live Server
Right-click on Index.html → "Open with Live Server"
```

---

## 🧭 How to Use

1. Open the app in your browser.
2. Type a recipe name, dish, or ingredient keyword into the search bar (e.g., *"chicken"*, *"pasta"*, *"biryani"*).
3. Click the **Search** button.
4. Browse the recipe cards displayed on screen.
5. Click any card to open the **detail panel** with full ingredients and instructions.
6. Click the **× (close)** button to dismiss the detail view and return to the results.

---

## 📸 Preview

> *(Add a screenshot or screen recording of the app here for better visibility on GitHub)*

---

## 🔗 API Used

This app integrates with an **external recipe API** to fetch real-time meal data. The API returns recipe names, images, ingredients, and step-by-step cooking instructions based on the user's search query.

> If you plan to fork or extend this project, ensure the API endpoint in `Script.js` is active and refer to the API provider's documentation for any key requirements.

---

## 🌱 What I Learned

- How to fetch and handle data from a third-party REST API using JavaScript `fetch()`
- Dynamically creating and injecting HTML elements into the DOM based on API response data
- Building a responsive UI layout using CSS Flexbox/Grid and media queries
- Implementing overlay/modal-style UI patterns without any JavaScript library
- Integrating icon libraries (Font Awesome) via CDN

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve this project:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. Commit your changes (`git commit -m 'Add: your feature description'`)
4. Push to the branch (`git push origin feature/your-feature-name`)
5. Open a Pull Request

---

## 👨‍💻 Author

**Pawan Tripathi**
- GitHub: [@tripathipawan](https://github.com/tripathipawan)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
