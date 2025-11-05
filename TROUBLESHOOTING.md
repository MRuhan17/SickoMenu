# Troubleshooting Guide

## Installation Issues

### Issue: pip install fails

**Solution:**
```bash
pip install --upgrade pip
pip install sickomenu
```

### Issue: Python version not compatible

**Solution:**
Ensure you're using Python 3.8 or higher:
```bash
python --version
```

## Runtime Issues

### Issue: ImportError

**Solution:**
- Ensure the package is installed: `pip list | grep sickomenu`
- Try reinstalling: `pip install --force-reinstall sickomenu`

### Issue: Module not found

**Solution:**
- Check your Python path
- Ensure virtual environment is activated

## Building Issues

### Issue: Build fails with compilation errors

**Solution:**
- Install build tools for your system
- Check dependencies are installed

## Getting Help

If you can't resolve your issue:

1. Check the FAQ
2. Search existing GitHub issues
3. Create a new issue with:
   - Python version
   - Error message
   - Steps to reproduce
