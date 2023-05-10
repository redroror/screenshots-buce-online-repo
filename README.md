
# BUCE Research Online Repository

A web-based system designed to store and display undergraduate theses and faculty researchers of the Bicol University College of Education(BUCE). 

Our project was developed using Laravel, a popular PHP framework known for its powerful features and ease of use. Laravel provides a wide range of tools and components that make it easier to build robust, scalable web applications quickly and efficiently.

To create a responsive and modern user interface for our application, we made use of Bootstrap, a popular CSS framework that provides a wide range of tools and components for frontend development.


## Features

#### System Administrator 

- Access Admin Dashboard
- Read, approve, edit, and unpublish thesis papes submitted by moderators
- Read, approve, edit, and inactivate researchers submitted by moderators
- Read, add, and remove specializations (Researchers)
- Read, add, and remove programs (Thesis Papers)
- Read and approve moderators
- Read and add system administrators

#### Moderator

- Access Moderator Dashboard
- Submit thesis papers
- Submit researchers information
- View Contributions (Submitted Thesis Papers and Researchers)

#### Guest

- View undergraduate thesis papers
- View faculty researchers
- Search undergraduate thesis papers and faculty researchers
- Register as Moderator

## Requirements

- PHP 8.0.0+
- VSCode or any preferred IDE
- XAMPP
- Download the file or source code

## Installation

1. Download the file and extract the provided source code zip file. Make sure to include the database or sql file as well.

2. Navigate to the root directory and install dependencies:

```bash
 composer install
```

## Usage

1. Create a database and import the sql file included in the zip file.
2. Open the file on VSCode. Find the .env file and configure environment variables

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=
DB_USERNAME=
DB_PASSWORD=
```

3. Open XAMPP and start Apache and MySQL
4. In the terminal, type the command below to start the server

```
php artisan serve
```

5. Visit http://127.0.0.1:8000/
6. By following the link provided, you will be redirected to the landing page. To access the admin panel, use the login credentials below:

- Username : bucerepoadmin
- Password : 12345678

If you want to contribute or be a moderator you may click the "Be a Contributor" tab in the landing page. Or use the login credentials provided below:

- Username: bucemoderator
- Password: 12345678


## Screenshots

![Landing Page](https://github.com/redroror/screenshots-buce-online-repo/blob/main/Screenshot%202023-05-10%20212438.png)

![Login Page](https://github.com/redroror/screenshots-buce-online-repo/blob/main/Screenshot%202023-05-10%20212751.png)

![Registration Page](https://github.com/redroror/screenshots-buce-online-repo/blob/main/Screenshot%202023-05-10%20212719.png)

![Admin's Dashboard](https://github.com/redroror/screenshots-buce-online-repo/blob/main/Screenshot%202023-05-10%20212854.png)

![Moderator's Dashboard](https://github.com/redroror/screenshots-buce-online-repo/blob/main/Screenshot%202023-05-10%20212644.png)


