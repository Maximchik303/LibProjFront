# Library Management System

This project is a web-based library management system developed using Flask for the backend and HTML/CSS/JavaScript for the frontend. It allows administrators to manage users, books, and book borrowings efficiently. Has the history of all the users, books, borrows. has a normal user system as well where you can log in and borrow an existing book. all bugs have been cleared and as far as I know its impossible to break the website without manipulating the data with outside sources such as dbeaver. ADMIN PASSWORD IS 1 AND THE NAME IS "admin"

## Features

- **User Management**: Administrators can view active users, disable users, and update user information.
- **Book Management**: Administrators can add new books, update book details, disable books, and view active books.
- **Borrow Management**: Administrators can track borrows, manage return dates, and view overdue returns.
- **Authentication**: Users and administrators have separate login portals with authentication handled securely.
- **User Accounts**: Users can log in and borrow an existing book from the list of active books.
- **Responsive Design**: The frontend is designed to be responsive, ensuring a good user experience across devices.

## Technologies Used

- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite (for simplicity in this example; can be replaced with more robust databases like PostgreSQL or MySQL for production)
- **External Libraries**: Axios (for API requests)

## Setup Instructions

1. **Clone the Repository**: `git clone <repository-url>`
2. **Install Dependencies**: `pip install -r requirements.txt`
3. **Run the Flask Application**: run the backend and launch frontend with live server

this is the frontend of the website, the backend is in -
https://github.com/Maximchik303/LibProjBack"# LibProjFront" 
