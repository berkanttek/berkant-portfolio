# Personal Portfolio — Project Report
**Student:** Berkant Tekkanat  21091000139 
**Course:** Web Technologies  
**Live Demo:** http://berkant-portfolio.rf.gd  
**GitHub:** https://github.com/berkanttek/berkant-portfolio  

---

## Project Overview
This project is a full-stack personal portfolio website built using HTML5, CSS3, JavaScript, PHP, and MySQL. The goal was to create a dynamic, responsive, and visually appealing web application that showcases my skills and projects.

---

## Technologies Used
- **HTML5** — Semantic structure, forms, and layout
- **CSS3** — Flexbox, Grid, animations, responsive design
- **JavaScript** — DOM manipulation, form validation, AJAX
- **PHP** — Server-side logic, session management, admin dashboard
- **MySQL** — Database for projects and contact messages

---

## Features Implemented

### Frontend
- Responsive design using Flexbox and CSS Grid
- Dark/Light mode toggle with Cookie persistence
- Interactive particle background with mouse repulse effect
- Smooth scroll animations and hover effects
- Contact form with JavaScript validation

### Backend
- Contact form submissions saved to MySQL database
- Projects dynamically loaded from database via AJAX (Fetch API)
- Admin dashboard with Session-based authentication
- CRUD operations for project management (add, edit, delete)
- Cookie-based last login tracking

### Database
- `projects` table — stores project title, description, tech stack, links
- `messages` table — stores contact form submissions
- `admin_users` table — stores admin credentials

---

## How It Works
1. User visits the portfolio and sees projects loaded dynamically via AJAX
2. User fills out the contact form — JavaScript validates the input before sending
3. PHP processes the form and saves the message to MySQL database
4. Admin can log in at `/admin/login.php` using session-based authentication
5. Admin can add, edit, or delete projects from the dashboard
6. Changes are immediately reflected on the main page

---

## Challenges & Solutions
- **Particle effect:** Implemented using particles.js library with custom configuration for both dark and light themes
- **AJAX integration:** Used Fetch API to load projects without page refresh
- **Responsive design:** Used CSS media queries for mobile, tablet, and desktop layouts

---

## Live Demo & Repository
- **Live:** http://berkant-portfolio.rf.gd
- **GitHub:** https://github.com/berkanttek/berkant-portfolio
