# To-Do List Flask Application

A simple and user-friendly To-Do List application built using Flask. This project demonstrates the use of Flask for creating a web application with essential CRUD (Create, Read, Update, Delete) operations. It provides a platform to manage daily tasks efficiently.

## Features

- Add tasks to your to-do list.
- Mark tasks as completed.
- Edit task details.
- Delete tasks.
- Filter tasks by status (completed or pending).
- Simple and responsive user interface.

## Tech Stack

- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS (no JavaScript)
- **Database**: SQLite

## Prerequisites

Before running the project, ensure you have the following installed:

- Python 3.7+
- pip (Python package manager)

## Getting Started

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/flask-todo-app.git
   cd flask-todo-app
   ```

2. **Create a virtual environment**:

   ```bash
   python3 -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**:

   ```bash
   flask run
   ```

5. **Access the application**: Open your browser and navigate to `http://127.0.0.1:5000`.

## Directory Structure

```
flask-todo-app/
├── static/
│   └── styles.scss/
├── templates/
│   ├── base.html
│   ├── index.html
│   └── update.html
├── app.py
├── requirements.txt
└── README.md
```

- `static/`: Contains static assets like CSS files.
- `templates/`: Contains HTML templates.
- `app.py`: Main application file.
- `requirements.txt`: Python dependencies.

## Database Initialization

Run the following command to initialize the SQLite database:

```bash
python
>>> from app import db
>>> db.create_all()
>>> exit()
```

This will create the necessary tables in the SQLite database.

## Usage

1. Navigate to the homepage.
2. Add new tasks using the input form.
3. Use the buttons next to each task to edit, delete, or mark it as completed.
4. Filter tasks using the provided options (if implemented).

## Screenshots

Add screenshots of your application here to showcase its interface.

## Future Improvements

- Add user authentication for personalized task management.
- Integrate a cloud database like PostgreSQL.
- Implement task priority and deadlines.
- Add a search functionality.
- Build a REST API for external integrations.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please fork the repository and submit a pull request.

1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Submit a pull request.

