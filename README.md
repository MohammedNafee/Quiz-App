# Quiz App

A simple and interactive Quiz Application that allows users to test their knowledge on various topics. Built using modern web technologies for an engaging user experience.

## Features
- Multiple-choice questions
- Timer for each question
- Score tracking
- Responsive design
- User-friendly interface
- Dynamic question fetching from an external API

## Technologies Used
- HTML, CSS, JavaScript
- [The Trivia API](https://the-trivia-api.com/) (for fetching quiz categories and questions)

## Installation

### Prerequisites
- Install [Visual Studio Code](https://code.visualstudio.com/) if not already installed.
- Install the **Live Server** extension in VS Code.

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/MohammedNafee/Quiz-App.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Quiz-App
   ```
3. Open the project in Visual Studio Code.
4. Ensure the **Live Server** extension is installed and enabled.
5. Right-click on `index.html` and select **Open with Live Server**.
6. The quiz will open in your default web browser.

**Important Note:**
- This project fetches quiz data dynamically from [The Trivia API](https://the-trivia-api.com/), requiring an HTTP server to bypass CORS restrictions. Opening `index.html` directly from the file system (`file://`) will not work.
- Running the project using **Live Server** ensures that API calls function correctly without security limitations.

## Usage
1. Select a quiz category from the available options.
2. Answer the multiple-choice questions within the allotted time.
3. Track your score in real-time as you progress.
4. View your final score at the end of the quiz.
5. Restart the quiz to try again with different questions.

## Contributing
Contributions are welcome! If you'd like to improve the app, follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push the branch.
4. Submit a pull request for review.

## License
This project is licensed under the MIT License.

