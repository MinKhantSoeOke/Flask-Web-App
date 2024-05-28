# Flask Notes App

This is a simple Flask web application for managing notes. Users can sign up, log in, and add notes. Each note can be deleted by clicking the close button next to it.

## Features
- User authentication (sign up, log in, log out)
- Add notes
- Delete notes
- Flash messages for feedback
- Responsive design using Bootstrap

## Technologies
- Python
- Flask
- Bootstrap

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/flask-notes-app.git
    cd flask-notes-app
    ```

2. Create a virtual environment:
    ```bash
    python -m venv venv
    ```

3. Activate the virtual environment:
    - On Windows:
      ```bash
      venv\Scripts\activate
      ```
    - On MacOS/Linux:
      ```bash
      source venv/bin/activate
      ```

4. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```
    
5. Run the application:
    ```bash
    python3 main.py
    ```

## Usage
- Open your web browser and navigate to `http://127.0.0.1:5000`.
- Sign up for a new account or log in if you already have one.
- Add notes using the text area and "Add Notes" button.
- Delete notes by clicking the close button next to each note.
