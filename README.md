# Markdown-Content-Display

A simple HTML project to display Markdown content in your browser.

## Features

- Renders Markdown files on a web page
- Easy to use and customize
- Pure HTML implementation (no frameworks required)

## Getting Started

### Prerequisites

You only need a web browser to use this project.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/imandaidfa/Markdown-Content-Display.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd Markdown-Content-Display
   ```
3. **Open `index.html` in your browser.**

## Usage

- Place your Markdown file in the project directory.
- Open `index.html` in your browser to view the rendered content.

## How to Change the Displayed Markdown File

To update the Markdown file being displayed:

1. Open `index.html` in a text editor.
2. Find the following line:

   ```javascript
   const markdownFilePath = 'README.md'; // Change this to your desired .md file
   ```

3. Replace `'README.md'` with the path or filename of your preferred Markdown file, for example:

   ```javascript
   const markdownFilePath = 'docs/guide.md';
   ```

4. Save the changes and refresh your browser to see the new Markdown content.

## Customization

You can modify `index.html` to change styles or support additional Markdown features.

## License

This project is licensed under the MIT License.

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

