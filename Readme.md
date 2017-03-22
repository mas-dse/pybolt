# PyBolt : A PySpark homework submission project

PyBolt is a website using which students can run their PySpark code on the cloud and submit their homework online! Currently in early development status.

Install dependencies::

    $ pip install -r requirements.txt

Run the app server (on port 5000 by default):

    $ python run.py

Use `admin` as the username and password to log in.

## Notes

1. The website depends on sqlite to store data.
2. Students need to sign up an account for the website. To avoid spammers, you need to provide the list of students with their student UIDs and emails in the `students.csv` file. The website will verify the student UID and their email address when a student register, and refuse the registration if UID/email don't exist or don't match.
