# ExpCli

An expense management tool for the command-line. Using it, you can track your
expenses across days, weeks, months and even years - without ever leaving your terminal.

## Features
- Tracking monthly income
- Setting a monthly budget
- Entering individual expenses
- Organising and categorising expenses
- Generating expense reports broken down by category into days, weeks, months and year
- Exporting expense reports to CSV and PDF formats

## Installation
Simply clone the repo into a directory with:
```bash
git clone https://github.com/kdormer/exp-cli.git
```

## Usage
To run the program run the command:
```bash
python3 __main__.py
```

Upon running this command, you will be greeted with a menu of 12 possible options that can be taken. It is recommended to create some expense categories, add your monthly income sources and add some expenses before attempting to export your expenses.

User data will be stored in an SQLite database in the same directory as the program was cloned to. Likewise, any PDF and CSV exports will also appear there.

To exit the program, simply enter option 12 when prompted to choose an option.
