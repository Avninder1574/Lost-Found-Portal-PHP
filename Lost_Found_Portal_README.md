# Lost and Found Portal

A web-based **Lost and Found Management System** developed using **PHP,
MySQL, HTML, CSS, and JavaScript**. The application provides a
centralized platform where users can browse found items, submit and
track claim requests, and manage their accounts, while administrators
can review claims, manage records, generate reports, and maintain portal
content.

## Features

### User Features

-   User registration and login
-   Secure user account access
-   Browse and search found items
-   Submit claim requests for found items
-   View and track personal claim requests
-   Check new, in-process, and completed claim statuses
-   Manage user profile and account information

### Admin Features

-   Separate administrator login
-   Admin dashboard and profile management
-   View and manage all claim requests
-   Process new and in-progress claims
-   Approve, reject, and track claim requests
-   View detailed claim information
-   Generate claim reports between selected dates
-   Manage portal content and About Us information
-   Centralized administration of the lost-and-found workflow

## Technologies Used

-   **Frontend:** HTML, CSS, JavaScript
-   **Backend:** PHP
-   **Database:** MySQL
-   **Database Management:** phpMyAdmin
-   **Local Server:** XAMPP / WAMP

## Project Structure

``` text
Lost-Found-Portal-PHP/
├── lostfound/
│   ├── admin/          # Administrator dashboard and claim management
│   ├── user/           # User account and claim management
│   ├── index.php       # Main application page
│   ├── login.php       # Login functionality
│   └── about.php       # About page
└── SQL File/
    └── lostandfounddb.sql
```

The project also contains CSS, fonts, images, JavaScript, and other
frontend assets used by the application.

## Database Setup

1.  Install **XAMPP** or **WAMP** and start Apache and MySQL.
2.  Open phpMyAdmin in your browser.
3.  Create a new database for the project.
4.  Import the SQL file:

``` text
SQL File/lostandfounddb.sql
```

5.  Verify the PHP database configuration files and update the database
    name, username, password, or host if your local MySQL configuration
    is different.

## Installation and Setup

1.  Download or clone the repository.
2.  Copy the project folder into your local web server directory.

For XAMPP:

``` text
C:/xampp/htdocs/
```

For WAMP:

``` text
C:/wamp64/www/
```

3.  Start **Apache** and **MySQL**.
4.  Import `lostandfounddb.sql` using phpMyAdmin.
5.  Open the application through your local server, for example:

``` text
localhost/Lost-Found-Portal-PHP/lostfound/
```

The exact path may vary depending on the folder name and local server
configuration.

## Application Workflow

1.  A user creates an account and logs into the portal.
2.  The user browses available found-item records.
3.  If an item belongs to the user, a claim request can be submitted.
4.  The claim enters the administrative review process.
5.  An administrator reviews the claim details and updates its status.
6.  The user can track the claim through the portal.
7.  Administrators can manage claims and generate reports.

## Key Modules

-   Authentication and User Management
-   Found Item Management
-   Claim Request Management
-   Claim Status Tracking
-   Admin Dashboard
-   User Dashboard
-   Reporting System
-   Database Integration
-   Profile Management

## Security Recommendations

For production deployment, consider implementing or verifying:

-   Password hashing using PHP `password_hash()` and `password_verify()`
-   Prepared statements to prevent SQL injection
-   Server-side input validation and sanitization
-   CSRF protection for forms
-   Secure session configuration
-   Role-based access control
-   File upload validation, if uploads are enabled

## Future Improvements

-   Add email notifications for claim-status updates
-   Add image-based item search
-   Add advanced search and filtering
-   Add automated item matching
-   Improve mobile responsiveness
-   Add REST API support
-   Deploy the application to a cloud hosting platform
-   Add audit logs for administrative actions

## Use Case

This project can be used by educational institutions, offices,
organizations, or public facilities to provide a structured system for
reporting, locating, claiming, and managing lost-and-found items.

## Author

**Avninder Singh**

MCA Student \| Aspiring Software Developer
