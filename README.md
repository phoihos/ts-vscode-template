# ts-vscode-template

This is a minimal TypeScript project template for use with VS Code.

## VS Code's Extensions to use this template

- [**ESLint**](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) (Optional) : A static code analysis tool.
  - This extension doesn't have own bundled eslint module, so this template includes eslint module within the `package.json`.

- [**Prettier**](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) (Recommended) : An opinionated code formatter.
  - This extension has own bundled prettier module.
  - If you want to use prettier module from your project's local dependencies, install prettier module in your project:
    >
    ```shell
    # Install prettier locally
    npm install --save-dev --save-exact prettier
    ```

- [**Code Spell Checker**](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) (Recommended) : A basic spell checker.
  - This extension allows [**Customization**](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker#customization) via `.vscode/cspell.json`.

## Getting Started

Before to use this template, make sure you're running the latest version of VS Code. And [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer.

1. [**Download this template**](https://github.com/phoihos/ts-vscode-template/archive/refs/heads/master.zip) and Unzip to **your project folder**.
2. Open **your project folder** in VS Code.
3. Install dependencies:
    >
    ```shell
    # Install dependencies
    npm install
    ```
4. Enjoy coding with TypeScript!

## Debugging

1. Go to the Run view and select **'Launch Program'** or press <kbd>F5</kbd> key to start debugging.
2. Set breakpoints in any of the files.

## License

[CC0 1.0 (Public Domain)](LICENSE.md)
