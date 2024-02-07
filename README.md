# Password Strength Tester

The Password Strength Tester is a web application built using Vue.js that allows users to check the strength of their passwords and estimate the time it would take to crack them using a brute-force attack. It also warns users if their password is commonly used.

## Features

- Password strength indicator: The application evaluates the strength of a password based on various criteria such as length, character types, and common patterns. The strength is displayed to the user as "Very Weak", "Weak", "Fair", "Strong", or "Very Strong".

- Strength bars: The strength of the password is visually represented by colored bars, with each bar indicating a certain level of strength.

- Common password check: The application checks if the entered password is commonly used and warns the user to choose a stronger one if necessary.

- Estimated crack time: The application estimates the time it would take to crack the password using a brute-force attack. The estimated time is displayed to the user in a human-readable format.

## Usage

To use the Password Strength Tester web application, follow these steps:

1. Clone or download this repository to your local machine.

2. Open the `index.html` file in a web browser.

3. Enter your password in the input field labeled "Enter your password".

4. As you type, the application will evaluate the strength of your password and display it along with the strength bars.

5. If your password is commonly used, a warning message will be displayed.

6. The estimated time it would take to crack your password will also be displayed.

## Dependencies

- Vue.js: The application is built using Vue.js, a JavaScript framework for building user interfaces.

## Credits

- Common Passwords: The list of common passwords used in this application is sourced from [this GitHub Gist](https://gist.github.com/JohnnyUrosevic/f0aafe33bfdd07a7c27d047b4bcf114e).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
