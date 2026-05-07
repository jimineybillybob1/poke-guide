# Pokémon Type Guide & Team Builder

A sleek, mobile-friendly static web application for searching Pokémon type effectiveness and building balanced teams with move coverage analysis.

## ⚔️ Features

- **Global Search:** Quickly look up any of the 1025 Pokémon (including regional forms and Mega Evolutions) to see their defensive weaknesses, resistances, and immunities.
- **Interactive Team Builder:** Build a team of up to 6 Pokémon and assign them specific moves.
- **Move Coverage Table:** Automatically generates a coverage matrix to show which types your team's moves are super-effective against.
- **Local Persistence:** Your team is automatically saved to your browser's `localStorage`, so you won't lose your progress when you refresh or close the page.
- **Mobile Optimized:** Designed with a "Web App" feel, featuring a responsive layout and touch-friendly interface.

## 🚀 How to Use

1. **Type Guide:** Use the search bar to find a Pokémon. The card will display its type-specific matchups (4x weaknesses, 2x weaknesses, resistances, etc.).
2. **My Team:** Switch to the "My Team" tab to start building.
   - Click a slot to search for a Pokémon.
   - Add up to 4 moves per Pokémon to see their offensive coverage.
   - The **Move Type Coverage** table at the bottom will update in real-time to show you which types your team can currently counter with super-effective damage.

## 🛠️ Technology Stack

- **HTML5/CSS3:** Custom styles with a dark-mode "Dex" aesthetic.
- **Vanilla JavaScript:** No external frameworks or libraries required.
- **GitHub Pages:** Hosted as a static site.

## 📦 Installation / Deployment

Since this is a static site, you don't need to install anything. 

1. Clone the repository: `git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git`
2. Open `index.html` in any modern web browser.
3. To host it, simply enable **GitHub Pages** in your repository settings.

---
*Data includes Pokémon through Generation 9 and various regional forms.*
