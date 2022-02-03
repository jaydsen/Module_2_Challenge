# The Loan Qualifier Application

Have you ever applied for a new loan? How was your experience? Most people who have been in this position would agree that the process can be quite arduous to say the least! With so many lenders in the market, it can be a harrowing experience trying to find the right match for a loan! If you are one of said people, you can put your mind at ease thanks to The Loan Qualifier Application! The purpose of this application is to streamline the process of applying for a loan by using programming tools to vastly improve the end-user experience without sacrificing the accuracy & precision of an elite loan matching application.

A common complaint amongst loan applicants is the repetitive nature of having to submit multiple loan applications to different lenders. To make matters worse, all that effort goes to waste when you realize you didn't qualify for the loan! With The Loan Qualifier App, you input a series of loan-related financial information i.e. credit score, monthly income, loan amount, etc. After providing this information a mere single time, Voila! At record speed, the application will generate a list of lenders that matches your financial profile!

Thus, The Loan Qualifier Application puts the power back in the hands of the loan applicant! The goal of the application is to reduce the time spent searching for a lender while eliminating redundancies and leveraging the same financial calculations used by lenders! Welcome to the new age of applying for a loan. Welcome to The Loan Qualifier Application!

---

## Technologies

This application has been programmed using Python 3.9.7.
The libraries imported for this application are sys, fire, questionary, csv and Path.
Coded on Visual Studio Code version: 1.63.2 (Universal).
System is macOS Big Sur version 11.6.

---

## Installation Guide

Using the python installation package via the Terminal, install the following modules: sys, fire, questionary, csv, Path.

Download the 'app.py' program script into desired system repository. In the same repository, create two folders: 'data' and 'qualifier'. In the 'data' folder, download 'daily_rate_sheet.csv' data file. In the 'qualifier' folder, create the following subfolders: 'filters' and 'utils'. These two subfolders will house the various coding block modules used in the program. In the 'filters' subfolder, download the 'credit_score.py', 'debt_to_income.py', 'loan_to_value.py' and 'max_loan_size.py' program files. Lastly, in the 'utils' subfolder, download the 'calculators.py' and 'fileio.py' program files.

---

## Usage

This is a prompt-based application. The following series of queries are requested of the end-user:

1. Enter a file path to a rate-sheet (.csv):
    * Provide file path of stored daily_rate_sheet.csv data file.

2. What's your credit score?
    * Provide credit score.

3. What's your current amount of monthly debt?
    * Provide monthly debt amount (in USD)

4. What's your total monthly income?
    * Provide monthly income amount (in USD)

5. What's your desired loan amount?
    * Provide desired loan amount (in USD)

6. What's your home value?
    * Provide home value amount (in USD)

If qualifying loans are found, the following queries will generate:

7. Would you like to save your qualifying loans to a file? Yes or No?
    * Provide an answer of either Yes or No if you would like to generate a csv file containing qualifying loans

8. Where do you want to save the file? Specify file path.
    * Provide desired file path of where qualifying loans file is to be saved (include <file name>.csv at end of file path)

9. Confirmation message to generate upon successful creation of qualifying loans csv file.

---

## Contributors

Project developer: Jay Sen
Contact via: https://www.linkedin.com/in/jay-sen-6434a134/

---

## License

The Loan Qualifier Application is officially licensed by Jay Sen, LLC and available for commercial use.
