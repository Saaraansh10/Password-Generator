# Password Generator

This project is a simple yet powerful password generator tool that allows users to create secure passwords based on specific criteria. Users can select options to include uppercase letters, lowercase letters, numbers, and symbols, and adjust the length of the generated password using a slider.

## Table of Contents

- [Features](#features)
- [Technologies Used](#Technologies_Used)
- [Installation](#installation)
- [Usage](#usage)

## Features

- Adjustable password length with a convenient slider.
- Options to include:
  - Uppercase letters
  - Lowercase letters
  - Numbers
  - Symbols
- Visual indicators showing the strength of the password.
- Clipboard functionality to easily copy the generated password.
- Dynamic feedback when checkboxes are selected or deselected.

## Technologies Used
- HTML: For the structure and layout of the web application.
- CSS: For styling the components and layout to enhance user experience.
- JavaScript: For the functionality of the password generation, including random character generation and strength assessment.


## Installation

To run this project locally, you need to have a web browser. Clone the repository and open the `index.html` file in your preferred web browser.

### Steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/password-generator.git
   ```

2. Navigate to the project directory:
   ```bash
   cd password-generator
   ```

3. Open `index.html` in your web browser. You can also set up a local server using tools like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) for better development experience.

## Usage

1. **Select Criteria:** Use the checkboxes to select the criteria for your password (uppercase letters, lowercase letters, numbers, and symbols).
  
2. **Adjust Length:** Use the slider to adjust the desired length of the password. The minimum length of the password will be enforced according to the selected options.

3. **Generate Password:** Click the "Generate Password" button to create a secure password.

4. **Copy to Clipboard:** Click the copy button to copy the generated password to your clipboard. A message will confirm whether the copy was successful.

5. **Strength Indicator:** The strength of the generated password will be indicated by a color-coded circle:
   - Green: Strong
   - Yellow: Moderate
   - Red: Weak


