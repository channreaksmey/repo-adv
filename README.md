# Advanced Programming for Data Science (ADV)

Repository for the **Advanced Programming for Data Science (ADV)** course for **I5-AMS-DAS B**. This repository contains course materials, practical work, exercises, notebooks, and datasets used during the course.

## Repository Structure

The repository is organized into three branches:

- **`main`** — The consolidated branch containing materials merged from both the course and TP branches.
- **`course`** — Materials covered during course classes, including lectures, examples, and theoretical content.
- **`TP`** — Materials covered during practical (TP) classes, including exercises, notebooks, datasets, and practical assignments.

## Working with the Branches

To clone the repository:

```bash
git clone <repository-url>
cd repo-adv
```

To switch to a specific branch:

```bash
git switch main
git switch course
git switch TP
```

The `main` branch is intended to provide the complete version of the repository after changes from the `course` and `TP` branches have been merged.

## Topics

Depending on the class and practical session, materials may cover topics such as:

- Clean and maintainable code
- PEP 8 and Python coding conventions
- Debugging techniques
- Object-oriented programming
- Design patterns
- Data cleaning and preparation
- Working with CSV files
- Data analysis with Python and pandas

## Requirements

The practical materials use Python. Some notebooks may require the following packages:

- Python 3
- pandas
- Jupyter Notebook or JupyterLab

Install the Python dependencies with:

```bash
pip install pandas jupyter
```

## Contributing Materials

When adding new materials:

1. Add course-class materials to the `course` branch.
2. Add practical-class materials to the `TP` branch.
3. Merge the updated branches into `main` when the combined repository should be updated.
4. Use clear file names and keep related datasets with their notebooks or exercises.
5. Avoid committing generated files, secrets, or unnecessary environment-specific files.

## Course

**Course:** Advanced Programming for Data Science (ADV)  
**Class:** I5-AMS-DAS B
```