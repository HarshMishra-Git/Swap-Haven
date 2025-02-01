# Swap Haven

Swap Haven is a web application built using Flask for the backend and HTML for the frontend. The application allows users to sign up, log in, and manage their profiles.

## Project Structure
Swap-Haven/
├── app.py
├── config.py
├── models.py
├── routes/
│ ├── init.py
│ ├── auth.py
│ ├── profile.py
├── templates/
│ ├── base.html
│ ├── login.html
│ ├── signup.html
│ ├── userProfile.html
│ └── index.html
├── static/
│ ├── css/
│ │ └── style.css
│ ├── js/
│ │ └── script.js
├── migrations/
└── requirements.txt

## Features

- User Authentication: Sign up, log in, and log out.
- User Profile Management: View and edit user profiles.
- Responsive UI: A clean and responsive user interface.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/HarshMishra-Git/Swap-Haven.git
    cd Swap-Haven
    ```

2. Create and activate a virtual environment:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Initialize and migrate the database:

    ```bash
    flask db init
    flask db migrate -m "Initial migration."
    flask db upgrade
    ```

5. Run the application:

    ```bash
    flask run
    ```

6. Open your web browser and navigate to `http://127.0.0.1:5000/`.

## Usage

- **Home Page:** The main landing page of the application.
- **Sign Up:** Create a new user account.
- **Log In:** Log in with an existing user account.
- **Profile:** View and edit user profile information.

## Contributing

If you would like to contribute to this project, please fork the repository and make changes as you'd like. Pull requests are warmly welcome.

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
