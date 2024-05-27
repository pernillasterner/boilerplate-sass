# Setting up a Sass Project

## About the Project

This project demonstrates how to set up a basic Sass structure. It includes a simple HTML file and organized Sass files to streamline CSS development. The primary goal is to showcase a well-structured workflow for managing styles using Sass.

## File Structure

The project is organized as follows:

```
project-root/
│
├── app/
│   ├── js/
│   └── scss/
│       ├── style.scss
│       ├── _resets.scss
│       └── _variables.scss
│
├── dist/
│   └── css/
│       ├── style.css
│       └── style.map
│
└── index.html
```

## Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [Sass](https://sass-lang.com/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/pernillasterner/theSociety-Sass
   cd theSociety-Sass

   ```

2. Install Sass

   ```
   npm install -g sass
   ```

3. Run Sass
   ```
   sass --watch app/scss/style.scss dist/css/style.css
   ```
