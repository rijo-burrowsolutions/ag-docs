# AG Framework 

![AG Framework Badge](https://img.shields.io/badge/Framework-AG%20CSS-c8392b?style=for-the-badge) ![Status](https://img.shields.io/badge/Status-Production%20Ready-2d7d46?style=for-the-badge)

A lightweight, atomic CSS framework engineered for ultra-fast, consistent UI development. This repository contains the official documentation portal and the complete utility suite for the framework.

## 🚀 Features
- **Zero-Build Architecture**: Use it instantly without Webpack, Vite, or PostCSS configuration.
- **5-Tier Responsive System**: Seamlessly target `xs`, `sm`, `md`, `lg`, and `xl` breakpoints.
- **80+ Flex Utilities**: Comprehensive flexbox alignment, wrapping, and distribution.
- **Micro-class Naming System**: Intuitively string together concise class names like `.p-20` and `.s-f-ai-c`.
- **Live Interactive Playground**: Built directly into the documentation to test code immediately.
- **Smart Global Search**: Includes debounced, exact-match text highlighting for frictionless documentation browsing.

## 📁 Repository Structure
- `index.html`: The fully-featured, standalone documentation portal (Open directly in any browser).
- `ag.css`: The core internal CSS framework.
- `ag-extensions.css`: The official extension stylesheet providing Gap, Grid, Box-Shadow, and Z-Index utility classes not found in the base framework.

## 💻 Getting Started
To integrate the AG framework into your project, simply link the core CSS and the extensions in your `<head>`:

```html
<!-- 1. Core AG Framework (via CDN or local file) -->
<link rel="stylesheet" href="ag.css" />

<!-- 2. AG Extensions (Gap, Grid, Box Shadows, etc.) -->
<link rel="stylesheet" href="ag-extensions.css" />
```

## 📖 Using the Documentation
The documentation portal is a static file that requires zero local server setup. 
1. Simply double-click `index.html` to open it in your browser.
2. Use the **Global Search (Ctrl+K or click)** to instantly find utilities. 
3. Switch between Dark and Light mode via the top navigation toggle.

---
*Built for speed, consistency, and a premium developer experience.*
