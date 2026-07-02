# PyLadies Indonesia Website

Official website for **PyLadies Indonesia**, built using **Python** and the **Django** web framework.

The purpose of this project is to provide an online platform for the PyLadies Indonesia community, including information about the community, events, blog posts, programs, and other activities that support women in technology.

---

## 🚀 Tech Stack

- Python 3.12+
- Django
- HTML5
- CSS3
- JavaScript
- SQLite (default for development)
- Git & GitHub

---

## 📁 Project Structure

```text
project/
│── manage.py
│── requirements.txt
│── .env
│── static/
│── media/
│── templates/
│── apps/
└── ...
```

---

## 📋 Requirements

Before running this project, make sure you have installed:

- Python 3.12 or newer
- pip
- Git
- Virtual Environment (`venv`)

You can verify your installation by running:

```bash
python --version
pip --version
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/<username>/<repository>.git
```

### 2. Navigate into the project directory

```bash
cd <repository>
```

### 3. Create a virtual environment

Windows

```bash
python -m venv venv
```

Linux / macOS

```bash
python3 -m venv venv
```

---

### 4. Activate the virtual environment

Windows

```bash
venv\Scripts\activate
```

Linux / macOS

```bash
source venv/bin/activate
```

---

### 5. Install project dependencies

```bash
pip install -r requirements.txt
```

---

### 6. Configure environment variables

Create a `.env` file.

Example:

```env
SECRET_KEY=your_secret_key
DEBUG=True
ALLOWED_HOSTS=127.0.0.1,localhost
```

---

### 7. Apply database migrations

```bash
python manage.py migrate
```

---

### 8. (Optional) Create an admin account

```bash
python manage.py createsuperuser
```

Follow the prompts to create your administrator account.

---

### 9. Collect static files (optional)

```bash
python manage.py collectstatic
```

---

## ▶️ Run Development Server

Start the Django development server:

```bash
python manage.py runserver
```

By default, the website will be available at:

```
http://127.0.0.1:8000/
```

To run on another port:

```bash
python manage.py runserver 8080
```

---

## 🧪 Running Tests

To execute the project's test suite:

```bash
python manage.py test
```

---

## 📦 Installing New Packages

Whenever a new dependency is added:

```bash
pip install <package-name>
```

Update the requirements file:

```bash
pip freeze > requirements.txt
```

---

## 📂 Static & Media Files

Static assets:

```
static/
```

Uploaded media:

```
media/
```

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/your-feature
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to your branch

```bash
git push origin feature/your-feature
```

5. Open a Pull Request

---

## 📄 License

This project is maintained by the **PyLadies Indonesia** community.

Please refer to the project license for more information.

---

## ❤️ Acknowledgements

- PyLadies Indonesia Community
- Django Community
- Python Software Foundation
