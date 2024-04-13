# Club Management System ReadMe

## Project Description
The Club Management System is a bespoke web application designed to manage a small, amateur club where members engage in weekly activities like salsa dancing. The club is characterized by its casual attendance policy, where members can choose to attend sessions as they wish, paying per session or in advance for up to a month with potential discounts. This application plays a crucial role in streamlining the administrative tasks such as tracking attendance, managing session payments, and maintaining financial records.

The system enables efficient handling of routine financial obligations such as hall rental payments and compensation for the club’s amateur coach, who is paid based on the actual sessions attended due to her other professional commitments. Special emphasis is placed on financial accountability, ensuring members who attend practice sessions either pay promptly or are followed up with reminders and notifications about their dues.

## Technology Stack
- **Python 3.8 or higher**: Primary programming language.
- **Flask**: A lightweight WSGI web application framework used to build the web interfaces.
- **Flask-SQLAlchemy**: Used for database interactions, utilizing SQLite for data storage.
- **SQLite**: A lightweight, disk-based database that doesn't require a separate server process.

## Setup Instructions
1. Install Python 3.8 or higher on your system.
2. Install Flask and Flask-SQLAlchemy via pip:
3. To start the application, navigate to the project directory and execute:

## File Structure
- `app.py`: Contains all routes and configurations for the Flask application.
- `templates/`: Houses HTML templates.
- `index.html`: Home page for member log-in and session registration.
- `member_statement.html`: Displays individual financial statements for members.
- `financial_statement.html`: Provides an overview of the club’s finances.
- `static/`: Storage for static files like CSS for styling.
- `style.css`: Stylesheet for the web pages.
- `ReadMe.txt`: Overview and instructions for the system.

## Usage
- **Homepage**: Access the application at `http://localhost:5000`. Members can register for sessions and view their financial statements.
- **Payment Tracking**: Members pay $10 per session or prepay monthly with discounts. The system tracks these transactions and flags unpaid sessions.
- **Financial Management**: Automatically calculates payments due to the coach and tracks hall rental payments.
- **Notifications**: Sends reminders to members for upcoming sessions and alerts for unpaid dues.

## Important Notes
- The system uses the `club.db` SQLite database, automatically generated at the first run.
- Designed for development environments. Review security configurations for production deployment.

For further assistance or contributions, please visit our GitHub repository.
