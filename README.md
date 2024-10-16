# custom-css-framework

## Framework Description
**Name:** Custom CSS Framework

This framework is designed for web developers and designers to provide a custom theme for standard HTML elements and utility classes.
It enables quick and efficient implementation of consistent designs, allowing for flexible customization.

## Installation
1. Clone the repository:
git clone https://github.com/your-username/custom-css-framework.git

2. Install SASS

3. Compile SCSS to CSS:
sass src/custom-css-framework.scss dist/custom-css-framework.css

4. Include the CSS file in HTML:
`<link rel="stylesheet" href="dist/custom-css-framework.css">`

## Usage Examples
1. Headings:
`<h1 class="fw-bold text-primary">Heading 1</h1>`
`<h2 class="text-secondary">Heading 2</h2>`

2. Buttons:
`<button class="btn btn-primary">Primary Button</button>`

3. Forms:
`<form><input type="text" class="form-input" placeholder="Enter text"><button type="submit" class="btn btn-secondary">Submit</button></form>`

4. Margin and Padding:
`<div class="m-2 p-3">Content goes here.</div>`

5. Background and Text Color:
`<div class="bg-secondary text-primary">Styled box.</div>`



## Customization
To customize the framework for your needs, you can override the default variables in the `_variables.scss` file.

1. Open `_variables.scss`:
    Navigate to the `src` folder and open the `_variables.scss` file.

2. Modify the Default Variables:
    Change the values of the existing variables or add new variables as needed.

3. Save the Changes:
    After modifying the variables, save the _variables.scss file.

4. Recompile the SCSS:
    Run the command to compile the SCSS files into CSS:
    sass src/custom-css-framework.scss dist/custom-css-framework.css

5. Check Your Changes: Refresh your HTML page to see the updated styles.

