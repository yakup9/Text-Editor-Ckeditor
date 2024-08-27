# Custom Text Editor

A lightweight and customizable text editor inspired by CKEditor. This editor is built with HTML, CSS, and JavaScript, making it easy to integrate into any web project.

## Features

- **Rich Text Formatting**: Supports bold, italic, underline, and strikethrough.
- **Text Alignment**: Align text left, center, or right.
- **Lists**: Create ordered and unordered lists.
- **Links**: Add and remove hyperlinks.
- **Image Support**: Easily insert and manage images within the text.
- **Customizable Toolbar**: Add or remove buttons based on your needs.
- **Responsive Design**: Works seamlessly on all devices.

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yakup9/text-editor-ckeditor.git
   cd text-editor-ckeditor
   ```

2. **Include the Editor in Your Project**:

   Add the following lines to your HTML file:

   ```html
   <link rel="stylesheet" href="style.css">
   <script src="script.js"></script>
   ```

3. **Initialize the Editor**:

   Include an element with the ID `editor` in your HTML where you want the text editor to appear:

   ```html
   <div id="editor"></div>
   ```

   Then, initialize the editor by calling:

   ```javascript
   document.addEventListener("DOMContentLoaded", function () {
       initializeEditor();
   });
   ```

## Usage

Simply start typing in the editor area to begin using the text editor. Use the toolbar to format text, create lists, add links, and insert images.

## Customization

The toolbar can be customized by modifying the `toolbarOptions` array in `script.js`. For example:

```javascript
const toolbarOptions = ['bold', 'italic', 'underline', 'link', 'image'];
```

Add or remove options to suit your needs.

## Contributing

Contributions are welcome! If you have ideas for new features or improvements, feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

---

Feel free to adjust the content to better suit your project and personal style.
