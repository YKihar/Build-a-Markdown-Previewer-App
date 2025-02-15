# Build-a-Markdown-Previewer-App

# Markdown Editor and Preview

This project provides a simple and intuitive Markdown editor with a live preview.  Users can write Markdown in the editor pane, and the rendered HTML output is displayed in the preview pane in real-time.

## Features

*   **Live Preview:** See the rendered HTML output of your Markdown as you type.
*   **Side-by-Side Editor and Preview:**  A split-screen layout makes it easy to write and preview your Markdown.
*   **Basic Styling:**  Uses Bootstrap for responsive design and basic styling.
*   **Markdown Parsing:** Employs the `marked` library for parsing Markdown into HTML.
*   **Responsive Design:** Adapts to different screen sizes for optimal viewing on various devices.

## Technologies Used

*   **HTML:**  Structure of the webpage.
*   **CSS:** Styling with Bootstrap and custom CSS.
*   **JavaScript:**  Interactivity and Markdown parsing using the `marked` library.
*   **Bootstrap:**  For responsive design and basic styling.
*   **marked.js:** A fast and robust Markdown parser.

## How to Run

1.  Save the `index.html`, `style.css`, and any JavaScript files (including marked.js) in the same directory.
2.  Open the `index.html` file in your web browser.

## Usage

1.  Type your Markdown into the editor pane on the left.
2.  The rendered HTML will be displayed in the preview pane on the right as you type.

## Code Explanation

*   **`index.html`:**
    *   Sets up the basic HTML structure, including the editor (`#editor`) and preview (`#preview`) divs.
    *   Includes the necessary CSS (Bootstrap and custom) and JavaScript files (including marked.js).
    *   Contains a `<textarea>` element with the id `editor` for the Markdown input and a `<div>` with the id `preview` to display the rendered HTML.
*   **`style.css`:**
    *   Styles the editor and preview panes, including layout, colors, fonts, and responsiveness.
*   **JavaScript (inline or in a separate .js file):**
    *   Listens for changes in the `#editor` textarea.
    *   Uses `marked()` to parse the Markdown text from the editor.
    *   Sets the innerHTML of the `#preview` div to the parsed HTML.

## Libraries Used

*   **marked.js:**  Included via CDN or local file.  Used for Markdown parsing.  See: [https://github.com/markedjs/marked](https://github.com/markedjs/marked)

## Developer

Yousef Kaihar ([@Kihar_Youssf](https://x.com/Kihar_Youssf)) - [LinkedIn](https://www.linkedin.com/in/YOUR_LINKEDIN_PROFILE)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.
