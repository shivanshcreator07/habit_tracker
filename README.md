README.md

Habit Tracker (Python Project)

This is a small Python program made to help keep track of daily habits.
You can add your habits, log what you did each day, and see how steady you’ve been over time.
Everything gets stored in a simple JSON file, so your data stays saved even after you close the program.

What the program basically does
1. Add Habits
You can make any habit you want (like “read 20 mins”, “workout”, “drink water”), and set a daily goal for it.

2. Log Your Progress
You can mark how much you did today, or log for any previous date if you missed it.

3. Streaks
The program automatically checks:
    •    Current streak – how many days in a row you hit your target
    •    Longest streak – the highest streak you’ve ever managed

4. Weekly & Monthly Stats
With NumPy, it gives you:
    •    Last 7 days data
    •    Last 30 days total and average

5. View All Habits in One Place
Shows every habit and how much you’ve logged overall.

6. Reset Logs
If you feel like starting fresh, you can clear all logs for any habit.

7. Remove Habit
Deletes a habit completely along with all its saved logs.

How to Run It
1. Install Python

Make sure Python is on your system.
2. Install NumPy

Run this:
pip install numpy

3. Start the program
Just run:
python habit_tracker.py

Files in this project
File Name    What it does
habit_data.json    Stores all habits + logs (it creates itself automatically)
habit_tracker.py    The main code for the project

Python modules used
    •    json
    •    os
    •    datetime
    •    random
    •    time
    •    numpy

Menu you’ll see when the program starts
1 Add Habit
2 Remove Habit
3 Log Habit
4 View Stats
5 Show All Habits
6 Reset Logs
7 Exit

Type the number and hit Enter.
It’s all simple and easy to follow.
Why this project works well
    •    Very beginner-friendly
    •    Clean and readable
    •    Uses basic Python concepts (functions, loops, input handling, JSON storage)
    •    Has a bit of analytics using NumPy
    •    Everything runs directly in the terminal without extra setup

