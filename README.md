# Book-Ease: Library Management System

## Introduction
**Book-Ease** is a Library Management System (LMS) designed to simplify the management of books, users, and transactions within a library. The system allows librarians to efficiently catalog books, track book availability, manage user accounts, and process transactions like checkouts and returns. This project aims to provide an intuitive interface for library staff to perform daily tasks seamlessly.

This project draws inspiration from industry standards like [Libib](https://www.libib.com/) and various online resources such as [GeeksforGeeks](https://www.geeksforgeeks.org/library-management-system/?ref=lbp).

## Features
- **Book Management**: Add, update, and delete book entries, including details such as title, author, genre, ISBN, and availability.
- **User Management**: Register new users, update their profiles, and manage their library transactions.
- **Transaction Management**: Handle the checkout and return of books, track overdue books, and calculate fines.
- **Search Functionality**: Search for books by title, author, or genre to quickly find available resources.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript (Bootstrap for responsive design)
- **Backend**: Django (Python web framework)
- **Database**: SQLite (default for development; can be configured to use PostgreSQL or MySQL for production)
- **Authentication**:  Django's built-in authentication system for user management and session handling

### Installation
### 1. Clone this repository:
```bash
git clone https://github.com/MTank76/Book-Ease.git
```

2. Navigate to the project directory:
```bash
cd Book-Ease
```

3. Create a virtual environment:
```bash
python3 -m venv env
```

 4. Activate the virtual environment:
```bash
source env/bin/activate  # On Windows, use `env\Scripts\activate`
```

5. Install the project dependencies:
```bash
pip install -r requirements.txt
```

6. Run the server:
```bash
python manage.py runserver
```

 7. Visit the application:
Go to `http://localhost:8000` in your browser to view the application.

---


## Database Setup
Refer to the detailed guide provided in the project for setting up your database. You may need to create tables or collections for books, users, and transactions based on the database you choose.

## References
1. [Libib - Library Management System](https://www.libib.com/): An online platform providing simple solutions for library cataloging and management. This project draws inspiration from the features Libib offers for managing books and users in a streamlined manner.
   
2. [GeeksforGeeks - Library Management System](https://www.geeksforgeeks.org/library-management-system/?ref=lbp): A comprehensive guide on designing a Library Management System, which inspired the backend architecture and features implemented in this project. The article covers various approaches, including how to manage books, users, and transactions.

## Contributing
If you would like to contribute to this project, feel free to fork the repository, create a new branch, and submit a pull request. Please ensure your code adheres to the coding guidelines and includes proper documentation.

## License:
This project is licensed under the MIT License [![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
