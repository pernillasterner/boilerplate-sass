# Setting up a Sass Project

## About the Project

This project demonstrates how to set up a basic Sass structure. It includes a simple HTML file and organized Sass files to streamline CSS development. The primary goal is to showcase a well-structured workflow for managing styles using Sass.

## File Structure

The project is organized as follows:

project-root/
│
├── dist/
│ ├── css/
│ │ └── style.css
│ └── index.html
│
├── sass/
│ ├── style.scss
│ ├── resets.scss
│ └── variables.scss

- **dist/css/style.css**: Compiled CSS file.
- **dist/index.html**: HTML file to demonstrate the styled output.
- **sass/style.scss**: Main Sass file that imports other Sass files.
- **sass/resets.scss**: Contains reset styles to ensure consistent styling across browsers.
- **sass/variables.scss**: Contains Sass variables for colors, fonts, etc.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [Sass](https://sass-lang.com/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/sass-project.git
   cd sass-project

   ```

2. Install Sass
   npm install -g sass

3. Run Sass
   sass sass/style.scss dist/css/style.css

See the Sass website for more ways to install Sass.
https://sass-lang.com/install/
