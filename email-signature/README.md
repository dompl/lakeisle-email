
# Email Template Project

This project uses MJML for responsive email template development, SASS for CSS pre-processing, and BrowserSync for real-time reloading during development.

## Prerequisites

- Node.js and npm
- MJML
- Node-sass
- BrowserSync

## Installation

Clone the repository and run `npm install` to install the dependencies.

```bash
git clone <repository-url>
cd <repository-directory>
npm install
```

## Development Scripts

- `npm start`: Starts MJML in watch mode, SASS watch mode, and BrowserSync for live reloading.
- `npm run mjml-watch`: Watches MJML file changes and compiles them to HTML in the `dist` directory.
- `npm run sass-watch`: Watches SASS file changes and compiles them to CSS in the `dist/assets/css` directory.
- `npm run serve`: Starts BrowserSync to serve files from the `dist` directory and watches for changes.

## Build Scripts

- `npm run build`: Compiles MJML and SASS files, minifies them, and outputs to the `dist` directory.
- `npm run mjml-build`: Compiles and minifies the MJML file to HTML.
- `npm run sass-build`: Compiles and minifies the SASS files to CSS.

## Directory Structure

- `assets/scss/`: SASS files for styling.
- `dist/`: Compiled and minified files ready for deployment.

## Usage

To start developing with live reloading, run:

```bash
npm start
```

To build the production-ready, minified files, run:

```bash
npm run build
```

The output will be in the `dist` directory.

## Contributing

Contributions are welcome! Please read the [contributing guide](CONTRIBUTING.md) to learn how to contribute to the repository.

## License

This project is licensed under the [MIT License](LICENSE).
