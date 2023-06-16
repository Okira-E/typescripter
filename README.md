# TypeScript Starter Kit

### This starter kit provides a basic setup for any TypeScript project with tsc (TypeScript compiler) and prettier (code formatter). It includes a sample package.json file to help you get started quickly.

### How to use this starter kit?

1. Clone this repository

```bash
git clone https://github.com/Okira-E/typescripter
```

2. Install dependencies

```bash
npm install
```

### Usage

## Once the installation is complete, you can use the following npm scripts:

- `compile`:  Compiles the TypeScript code using tsc. The compiled JavaScript files will be generated in the ./build directory.
- `start`: Runs the compiled JavaScript code using node. This script assumes the compiled files are in the ./build/src directory.
- `clean`: Deletes the ./build directory and its contents.
- `format`: Formats the TypeScript code using prettier. This script formats all .ts files in the src directory.

### To execute a script, use the following command:

```bash
npm run <script-name>
```

## Project Structure

### The project structure assumes the following directory structure:

```
.
├── build/
├── node_modules/
├── src
│   └── main.ts
├── .prettierrc
├── package.json
└── tsconfig.json
```
- The TypeScript source files should be placed in the src directory.
- The compiled JavaScript files will be generated in the build directory.
- The .prettierrc file contains the configuration for prettier.
- The package.json file includes the project's metadata and scripts.
- The tsconfig.json file contains the configuration for tsc.

### Feel free to modify the project structure and configuration files as per your needs.

