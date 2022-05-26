# Install
**Note:** This package requires Python 3.8 or later.

There are many ways to install this package. Below are some examples.

## Install using pip (recommended).

### Requirements
- [Python](https://www.python.org/downloads/) (>=3.8)
- [`pip`](https://pypi.org/project/pip/) (This should come with your Python distribution)

### Steps
- Open the terminal.
- To install the package from PyPi, just run this command:
  ```bash
  # Linux/macOS
  python3 -m pip install -U sort-requirements-file
  # Windows
  py -3 -m pip install -U sort-requirements-file
  ```
- If you want to install the development version, do the following (note that this required you to have `Git` installed in your machine):
  ```bash
  pip install git+https://github.com/HigherOrderLogic/sort-requirements-file
  ```

## Install using `git`.

### Requirements
- [`git-scm`](https://git-scm.com/downloads/)
- [Python](https://www.python.org/downloads/) (>=3.8)

### Steps
- Clone the repo.
  ```bash
  git clone https://github.com/HigherOrderLogic/sort-requirements-file.git
  cd sort-requirements-file
  ```
- Then run this command to install the package.
  ```bash
  python setup.py install
  ```