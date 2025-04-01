This Python application reads student data from a YAML file and provides functionality to display and filter student information based on GPA.

## Features

- Load student data from a YAML file
- Display all student information
- Filter students by minimum GPA
- Simple command-line interface

## Prerequisites

- Python 3.x
- PyYAML library

## Installation

1. Clone this repository or download the files to your local machine
2. Install the required package:

```bash
pip install pyyaml
```

## Files

- `students.yaml`: Contains student data in YAML format
- `app.py`: Main Python application file

## YAML File Structure

The `students.yaml` file should follow this structure:

```yaml
students:
  - name: Alice
    age: 21
    major: Computer Science
    gpa: 3.8
  - name: Bob
    age: 22
    major: Mathematics
    gpa: 3.5
  # ... more students
```

## How to Run

1. Ensure both `app.py` and `students.yaml` are in the same directory
2. Run the application:

```bash
python app.py
```

## Usage

1. The application will first display all student information
2. Then it will prompt you to enter a minimum GPA value
3. It will display all students meeting or exceeding that GPA

## Example Output

```
All Students:
Name: Alice, Age: 21, Major: Computer Science, GPA: 3.8
Name: Bob, Age: 22, Major: Mathematics, GPA: 3.5
Name: Charlie, Age: 20, Major: Physics, GPA: 3.9
Name: David, Age: 23, Major: Chemistry, GPA: 3.2
Name: Eva, Age: 21, Major: Computer Science, GPA: 3.7

Enter minimum GPA to filter students: 3.6
Students with GPA >= 3.6:
Name: Alice, Age: 21, Major: Computer Science, GPA: 3.8
Name: Charlie, Age: 20, Major: Physics, GPA: 3.9
Name: Eva, Age: 21, Major: Computer Science, GPA: 3.7
```
![Alt text describing the screenshot](![yaml-screenshot 1](https://github.com/user-attachments/assets/5555639c-6cc6-4b83-a2ec-b34530f79ee7)
)
![Alt text describing the screenshot](![yaml-screenshot-2](https://github.com/user-attachments/assets/03c848cf-b947-44d8-9f65-c5da821f924f)
)

## Customization

You can easily modify the application to:
- Add more filtering options (by major, age, etc.)
- Sort students by different criteria
- Add functionality to edit and save student data back to the YAML file
- Implement additional student attributes

## License

This project is open-source and available for anyone to use and modify.

## Author

Simran Negi

## Date

2025-04-01
