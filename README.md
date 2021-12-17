# Qualifying loans Application

This is a pyhton command-line interface application that allows users to see qualifying loans from lenders. This application works by taking the 'daily_rate_sheet' of loan criteria from various loan providers, asking the user questions evaluating their loan eligibility, returning them a list of qualifying loans and allowing them to save it to a CSV file so the results can be shared as a spreadsheet.. 

---

## Technologies

This project leverages python 3.7 with the following packages:

* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entrypoint.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs

---

## Installation Guide

Before running the application first install the following dependencies.

```python
  pip install fire
  pip install questionary
```
---

## Usage

To use the loan qualifier application simply clone the repository and run the **app.py** with:

```python
python app.py
```

Upon launching the loan qualifier application you will be greeted with the following prompts.

![text_image](https://github.com/Oleener/Challenge_2/blob/main/Prompt.png)

---

## Contributors

Brought to you by Olena Shemedyuk.

email: Olenashemedyuk@gmail.com 

---

## License

MIT
