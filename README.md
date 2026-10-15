# JavaScript Assignments & Product Inventory Analytics Dashboard

**Student:** Satyam Pratap  
**College:** DDU Gorakhpur University  
**Internship domain:** Web Development — JavaScript  
**Stack:** HTML5, CSS3, Vanilla JavaScript

## Project overview
This repository contains six interactive JavaScript assignment pages, separate reusable JavaScript source files, expected-output notes, and a featured Product Inventory & Analytics Dashboard mini project.

## Run locally
No installation or build step is needed. Open `index.html` in a modern browser. For the best experience, use a simple local web server or GitHub Pages so all linked files are served from the same folder.

## Files
- `index.html` — portfolio landing page and navigation.
- `assets/styles.css` — portfolio design and responsive layout.
- `assets/app.css` — shared styles for assignment pages and dashboard.
- `assignments/` — six interactive assignment pages.
- `js/` — six assignment source files and the dashboard application logic.
- `mini-project/index.html` — full inventory dashboard.
- `expected-output/` — sample outputs for the assignment tasks and mini project.

## Assignments
1. Variables and data types (`var`, `let`, `const`, `typeof`)
2. Operators and tip calculator with validation
3. Conditionals, switch, and ternary pass/fail
4. Loops, `break`, and `continue`
5. Functions, default parameters, arrow functions, and scope
6. Product objects and `forEach`, `filter`, and `map`

## Mini project features
- Add, edit, and delete inventory products.
- Validate names, prices, quantities, and duplicate SKUs.
- Search, filter by price tier, and sort products.
- Dashboard KPIs: product count, total units, inventory value, and products under $200.
- Budget / Standard / Premium labels based on unit price.
- Tax and discount calculator.
- Export inventory as CSV.
- Persist inventory with `localStorage`.
- Restore original sample data.

## Sample starting inventory
Laptop ($800 × 1), Mouse ($25 × 2), Keyboard ($45 × 1). Starting inventory value is **$895** (calculated as price × quantity). You can add Monitor ($150 × 1) in the dashboard; inventory value then becomes **$1,045**. The dashboard computes all totals dynamically.

## Notes
- This project uses no third-party JavaScript libraries.
- The source code uses browser APIs such as `localStorage`, `Blob`, and `URL.createObjectURL` for persistence and CSV export.
- Keep personal contact details out of the public repository unless you intentionally want them public.
