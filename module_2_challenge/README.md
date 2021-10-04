# Qualifying Loans Saver

This code allows for a user to look up and save qualifying loans to a CSV file so the results can be shared as spreadsheet.

---

## Technologies

```
pyhton
fire
questionary
```

---

## Installation Guide

clone the code and run `python app.py`

---

## Usage
run `python app.py` and follow the prompt and enter the file name you want the file to be saved as:
```
~$ python app.py
? Enter a file path to a rate-sheet (.csv): ./data/daily_rate_sheet.csv
? What's your credit score? 760
? What's your current amount of monthly debt? 1
? What's your total monthly income? 8000
? What's your desired loan amount? 300000
? What's your home value? 350000
The monthly debt to income ratio is 0.00
The loan to value ratio is 0.86.
Found 3 qualifying loans
? Do you want to save the file? Yes
? Enter the filename to save: 300loan
data/300loan.csv saved
```
---

## Contributors

Ahmad S

---

## License

No license
