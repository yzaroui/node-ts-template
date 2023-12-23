
# Node.js TypeScript Template

## Overview

This repository offers a Node.js project template using TypeScript, adhering to common best practices. It's an ideal starting point for new Node.js projects.

## Features

- **TypeScript Support:** Ready-to-use setup for TypeScript.
- **Development Tools:** Includes ESLint, Prettier, and `ts-node-dev` for an enhanced development workflow.
- **Build and Run Scripts:** Streamlined scripts for development, build, and execution.
- **MIT License:** Open for both personal and commercial use.

## Getting Started

### Prerequisites

- Node.js
- pnpm

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yzaroui/node-ts-template <app name>
    cd <app name>
    rm -rf ./.git/
    git init
    ```
1. Install dependencies using pnpm:
    ```sh
    pnpm install
    ```

### Usage

- **Development:**
  ```sh
  pnpm run dev
  ```
  Starts the TypeScript Node application in development mode with hot reload.

- **Build:**
  ```sh
  pnpm run build
  ```
  Compiles TypeScript files to JavaScript in the `dist/` directory.

- **Start:**
  ```sh
  pnpm start
  ```
  Runs the built JavaScript application from the `dist/` directory.

- **Linting:**
  ```sh
  pnpm run lint
  ```
  Lints TypeScript files using ESLint.

- **Formatting:**
  ```sh
  pnpm run format
  ```
  Formats the codebase using Prettier.

## Contributing

Feel free to submit pull requests or open issues to contribute to this project.

## License

Licensed under the MIT License - see the LICENSE file for details.

---

For additional details, visit the [project repository](https://github.com/yzaroui/node-ts-template).
