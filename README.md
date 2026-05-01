# 🧑‍💼 Employee Management System

A web-based Employee Management System designed to efficiently manage employee records, including personal information, geographic locations, and searchable listings. The application provides a responsive interface with interactive mapping and browser-based data storage for a smooth user experience.

---

## 📌 Overview

This project is a full client-side + lightweight backend-integrated system for managing employee data. It allows users to add employees, view structured listings, and visualize their locations on an interactive map using a free mapping solution.

The system supports real-time updates and combines external data (if available) with browser storage for better flexibility.

---

## ✨ Key Features

* **Employee Registration**
  Add employees with personal details and location coordinates.

* **Employee Directory**
  View all employees in a structured table with search and pagination.

* **Location Visualization**
  Display employee locations on an interactive map with markers and popups.

* **Smart Marker Handling**
  Automatically adjusts overlapping locations for better visibility.

* **Hybrid Data Storage**
  Uses browser storage for added employees and optional backend data sources.

* **Responsive Design**
  Fully optimized for desktop, tablet, and mobile devices.

---

## 🛠️ Technology Stack

* **HTML5** – Page structure
* **CSS3** – Styling and responsive layout
* **JavaScript (ES6+)** – Application logic and interactivity
* **Bootstrap 5** – UI components and responsive grid system
* **Font Awesome** – Icons
* **Leaflet.js** – Interactive mapping library
* **OpenStreetMap** – Free map tile provider
* **Browser Storage (localStorage / sessionStorage)** – Data persistence

---

## 📁 Project Structure

employee-management-system/
│
├── index.html        # Home page / dashboard
├── add.html          # Add employee form
├── view.html         # Employee listing (search, sort, pagination)
├── location.html     # Interactive map view (Leaflet + OSM)
└── README.md         # Project documentation

---

## ▶️ How to Run

* Open `index.html` directly in a modern web browser
* No build tools or server required

### ⚠️ Requirements:

Internet connection is needed for:

* Bootstrap CDN
* Font Awesome
* OpenStreetMap tiles

---

## 🚀 Usage

### 🏠 Home Page

Navigation hub for all system features.

---

### ➕ Add Employee

Users can add employees with:

* Name and contact details
* City and country
* Latitude and longitude for mapping

Data is stored in browser storage and rendered dynamically.

---

### 📋 Employee Directory

Displays employee data with:

* Search functionality
* Pagination (5 records per page)
* Structured table layout

---

### 🗺️ Location Map

Interactive map features:

* Employee markers on map
* Popup showing employee details
* Smart handling of overlapping locations
* Auto-refresh updates

---

## 🔄 Data Management

* **localStorage** → Stores newly added employees
* **sessionStorage** → Temporary session data
* **Optional external source** → Used if backend data exists

All data is merged dynamically at runtime.

---

## 🧠 Project Purpose

This project demonstrates:

* Frontend development skills
* JavaScript logic and DOM manipulation
* Interactive map integration
* Data handling and storage techniques
* Real-world UI system design

---

## 🏆 Key Highlights

* Fully functional employee tracking system
* No paid APIs or billing required
* Clean, responsive UI design
* Real-time map visualization
* Portfolio-ready project for internships
