# AI Ethics Quiz Application

A responsive, interactive web-based quiz application to learn Topics from the TUM AI-Ethics lecture (ID: SOT87317) with dark/light mode support and progress tracking.

## Features

- **Interactive Quiz Interface**: Clean, user-friendly interface for answering multiple-choice questions
- **Dark/Light Mode**: Toggle between color schemes for comfortable viewing
- **Progress Tracking**: Visual progress bars showing completion status and correct/incorrect answers
- **Question Navigation**: Navigate between question sets with Previous/Next buttons or keyboard arrows
- **Randomized Questions**: Questions and answer options are shuffled for each session
- **Responsive Design**: Works on desktop and mobile devices
- **Instant Feedback**: Submit answers to see your score and which questions you got right/wrong
- **Question Sets**: Questions are divided into manageable sets (10 questions per page by default)

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge, ...)
- A local web server (Python, NodeJS, ...)

### Installation

1. Clone or download the project files
2. Ensure both `index.html` and `aiEthics.json` are in the same directory

### Running the Application

```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if you have http-server installed)
npx http-server
```

Then open `http://localhost:8000/quiz.html` in your browser.

## Project Structure

```
tum_quiz/
├── index.html          # Main application file
├── aiEthics.json       # Quiz questions and data
└── README.md           # This file
```

## Quiz Content

The contents of this Quiz are oriented on the contents of the SoSe2025 TUM AI-Ethics lecture (ID: SOT87317).

The quiz covers various topics including:
- Philosophical foundations of ethics
- Normative ethics approaches (Consequentialism, Deontology, Virtue Ethics)
- AI bias and fairness
- Trustworthy AI principles
- Autonomous vehicles ethics
- AI in healthcare and military applications
- Institutional ethics and governance frameworks

## Usage

1. **Starting the Quiz**: Open the application in your browser
2. **Answering Questions**:
    - Select your answer for each question
    - Use Previous/Next buttons or arrow keys to navigate
    - Click on progress bars to jump to specific question sets
3. **Submitting Answers**: Click "Submit Answers" to check your score
4. **Viewing Results**: After submission, see which answers were correct/incorrect and your overall score
