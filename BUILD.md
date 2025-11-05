# Build Instructions

This document provides instructions for building SickoMenu.

## Prerequisites

- Python 3.8+
- pip
- Development dependencies

## Building from Source

### 1. Clone the Repository

```bash
git clone https://github.com/MRuhan17/SickoMenu.git
cd SickoMenu
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Build the Project

```bash
python setup.py build
```

### 4. Install Locally

```bash
pip install -e .
```

## Creating a Distribution

```bash
python setup.py sdist bdist_wheel
```

## Troubleshooting

If you encounter issues during the build, see TROUBLESHOOTING.md for common solutions.
