# MediCare – Patient Management Portal

A front-end patient portal built with HTML5, CSS3, JavaScript (ES6+), Bootstrap 5 and Font Awesome. It has no backend: all data is stored in the browser's `localStorage`.

## Features

**Patient**
- Register, log in and manage a profile
- Browse doctors, view full profiles and book appointments
- View medical records and prescriptions, and print prescriptions

**Admin**
- Confirm, complete or cancel appointments
- View and delete patients
- Add, edit and delete doctors
- Add medical records and issue prescriptions

## Run it

1. Put `index.html` in a folder and open the folder in VS Code.
2. Install the **Live Server** extension.
3. Right-click `index.html` and choose **Open with Live Server**.

You can also double-click `index.html` to open it directly in a browser. An internet connection is needed for Bootstrap, Font Awesome and fonts.

## Demo logins

| Role    | Email                | Password   |
|---------|----------------------|------------|
| Patient | demo@medicare.com    | Demo@123   |
| Admin   | admin@medicare.com   | Admin@123  |

## Reset data

Open browser DevTools (F12), go to **Application → Local Storage**, clear the site's entries and refresh.

## Notes

- Demo project only. Do not enter real patient information.
- Passwords are only encoded, not securely hashed.
