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

* You should always create a new branch, push your changes, and make a pull request (PR) to merge into this repo.
* We do not require PRs to be reviewed or past tests so be vigilant of commit errors.
* You may add new workshops under `/workshops`
* You must use [poetry](https://python-poetry.org/) to handle python dependencies adding new dependencies to `pyproject.toml`.
* Every commit to master must be installable using both the `pip` and `poetry` method.

To get started:

1. Set up the project
    ```bash
    $ git clone https://github.com/FilippenkoGroup/workshops.git
    $ cd workshops
    $ git checkout -b myname/short-description  # e.g., johndoe/add-some-workshop
    $ poetry install .
    
    # Make changes
    $ git add <your changes>
    $ git push origin <your branch name>
    ```
2. After you made your changes, head over to https://github.com/FilippenkoGroup/workshops/pulls and make a PR using your branch.
3. Wait until your PR passes before merging. If you see any failures, fix it until the test passes.
4. When ready, at the end of your PR, click "Merge" (we recommend "Squash and merge").
