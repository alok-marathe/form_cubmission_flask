# Flask User Details App

This Flask app is designed to store user details submitted through a form in a SQLite database named `data.db`. Additionally, it sends a confirmation email to the user who has provided their email address upon submitting the form.

## Features

- **User Form Submission:** Collects and stores user details in the SQLite database.
- **Email Confirmation:** Sends a confirmation email to the user after form submission.

## Prerequisites

- Python 3.x
- Flask
- SQLite

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo

2. Install dependencies:

   ```bash
   pip install -r requirements.txt

3. Create a database named 'data.db' and add a table named `form` with the following columns within it:

    |id|first_name|last_name|email|date|occupation|
    |--|----------|---------|-----|----|----------|

4. Insert a `SECRET_KEY` (Your choice)
5. Now, add the desired gmail username from which you want to send the mail `MAIL_USERNAME`
6. Also add the app password from **Manage your Google Account -> Security -> 2-Step Verification -> App Passwords -> App Name** (give whatever name you like)
   -> and then copy and paste the password in `MAIL_PASSWORD`

### Your setup is now ready!

You just need to type the following command in your terminal and Voilà!

  ```bash
  python app.py
  ```
---
> "In the world of web development, when life gets complex, uncork Flask to simplify the journey." ~ Flask Community
