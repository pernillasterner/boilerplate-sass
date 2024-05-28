# Sass Boilerplate

## 📖 About the Boilerplate

My goal with this boilerplate is to have everything ready to go when starting a new project, with a structure that is easy to use and enhance.

I've included mixins to handle breakpoints, variables for colors, and functions for media queries to simplify the process of creating responsive and easy-to-maintain styles.


## 🗂 File Structure

I've organized the files into three categories: globals, layout, and util.

```
project-root/
│
├── app/
│   ├── js/
│   └── scss/
│       ├── globals/
│       │   ├── _boilerplate.scss
│       │   ├── _typography.scss
│       │   ├── _colors.scss
│       │   ├── _index.scss
|       ├── layout/
│       │   ├── _grid.scss
│       │   ├── _index.scss
|       ├── util/
|       |   ├── _breakpoints.scss
│       │   ├── _fonts.scss
|       |   ├── _functions.scss
│       │   ├── _index.scss
│       └── style.scss
│
├── dist/
│   └── css/
│       ├── style.css
│       └── style.map
│
└── index.html
```

## 🚀 Getting Started

### 📋 Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [Sass](https://sass-lang.com/)

### 📦 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/pernillasterner/boilerplate-sass
   cd boilerplate-sass

   ```

2. Install Sass

   ```
   npm install -g sass
   ```

3. Run Sass
   ```
   sass --watch app/scss/style.scss dist/css/style.css
   ```

### 🌐 Usage

After setting up the project, you can start editing the Sass files under the app/scss/ directory. The changes will be automatically compiled into the dist/css/style.css file.
