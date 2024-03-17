# Pomodoro-App
Pomodoro timer application

This is a simple Pomodoro timer application created using Tkinter in Python. It implements the Pomodoro Technique, which is a time management method that uses a timer to break down work into intervals separated by short breaks.
Features

    Work sessions with customizable duration
    Short and long breaks with customizable duration
    Visual timer display
    Checkmarks to track completed work sessions
    Start, reset, and title label functionality

Requirements

    Python 3
    Tkinter library (usually included with Python)

Running the App

    Save the code as pomodoro.py.
    Open a terminal or command prompt and navigate to the directory where you saved the file.
    Run the following command:

python pomodoro.py

This will launch the Pomodoro app.
Customization

    You can modify the following constants at the beginning of the code to customize the app:
        WORK_MIN: The duration of a work session in minutes (default: 1)
        SHORT_BREAK_MIN: The duration of a short break in minutes (default: 1)
        LONG_BREAK_MIN: The duration of a long break in minutes (default: 20)
    You can replace the image path in the canvas.create_image line with the path to your own image file for the tomato icon (optional).

Functionality

    Click the "Start" button to begin the Pomodoro timer.
    The timer will count down and display the remaining time in the center of the app.
    The title label will change color and text depending on the current state (Work, Short Break, or Long Break).
    Checkmarks will appear at the bottom of the app to track completed work sessions.
    Click the "Reset" button to stop the timer and reset all values.

