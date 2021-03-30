# Workshops
## Getting Started

1. First, you need Python 3.7+ installed. There's many ways to do this and it's best to look online.
2. Download this repository
    ```bash
    $ git clone https://github.com/FilippenkoGroup/workshops.git
    ```

    You should have a folder named `workshops`
3. Inside `workshops` folder, install python packages by one of these method

    * Using pip
        ```bash
        # We highly recommend you create a virtual environment specificallyy for the workshops
        $ pip install .
        ```

    * Using poetry
        ```bash
        $ poetry install
        ```

## Contributing
Few rules to follow:

* You may add new workshops under `/workshops`
* You must use [poetry](https://python-poetry.org/) to handle python dependencies adding new dependencies to `pyproject.toml`.
* Every commit to master must be installable using both the `pip` and `poetry` method.