# Engineering Book-hub

This is a full stack web application developed using Django and React. 

# Key features of the project
  <li>Creation of new admins for the website.
  <li>Login and Authetication using Django-admin-auth
  <li>User friendly UI
  <li>CRUD opertaions on the books section by the admin.


## Table of Contents 
- [Installation](#installation)
- [Running the application](#run-the-application)


## Installation

### 1. Create a virtual environment

From the **root** directory run:

```bash
cd backend
```
```bash
python -m venv venv
```

### 2. Activate the virtual environment

From the **backend** directory run:

On macOS:

```bash
source venv/bin/activate
```

On Windows:

```bash
venv\scripts\activate
```

### 3. Install required backend dependencies

--> got tired to make a requirements.txt.<br/>
From the **backend** directory run:

```bash
pip install django
pip install cors
```

### 4. Install required frontend dependencies

From the **root** directory run:

```bash
cd frontend
```
```bash
npm install
```

## Run the application

To run the application, you need to have both the backend and the frontend up and running.

### 1. Run backend

From the **backend** directory run:

```bash
python manage.py runserver
```

### 2. Run frontend

From the **frontend** directory run:

```bash
npm start
```

### 3. View the application

Go to http://localhost:3000/ to view the application.
# Enjoy surfing the website

# Future updates
<li>Update for each faculty</li>
<li>Options to login as user/admin</li>
<li>Update images on the books.</li>
