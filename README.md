# Dynamic ID Card Generator

A clean, responsive web application that allows users to input their professional details and upload a profile picture to instantly generate a custom ID card. Built entirely with vanilla front-end technologies.

### Features
* **Local Image Uploading:** Utilizes the JavaScript `FileReader` API to instantly preview uploaded profile pictures without needing a backend server.
* **Dynamic DOM Updates:** Captures user input (Name, Age, Department, ID, and Status) and dynamically injects it into the DOM to build the card.
* **Form Validation:** Includes logic to ensure all input fields and dropdowns are filled before generating the card.
* **Keyboard Accessibility:** Users can press the `Enter` key while inside any input field to trigger the card generation.
* **Responsive Layout:** Uses CSS Flexbox and media queries to display the form and the generated card side-by-side on desktop, and neatly stacked on mobile devices.

### Tech Stack
* **HTML5:** Semantic structure and form inputs (including file and number types).
* **CSS3:** Custom gradients, box-shadows, styling, and responsive media queries.
* **JavaScript (ES6):** DOM traversal (`querySelectorAll`), Event Listeners (`click`, `keypress`), and the `FileReader` object.

### How to Run Locally
The live link for this project is available in the description.
1. Clone this repository to your local machine.
2. Open the `index.html` file in any modern web browser.
3. Fill out the form, upload an image, and click "Generate Card" (or press Enter).
