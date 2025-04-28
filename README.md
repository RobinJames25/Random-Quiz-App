# Random-Quiz-App
Key Features:

    Dynamic Question Display: Use a random selection of questions from a predefined set to ensure variety each time the quiz is taken.

    State Management: Manage the quiz state (e.g., current question, selected answers, score) using React's useState hook.

    Timer (Optional): If you want to add a timer, you can implement it using the useEffect hook.

    Score Summary: After the quiz, display the user's score out of the total number of questions.

    Question Loop: After answering 20 questions, you can display a new set of random questions from the pool or restart the quiz.

    UI/UX: Use simple navigation like "Next" to move between questions, and "Submit" to show the result at the end.

Recommended Structure:

    Question Pool: Create a pool of questions and answers (e.g., an array of objects), where each question has options and the correct answer.

    Randomization: Shuffle the question pool and pick the first 20 questions, or randomize on every restart.

    Score Calculation: Keep track of the number of correct answers and display a score summary after completing the quiz.

Tools/Libraries:

    React: For the app structure.

    React Router (optional): For any page routing if you want to have separate pages for the quiz, results, etc.

    CSS: For styling, or you could use something like Styled Components if you're comfortable with it.

Example Flow:

    Start Page: A page where the user clicks "Start" to begin the quiz.

    Quiz Page: Displays one question at a time, with options to select the answer.

    Results Page: Shows the user's score, with an option to restart or view explanations.
