# Testing Guide

This document describes how to test SickoMenu.

## Unit Tests

Run all unit tests:

```bash
python -m pytest tests/
```

Run specific test file:

```bash
python -m pytest tests/test_core.py
```

Run with coverage:

```bash
pip install pytest-cov
python -m pytest --cov=sickomenu tests/
```

## Integration Tests

```bash
python -m pytest tests/integration/
```

## Test Development

When adding new features, write tests in the `tests/` directory.

### Test Structure

```
tests/
├── test_core.py
├── test_utils.py
├── integration/
│   └── test_api.py
```

## Continuous Integration

Tests run automatically on push and pull requests via GitHub Actions.
