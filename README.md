# GitHub Repo Analyzer

A command-line tool that fetches and displays a user's top GitHub repositories using the GitHub API. It serves as a non-trivial initial codebase for implementing build automation.

## Setup
```bash
pip install -r requirements.txt
```

## Usage
```bash
python src/analyzer.py <github_username>
```

## How to replicate the build

1. Install dependencies:

```bash
poetry install```

2. Generate the project:
```bash
poetry build```

# How to use

## Build the project

Create a dist directory containing the wheel and the compressed archive:
```bash
poetry build```

## Test the project

```bash
poetry run pytest```

## Run the project

```bash
poetry run python src/analyzer.py [GitHub_account]```
