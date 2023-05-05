# How to Create a Monthly Calendar Using HTML, CSS and JavaScript


![](images/finished-calendar.png)

You are going to learn how to create a monthly calendar using html, css and javascript. 

Use the JavaScript’s `Date` object to get the current month and year and generate a calendar according to the month. 

Below is a step-by-step coding tutorial. 

- Get the source code for this project by clicking on here; [Source Code](https://github.com/DrVicki/my-claendar).

## Instructions

1. Open VS Code
2. Click on "Terminal" at the top
3. Move to your desktop.
	- `cd desktop`
4. Create project folder
	- `mkdir my-calendar`
5. Change Directory to your project
	- `cd my-calendar`
6. Create 3 files: `index.html`, `styles.css`, and `script.js`
	- `touch index.html`
	- `touch styles.css`
	- `touch script.js`
7. Save your work
	- "File" and top of screen
	- "Save All"

## Code the Calendar

1. Set up HTML
	- Add the boiler plate of the `html` document
	- inside `body` create container `div`. 
	- in the `div` container create an `h2` tag to display the current month and year. 
	- use `table` tag to build the calendar for the current month and year.

```
// index.html

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Calendar</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="container">
      <h2 id="info"></h2>
      <table id="calendar">
        <thead id="days"></thead>
        <tbody id="dates"></tbody>
      </table>
    </div>
    <script src="script.js"></script>
  </body>
</html>
```