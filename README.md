## Setup Instructions

### Prerequisites

- Install `pyenv` by following the instructions at [this link](https://github.com/pyenv/pyenv#installation).
- Install `virtualenv`.

### Setting Up the Project

1. Clone the repository:

```sh
git clone https://github.com/yourusername/yourproject.git
cd yourproject
```

2. Install the specified Python version:

```sh
pyenv install 3.12.3
```

3. Set the local Python version:

```sh
pyenv local 3.12.3
```

4. Create and activate a virtual environment:

```sh
virtualenv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
# Deactivate later using command `deactivate`
```

5. Install the project dependencies:

```sh
pip install -r requirements.txt
```
