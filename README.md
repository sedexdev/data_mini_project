# 📘 Data Mini Project

> Mini project to demonstrate understanding of an ETL pipeline in a data-driven Python app

This sample project is intended to demonstrate a working understanding of the fundamentals of
creating data-driven applications in Python. The project uses modern tooling and workflows to
design and test a data application, and then deploy it to the cloud.

The sample datasets used represent global levels of education on a national basis.

## ✨ Features

-   ✅ `pandas` library for data handling
-   ✅ SQL DB integration with `SQLAlchemy`
-   ✅ Robust logging and error handling
-   ✅ Testing with `pytest`
-   ✅ CSV -> SQL ETL pipeline
-   ✅ CI/CD automation with `docker` and _GitHub Actions_
-   ✅ Cloud deployment using _Azure Container Instances (ACI)_
-   ✅ `jinja` frontend for data visualisation served by `flask`
-   ✅ Clear and concise documentation

## 📦 Installation

### Prerequisites

-   A system account with sudo / administrator privileges
-   `Git` - https://github.com/git-guides/install-git
-   `Docker` - https://docs.docker.com/engine/install/
-   `Docker` Compose - https://docs.docker.com/compose/install/
-   `wsl2` - https://learn.microsoft.com/en-us/windows/wsl/install (Windows only when using Docker Desktop)

### Local Setup

```bash
# Clone the repository
git clone https://github.com/sedexdev/data_mini_project.git
cd data_mini_project

# use your preferred virtual environment - I'm using virtualenv
virtualenv venv
source venv/bin/activate
pip install -r src/requirements.txt

# Run the app
TBC...
```

## 📂 Project Structure

```
your-repo-name/
│
├── .github/            # GitHub workflows and issue templates
├── data/               # Data files
├── docs/               # Documentation
├── src/                # Source files
├── tests/              # Unit and integration tests
├── .gitignore          # Ignore file
├── Dockerfile          # Docker container config
├── LICENSE             # MIT license file
└── README.md           # This document
```

## 🧪 Running Tests

Create a new environment and install the dependencies

```bash
# use your preferred virtual environment - I'm using virtualenv
virtualenv venv
source venv/bin/activate
pip3 install -r src/requirements.txt
```

Run the test suite

```bash
# with venv active
pytest -s tests/
```

## 📄 Documentation

-   [ETL Pipeline Reference](https://github.com/sedexdev/data_mini_project/docs/pipeline.md)

## 🐛 Reporting Issues

Found a bug? Open an issue [here](https://github.com/sedexdev/data_mini_project/issues).

## 🧑‍💻 Authors

-   **Andrew Macmillan** – [@sedexdev](https://github.com/sedexdev)

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/sedexdev/data_mini_project/blob/main/LICENSE) file for details.

## 📣 Acknowledgements

-   Many thanks to **Mohamadreza Momeni** who created the sample dataset
-   The files were sourced from [Kaggle](https://www.kaggle.com/datasets/imtkaggleteam/global-education)
