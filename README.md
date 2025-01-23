
# Guess The Code Game

Welcome to the **Guess The Code** game! This project is a fun and interactive browser-based game where players attempt to guess a randomly generated code within a set number of attempts.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Demo](#demo)
- [How to Play](#how-to-play)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

**Guess The Code** is designed to test your logical thinking and pattern recognition skills. The game generates a secret code, and players must guess it using feedback provided after each attempt.

## Features

- Randomly generated codes for each game session.
- Intuitive user interface.
- Feedback on each guess to guide the player.
- Responsive design for desktop and mobile users.
- Easy to customize and extend.

## Demo

You can try the live version of the game [here](#). *(Not Available for now)*

## How to Play

1. Open the game in your browser.
2. Enter your guess in the input field.
3. Submit your guess to receive feedback:
   - Correct digits in the correct position.
   - Correct digits in the wrong position.
4. Use the feedback to refine your guesses.
5. Win the game by guessing the code within the allowed attempts!

## Installation

Follow these steps to set up the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/Developer-Parth/Guess-The-Code.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Guess-The-Code
   ```
3. Open the `index.html` file in your browser.

## Usage

To customize the game:

- Modify the code generation logic in `generateNew.js`.
- Update the styling in `index-style.css`.
- Enhance interactions in `interactions.js`.

### Example

Hereâ€™s an example of how the game works:

- Secret code: `1234`
- Player guess: `1356`
- Feedback:
  - Correct digit in the correct position: 1 (1st position).
  - Correct digit in the wrong position: 3.

## Project Structure

| File/Folder       | Description                                        |
|-------------------|----------------------------------------------------|
| `index.html`      | Main HTML file for the game interface.             |
| `index-style.css` | CSS file for styling the game.                     |
| `generateNew.js`  | JavaScript file for generating random codes.       |
| `interactions.js` | JavaScript file for handling user interactions.    |
| `res/`            | Folder for additional resources (e.g., images).    |
| `LICENSE`         | License file for the project.                      |

## Contributing

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the terms of the MIT License. See the [LICENSE](./LICENSE) file for details.

## Contact

For any questions or feedback, feel free to contact me:

- GitHub: [Developer-Parth](https://github.com/Developer-Parth)
- Email: [parththukral16@gmail.com](mailto:parththukral16@gmail.com)
