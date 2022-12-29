
# SACHIN's FINANCE

### Video url: https://youtu.be/SV8voADQKao

### Description:

My final project is a stock market website that allows the user's to register to use the services of my website.

By using my website the user can check the real-world current value of any stock.
He can also buy the stocks (not applied in real-life), and also he can sell the stocks shares he bought, and also see the transactions history of his account
and also he can also add cash into the account. In the home page he will able to see the Portfolio of his stocks and their current values in real-life.

My website is best use for practicing the trading the stock markets for the absolute beginners.


### CS50
>This was my final project for conclude the CS50 Introduction to Computer Sciense course.

>CS, python, flask, flask web framework, web development, CS50

### Database


All information about users, their transactions are stored in finance.db file
I needed 2 tables for my database, namely users table and transactions table
In the user table, I kept id, username, hash (for password) and cash.
Initially the default cash for every user is $10000.
The id are unique values and duplicate usernames are not allowed in my website as we are registering using username and password.

In the transactions table, I kept id, user_id, symbol, shares, price, trasacted(date and time).
The id is unique value and user_id is the id value in users table 
and symbol is the name of the Stock which he bought
and shares represent the no. of shares he bought or sell in each transaction
buying the stocks is represented as +ve value in shares and
selling the stocks is represented as -be value in shares
and the price column represents the stock price for 1 share at the time he bought
and the transacted column represents the date and time he bought the particular share.

### Demonstration on youtube
For the CS50 final project you have to make a video showning your project,
[My Final Project presentation](https://youtu.be/SV8voADQKao)


### About CS50
CS50 is a openware course from Havard University and taught by David J. Malan

Introduction to the intellectual enterprises of computer science and the art of programming. This course teaches students how to think algorithmically and solve problems efficiently. Topics include abstraction, algorithms, data structures, encapsulation, resource management, security, and software engineering. Languages include C, Python, and SQL plus students’ choice of: HTML, CSS, and JavaScript (for web development).

Thank you for all CS50.

- Where I get CS50 course?
https://cs50.harvard.edu/x/2020/


