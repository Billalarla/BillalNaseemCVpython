# Flask CV Application

This project is a simple web application built using Flask to showcase a CV (Curriculum Vitae). It serves as a personal portfolio to present skills, experience, and education in a structured format.

## Project Structure

```
flask-cv-app
├── app
│   ├── __init__.py
│   ├── routes.py
│   ├── templates
│   │   └── index.html
│   └── static
│       └── style.css
├── requirements.txt
├── run.py
└── README.md
```

## Setup Instructions

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd flask-cv-app
   ```

2. **Create a virtual environment:**
   ```
   python -m venv venv
   ```

3. **Activate the virtual environment:**
   - On Windows:
     ```
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```
     source venv/bin/activate
     ```

4. **Install the required dependencies:**
   ```
   pip install -r requirements.txt
   ```

## Running the Application

To run the Flask application, execute the following command:
```
python run.py
```

The application will be accessible at `http://127.0.0.1:5000/`.

## Usage

Once the application is running, you can view the CV by navigating to the main page in your web browser. The content is dynamically rendered using Jinja2 templating.

## License

This project is licensed under the MIT License.