# Sylveon

[![CircleCI Status](https://dl.circleci.com/status-badge/img/circleci/3xWZeNMCu5Vj5AMLtYkBLD/3BbpjRhT2mTt2SAzHyziCj/tree/main.svg?style=svg&circle-token=a3755171dc7af90c9eed83c7eb96aa5f59faef63)](https://dl.circleci.com/status-badge/redirect/circleci/3xWZeNMCu5Vj5AMLtYkBLD/3BbpjRhT2mTt2SAzHyziCj/tree/main)

<!-- [![CircleCI](https://dl.circleci.com/status-badge/img/circleci/3xWZeNMCu5Vj5AMLtYkBLD/3BbpjRhT2mTt2SAzHyziCj/tree/main.svg?style=shield&circle-token=a3755171dc7af90c9eed83c7eb96aa5f59faef63)](https://dl.circleci.com/status-badge/redirect/circleci/3xWZeNMCu5Vj5AMLtYkBLD/3BbpjRhT2mTt2SAzHyziCj/tree/main) -->

## Description

This is a template repository for Python designed to work out of the box for developing software projects. This repository provides the fundamental building blocks needed to design and develop projects including:

- Build Management
- Unit Testing
- Continuous Integration
- Static Analysis
- Code Formatting
- Component Specification

A template for issue and pull requests is also provided for collaborative development. 

## Setup (PDM)

### Requirements

- [PDM](https://pdm-project.org/latest/)

### Instructions

1. Clone project repository to your local machine
2. Initialize repository using `pdm install`
3. Activate virtual environment using `pdm venv activate`
4. Run the project using `pdm run start`

View available scripts using `pdm run --list`

### Scripts

- `start` - Start the project
- `test` - Run tests
- `lint` - Run static analysis
- `format` - Format code

## Component Specification

We have included two examples of components within the `__main__.py` file: one is "Hello World" and the second is a component which finds the length of a string. 

The "Hello World" component is a basic module which provides a function to print the greeting message "Hello World!" 

The "String Length" component is designed to calculate the length of a given string. 

We have imported both modules into the `__main__.py` file, to showcase how components can be imported into different files within a Python project. As seen from the code structure below (which only includes files relevant to the components) our import strategy assumes that all components will be within the `src/sylveon` directory. 

```
src/sylveon/
|-- __init__.py
|-- __main__.py
|-- hello_world/
|   |-- __init__.py
|   |-- hello.py
|-- string_length/
|   |-- __init__.py
|   |-- string_length.py

```

## Objectives (Tentative):

1. Programming Language: ```Python``` ✅
2. Toolchain/Runtime Environment: ```Python``` >= 3.9 ✅
3. Testing Framework: ```pytest``` ✅
4. Continuous Integration Solution: ```CircleGI``` ✅
5. Static Analysis Tool: ```mypy```✅
6. Code Formatting Solution: ```black``` ✅
7. Package Manager: ```pip``` ✅
8. Python Dependency Management ✅
9. Component Specification: ✅
10. Issue and Pull Request Templates ❌

## Authors

- Susmitha Kusuma (sk10689@nyu.edu)
- Berry Liu (bl3056@nyu.edu)
- Margaret Jagger (mj3102@nyu.edu)
- Calvin Tian (calvin.tian@nyu.edu)
- Kevin Zheng (kz1252@nyu.edu)
