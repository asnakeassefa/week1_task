
## Brief Description of Each Directory

- **`.vscode/`**: Contains Visual Studio Code specific settings. The `settings.json` file can be configured for your development environment.

- **`.github/workflows/`**: Holds GitHub Actions workflows, such as `unittests.yml`, which is used to automatically run unit tests whenever changes are pushed to the repository.

- **`.gitignore`**: Lists files and directories that Git should ignore. This usually includes environment files, build artifacts, and other files that should not be version controlled.

- **`requirements.txt`**: Specifies the Python libraries and packages required to run the project. You can install these dependencies using `pip install -r requirements.txt`.

- **`README.md`**: The main documentation for the project.

- **`src/`**: Contains the main source code for the project. The `__init__.py` file makes this directory a package.

- **`notebooks/`**: Contains Jupyter notebooks for exploratory data analysis and experimentation. The `README.md` provides guidelines for working within this directory.

- **`tests/`**: Dedicated to unit and integration tests. The `__init__.py` file allows you to organize and run tests as a package.

- **`scripts/`**: Contains various scripts used for data processing, analysis, or other automation tasks. The `README.md` here explains how to use these scripts.

## Getting Started

1. **Install Dependencies**: 
   Install the required Python libraries using:
   ```bash
   pip install -r requirements.txt
