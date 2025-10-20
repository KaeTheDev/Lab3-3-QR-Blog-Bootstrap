# Lab 3.3 - Frontend Mentor Projects

This repository contains two simple frontend projects rebuilt from Frontend Mentor challenges: the QR Code Component and the Blog Preview Card. Both projects demonstrate semantic HTML, Bootstrap 5 styling, and responsive, mobile-first design principles.

## Description

These projects were rebuilt using Bootstrap 5 to practice applying its flex utilities, spacing system, and responsive design features.

The QR Code Component focuses on a clean, single-column layout that uses Bootstrap’s flexbox utilities to center content both vertically and horizontally within the viewport.

The Blog Preview Card demonstrates a more detailed card layout built with semantic HTML and Bootstrap’s spacing, typography, and flex utilities for alignment and structure — without relying on prebuilt Bootstrap card components.

Together, these projects emphasize understanding utility-first styling, semantic markup, and mobile-first design principles using Bootstrap instead of custom SCSS or CSS Flexbox

## Getting Started

### Dependencies

* A modern browser (Chrome, Firefox, Safari, Edge)
* Node.js installed (optional, only if using npm scripts)
* Live Server extension for VS Code (or similar) to preview projects
* OS: Windows, macOS, or Linux

### Installing

1. Clone this repository to your local machine:
git clone https://github.com/KaeTheDev/Lab3-QR-Blog-FEM-Project
2. Open the project folder of your choice (`QR` or `Blog`) in VS Code.
3. Ensure you have the Live Server extension installed to preview the project in the browser.

### Executing program

1. Open the HTML file you want to view (`index.html`) in VS Code.
2. Right-click and select **"Open with Live Server"**.
3. Your project will open in the browser, reflecting live changes when you edit SCSS or HTML.

Example command if using npm for SCSS compilation
npm run scss:watch

## Help

If your styles don’t appear correctly:  
* Make sure your SCSS is compiled to CSS.  
* Ensure the Live Server is pointing to the correct HTML file.

Example: compile SCSS manually if needed
sass --watch scss:css

## Authors

Shakira Reid-Thomas  
[@ShakiraReidThomas](https://github.com/kaethedev)

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgments

* Flexbox Froggy & [CSS Tricks - A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)  
* [MDN Docs - Semantic HTML](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)  


# REFLECTION QUESTIONS

1. What challenges did you face when refactoring your code to use Bootstrap?

- Only challenges that I noticed is that Bootstrap has built-in classes that needs
to be customized in order to get the exact design specifications. Some of my project
did not turn out the way it did when I built the project with CSS/SCSS.

2. How did using Bootstrap utility classes and components simplify your styling process?

- I didn't need as many files, or classes inside the styles.css file. The project
was built a lot faster.

3. In what scenarios might you choose not to use Bootstrap and write custom CSS instead?

- When I notice that the styles could be a little better or closer to the design. 
Bootstrap only gets it so close otherwise every project will look "out of the box".
