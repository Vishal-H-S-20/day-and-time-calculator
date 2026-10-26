
# Day and Time Calculator

A Python application that combines date calculations and event countdown functionality in a single program. It includes a calendar-based day-of-the-week calculator, a graphical event countdown timer with an alarm, and a detailed age calculator.

## Features

### 1. Day of the Week Calculator
- Enter a date in DD/MM/YYYY format.
- Display the calendar for the selected month.
- Highlight the selected day.
- Calculate the day of the week for the given date.

### 2. Event Countdown Timer
- Enter an event name, date, and time.
- Display the remaining days, hours, minutes, and seconds.
- Show a notification when the event time arrives.
- Play an alarm when the countdown finishes.

### 3. Age Calculator
- Enter your date of birth.
- Calculate your exact age in years, months, and days.
- Validate the date input and prevent future birth dates.

## Technologies Used

- Python 3
- Tkinter for the graphical user interface
- Pygame for alarm playback
- Pillow for image handling
- Python-dateutil for detailed date calculations
- Calendar and datetime modules

## Requirements

- Python 3
- Pygame
- Pillow
- Python-dateutil

## Installation

Install the required dependencies:

```bash
python -m pip install -r requirements.txt
```

## Run the Application

Run the Python script:

```bash
python Jackfruit_Mini_Project.py
```

## How It Works

The application presents a menu that allows users to choose between calculating the day of the week, setting an event countdown, and calculating their age. Each feature uses Python's date and time functionality to process user input and display the results.

The event countdown uses a Tkinter graphical interface, while the day-of-the-week and age calculators accept input through the terminal.

## Author

Vishal H S
