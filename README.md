# CSS-Animation

A simple project that demonstrates CSS animations and interactive UI components using pure HTML and CSS.

## Overview

This project showcases how to build interactive web elements with animated effects using just CSS and HTML. The main feature is an animated `<div>` whose behavior can be toggled by a custom "move button" switch. The project is modularized with separate CSS files for layout, animation, and the button component.

## Demo

👉 **[Live Demo](https://diaahsharqawi.github.io/CSS-Animation/)**

See the animation and interactivity in action!

## Features

- **Animated Div:** A visual element (`#animated-div`) with CSS-driven animation.
- **Move Button:** An interactive checkbox switch that triggers the animation.
- **Component-based CSS:** The CSS is organized into modular components for easy maintenance and scalability.

## Project Structure

```
.
├── index.html
├── styles.css
├── styles/
│   └── components/
│       ├── page-layout.css
│       ├── animated-div.css
│       └── move-button.css
├── package.json
```

- `index.html`: Main HTML file, includes the structure and references to the styles.
- `styles.css`: Imports component styles.
- `styles/components/`: Contains modular CSS files for layout, animation, and the button.

## Getting Started

### Prerequisites

- Node.js (for running a local development server)

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/DiaaHSharqawi/CSS-Animation.git
   cd CSS-Animation
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

### Running the Project

```bash
npm start
```

This will serve the project locally using the `serve` package. Open your browser and navigate to `http://localhost:3000` (or the provided port) to view the animation.

## Customization

- **Add More Animations:** Extend the `animated-div.css` or add new components for additional animated elements.
- **Style the Move Button:** Tweak `move-button.css` to change the look and feel of the toggle switch.
- **Layout Adjustments:** Use `page-layout.css` for overall layout changes.

## License

This project is licensed under the [MIT License](LICENSE).

---

© 2025 Done by Diaa Sharqawi
