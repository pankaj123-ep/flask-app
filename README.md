# Flask Application

This is a simple Flask application project.

## Project Structure

```
flask-app
├── app.py
├── requirements.txt
├── Dockerfile
└── README.md
```

## Setup Instructions

1. **Clone the repository**:
   ```
   git clone <repository-url>
   cd flask-app
   ```

2. **Create a virtual environment** (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies**:
   ```
   pip install -r requirements.txt
   ```

## Running the Application

To run the Flask application, execute the following command:
```
python app.py
```

The application will be available at `http://127.0.0.1:5000`.

## Docker Instructions

To build and run the Docker container, use the following commands:

1. **Build the Docker image**:
   ```
   docker build -t flask-app .
   ```

2. **Run the Docker container**:
   ```
   docker run -p 5000:5000 flask-app
   ```

The application will be accessible at `http://localhost:5000` in your web browser.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.