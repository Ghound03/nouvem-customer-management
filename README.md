# NOUVEM Customer Management System

A single-page customer management application built with HTML, CSS, and JavaScript as a demonstration project for the NOUVEM Junior Software Solution Specialist application.

## Features

- Add new customers
- View customer details in a table
- Edit existing customers
- Delete customers with confirmation
- Search customers by company, contact, email, or location
- Filter customers by status
- View live dashboard statistics
- Prevent duplicate company names and email addresses
- Display success and error messages
- Save customer records in the browser using localStorage
- Responsive layout for smaller screens

## How to Run

1. Download or clone this repository.
2. Open `index.html` in a web browser.
3. Use **Add Customer** to create a record, or use the Edit and Delete buttons to manage existing records.

No installation, server, or external dependencies are required.

## Technologies Used

- HTML5 — page structure and forms
- CSS3 — styling and responsive layout
- JavaScript — customer management, validation, search, and filtering
- localStorage — browser-based data persistence

## Customer Statuses

Each customer has one of three statuses:

- Active
- Implementation
- Support Required

The dashboard updates its counts when customer records change.

## Data Storage and Limitations

This is a front-end demonstration, not a production customer management system.

Customer data is stored in the browser's localStorage. It is not shared between devices or browsers, and it may be lost if browser storage is cleared. The application does not include user accounts, a backend, or a database.

The initial customer records are fictional examples. Do not use real or sensitive customer information in this demo.

## Project Structure

```text
nouvem-customer-management/
├── index.html
└── README.md
```

All application HTML, CSS, and JavaScript are contained in `index.html`.

## Testing

The application can be tested by adding, editing, and deleting customers; refreshing the page to check persistence; searching and filtering; and checking that dashboard totals update correctly.