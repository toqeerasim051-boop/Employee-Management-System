# Employee Management System

A web-based Employee Management System designed to efficiently manage employee records, including personal information, geographic locations, and searchable listings. The application integrates REST APIs, Google Maps, and browser-based storage to provide a seamless and responsive user experience.

---

## Overview

This project provides a complete client-side solution for managing employee data with real-time synchronization between backend services and local storage. It supports employee registration, data visualization, and interactive mapping of employee locations.

---

## Key Features

- **Employee Registration**  
  Add new employees with detailed personal and geographic information.

- **Employee Directory**  
  View all employees in a structured table with search, sorting, and pagination capabilities.

- **Location Visualization**  
  Display employee locations on an interactive Google Map with dynamic marker handling.

- **Hybrid Data Persistence**  
  Combines backend API storage with browser `localStorage` for improved reliability and offline resilience.

- **Authentication Mechanism**  
  Implements activation-code-based API authentication for secure data transactions.

- **Responsive Interface**  
  Fully responsive design compatible with desktop, tablet, and mobile devices.

---

## Technology Stack

- **HTML5** – Semantic and structured markup
- **CSS3** – Custom styling, layout design, and responsiveness
- **JavaScript (ES6+)** – Application logic, asynchronous operations, and DOM manipulation
- **Bootstrap 5** – UI components and responsive grid system
- **Font Awesome** – Iconography
- **Google Maps JavaScript API** – Location rendering and map interaction
- **REST API Integration** – External backend communication

---

## Project Structure
employee-management-system/
│
├── index.html # Landing / Home page
├── add.html # Employee registration form
├── view.html # Employee listing (search, sort, pagination)
├── location.html # Google Maps-based visualization
└── README.md # Project documentation

Launch the application:
Open index.html directly in a modern web browser
No build process or local server is required

Note: Internet connectivity is required for API requests, Google Maps, Bootstrap CDN, and Font Awesome resources.

Usage
Home Page

Serves as the central navigation hub for all system functionalities.

Add Employee

Users can register employees by providing:

Name and contact details
City and country information
Latitude and longitude for map integration

Upon submission:

An activation code is requested from the backend
Employee data is stored in both the API and local storage
Confirmation feedback is displayed via notifications
Employee Directory

Provides a structured view of all employee records with:

Real-time search functionality
Sorting by name, city, or country
Pagination (5 records per page)

Data is aggregated from both backend API and local storage sources.

Location Mapping

Displays all employees on a Google Map interface:

Interactive markers with employee details
Intelligent marker offsetting for overlapping coordinates
Real-time updates for newly added employees
API Integration
Endpoint	Method	Description
/get_activation_code	POST	Generates API authentication code
/add_employee	POST	Adds a new employee record
/get_all_employee	POST	Retrieves all employee records

Base URL: https://api.findofficers.com/hiring_test

Data Management
Backend API: Primary storage for persistent employee records
localStorage: Stores locally added employees (newEmployees)
sessionStorage: Temporarily stores activation codes per session
Data is merged dynamically during application runtime
Google Maps Configuration

The application uses the Google Maps JavaScript API for location rendering.

For production environments, replace the API key as follows:
<script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap" async defer></script>


