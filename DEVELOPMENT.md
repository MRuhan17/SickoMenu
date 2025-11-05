# Development Guide

This guide covers how to set up your development environment and contribute to SickoMenu.

## Prerequisites

- Python 3.8 or higher
- Git
- pip or Poetry

## Setup

### 1. Clone the Repository

```bash
git clone https://github.com/MRuhan17/SickoMenu.git
cd SickoMenu
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
pip install -r requirements-dev.txt  # For development tools
```

## Running Tests

```bash
python -m pytest tests/
```

## Code Style

We use Black for code formatting and Flake8 for linting.

```bash
black .
flake8 .
```

## Making Changes

1. Create a new branch for your feature or bugfix
2. Make your changes
3. Run tests and linters
4. Commit with a descriptive message
5. Push to your fork
6. Open a pull request

## Debugging

For debugging, you can use pdb or your IDE's debugger:

```python
import pdb; pdb.set_trace()
```
