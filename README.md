# QUIZ

## Overview

QUIZ is a vibrant, web-based quiz application designed to deliver interactive multiple-choice quizzes to users, with a visually appealing interface and engaging features such as animated backgrounds and fun facts. The project leverages HTML, CSS, and modern JavaScript modules for a smooth user experience.

## Features

- **Quiz Engine**: Presents a series of multiple-choice questions, tracks user answers, and calculates the final score.
- **Navigation**: Users can move forward and backward between questions, with prompts to answer before proceeding.
- **Score Feedback**: At the end of the quiz, users receive an emoji-based message according to their performance (e.g., 👑 for a perfect score).
- **Random Facts**: Displays rotating fun facts on the welcome screen for added engagement.
- **Animated Interface**: Uses CSS gradients, transitions, and keyframe animations for a lively look and feel.

## Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Edge, Safari)
- (Optional) Docker for containerized deployment

### Running Locally

1. **Clone the repository**
    ```sh
    git clone https://github.com/hem4arya/QUIZ.git
    cd QUIZ
    ```

2. **Open `TEMPLATE/index.html` or `home.html` in your browser**  
   No build steps required; all dependencies are included.

#### Docker Deployment

A `Dockerfile` is provided for easy deployment with Nginx:

```sh
docker build -t quiz-app .
docker run -p 80:80 quiz-app
```

## File Structure

- `TEMPLATE/index.html`, `home.html` – Entry points for the app
- `SCRIPT/` – JavaScript modules for quiz logic, rendering, and question data
- `CSS/` – Stylesheets for animated backgrounds and quiz UI
- `IMAGES/` – Icons and graphics
- `Dockerfile` – Container configuration

## Customization

- **Questions**: Add or modify questions in `SCRIPT/questions.js`.
- **Facts**: Edit the `facts` array in `SCRIPT/index.js` for your own trivia or information.
- **Styling**: Tweak CSS in `CSS/index.css` and `CSS/home.css` to change colors, fonts, or animations.

## Credits

Created by [hem4arya](https://github.com/hem4arya).

---

Feel free to contribute, suggest improvements, or fork for your own quiz projects!
