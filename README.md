# 💰 My Budget Tracker

A simple, static budget tracking web page built with HTML and CSS as part of the Week 2 assignment. This project will be extended over the course with interactivity and persistence.

## Project Structure

- `index.html` — the page structure and content
- `style.css` — all styling for the page
- `README.md` — this documentation file

## Description

This is the static skeleton of a Personal Budget & Expense Tracker. The page includes an Add Expense form, a Your Expenses table, a collapsible How To section, and an embedded budgeting tip video.

## What Each Part Does

### Header
Displays the site title, a small logo image, and a subheading.

### How to Use (Details/Summary)
A collapsible section that explains how the tracker works. Click the summary text to expand or collapse it.

### Add Expense Form
A form with inputs for expense name, amount, category (dropdown), and date.
- The category dropdown has options like Food, Transport, Rent, Entertainment, and Other.
- The "Add Expense" button is `type="button"` — it does not submit yet (JavaScript will be added later).

### Your Expenses Table
A table showing sample expense data with four columns: Name, Amount, Category, Date. Styled with a dark header row, borders, padding, and alternating row colors.

### Budgeting Tip
An embedded YouTube video offering budgeting advice.

### Footer
A simple copyright notice.

## Advanced CSS Selectors Used

1. `tbody tr:nth-child(even)` — alternating row background colors
2. `tbody tr:hover` — row highlight on mouse hover
3. `#your-expenses td` — descendant selector
4. `#add-expense > h2` — direct child selector
5. `input:not([type="submit"])` — negation pseudo-class
6. `input:focus`, `select:focus` — focus states

## Technologies Used

- HTML5 — Page structure and content
- CSS3 — Styling and layout
- Git & GitHub — Version control

## Notes

This file was merged to resolve a remote/local conflict; it contains the consolidated Week 2 content.
