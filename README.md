# Age Calculator

A simple Python command-line tool that calculates a person's exact age (in years, months, and days) from their date of birth.

## Features

- Calculates age in years, months, and days
- Validates date input and handles invalid formats gracefully
- Accounts for leap years
- Simple, dependency-free CLI interface

## Demo

```
Enter your date of birth (YYYY-MM-DD): 2000-05-14
You are 26 years, 2 months, and 19 days old.
```

## How It Works

The script uses Python's built-in `datetime` module to:
1. Parse the user's birth date input
2. Compare it against the current date
3. Compute the exact difference in years, months, and days

## Getting Started

### Prerequisites
- Python 3.x (no external libraries required)

### Installation
```bash
git clone https://github.com/vanshhiiikaa/Age-Calc.git
cd Age-Calc
```

### Usage
```bash
python age_calc.py
```
Then enter your date of birth when prompted.

## Tech Stack
- Python 3
- `datetime` module

## Possible Improvements
- [ ] Add input validation for future dates
- [ ] Support multiple date formats (DD/MM/YYYY, MM-DD-YYYY, etc.)
- [ ] Add a simple GUI using Tkinter
- [ ] Add unit tests

## Author
**Vanshika**
- GitHub: [@vanshhiiikaa](https://github.com/vanshhiiikaa)
- LinkedIn: [Vanshika Gupta](https://linkedin.com/in/vanshika-gupta-4a2002329)

## License
This project is open source and available under the [MIT License](LICENSE).
