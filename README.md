Abdul Hamad - Portfolio Website
A modern, responsive portfolio website for Abdul Hamad featuring animated landing pages, project showcases, and a functional contact form.

https://img.shields.io/badge/Portfolio-Abdul%2520Hamad-blue
https://img.shields.io/badge/License-MIT-green

🌟 Features
Modern Design: Clean, professional layout with smooth animations

Responsive: Fully responsive design that works on all devices

Interactive Elements: Hover effects, scroll animations, and dynamic content

Project Showcase: Filterable portfolio with project details

Contact Form: Functional contact form with database storage

Performance Optimized: Fast loading times and smooth interactions

🚀 Live Demo
View Live Website <!-- Replace with your actual domain -->

📁 Project Structure
text
abdul-hamad-portfolio/
├── index.html                 # Homepage
├── about.html                 # About page
├── projects.html              # Projects showcase
├── contact.html               # Contact form
├── submit_contact.php         # PHP backend for contact form
├── assets/
│   ├── css/
│   │   └── style.css          # Main stylesheet
│   ├── js/
│   │   └── script.js          # Main JavaScript file
│   └── images/                # Project images and assets
├── database/
│   └── setup.sql              # Database schema
└── README.md
🛠️ Technologies Used
Frontend: HTML5, CSS3, JavaScript (ES6+)

Backend: PHP

Database: MySQL

Icons: Font Awesome

Fonts: Google Fonts (Poppins)

Animation: Custom CSS animations and JavaScript

📋 Prerequisites
Before running this project, make sure you have:

Web server with PHP support (Apache, Nginx, etc.)

MySQL database

Modern web browser

⚡ Installation & Setup
1. Clone the Repository
bash
git clone https://github.com/your-username/abdul-hamad-portfolio.git
cd abdul-hamad-portfolio
2. Database Setup
Create a MySQL database:

sql
CREATE DATABASE abdul_hamad_portfolio;
Import the database schema:

sql
USE abdul_hamad_portfolio;

CREATE TABLE contacts (
    id INT(11) AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100) NOT NULL,
    email VARCHAR(100) NOT NULL,
    subject VARCHAR(100) NOT NULL,
    budget VARCHAR(50),
    message TEXT NOT NULL,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    is_read TINYINT(1) DEFAULT 0
);
3. Configuration
Update the database credentials in submit_contact.php:

php
$servername = "localhost";
$username = "your_database_username";
$password = "your_database_password";
$dbname = "abdul_hamad_portfolio";
4. Web Server Setup
Place all files in your web server's root directory

Ensure PHP is properly configured

Set proper file permissions:

bash
chmod 755 submit_contact.php
🎨 Customization
Updating Personal Information
Homepage (index.html):

Update name, tagline, and hero section

Modify skills and expertise

About Page (about.html):

Update personal bio and experience

Modify timeline and values

Projects Page (projects.html):

Add your actual projects

Update project images and descriptions

Modify testimonials

Contact Page (contact.html):

Update contact information

Modify FAQ section

Styling Customization
The website uses CSS custom properties for easy theming. Update colors in the :root selector:

css
:root {
    --primary-color: #3498db;
    --secondary-color: #2c3e50;
    --accent-color: #e74c3c;
    /* Add your custom colors */
}
📱 Pages Overview
🏠 Homepage
Animated hero section

Skills overview

Call-to-action buttons

Smooth scrolling navigation

👨‍💻 About Page
Personal introduction

Experience timeline

Skills showcase

Professional values

💼 Projects Page
Filterable project gallery

Project details with technologies

Featured project highlight

Client testimonials

📞 Contact Page
Contact information

Functional contact form

FAQ section

Interactive map placeholder

🔧 Technical Features
Frontend
Responsive grid layout

CSS animations and transitions

Form validation

Scroll-triggered animations

Mobile-friendly navigation

Backend
PHP form processing

MySQL database integration

Email notifications

Security measures (SQL injection prevention)

🐛 Troubleshooting
Common Issues
Contact form not working

Check PHP configuration

Verify database credentials

Ensure proper file permissions

Animations not working

Check browser compatibility

Verify JavaScript is enabled

Responsive issues

Check viewport meta tag

Test on different screen sizes

Browser Support
Chrome (latest)

Firefox (latest)

Safari (latest)

Edge (latest)

📈 Performance Optimization
Optimized images

Minified CSS and JavaScript

Efficient database queries

Caching strategies

🤝 Contributing
Fork the repository

Create a feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

📞 Support
If you have any questions or need help with setup, please open an issue or contact:

Email: abdul.hamad@example.com

LinkedIn: Abdul Hamad

Portfolio: Your Portfolio Website

🙏 Acknowledgments
Icons by Font Awesome

Fonts by Google Fonts

Inspiration from modern web design trends

Note: Remember to update all placeholder content (images, contact information, project details) with your actual information before deploying the website.

⭐ If you found this project helpful, please give it a star!

