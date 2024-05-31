# Transformers for Time-series Forecasting

This repository contains code, notebooks.
```text
├── Dockerfile               # The file to build a container using build a or docker container
├── CONTRIBUTING.md          # Onboarding instructions for new contributors
├── docs                     # Documentation site (PyDocs)
├── .github                  # Github metadata for repository
│   ├── release_message.sh   # A script to generate a release message
│   ├── ISSUE_TEMPLATE       # Templates
│   └── workflows            # The CI pipeline for Github Actions
├── .gitignore               # A list of files to ignore when pushing to Github
├── HISTORY.md               # Auto generated list of changes to the project
├── LICENSE                  # The license for the project
├── Makefile                 # A collection of utilities to manage the project
├── MANIFEST.in              # A list of files to include in a package
├── src/{transformers_ts}       # The main python package for the project
│   ├── __init__.py          # This tells Python that this is a package
│   ├── info.py              # Project info [Author, version]
├── data                     # Required data
├── notebooks                # Jupyter Notebooks for the project
├── config                   # Required configuration files
├── README.md                # The main readme for the project
├── requirements.txt         # List of requirements for the project
├── requirements-test.txt    # List of requirements for testing and development
└── tests                    # Unit tests for the project (add mote tests files here)
    ├── data                 # Data and fixtures for pytest
    ├── __init__.py          # This tells Python that this is a test package
    ├── conftest.py          # Configuration, hooks and fixtures for pytest
    └── test_base.py         # The base test case for the project
```
