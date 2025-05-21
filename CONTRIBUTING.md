# Contributing to Makerspace C4 Models

Thank you for your interest in contributing to our Makerspace architecture documentation! This guide provides basic information on how to contribute to our C4 modeling project.

## Before You Start

- Familiarize yourself with [C4 modeling](https://c4model.com/) if you're new to this approach
- Review our existing diagrams in the `assets` directory
- Check existing issues to see where help is needed

## Basic Workflow

1. **Set up**: Install Node.js and LikeC4 (`npm install -g likec4`)
2. **Branch**: Create a branch for your changes
3. **Model**: Update or create `.c4` files
4. **Preview**: Generate diagrams to verify your changes
   ```
   npx likec4 export png -o ./assets
   ```
5. **Submit**: Create a pull request with your changes

## Modeling Guidelines

- Focus on clarity and simplicity
- Maintain consistent naming conventions
- Provide descriptions for all elements
- We primarily focus on Context and Container levels of the C4 model

## Generating Diagrams

After making changes to the C4 model files, regenerate diagrams:

- **Static diagrams**: `npx likec4 export png -o ./assets`
- **Interactive views**: `npx likec4 build -o ./dist`

### VSCode Integration

For a more efficient workflow, install the [VSCode extension](https://likec4.dev/tooling/vscode/) for LikeC4 which provides real-time diagram previews as you edit:

1. Open VSCode Extensions (Ctrl+Shift+X / Cmd+Shift+X)
2. Search for "LikeC4"
3. Install the official extension
4. Open a `.c4` file and use the "LikeC4: Open Preview" button to see your diagrams update in real time

## Questions?

If you have questions or need help, please open an issue or contact the project maintainers.

Thank you for contributing to better architecture documentation for our Makerspace systems!