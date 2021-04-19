# Journal Day 3 - Week 11

## Daily Journal Questions

1. What is SQL injection?

    SQL injection is a type of attack that can give an adversary complete control over your web application database by inserting arbitrary SQL code into a database query.

2. What are 3 methods SQL injection can be done by?

    1. User Input
    2. Modifying Cookies
    3. Server variables such as HTTP headers

3. How can we detect and sanitize SQL injection attacks?

    Intrusion Detection Systems (IDS) can be tuned to detect SQL injection attacks. A few ways to sanitize injection attacks would be to whitelist input validation to use prepared statements with parameterized queries, and to escape all user-supplied input; limit account privileges; and, lastly, creating stored procedures.
