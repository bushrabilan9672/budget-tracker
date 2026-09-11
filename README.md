# 💰 Budget Tracker - Week 1

## 📝 Description
This is the static skeleton of my Personal Budget & Expense Tracker. Built with **HTML** and **CSS** as the foundation for a fully functional budget tracking application.

This is a **portfolio project** that will grow throughout the course, adding new features each week.

---

## Assignment Requirements Fulfilled  week 2

## | Requirement | Status |
| `index.html` file 
| `style.css` file 
| Main heading "My Budget Tracker"
| Subheading describing the site 
| "Add Expense" section with 3 inputs
| "Your Expenses" section with placeholder
| CSS Element selectors 
| CSS Class selectors 
| CSS ID selectors 
| CSS file linked to HTML 
| DevTools practice 

---

##  Technologies Used

- **HTML5** - Page structure and content
- **CSS3** - Styling and layout
- **Git & GitHub** - Version control

---

## 📁 Project Structure

# My Budget Tracker

A simple budget tracking web page built with HTML and CSS as part of the Week 2 assignment.

## Project Structure

- `index.html` — the page structure and content
- `style.css` — all styling for the page
- `README.md` — this documentation file

## What Each Part Does

### Header
Displays the site title, a small logo image, and a subheading.

### How to Use (Details/Summary)
A collapsible section that explains how the tracker works. Click the summary text to expand or collapse it.

### Add Expense Form
A form with inputs for expense name, amount, category (dropdown), and date.
- The category dropdown has 5 options: Food, Transport, Rent, Entertainment, Other.
- The "Add Expense" button is `type="button"` — it does not submit yet (JavaScript comes in Week 6).
- All inputs have unique `id` attributes for future JavaScript use.

### Your Expenses Table
A table showing sample expense data with four columns: Name, Amount, Category, Date.
Styled with a dark header row, borders, padding, and alternating row colors.

### Budgeting Tip
An embedded YouTube video offering budgeting advice.

### Footer
A simple copyright notice.

## Advanced CSS Selectors Used

1. `tbody tr:nth-child(even)` — alternating row background colors
2. `tbody tr:hover` — row highlight on mouse hover
3. `#your-expenses td` — descendant selector for table cells
4. `#add-expense > h2` — direct child selector
5. `input:not([type="submit"])` — negation pseudo-class
6. `input:focus`, `select:focus` — focus states on form fields
