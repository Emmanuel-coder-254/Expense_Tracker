# My Budget Tracker

## Project Overview

My Budget Tracker is a simple web-based expense tracking project built using **HTML5 and CSS3**.

This project was originally created in Week 1 and has now been upgraded with an expense table, an improved expense form, multimedia content, interactive elements, and advanced CSS selectors.

The purpose of the project is to provide a simple interface where users can enter expense information and view their expenses in an organized table.

---

## Project Files

The project contains three main files:

```text
My-Budget-Tracker/
│
├── index.html
├── style.css
└── README.md
```

### 1. index.html

The `index.html` file contains the structure and content of the Budget Tracker.

It includes:

* Main page heading
* Budget Tracker logo
* Add Expense form
* Expense name input
* Amount input
* Category dropdown
* Date input
* Add Expense button
* Expense table
* Five sample expense records
* How to use section
* Embedded YouTube budgeting video
* Footer

---

## 2. Add Expense Form

The Add Expense section allows users to enter information about an expense.

The form contains:

* **Expense Name**
* **Amount**
* **Category**
* **Date**
* **Add Expense button**

The category field was changed from a normal text input into a dropdown menu.

The dropdown contains five options:

1. Food
2. Transport
3. Rent
4. Entertainment
5. Other

The form uses a proper `<form>` element, and the button uses:

```html
<button type="button">Add Expense</button>
```

The button does not add expenses yet because JavaScript functionality will be introduced in a later stage of the project.

---

## 3. Expense Table

The original "No expenses yet" placeholder was replaced with a properly structured HTML table.

The table uses:

* `<table>`
* `<thead>`
* `<tbody>`
* `<tr>`
* `<th>`
* `<td>`

The table contains four columns:

| Column   | Description         |
| -------- | ------------------- |
| Name     | Name of the expense |
| Amount   | Amount spent        |
| Category | Expense category    |
| Date     | Date of the expense |

Five sample expenses have been added to demonstrate how the table works.

---

## 4. Multimedia Content

A small logo has been added near the main heading using the `<img>` element.

The image contains:

* `src`
* `alt`
* `width`

A YouTube video has also been embedded using an `<iframe>`.

The iframe contains:

* `src`
* `width`
* `height`
* `title`
* `frameborder`

The video provides budgeting-related information.

---

## 5. Interactive Elements

A collapsible section was added using the HTML `<details>` and `<summary>` elements.

The section is called:

**How to use this tracker**

It explains how users can enter expense information using the form.

The table also has a hover effect. When the user moves the mouse over a table row, its background changes.

The Add Expense button uses:

```css
cursor: pointer;
```

This displays a hand cursor when the user moves the mouse over the button.

---

## 6. CSS Styling

The `style.css` file controls the appearance of the Budget Tracker.

The stylesheet includes:

* Page background styling
* Header styling
* Section styling
* Form styling
* Input styling
* Select dropdown styling
* Button styling
* Table styling
* Table borders
* Table cell padding
* Table header styling
* Alternating table row colors
* Table hover effects
* Input focus effects
* Video styling
* Footer styling

---

## 7. Advanced CSS Selectors

Several advanced CSS selectors were used in the project.

### Descendant Selector

```css
.expenses-section th,
.expenses-section td
```

This applies styling to table headers and table cells inside the expenses section.

### Position-Based Selector

```css
.expenses-section tr:nth-child(even)
```

This creates alternating background colors for the table rows.

### Negation Pseudo-Class

```css
input:not([type="submit"])
```

This targets input elements that are not submit buttons.

### Focus Pseudo-Class

```css
input:focus,
select:focus
```

This changes the appearance of an input or dropdown when the user selects it.

### Hover Pseudo-Class

```css
.expenses-section tr:hover
```

This changes the background color of a table row when the mouse moves over it.

---

## 8. Technologies Used

The project was created using:

* **HTML5**
* **CSS3**

No JavaScript functionality has been added yet.

---

## 9. Current Functionality

The current version allows users to:

* View the Budget Tracker interface
* View sample expenses
* Select an expense category
* Enter expense information
* Open and close the "How to use this tracker" section
* Watch the embedded budgeting video
* Interact with table rows using hover effects
* See input focus effects

The Add Expense button is currently not connected to JavaScript.

---

## 10. Future Improvements

Future versions of the project can include JavaScript functionality.

Possible improvements include:

* Adding new expenses dynamically
* Calculating total expenses
* Removing expenses
* Editing expenses
* Filtering expenses by category
* Saving expenses
* Adding a monthly budget
* Showing remaining budget
* Adding charts and expense summaries

---

## Author

**Mtendechi Emmanuel**

## Project Status

**Completed HTML & CSS Technical Coding Challenge**

