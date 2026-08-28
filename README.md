# TimeSheet Pro

TimeSheet Pro is an enterprise web-based timesheet and payroll management system developed by **PrasaTek System Solutions**[cite: 4]. It features cloud synchronization via Firebase Firestore, automated overtime and salary calculations, batch Excel imports, and PDF/Excel export capabilities[cite: 4, 6].

## Features

- **Authentication & Security**: Email/Password authentication, Email Verification, Google OAuth SSO, and password recovery workflows[cite: 2].
- **Emergency Lockdown**: Real-time administrative lockout engine that immediately restricts standard operator access in emergencies[cite: 2, 6].
- **Time Tracking**: Create and manage month-long timesheets with granular check-in/out timestamps and day-off indicators[cite: 4, 6].
- **Excel Importer Engine**: Batch import external timesheets with custom date/time parsing, auto-population of full month days, and instant template downloads (`PrasaTek_timesheet_pro_templete.xlsx`)[cite: 6].
- **Overtime & Holiday Detection**: Dynamic separation of Normal Hours and Mercantile Overtime referencing Sri Lankan holidays and Full Moon Poya days[cite: 6].
- **Salary & EPF Calculator**: Automatically compute gross and net salaries factoring in allowances, overtime tiers, and EPF deductions[cite: 4, 6].
- **Export Capabilities**: Client-side document generation to download timesheets and payslips directly in PDF and Excel (`.xlsx`) formats[cite: 4, 6].
- **Admin Suite & Audit Trails**: Multi-user permission assignment, approval status pipelines, and audit logging to Firestore[cite: 6].

## Technology Stack

- **Frontend**: HTML5, Vanilla JavaScript (ES6 Modules)[cite: 4]
- **Styling**: Tailwind CSS (CDN), FontAwesome 6[cite: 4, 6]
- **Cloud Backend**: Google Firebase (Firestore Database & Firebase Authentication)[cite: 4, 6]
- **Document Generation**: SheetJS (`xlsx`), jsPDF, jsPDF-AutoTable[cite: 4, 6]
- **Analytics**: Chart.js[cite: 6]

## Getting Started

1. Clone or download the project files[cite: 4].
2. Run the application using a local web server (e.g., VS Code *Live Server* or `npx serve`) due to ES module imports[cite: 4].
3. Open `index.html` in any modern web browser[cite: 4].
4. User accounts can be provisioned through the Firebase Console or directly via the built-in Admin Panel[cite: 4, 6].

## Contact & Support

- **Company**: PrasaTek System Solutions
- **Email**: info@prasatek.lk
- **Mobile**: +94 71 932 3239
- **Website**: [www.prasatek.lk](http://www.prasatek.lk)

## License

Copyright (c) 2026 PrasaTek System Solutions. All Rights Reserved.[cite: 3, 4]  
This software is strictly proprietary and confidential[cite: 3, 4].
