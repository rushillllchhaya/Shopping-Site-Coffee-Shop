# Drip Cafe - Coffee Shop Website

This repository contains the source code for "Drip Cafe," a modern and responsive coffee shop website. It's designed to showcase a coffee shop's offerings, services, and contact information, providing a pleasant user experience with a clean design and interactive elements.

## Project Overview

Drip Cafe is a static website built primarily with HTML, CSS (using Sass for pre-processing), and JavaScript. It features multiple pages, including a homepage, menu, services, contact, and sign-in/sign-up pages. The website also includes a functional shopping cart for ordering coffee items.

## Functionality

- **Homepage (`dist/index.html`)**: Introduces Drip Cafe, its history, services, and menu highlights.
- **Menu Page (`dist/menu.html`)**: Displays a variety of coffee drinks with detailed nutritional information and ingredients. Users can view items and add them to a shopping cart.
- **Services Page (`dist/services.html`)**: Outlines the additional services offered by the cafe, such as entertainment, parking, and venue hosting for parties.
- **Contact Page (`dist/contact.html`)**: Provides contact information and a form for user inquiries.
- **Sign In/Sign Up Pages (`dist/sign-in.html`, `dist/sign-up.html`)**: Placeholder pages for user authentication.
- **Shopping Cart**: A client-side shopping cart implemented with JavaScript, allowing users to add items from the menu and view their selections.
- **Responsive Design**: The website is designed to be responsive and work well on various screen sizes.

## File Structure

```
Shopping-Site-Coffee-Shop/
├── css/                  # Compiled CSS files
│   └── main.css
├── dist/                 # Distribution folder (ready for deployment)
│   ├── assets/           # Assets for the distributed site
│   │   ├── css/
│   │   │   └── style.css
│   │   ├── images/       # Images used in the distributed site
│   │   └── js/
│   │       ├── maps.js
│   │       ├── script.js
│   │       └── sendEmail.js
│   ├── index.html
│   ├── contact.html
│   ├── menu.html
│   ├── services.html
│   ├── sign-in.html
│   └── sign-up.html
├── img/                  # Original image assets
├── js/                   # JavaScript source files
│   ├── menu.js
│   └── script.js
├── scss/                 # Sass source files
│   ├── _config.scss
│   ├── _home.scss
│   ├── _menu.scss
│   ├── _services.scss
│   ├── _contact.scss
│   ├── _sign-in.scss
│   ├── _sign-up.scss
│   ├── _responsive.scss
│   └── main.scss
└── README.md             # This README file
```

## Requirements

To view and run this website, you only need a modern web browser. To modify the source code and compile the Sass files, you will need:

-   **Node.js and npm (or Yarn)**: For installing Sass and other potential development dependencies.
-   **Sass**: To compile the `.scss` files into `.css`.

## Setup and Usage

### 1. Clone the Repository

```bash
git clone https://github.com/rushillllchhaya/Shopping-Site-Coffee-Shop.git
cd Shopping-Site-Coffee-Shop
```

### 2. Install Dependencies (for development)

If you plan to modify the Sass files, you'll need to install Sass. You can do this globally via npm:

```bash
npm install -g sass
```

### 3. Compile Sass (for development)

If you make changes to the `.scss` files, you'll need to compile them into `css/main.css`. Navigate to the root of the project and run:

```bash
sass scss/main.scss css/main.css
```

For continuous compilation during development, you can use the `--watch` flag:

```bash
sass --watch scss/main.scss:css/main.css
```

### 4. View the Website

To view the website, simply open the `dist/index.html` file in your web browser. You can also open any other `.html` file in the `dist/` directory directly.
