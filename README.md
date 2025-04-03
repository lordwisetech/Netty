


# Netty - Networking Web App

Netty is a modern networking web application built using Django and JavaScript. This project allows users to connect, manage posts, and interact with other users. It’s designed to offer an interactive and engaging experience while also making it suitable for desktop and laptop use (currently not optimized for mobile devices).

## Features
- **User Authentication**: Users can sign up, log in, and log out.
- **Create Posts**: Users can create and share posts.
- **Follow Other Users**: Users can follow others to stay updated with their content.
- **Saved Posts**: Users can save posts for later viewing.
- **User Profiles**: Each user has their own profile where they can manage their information.
- **Responsive Layout**: Optimized for desktop and laptop users (mobile optimization is currently in progress).

## Getting Started

To get a local copy of the project up and running, follow these simple steps:

### Prerequisites
- Python 3.x
- Django (for backend development)
- JavaScript (for frontend features)
- SQLite or PostgreSQL for the database (Django comes with SQLite by default)

### Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/netty.git
cd netty
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate the virtual environment:

- On Windows:
    ```bash
    venv\Scripts\activate
    ```

- On macOS/Linux:
    ```bash
    source venv/bin/activate
    ```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Apply database migrations:

```bash
python manage.py migrate
```

Create a superuser to access the admin panel (optional but recommended):

```bash
python manage.py createsuperuser
```

Run the development server:

```bash
python manage.py runserver
```

Open your browser and go to [http://127.0.0.1:8000/](http://127.0.0.1:8000/) to see the app in action.

## Usage
- **User Signup**: Users can register for an account using the signup page.
- **Login/Logout**: Users can log in with their credentials, or log out to end their session.
- **Create Post**: After logging in, users can create new posts.
- **Follow Users**: Follow other users to stay updated with their content.
- **Save Posts**: Users can save posts they like for later.
- **Profile Management**: Users can update their profile picture and personal details from their profile page.

## Mobile Compatibility
At the moment, Netty is optimized for desktop and laptop devices only. If you open the site on a mobile device, you will see a message saying the app is not optimized for mobile usage.

## Technologies Used
- **Backend**: Django
- **Frontend**: HTML, CSS, JavaScript

## App Preview

### Screenshot:

![Netty - Networking App](https://github.com/lordwisetech/Netty/issues/1#issue-2969720440)

