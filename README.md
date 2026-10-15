# PeatGuard Simulator

An interactive, bilingual (English / Indonesian) web-based simulation tool designed for Indonesia's peatland fire risk assessment, hydrological monitoring, and mitigation strategy planning.

## Overview

PeatGuard Simulator provides clean interface to model the environmental factors driving Indonesia's tropical peatland fires. By adjusting real-time environmental levers—such as Water Table Depth (WTD), Rainfall Deficit, Wind Speed, and Temperature—users can instantly observe changes in Peat Moisture Content, Wildfire Risk Status, and live 2D geometric vector animations (smoke dispersion, wind streams, and underground fire hotspots).

## Key Features

* **Interactive Environmental Levers:** Fine-tune WTD (-120 cm to 0 cm) and rainfall deficit days (0 to 90 days) with instant dynamic response.
* **Live 2D Vector Visualizations:** Continuous `requestAnimationFrame` canvas rendering reflecting real-time wind particle streams, atmospheric haze, and subsurface thermal risks.
* **Bilingual Support (EN / ID):** Full linguistic parity across all interface elements, units, tooltips, and mitigation strategies with a single toggle.
* **Actionable Mitigation Strategies:** Real-time generation of targeted intervention measures (e.g., canal blocking, wetting, firebreak creation).
* **Modern Minimalist UI:** Designed with a neutral slate/charcoal aesthetic for high readability and professional presentation.

## Built With

* **HTML5 Canvas \& JavaScript:** For real-time vector graphics and physics-based calculations.
* **Tailwind CSS / Custom Styling:** Create a clean, responsive, and accessible layout across all desktop and mobile viewports.
* **Built with Google Gemini:** Developed, structured, and refined with assistance from advanced AI capabilities.

## Getting Started / Deployment

To run this project locally or deploy it live via GitHub Pages:

1. Clone or download the repository containing `index.html`.
2. Open `index.html` directly in any modern web browser.
3. To host publicly, push `index.html` to a public GitHub repository and enable **GitHub Pages** under your repository settings (`Settings > Pages > Branch: main`).

## License

This project is open-source and available under the MIT License. Feel free to adapt, extend, and share!

