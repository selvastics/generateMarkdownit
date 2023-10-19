# Generate MarkdownIt

## Overview
This repository contains a Node.js script that converts Markdown files to HTML files with added functionalities like syntax highlighting, a copy code button, and other formatting enhancements. It also includes a `package.json` file to manage dependencies. It requires a folder named `blogarticles` where `.md` files are to be converted.

## Pre-requisites

1. Node.js installed
2. npm installed

### How to Install Dependencies
Navigate to the project directory and run the following command:
```
npm install
```

## Directory Structure
- `/generateMarkdownIt.js` - Main script
- `/blogarticles` - Directory containing `.md` files to be converted
- `/package.json` - Dependency management

To create the `blogarticles` folder, you can run:
```
mkdir blogarticles
```

## How It Works
The script uses multiple packages for various functionalities:

- `MarkdownIt` for Markdown to HTML conversion
- `highlight.js` for syntax highlighting in code blocks
- `markdown-it-toc-and-anchor` for adding table of contents and anchor links

### Additional Features
1. **Copy Code Button**: A button is added to each code snippet allowing the content to be copied to clipboard.
2. **Syntax Highlighting**: The code blocks are highlighted for readability.
3. **MathJax Support**: For rendering LaTeX in Markdown files.

## Usage
Place your `.md` files inside the `blogarticles` folder. To run the script, execute:
```
node generateMarkdownIt.js
```

## Author
- Clievins Selva

## License
CC BY 4.0

## Contributing
Pull requests are welcome.
