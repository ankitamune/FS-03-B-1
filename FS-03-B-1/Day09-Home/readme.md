# DAY 09 Homework
HTML AND CSS 
-- firstly created one input box and button using html
-- adding some styles to the input box and button

JAVASCRIPT

-- contentInput = document.getElementBy("contentInput")
in this line  retrieves the HTML element with the ID "contentInput", which is an input element where users can type in the content they want to add.

-- addButton = document.getElementById("addButton")In this line retrieves the HTML element with the ID "addButton", which is a button that users can click to add the content from the input field to the output

-- outputDiv = document.getElementById("output")
This line retrieves the HTML element with the ID "output", which is a <div> element that will contain the <p> tags with the added content.

-- addButton.addEventListener("click", () => { ... })
 This line adds an event listener to the "Add" button. When the button is clicked, the code inside the curly braces { ... } will be executed.

 --if (text.trim() !== "") { ... } This line checks if the text variable has content after removing any leading and trailing whitespace. If it's not an empty string, the code inside the curly braces { ... } will be executed.
const newParagraph = document.createElement("p")
In this creates new paragraph

newParagraph.textContent = text This line sets the textContent property of the newly created <p> element to the value of the text variable. 
