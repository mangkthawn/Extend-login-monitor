# Extend-login-monitor
# Login Monitor

This project is a Python program that analyzes login records and looks for possible security problems. It can find failed login attempts, locked accounts, suspicious IP addresses, users who use different IP addresses, and the busiest login hour.

## How to Run

To run the program, open the terminal in the project folder and use:

python3 assignment_starter_login_monitor.py

## Busiest Hour

For the busiest_hour() method, I created an empty dictionary to count the login attempts for each hour. I used a for loop to go through the login records and split the timestamp to get the time. Then I used the first two characters of the time to get the hour and counted how many login attempts happened during each hour. Finally, I used max() to find the hour with the most login attempts and returned the hour and the number of attempts.
