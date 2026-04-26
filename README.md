📚 Share Your Knowledge

Share Your Knowledge is a professional knowledge-sharing ecosystem built with the Laravel framework. Designed to bridge the gap between authors and learners, it provides a centralized platform for writing blogs in Bangla, sharing video tutorials, and engaging in collaborative Q&A.

🚀 Key Features

👤 Author Experience

Content Creation: Seamlessly write and upload blogs with full support for Bangla typography.

Tutorial Hub: Dedicated module for video/tutorial uploading to facilitate visual learning.

Community Interaction: Engage with the audience through a built-in Question & Answer platform.

Social Features: Robust engagement tools including Likes, Comments, Shares, and Favorites.

🛡️ Administrative Control

Content Moderation: Comprehensive workflow for the Admin to approve or reject blog submissions.

Queue Management: Optimized Queue Mail System for background notification processing.

Multi-Level Auth: Secure, distinct authentication layers for Admin and Author roles.

🛠️ Technical Highlights

Architecture: Built on the MVC (Model-View-Controller) design pattern for scalability.

Notifications: Real-time system alerts for administrative and author actions.

Subscriptions: Integrated with Mailtrap.io for reliable email subscription handling.

Responsive Design: A modern, mobile-first frontend optimized for all reading devices.

💻 Tech Stack

Layer

Technology

Backend

Laravel (PHP)

Frontend

JavaScript, HTML5, CSS3

Database

MySQL

Tooling

Composer, Artisan CLI, Mailtrap

⚙️ Installation Guide

Follow these steps to deploy the project locally:

1. Clone the Project

git clone [https://github.com/your-username/share-your-knowledge.git](https://github.com/your-username/share-your-knowledge.git)
cd share-your-knowledge


2. Install Dependencies

Ensure you have Composer installed:

composer install


3. Environment Setup

Create your local environment file from the template:

Windows (CMD):

copy .env.example .env


Linux / macOS:

cp .env.example .env


4. Database Configuration

Open the .env file and configure your database credentials:

DB_DATABASE=your_database_name
DB_USERNAME=root
DB_PASSWORD=         # Leave empty for XAMPP; use 'root' for LAMP


5. Application Initialization

Initialize the app key and migrate the database schema:

php artisan key:generate
php artisan migrate


6. Start the Server

php artisan serve


Visit the application at: http://localhost:8000

🎓 Academic Information

Field

Detail

Student Name

Prithwiraj Bhattacharjee

Reg. No

2015331012

Course Code

CSE 332

Supervised By

Md. Saiful Islam (Assistant Professor, Dept. of CSE)
