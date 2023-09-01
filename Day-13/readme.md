# calander project
const monthName = document.getElementById("month-name") This line selects an HTML element with the ID "month-name" and stores it in the monthName variable.
const DayName = document.getElementById("day-name") This line selects an HTML element with the ID "day-name" and stores it in the DayName variable.
const Number = document.getElementById("date-num") This line selects an HTML element with the ID "date-num" and stores it in the Number variable.
const Year = document.getElementById "year" This line selects an HTML element with the ID "year" and stores it in the Year variable.

const date = new Date() This line creates a new JavaScript Date object, which represents the current date and time.

const month = date.getMonth(): This line retrieves the month from the date object and stores it in the month variable.

monthName.innerText = date.toLocaleString("en", { month: "long" }) This line updates the text content of the HTML element represented by monthName.

DayName.innerText = date.toLocaleString("en", { weekday: "long" }): This line updates the text content of the HTML element represented by DayName.

Number.innerText = date.getDate(); This line updates the text content of the HTML element represented by Number with the day of the month obtained using getDate().

Year.innerText = date.getFullYear() This line updates the text content of the HTML element represented by Year with the current year obtained using getFullYear().