# JS Quiz App

## Overview

The **JS Quiz App** is an interactive web application designed to test users' knowledge through multiple-choice quizzes. Built using JavaScript, HTML, and CSS, this project showcases front-end development skills and provides a dynamic user experience. The app can be tried at [JS Quiz App Demo](https://qyuzet.github.io/js-quiz-app/)...

![image](https://github.com/Qyuzet/js-quiz-app/assets/93258081/57ded999-cabf-4516-9763-277389c256ca)

![js-quiz-app demo](https://github.com/Qyuzet/js-quiz-app/assets/93258081/2362db0d-e014-43b5-adbe-f84bb28aab3a)


## Features

- **Multiple Choice Questions**: Users can select from multiple options for each question.
- **Immediate Feedback**: Correct and incorrect answers are indicated instantly.
- **Score Tracking**: Users' scores are displayed at the end of the quiz.
- **Responsive Design**: The app is accessible on various devices, including desktops and mobiles.

## Installation

To run the app locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/Qyuzet/js-quiz-app.git
    ```
2. Navigate to the project directory:
    ```bash
    cd js-quiz-app
    ```
3. Open `index.html` in your preferred web browser.

## File Structure

- **index.html**: The main HTML file containing the structure of the app.
- **style.css**: The CSS file providing the styling for the app.
- **script.js**: The JavaScript file containing the logic and functionality of the app.
- **questions.js**: A separate file to store quiz questions and answers.

## Usage

1. Open `index.html` in a web browser.
2. Start the quiz by clicking the "Start Quiz" button.
3. Select an answer for each question and click "Next" to proceed.
4. View the score at the end of the quiz.

### Code Explanation

#### HTML (`index.html`)

The HTML file sets up the basic structure of the quiz app. It includes elements such as the quiz container, question text, answer choices, and navigation buttons.

#### CSS (`style.css`)

The CSS file ensures the app has a clean and modern look. It styles the quiz container, buttons, and feedback messages. Key CSS rules include:

- **Flexbox**: Used for layout management to create a responsive design.
- **Transitions**: Smooth animations for displaying feedback messages.

#### JavaScript (`script.js`)

The JavaScript file implements the core functionality of the app. Key functions and features include:

- **Event Listeners**: For handling user interactions such as answering questions and navigating the quiz.
- **Quiz Logic**:
  - **loadQuestion()**: Loads and displays the current question and answer choices.
  - **checkAnswer()**: Verifies if the selected answer is correct and provides feedback.
  - **showScore()**: Calculates and displays the user's score at the end of the quiz.

#### Questions (`questions.js`)

The `questions.js` file contains an array of question objects, each with properties for the question text, answer choices, and the correct answer. This modular approach makes it easy to update or add new questions.

### Detailed Explanation

#### Loading Questions
The `loadQuestion()` function fetches the current question from the array and populates the HTML elements with the question text and answer choices.

#### Answer Validation
The `checkAnswer()` function compares the selected answer with the correct answer stored in the question object. It provides immediate feedback to the user by highlighting the correct or incorrect choices.

#### Score Calculation
The `showScore()` function calculates the user's total correct answers and displays the score at the end of the quiz. It provides a summary of the user's performance.

## Responsive Design

The app is designed to be fully responsive, ensuring it works seamlessly on various devices, including desktops, tablets, and mobile phones. The use of CSS Flexbox and media queries ensures that the layout adjusts appropriately to different screen sizes.

## Academic Insights

This project demonstrates key concepts in web development, including DOM manipulation, event handling, and dynamic content generation. It serves as a practical example for computer science students to understand how front-end technologies can be integrated to create interactive web applications. Through this project, students can learn:

- **HTML5**: Structuring web content.
- **CSS3**: Styling web pages.
- **JavaScript**: Adding interactivity and handling data.
- **Modular Code**: Organizing code into separate files for better maintainability.
- **Responsive Design**: Ensuring usability across different devices.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/Qyuzet/js-quiz-app/blob/main/LICENSE) file for details.

## Contact

For any questions or suggestions, please contact Riki Awal Syahputra at [riqi20082003@gmail.com](mailto:riqi20082003@gmail.com).

## Live Demo

You can try the app live at [JS Quiz App Demo](https://qyuzet.github.io/js-quiz-app/).

For more details and to view the code, visit the [GitHub repository](https://github.com/Qyuzet/js-quiz-app).
