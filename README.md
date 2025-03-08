# Guess 2/3 of the Average Game

A Flask-based web application for playing the "Guess 2/3 of the Average" game.

## Features
- Users can submit their guesses (between 1 and 100).
- Results are stored in an SQLite database.
- Developers can view the final results by entering a password.
- Visualized guess distribution using matplotlib.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/guess_game.git
   ```

2. Navigate to the project directory:
   ```bash
   cd guess_game
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Flask application:
   ```bash
   python flask_app.py
   ```

5. Open your browser and go to `http://127.0.0.1:5000`.

## Set Up Environment Variables

1. Create a `.env` file in the root directory of the project.
2. Add the following variables to the `.env` file:
   ```plaintext
   SECRET_KEY=your_secret_key_here
   DATABASE_PATH=/path/to/your/database.db
   DEVELOPER_PASSWORD=your_developer_password_here
   ```

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes.
4. Push your changes to your fork.
5. Submit a pull request.

## License

This project is licensed under the MIT License.
