# Pytest Basic

Some examples about pytest.

## About

Pytest - Python Automation Test Framework help us Unit Testing, Integration Test,... 

This repo is some examples and very first knowledge of this framework.

Resources for you to start with Pytest:

- [What is Pytest? - Definition & Tutorial](https://www.guru99.com/pytest-tutorial.html)
- [Tutorialspoint - Tutorial Pytest](https://www.tutorialspoint.com/pytest/index.htm)
- [Code Coverage](https://improveandrepeat.com/2021/01/python-friday-53-code-coverage-for-pytest/)

## Getting Started

When you complete the test.py file, you can run the test by this command:

- python -m pytest test.py

HTML report with line-by-line coverage example:

- pytest --cov-report html  --cov=gilded_rose .\test_gilded_rose.py

Branch coverage example:

- pytest --cov-report html  --cov . .\test_branches.py
Or:
- pytest --cov-report html  --cov . --cov-branch .\test_branches.py

## Contact

If you have any concern, please contact me via:

- Gmail: huytuduelist@gmail.com
- Other: [Facebook](https://www.facebook.com/pororo1001)


