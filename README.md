# custom-css-framework

## Framework Description
Name: QnJ Custom CSS Framework

This framework is designed for web developers and designers to provide a custom theme for standard HTML elements and utility classes.<br>
It enables quick and efficient implementation of consistent designs, allowing for flexible customization.

## Installation
1. Clone the repository:<br>
git clone https://github.com/your-username/custom-css-framework.git

2. Install SASS:<br>
Ensure you have Node.js and npm installed.<br>
If not, download and install them from nodejs.org.<br>
Once Node.js is installed, install SASS by running the following command in terminal:<br>
npm install -g sass

3. Compile SCSS to CSS:<br>
Once the SCSS files created, compile them into CSS by running the following command in terminal:<br>
sass src/custom-css-framework.scss dist/custom-css-framework.css

4. Include the CSS file in HTML:<br>
`<link rel="stylesheet" href="dist/custom-css-framework.css">`

## Usage Examples
1. Headings: <br>
`<h1 class="fw-bold text-primary">Heading 1</h1>`<br>
`<h2 class="text-secondary">Heading 2</h2>`<br>

2. Buttons:<br>
`<button class="btn btn-primary">Primary Button</button>`

3. Forms:<br>
`<form><input type="text" class="form-input" placeholder="Enter text"><button type="submit" class="btn btn-secondary">Submit</button></form>`

4. Margin and Padding:<br>
`<div class="m-2 p-3">Content goes here.</div>`

5. Background and Text Color:<br>
`<div class="bg-secondary text-primary">Styled box.</div>`

6. Functions:<br>
(1) lighten-color($color, $amount):<br>
`.example {
  background-color: lighten-color($primary-color, 20%);
}`
(2) darken-color($color, $amount):<br>
`.header {
  background-color: darken-color($secondary-color, 15%);
}`
(3) spacing($value, $unit: px):<br>
`.button {
  padding: spacing(1.5, em);
}`
(4) border-radius($radius): <br>
`.box {
  border-radius: border-radius(10);
}`
(5) responsive-font-size($base-size, $scale-factor): <br>
`.p {
  font-size: responsive-font-size(16, 1.5);
}`


## Customization
To customize the framework for your needs, you can override the default variables in the `_variables.scss` file.

1. Open `_variables.scss`:<br>
    Navigate to the `src` folder and open the `_variables.scss` file.

2. Modify the Default Variables:<br>
    Change the values of the existing variables or add new variables as needed.

3. Save the Changes:<br>
    After modifying the variables, save the _variables.scss file.

4. Recompile the SCSS:<br>
    Run the command to compile the SCSS files into CSS:
    sass src/custom-css-framework.scss dist/custom-css-framework.css

5. Check Your Changes:<br>
    Refresh your HTML page to see the updated styles.

