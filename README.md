# Social Media Application

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation & Setup](#installation--setup)
- [Usage](#usage)
- [Database Schema (ER Diagram)](#database-schema-er-diagram)
- [Testing Credentials](#testing-credentials)
- [Evaluation Criteria](#evaluation-criteria)
- [License](#license)

## Introduction

This is a basic social media application built using Django for the backend and HTML, CSS, and JavaScript for the frontend. The project simulates a simplified version of Facebook with user authentication, post creation, and profile management.

## Features

### User Management
- **Registration:** Users can sign up with a username, email, and password.
- **Authentication:** Login/logout functionality using Django's built-in authentication system.
- **Profile Management:** Users can view their posts on their profile page.

### Post Management
- **Homepage (Global Feed):** Displays posts from all users.
- **User Profile Page:** Shows posts of the logged-in user with edit and delete options.
- **Create Post:** Users can create new posts with text and optional image uploads.
- **Update & Delete Post:** Users can edit or delete their own posts.

### User Interaction & Layout
- **Navigation:** A simple navbar with links to the homepage, profile page, login/logout, and registration.
- **Feedback Messages:** Uses Django’s messages framework for user notifications.

## Technology Stack

- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, JavaScript
- **Database:** SQLite (default Django database)
- **Version Control:** Git & GitHub
- **Authentication:** Django’s built-in authentication system

## Installation & Setup

### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Django
- Git

### Clone the Repository
```sh
$ git clone https://github.com/yourusername/social-media-app.git
$ cd social-media-app
```


### Apply Migrations
```sh
$ python manage.py migrate
```

### Create a Superuser
```sh
$ python manage.py createsuperuser
```
(Use `admin` as the username and `test@1234` as the password)

### Run the Development Server
```sh
$ python manage.py runserver
```
Now, open [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your browser.

## Usage

1. Register a new user or log in with the provided credentials.
2. Navigate to the homepage to view all posts.
3. Go to your profile to view, edit, or delete your posts.
4. Create a new post from the homepage.
5. Log out when done.

## Database Schema (ER Diagram)
Include an ER diagram image here (e.g., `social_media_ER_Digram.png` in the repository).
<img src="https://raw.githubusercontent.com/mhtusher131/social_media_application/main/social_media/social_media_ER_Diagram.png" width="600">


## Testing Credentials

| Username | Password |
|----------|----------|
| hasan | test@123 |
| admin | test@1234 |

## Evaluation Criteria

- **Functionality:** Implements required features such as user authentication, post creation, and profile management.
- **Code Quality:** Follows Django best practices with clean, well-documented code.
- **User Interface:** Simple, intuitive, and consistent UI.
- **Documentation:** Clear setup instructions and feature descriptions.
## Live Exam Search Feature
Searching by UserName
![Live Exam Search Result](""  width="600")
<img src="https://raw.githubusercontent.com/mhtusher131/social_media_application/main/Live_exam_search_result.png" width="600">

## License

This project is for educational purposes. Feel free to modify and expand it.

**Happy coding!** 🎉
