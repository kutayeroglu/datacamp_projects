# My Solutions to DataCamp Projects

This repository contains my solutions to various projects from DataCamp, intended for learning and future reference.

## Environment Setup

To replicate the environment I used for these projects, follow these steps:

1. **Install Poetry**: If you haven't installed Poetry, follow the instructions on the [Poetry website](https://python-poetry.org/docs/#installing-with-pipx).

2. **Install Dependencies**: Navigate to the root directory of the project and run:
    ~~~
    poetry install
    ~~~

3. **Add Virtual Environment as a Jupyter Kernel**: Execute the following command, replacing `<kernel-name>` with a name for your kernel and `"Python (project-name)"` with a display name of your choice:
    ~~~
    python -m ipykernel install --user --name=<kernel-name> --display-name="Python (project-name)"
    ~~~

This setup ensures you're using the same library versions as those used in my project solutions.

To activate the virtual environment, navigate to the root directory and use:
~~~
poetry shell
~~~
