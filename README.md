# Web Project: Front-end e muito mais

## Project Overview
This project is designed to provide lessons on HTML and CSS, focusing on front-end development. It includes a homepage, a form page for user input, and a display page to show the submitted data.

## Project Structure
```
web-project
├── css
│   └── style.css          # Styles for the HTML pages
├── js
│   └── script.js         # JavaScript functionality (currently empty)
├── form.html             # Form for user input
├── display.html          # Displays submitted data
└── index.html            # Homepage themed "Front-end e muito mais"
```

## File Descriptions

### index.html
- The homepage featuring:
  - A header with a navigation menu linking to the homepage and the form page.
  - A prominent header (`<h1>`).
  - A brief introduction to HTML.
  - An attached image.
  - Various links (`<a>`).
  - Unordered lists (`<ul>`) and ordered lists (`<ol>`).
  - Bold and italic text.
  - Multiple paragraphs.
  - Horizontal lines and line breaks.
  - A table for structured data.

### form.html
- Contains a comprehensive form with:
  - Input types: text, number, email, URL, radio buttons, checkboxes, and datetime.
  - Proper labels, IDs, and names for all inputs.
  - Uses the GET method for form submission.
  - Reset and submit buttons.
  - A checkbox for confirming the validity of the data.

### display.html
- Collects and displays the data submitted from the form:
  - Shows "Não informado" for empty fields.
  - Displays a message based on the confirmation checkbox status:
    - "Marcado como dados verídicos!" if checked.
    - "Dados não confirmados como verídicos!" if not checked.

### css/style.css
- This file is intended for styling all HTML pages. It is currently empty but ready for CSS integration later.

### js/script.js
- This file is intended for any JavaScript functionality needed for the project. It is currently empty but ready for future use.

## Usage
To view the project, open `index.html` in a web browser. Navigate through the menu to access the form and display pages. 

## Future Enhancements
- Add CSS styles in `style.css` to improve the visual presentation of the pages.
- Implement JavaScript functionality in `script.js` for enhanced interactivity.