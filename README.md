# Job Application Tracker | Manage Your Job Search

Job application tracker with status updates, search, filters, stats and CSV export, built with HTML, CSS and JavaScript.

**Live demo:** [Open the Job Application Tracker](https://soni200294.github.io/job-application-tracker/)

## Description
Built a job application tracker in JavaScript to record companies, roles and statuses. Includes live status counts, search, filters, CSV export and data saved with localStorage. Uses safe DOM rendering to prevent HTML injection. Deployed live on GitHub Pages.

## Output
When you open the live demo, the app shows:

- A heading **Job Application Tracker** with five count boxes: **Total, Applied, Interview, Offer, Rejected**
- A form to enter **company name**, **job role** and **status**, with an **Add Application** button
- A table listing every application with company, role, date and a status dropdown
- A **search box**, a **status filter** and an **Export CSV** button

Example after adding two applications:

| Company | Role | Date | Status |
|---|---|---|---|
| Infosys | Software Trainee | 3/10/2026 | Applied |
| TCS | Associate Engineer | 3/10/2026 | Interview |

The count boxes then show: Total 2, Applied 1, Interview 1, Offer 0, Rejected 0.

- Changing a status updates the counts instantly
- Searching or filtering shows only matching rows
- **Export CSV** downloads `applications.csv`
- Refreshing the page keeps all data (saved in the browser)

## Features
- Add, update and delete applications
- Live counts for each status
- Search by company or role
- Filter by status
- Export to CSV
- Data saved in the browser (localStorage)
- Safe handling of user input

## Tech Used
HTML, CSS, JavaScript (DOM, localStorage, Blob)

## Author
Gugulothu Soni | [GitHub](https://github.com/soni200294)
