# ToDo-App
# Django ToDo Application

A simple ToDo application built with Django.

## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Running the Application](#running-the-application)
  - [Accessing the Web Interface](#accessing-the-web-interface)

## Features

- User registration and authentication.
- Create, update, and delete tasks.
- Mark tasks as completed.
- User-friendly web interface.

## Getting Started

### Prerequisites

- Python 3.x
- Django

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/raja9112/ToDo-App.git
   cd todo-app
   
2. Create a virtual environment (optional but recommended):
   ```python
   python -m venv venv
   source venv/bin/activate  # On Windows, use: venv\Scripts\activate
   ```

3. Install the required packages:
   ```python
   pip install -r requirements.txt
   ```

4. Set up the database:
   ```python
   python manage.py migrate
   ```


##Usage
###Running the Application
To run the application locally, use the following command:
   ```python
   python manage.py runserver
   ```

###Accessing the Web Interface
Open a web browser and navigate to http://localhost:8000 to access the application.
