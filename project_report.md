Project Report: Simple Typing Speed Test

1. Cover Page
Project Title: Simple Typing Speed Test
Author: Yuvraj Singh
Date: 25th November 2025

2. Introduction
This project implements a basic typing speed test application in Python. It measures the typing speed in words per minute and accuracy in typing a predefined sentence. The project helps users assess and improve their typing skills through immediate feedback.

3. Problem Statement
Many users want a quick and easy tool to evaluate and enhance their typing speed and accuracy, but available options can be too complex or not readily accessible. This lightweight command-line application fills that gap by providing a simple typing test with instant results.

4. Functional Requirements
•Displays a fixed sentence for the user to type.

•Starts timer when the user begins typing.

•Calculates the total time taken to type the sentence.

•Computes words per minute (WPM) based on typed input.

•Calculates accuracy percentage based on correct characters typed.

•Displays time taken, WPM, and accuracy after typing completion.

5. Non-functional Requirements
•Usability: Simple command-line interface with straightforward instructions.

•Performance: Fast response with immediate calculation after input.

•Reliability: Accurate timing and character comparison.

•Maintainability: Clean, modular Python code for easy updates.

6. System Architecture
The system is a straightforward Python script using a sequential flow: display text → user readiness prompt → timing start → user input → timing end → calculations → results display.

7. Design Decisions Rationale
The project uses Python's built-in time module for precision timing and simple string operations for accuracy calculations to keep dependencies minimal and ensure cross-platform usability.

8. Implementation Details
•Prompts the user to type a fixed sentence.

•Records time before and after typing.

•Calculates WPM based on the number of words typed and elapsed time.

•Accuracy is computed by character comparison with the original sentence.

9. Testing Approach
Manual testing by running the script several times, verifying results with varied typing speeds and accuracy.

10. Challenges Faced
Handling edge cases where user input length differs from original text; avoiding zero-division errors when timing is too short.

11. Learnings / Key Takeaways
Gained practical experience with timing user input, calculating performance metrics, and structuring simple Python projects.

12. Future Enhancements
•Random sentence selection for greater variety.

•Simple GUI for user-friendliness.

•More detailed analytics such as error tracking or performance graphs.

15. References
Python documentation (time module)

Online tutorials and examples of typing speed test projects