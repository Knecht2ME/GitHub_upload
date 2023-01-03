# Loan Qualifier Application

This project qualifies people by using their credit score, monthly debt, monthly income, desired loan amount, and current home value. To filter against a list of Banks which offer loans. Then producing a list of loans the user can save to take home.

---

## Technologies

This application runs on python 3.9.13

And uses the following libraries:

Python Fire

Questionary

---

## Installation Guide

Install Python Fire writing the following in the terminal:
```
pip install fire
```

Next create a new file, and import the following 
```
import fire
import random
```
Save this file as cli.py

Next install questionary in your terminal
```
pip install questionary
```
Next create a new file, and import the following
```
import questionary
```
save this file as dialog.py

---

## Usage

When prompted 
```
?Enter a file path to a rate-ssheet (.csv):
>Enter: data/daily_rate_sheet.csv

? What's your credit score?
>Enter:______

? What's your current amount of monthly debt?
>Enter:______

? What's your desired loan amount?
>Enter:______

? What's your home value?
>Enter:______

? Would you like to save your qualified loan list?
>Enter: yes or no
```

---

## Contributors

Cary Gutknecht, Knecht2me

---

## License

MIT License

Copyright (c) [2023] [Cary Dennis Gutknecht]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
