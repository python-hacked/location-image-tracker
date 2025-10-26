# Contributing to Location Image Tracker

Thank you for your interest in contributing to Location Image Tracker! This project is open source and we welcome contributions from the community.

## Code of Conduct

This project follows a code of conduct to ensure a welcoming environment for all contributors. By participating, you agree to:

- Be respectful and inclusive
- Focus on constructive feedback
- Accept responsibility for mistakes
- Show empathy towards other contributors

## How to Contribute

### 1. Fork the Repository

Click the "Fork" button on GitHub to create your own copy of the repository.

### 2. Clone Your Fork

```bash
git clone https://github.com/your-username/location-image-tracker.git
cd location-image-tracker
```

### 3. Create a Feature Branch

```bash
git checkout -b feature/your-feature-name
```

### 4. Make Your Changes

- Follow the existing code style
- Add tests for new features
- Update documentation as needed
- Ensure your code works on different browsers

### 5. Test Your Changes

```bash
# Install dependencies
pip install -r requirements.txt

# Run the application
python -m uvicorn main:app --host 0.0.0.0 --port 8000

# Test in browser at http://localhost:8000
```

### 6. Commit Your Changes

```bash
git add .
git commit -m "Add: Brief description of your changes"
```

### 7. Push to Your Fork

```bash
git push origin feature/your-feature-name
```

### 8. Create a Pull Request

Go to the original repository and create a pull request from your feature branch.

## Development Guidelines

### Code Style

- Use descriptive variable and function names
- Add comments for complex logic
- Follow PEP 8 for Python code
- Use consistent HTML/CSS/JS formatting

### Testing

- Test on multiple browsers (Chrome, Firefox, Safari, Edge)
- Test on mobile devices
- Verify location permissions work correctly
- Check error handling

### Documentation

- Update README.md for new features
- Add inline comments for complex code
- Document API endpoints if added

## Types of Contributions

### 🐛 Bug Fixes
- Fix reported issues
- Improve error handling
- Fix browser compatibility issues

### ✨ Features
- Add new functionality
- Improve user interface
- Enhance performance

### 📚 Documentation
- Improve README
- Add code comments
- Create tutorials

### 🎨 UI/UX
- Improve design
- Add animations
- Enhance mobile experience

### 🔧 Maintenance
- Update dependencies
- Improve code quality
- Add tests

## Reporting Issues

When reporting bugs, please include:

- Browser and version
- Operating system
- Steps to reproduce
- Expected vs actual behavior
- Screenshots if applicable

## License

By contributing, you agree that your contributions will be licensed under the MIT License.

## Questions?

Feel free to open an issue for questions or join our discussions!