# DAY 09 ASSIGNMENT
JS
-- const colorDropdown = document.getElementById("colorDropdown") This line retrieves the HTML element with the ID "colorDropdown", which is a dropdown (select) element for selecting a color.

const bgColorDropdown = document.getElementById("bgColorDropdown") This line retrieves the HTML element with the ID "bgColorDropdown", which is a dropdown element for selecting a background color.

const paddingDropdown = document.getElementById("paddingDropdown") This line retrieves the HTML element with the ID "paddingDropdown", which is a dropdown element for selecting padding.

const fontSizeDropdown = document.getElementById("fontSizeDropdown") This line retrieves the HTML element with the ID "fontSizeDropdown", which is a dropdown element for selecting font size.

const fontWeightDropdown = document.getElementById("fontWeightDropdown")  This line retrieves the HTML element with the ID "fontWeightDropdown", which is a dropdown element for selecting font weight.


colorDropdown.addEventListener("change", () => { ... });: This line adds an event listener to the "change" event of the colorDropdown. When the user selects a different color from the dropdown, the code inside the curly braces { ... } will be executed.

targetDiv.style.color = colorDropdown.value;: Inside the event listener, this line sets the color CSS property of the targetDiv (the <div> element) to the value selected in the colorDropdown.

Similarly, the code adds event listeners to each of the other dropdowns (bgColorDropdown, paddingDropdown, fontSizeDropdown, fontWeightDropdown) and adjusts the corresponding CSS properties (backgroundColor, padding, fontSize, fontWeight) of the targetDiv based on the selected values from the dropdowns.