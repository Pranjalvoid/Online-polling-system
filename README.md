# Online Polling System

An interactive command-line Python application that enables users to register, log in, cast votes for predefined parties, and view the voting results. This project demonstrates user authentication, voting mechanics, and a simple results tally.

---

## Features

- **User Registration**: Users can create accounts with secure passwords.
- **Login System**: Secure user authentication to ensure voting integrity.
- **Voting**: Users can vote for predefined parties, ensuring each user votes only once.
- **Results Display**: Real-time results showing the number of votes for each party.

---

## Technologies Used

- **Python**: Core programming language.
- ``: For secure password input.

---

## Setup and Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/online-polling-system.git
   cd online-polling-system
   ```

2. **Run the project**:\
   Execute the main script using Python:

   ```bash
   python main.py
   ```

---

## Usage

### Menu Options

1. **Register**:\
   Allows a new user to register with a unique username and password.

2. **Login**:\
   Existing users can log in with their credentials.

3. **Vote**:\
   Authenticated users can cast their votes for the following parties:

   - Capsule Corporation
   - Daishinkan
   - Soul Society Reformation Front

4. **View Results**:\
   Displays the total votes received by each party.

5. **Exit**:\
   Terminates the program.

### Example Usage:

```plaintext
1. Register
2. Login
3. Vote
4. View Results
5. Exit
Enter your choice: 1
```

---

## Files Structure

- ``:\
  The main entry point for the application. Handles the program flow and user interaction.

- ``:\
  Manages user registration and authentication using a simple in-memory database.

- ``:\
  Implements the voting mechanism and results display functionality.

---

## Future Improvements

- Add data persistence using a database or file system.
- Introduce encryption for passwords to enhance security.
- Add a graphical user interface (GUI) for better user experience.
- Implement error handling for edge cases (e.g., invalid input, network issues).

---

## Contribution

Contributions are welcome!\
Fork the repository, make your changes, and submit a pull request.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

