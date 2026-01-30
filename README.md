📅 Sistema de Reservas – PHP

Web application for event and reservation management, built with PHP, Bootstrap 5, and JavaScript, featuring an interactive calendar, modal-based CRUD operations, and a clean user interface.

This project demonstrates classic PHP frontend-backend integration, UI state handling, and client-side interaction using modern libraries.

🚀 Tech Stack
Backend

PHP (server-side rendering)

Base URL configuration for environment handling

Frontend

HTML5

Bootstrap 5 (UI & responsive design)

JavaScript (ES6)

Libraries & Plugins

Moment.js – Date handling

SweetAlert2 – User-friendly alerts

Custom JS modules

Bootstrap Modal – CRUD forms

Calendar plugin (JS-based)

✨ Features

📆 Interactive calendar view

➕ Create events

✏️ Edit existing reservations

🗑️ Delete events

🎨 Custom event color selection

🧾 Modal-based form handling

🔔 Visual feedback with alerts

📱 Responsive layout

🧩 Application Flow
User Action
   ↓
JavaScript (app.js)
   ↓
PHP Controller / Endpoint
   ↓
Response → UI Update


The system uses modals to manage events dynamically without full page reloads, improving user experience.

📁 Project Structure (Simplified)
/
├── index.php
├── Assets/
│   ├── css/
│   │   └── main.min.css
│   ├── js/
│   │   ├── app.js
│   │   ├── main.min.js
│   │   ├── moment.js
│   │   ├── sweetalert2.all.min.js
│   │   └── es.js

⚙️ Requirements

PHP 7.4+

Local server (XAMPP, WAMP, Laragon, etc.)

Modern browser (Chrome, Edge, Firefox)

▶️ How to Run

Clone the repository

git clone https://github.com/your-username/reservas-php.git


Place the project inside your server directory
(e.g. htdocs for XAMPP)

Configure base_url if needed

Start Apache and open:

http://localhost/reservas-php

🎯 Key Concepts Demonstrated

PHP templating with dynamic paths

Modal-driven CRUD UX

Frontend-backend coordination

Date handling and formatting

Clean UI with Bootstrap

JavaScript-based state management

📌 Notes

This project focuses on frontend interaction + PHP rendering

Database integration can be added or extended

Ideal as a base for booking systems, agendas, or scheduling apps

👤 Author

Gonzalo Rodríguez
💻 Software Developer | Backend & Data Oriented
📧 gnrd.developer@gmail.com

🔗 LinkedIn | GitHub
