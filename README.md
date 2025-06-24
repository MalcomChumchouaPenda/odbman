# Odbman - Text-Based Modular Open Database Manager

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/license-CC0%201.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

---

## Description

**Odbman** is a modular command-line application for database administration, designed like a text-based adventure game.
It allows users to perform complex tasks in various functional domains (students, payments, registrations...) through an immersive and interactive interface.

---

## Features

- Text-based adventure style CLI for an engaging user experience
- Modular architecture: each module handles a distinct business domain
- Generic database connection engine supporting multiple DBMS
- Menu-driven navigation with contextual commands
- Suitable for DBAs, developers, and educators

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/odbman.git
cd odbman
```

2. (Optional) Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:

pip install -r requirements.txt
```

## Usage
Run the main application:
```bash
python main.py
Example interaction:

Welcome to ODBMAN
=================
You are connected to the database: school.db

Where would you like to go?
1. Manage Students
2. Manage Payments
3. Manage Registrations
4. Quit
> 1

[STUDENTS MODULE]
What would you like to do?
1. Add a student
2. Remove a student
3. Back
```

## Project Structure
```bash
odbman/
├── core/         # Core services: config, DB connector, logging
├── modules/      # Business modules: students, payments, etc.
├── main.py       # Entry point
└── assets/       # Narrative or decorative text files
```


## Contributing
Contributions are welcome! Please open issues or pull requests on GitHub.

## License
This project is dedicated to the public domain under the CC0 1.0 Universal (CC0 1.0) Public Domain Dedication.
