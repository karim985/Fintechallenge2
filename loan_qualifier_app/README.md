# Loan qualifier app

Loan application using Python to filter thrue customers information such as (credit score, debt to income, loan to value and max loan size) The application works by taking in a `daily_rate_sheet` of loan criteria from various loan providers, asking the user a number of questions to evaluate their loan eligibility, and then returning to them a list of qualifying loans.
---

## Technologies

This is a command line application to match applicants with qualifying loans.
This project leverages python 3.8 with the following packages:

* [fire](https://pypi.org/project/fire/) - For the command line interface, help page, and entrypoint.

* [questionary](https://pypi.org/project/questionary/) - For interactive user prompts and dialogs

---

## Installation Guide

in order to use the app the user need to make sure he has the flowing items intalled
sys
fire
qyuestionary
an `import` will be needed to get our three libraies available to perform a successful call on functions
```
import sys
import fire
import questionary
```


```Python
pip intall fire
```
```
pip install questionary
```
---

## Usage

To use the loan qualifier application simply clone the repository and run the **app.py** with:

```python
python app.py
```
![Loan Qualifier Prompts](Image.png)
---

## Contributors

Karim Bouzina
[linkedin](https://www.linkedin.com/feed/)

---

## License

This Project owned ny UW Fintech Bootcamp
