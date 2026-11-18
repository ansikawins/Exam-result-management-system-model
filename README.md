# Exam Result Management System

A browser-based Exam Result Management System built with HTML, CSS, and JavaScript.

## Features

- Role-based views for administrators, faculty, and students
- Student management (add, edit, delete, and search)
- Subject management
- Internal and external marks entry with validation
- Automatic totals, percentages, grades, pass/fail status, and rankings
- Dashboard and performance reports
- Printable result sheets and CSV exports
- Light and dark theme

## Run the project

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.

No build tools or server-side setup are required for the demo.

## Demo sign-in accounts

The current demo page includes these sample sign-ins:

| Role | User ID | Password |
|---|---|---|
| Administrator | `admin` | `admin123` |
| Faculty | `F001` | `fac123` |
| Student | `S001` | `pass123` |

These are demonstration credentials only. Do not use real student information or real passwords in this public demo.

## Data storage

The application stores demo data in the browser's `localStorage`. Data is local to the browser/device and is not shared with other users or synchronized to a server. Clearing browser storage may remove saved changes.

## Publish with GitHub Pages

1. Upload `index.html` and `README.md` to the root of a public GitHub repository.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**, then click **Save**.
5. Wait for the Pages deployment to finish. GitHub will show the published website URL in the Pages section.

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- Browser localStorage
