# Ticket Calculator

An interactive, client-side web application designed to dynamically calculate event ticket pricing based on ticket tier, quantity, and discount options.

Developed for **Web Development 1 (Lab 5: Using JavaScript and Deploying a Website)** in the Software Development Diploma program at the Southern Alberta Institute of Technology (SAIT).

## Overview

This project demonstrates core JavaScript fundamentals in the browser, focusing on event-driven programming, input validation, dynamic calculation logic, and DOM manipulation without external dependencies.

## Features

- **Real-Time Total Calculation:** Automatically calculates subtotals, discounts, taxes, and final totals based on user selections.
- **Input Validation:** Enforces positive integer inputs and handles boundary cases gracefully.
- **Responsive Layout:** Clean, accessible interface structured for mobile and desktop screens using modern CSS.
- **Vanilla Implementation:** Built using native web standards with zero dependencies or build steps.

## Tech Stack

- **HTML5:** Semantic document structure and form controls.
- **CSS3:** Responsive layout, flexbox, and styling.
- **JavaScript (ES6+):** Event listeners, form state handling, and calculation algorithms.

## Getting Started

### Prerequisites

A modern web browser (Chrome, Firefox, Safari, or Edge).

### Running Locally

1. Clone the repository:
   ```bash
   git clone [https://github.com/wallaceip/ticket-calculator.git](https://github.com/wallaceip/ticket-calculator.git)

```

2. Navigate to the project directory:
```bash
cd ticket-calculator

```


3. Open `index.html` directly in your browser, or launch it with a local development server such as VS Code's **Live Server**.

## Project Structure

```text
ticket-calculator/
├── index.html        # Main HTML document and form inputs
├── styles.css        # Responsive styling and layout rules
├── script.js         # Core calculation and DOM manipulation logic
└── README.md         # Project documentation

```

## Deployment

The static files can be served directly through any static host:

* **GitHub Pages:** Serve directly from the `main` branch root.
* **Vercel / Netlify:** Import the Git repository for automatic static deployment.
