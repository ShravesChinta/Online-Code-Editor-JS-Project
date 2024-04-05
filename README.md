# Online Code Editor

This is a simple online code editor built using vanilla JavaScript. It allows users to write and preview HTML, CSS, and JavaScript code in real-time within the browser. The editor consists of separate input fields for HTML, CSS, and JavaScript code, with an output area where the combined result is displayed.

## Features

- **Live Preview:** As you type your HTML, CSS, or JavaScript code in their respective input fields, the output area updates in real-time to reflect the changes.
- **Syntax Highlighting:** Provides syntax highlighting for HTML, CSS, and JavaScript for better code readability.
- **Responsive Design:** The editor is designed to be responsive, ensuring a consistent experience across different devices and screen sizes.

## Usage

1. **HTML Input:** Write your HTML code in the provided textarea under the HTML label.
2. **CSS Input:** Enter your CSS styles in the textarea under the CSS label.
3. **JavaScript Input:** Write your JavaScript code in the textarea under the JS label.
4. **Output:** The combined result of the HTML, CSS, and JavaScript code will be displayed in the output iframe.

## How It Works

The editor utilizes JavaScript to dynamically update the content of the output iframe based on the user's input. Here's a basic overview of how it works:

- **Event Listeners:** Event listeners are added to each textarea input to detect any changes in the code.
- **JavaScript Function (`run`):** Whenever a key is released in any of the textareas, the `run` function is triggered.
- **`run` Function:** This function retrieves the HTML, CSS, and JavaScript code from their respective textareas and combines them to update the content of the output iframe.
- **Styling:** The styling of the editor is done using CSS to ensure a visually appealing and user-friendly interface.

## Dependencies

- [Boxicons](https://boxicons.com/): Provides the icons used for HTML, CSS, and JavaScript labels.
- [Google Fonts](https://fonts.google.com/): Utilized for the 'Poppins' and 'Roboto' fonts used in the editor.

## Credits

This online code editor is created and maintained by [Your Name/Username]. Feel free to contribute or report any issues on [GitHub](https://github.com/yourusername/online-code-editor).

## License

This project is licensed under the [MIT License](LICENSE).
