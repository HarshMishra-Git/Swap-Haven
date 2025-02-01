# Swap Haven

SwapHaven is a community-focused platform designed to facilitate the sustainable exchange of skills, items, and resources among individuals. It aims to create a space where people can connect, share, and collaborate without relying on monetary transactions. The platform addresses issues such as overconsumption, waste, and the disconnection often found in modern communities.

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

SwapHaven will have the following key functionalities:

1) User Registration and Profiles:

Users can create accounts and set up profiles to showcase their skills and items available for sharing or swapping.
Item and Skill Listings:

Users can list items they want to share or swap, as well as skills they are willing to offer. This includes descriptions, images, and availability.
2) Search and Browse:

Users can search for specific items or skills and browse through available listings in their community.
3) Direct Communication:

The platform will enable users to connect directly with each other to negotiate swaps or borrow items.
4) Rating and Review System:

Users can rate and review each other based on their experiences, helping to build trust within the community.
5) Privacy Settings:

Users can manage their privacy settings to control who can see their listings and contact them.
6) Skill Sharing and Development:

Users can offer workshops or sessions to share their skills with others, promoting learning and collaboration.
7) Community Building:

The platform will encourage community engagement through forums or discussion boards where users can share experiences, tips, and ideas.
8) Environmental Impact Tracking:

Users can track the environmental impact of their swaps, such as reduced waste and carbon footprint, promoting sustainability.
9) Mobile Responsiveness:

The platform will be designed to be mobile-friendly, allowing users to access it from their smartphones or tablets.
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
