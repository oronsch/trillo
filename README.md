
# Trillo

Trillo is a modern, responsive web application for booking hotels, flights, car rentals, and tours. Inspired by cutting edge CSS techniques.

## Table of Contents
- [Project Overview](#project-overview)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Development Scripts](#development-scripts)
- [Technologies Used](#technologies-used)

## Project Overview
Trillo is a single-page application showcasing a responsive design for booking services. It includes:
- A user-friendly interface.
- Navigation for hotels, flights, car rentals, and tours.
- Fully styled components using advanced CSS and Sass.
- Dynamic SVG icons and imagery.

## Setup and Installation
1. Clone this repository:
   git clone https://github.com/your-repo/trillo.git
   cd trillo
   ```
2. Install dependencies:
   pnpm install
   ```
3. Start the development server:
   pnpm run start
   ```

## Usage
- Run the app locally using the development server.
- Modify the styles or HTML for customization.
- Build the CSS for production.

## File Structure
```
Trillo/
├── index.html            # Main HTML file
├── package.json          # Project configurations and scripts
├── css/
│   ├── style.css         # Minified production CSS
│   ├── style.comp.css    # Compiled Sass output
│   ├── style.prefix.css  # Prefixed CSS with Autoprefixer
├── sass/
│   ├── main.scss         # Main Sass file
│   ├── _variables.scss   # Sass variables
│   ├── _mixins.scss      # Sass mixins
│   └── _components.scss  # Component styles
├── img/                  # Images and SVG icons
└── README.md             # Project documentation
```

## Development Scripts
The following scripts are defined in the `package.json` file:
- **Watch Sass:**
  pnpm run watch:sass
  ```
  Watches and compiles `sass/main.scss` into `css/style.css`.

- **Start Development Server:**
  pnpm run start
  ```
  Runs a live development server and watches Sass files.

- **Build CSS for Production:**
  pnpm run build:css
  ```
  Compiles, prefixes, and compresses Sass into a single CSS file.

- **Individual Steps for Building CSS:**
  1. Compile Sass:
     pnpm run compile:sass
     ```
  2. Add CSS prefixes:
     pnpm run prefix:css
     ```
  3. Compress the final CSS:
     pnpm run compress:css
     ```

## Technologies Used
- **Sass**: Advanced CSS preprocessor for maintainable styles.
- **PostCSS**: Processes CSS with plugins like Autoprefixer.
- **Autoprefixer**: Adds vendor prefixes for compatibility.
- **CSSNano**: Compresses and optimizes the final CSS.
- **npm-run-all**: Runs multiple scripts in parallel or sequentially.
- **Live Server**: A lightweight development server with live reload.

## License
This project is licensed under the ISC License. Feel free to use and modify it as needed.

---

© 2024 by Oron Sch. Inspired by [Jonas.io](https://jonas.io/).
