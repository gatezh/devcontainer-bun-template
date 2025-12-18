# Devcontainer bun template

Minimal template repo containing only a `.devcontainer` that uses a pre-built **Alpine** image with **bun** installed.

Uses image from [gatezh/devcontainer-images](https://github.com/gatezh/devcontainer-images).


## Purpose

Starter container for creating "what used to be Node" apps (React, Vite, Next, etc.) — safe, fast, minimal, bun-first.


## Quick start

1. Clone this repo.
2. Open in VS Code and choose **Reopen in Container** (or use *Remote - Containers*).
3. The container pulls the pre-built image and installs the listed extensions.



## VS Code extensions (auto-installed via `customizations.vscode.extensions`)



```
// **General**
// Prettier - Code Formatter - General code formatting
"esbenp.prettier-vscode",
// Code Spell Checker - Spell checking
"streetsidesoftware.code-spell-checker",
// YAML - YAML support
"redhat.vscode-yaml",
// Markdown Preview Github Styles - Markdown preview
"bierner.markdown-preview-github-styles",

// **JS**
// Bun VS Code - bun tooling (run, dev, inspector)
"oven.bun-vscode",
// ESLint - JavaScript linting
"dbaeumer.vscode-eslint",
// NPM Intellisense - NPM package intellisense
"christian-kohler.npm-intellisense",
// TS Error Translator - Translates TypeScript errors into readable suggestions
"mattpocock.ts-error-translator",

// **CSS**
// Color Info - Provides color information (names, values)
"bierner.color-info",
// Colorize - Colorizes code with visual swatches
"kamikillerto.vscode-colorize",
// Tailwind Fold - Fold Tailwind utility classes for readability
"stivo.tailwind-fold",
// Tailwind CSS IntelliSense - Tailwind CSS completions & linting
"bradlc.vscode-tailwindcss"
```