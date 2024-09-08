# Text Formatter and JSON Beautifier

This web-based application allows you to easily format text, validate and beautify JSON, and convert JavaScript/TypeScript objects to JSON. It provides simple options for text transformation and comes with features such as clipboard copy-paste functionality, text resizing, and syntax highlighting for JSON.

## Features

- **Text Transformation**: Converts special characters like `\n`, `\"`, and `\\` into readable format.
- **JSON Beautifier**: Validates JSON and formats it in a readable, indented format.
- **JS/TS to JSON Conversion**: Converts JavaScript/TypeScript object literals into JSON format.
- **Clipboard Support**: Easily copy text from and paste text into the input field using clipboard buttons.
- **Dynamic Font Resizing**: Adjust the font size of the output text for better readability.
- **Text Area Toggle**: Minimize or maximize the input/output text areas to save screen space.
- **Syntax Highlighting**: Uses `highlight.js` to provide syntax highlighting for JSON in the output field.

## Getting Started

1. **Clone the repository**:
    ```bash
    git clone https://github.com/EnjoyFX/reoConverter.git
    ```
   
2. **Open `reoConverter.html`**:
   Simply open the `reoConverter.html` file in your web browser to run the application locally. The application works fully offline and does not require a server setup.

## How to Use

1. **Input Field**:
   - Enter your text, JSON, or JS/TS object in the input field.
   - Use the **Paste** button to paste from the clipboard into the input field.

2. **Transform Non-JSON Text**:
   - Click the **Transform Text** button to format regular text, replacing special characters with readable equivalents.

3. **Beautify JSON**:
   - Paste or type a JSON string into the input field. If the JSON is valid, the **Beautify JSON** button will activate. Click it to beautify the JSON and display it in the output field.

4. **Convert JS/TS to JSON**:
   - If you input a JavaScript or TypeScript object literal, use the **JS/TS to JSON** button to convert it to JSON format.

5. **Copy Functionality**:
   - Use the **Copy** button near the output field to copy the formatted or beautified result into your clipboard.

6. **Font Size**:
   - Adjust the font size of the output text by using the up and down arrows.

7. **Toggle Text Area Sizes**:
   - Use the **Toggle** button to minimize the input field and maximize the output field or restore them to their original sizes.

## Technologies Used

- **HTML5**: Structure of the application.
- **CSS**: Styling for layout and responsive design.
- **JavaScript**: Core logic for text transformation, JSON validation, and clipboard functionality.
- **highlight.js**: Provides syntax highlighting for JSON in the output field.
