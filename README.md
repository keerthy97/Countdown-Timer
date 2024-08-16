# Countdown Timer

A simple Django-based countdown timer web application with a visually appealing front-end, hosted on Vercel.

## Features
- **Countdown Timer**: Users can set hours, minutes, and seconds to start the countdown.
- **Start/Pause Functionality**: The timer can be started or paused with a single button.
- **Reset Option**: Users can reset the timer to zero at any time.
- **Time's Up Modal**: When the countdown reaches zero, a modal appears to notify the user.
- **Responsive Design**: The application is fully responsive and adjusts for different screen sizes.

## Project Structure

```plaintext
countdown_timer/
│
├── countdown_timer/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
│
├── timer/
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
│   └── templates/
│       └── timer/
│           └── index.html
│
└── manage.py
```

## Setup and Installation
### Prerequisites
Python 3.9
Django

## Installation Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/countdown_timer.git
   cd countdown_timer
   pip install -r requirements.txt
   python manage.py runserver

## Live Demo

Check out the live demo of the project [here](https://countdown-timer-iota-flame.vercel.app/).

