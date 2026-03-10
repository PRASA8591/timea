# TimeSheet Pro

TimeSheet Pro is a web-based timesheet management system created by PrasaTek System Solutions. It features cloud syncing via Firebase, salary calculations, and exporting options to Excel and PDF formats.

## Features

- **User Authentication**: Secure login system with standard and admin roles
- **Time Tracking**: Create and manage timesheets with check-in and check-out durations.
- **Salary Calculator**: Calculate net pay by taking into account basic pay, allowances, overtime, and deductions (like EPF).
- **Dashboard**: Track hours, timesheets, and saved salary reports.
- **Cloud Storage**: Secure and continuous syncing with Firebase Cloud Firestore.
- **Exports**: Ability to print sheets or download them as PDF/Excel.

## Technologies Used

- HTML5
- JavaScript (ES6 Modules)
- Tailwind CSS via CDN for styling
- FontAwesome for icons
- jsPDF & SheetJS for data export
- Firebase Firestore (Cloud Database)

## Setup and Usage

1. Clone the project or open it in your code editor.
2. Since Firebase relies on ES modules, we recommend running this project via a local HTTP server such as `Live Server` in VS Code or `npx serve`.
3. Open `index.html` in your web browser.
4. Default users can be configured through the Firebase database. Ask the administrator for an account setup.

## License
**Proprietary and Confidential**
Copyright (c) 2026 PrasaTek System Solutions. All Rights Reserved.

This code, its structure, and its contents are strict intellectual property of PrasaTek System Solutions. **You are strictly prohibited from copying, modifying, reproducing, distributing, or publishing any part of this software, its database models, or its source code.** Any unauthorized use is considered a direct violation of copyright and may be subject to legal action.
