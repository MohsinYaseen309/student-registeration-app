# Student Registration App

## Overview
This is a **Django-based Student Registration App** that allows users to register students and view their details.

## Features
- User-friendly student registration form.
- Student details viewing functionality.
- Django-based backend with database integration.
- HTML templates for frontend rendering.

## Project Structure
```
myProject/
|-- myProject/
|   |-- settings.py
|   |-- urls.py
|   |-- wsgi.py
|
|-- studentApp/
|   |-- models.py
|   |-- views.py
|   |-- urls.py
|   |-- forms.py
|   |-- templates/
|       |-- register.html
|       |-- view.html
|
|-- manage.py
|-- requirements.txt
```

## Installation
### Prerequisites
- Python 3.10+
- Django framework

### Setup Instructions
1. **Clone the repository**
   ```bash
   git clone https://github.com/MohsinYaseen309/student-registeration-app.git
   cd student-registeration-app
   ```
2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On macOS/Linux
   venv\Scripts\activate      # On Windows
   ```
3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. **Run database migrations**
   ```bash
   cd myProject
   python manage.py migrate
   ```
5. **Start the Django server**
   ```bash
   python manage.py runserver
   ```
6. **Access the app**
   Open your browser and go to: `http://127.0.0.1:8000/`

## Usage
- Open `http://127.0.0.1:8000/` in your browser.
- Register new students using the form.
- View registered students.

## Contributing
Feel free to fork the repository, submit issues, and create pull requests.

## License
This project is open-source and available under the **MIT License**.

