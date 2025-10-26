# Location Image Tracker 🗺️

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.118.0-green.svg)](https://fastapi.tiangolo.com/)

A modern, ethical location tracking web application built with FastAPI. Users can view images while optionally sharing their location data for educational and research purposes.

## ⚠️ Important Ethical Notice

**This project is strictly for educational and ethical demonstration purposes only.**

🚫 **NEVER use this to track, spy on, or collect location data from anyone without their explicit, informed consent.**

Misuse of this tool (e.g., deceptive image links to secretly obtain location) is:
- **Illegal** under privacy laws (India's IT Act, GDPR, DPDP Act 2023)
- **Unethical** and violates digital rights
- **Traceable** through IP logs and browser fingerprints

The authors are **NOT responsible** for any misuse, illegal activity, or harm caused by third parties.

## ✨ Features

- 🎯 **Consent-Based Tracking**: Location access only after explicit user interaction
- 📱 **Mobile-First Design**: Responsive UI that works on all devices
- 🗺️ **Interactive Maps**: View tracked locations with Leaflet maps
- 🔄 **Live Tracking**: Continuous location updates while active
- 🎨 **Modern UI**: Beautiful gradient design with smooth animations
- 📊 **Real-Time Stats**: Location accuracy and timestamp tracking
- 🔒 **Privacy-Focused**: No data collection without user consent

## 🚀 Quick Start

### Prerequisites

- Python 3.8 or higher
- pip package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/location-image-tracker.git
   cd location-image-tracker
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**
   ```bash
   python -m uvicorn main:app --host 0.0.0.0 --port 8000
   ```

4. **Access the app**
   - Open http://localhost:8000/view/your-image.jpg
   - View maps at http://localhost:8000/map/your-image.jpg

## 📖 Usage

1. **Add Images**: Place your images in the `static/images/` directory
2. **Share Links**: Send links like `http://your-domain.com/view/image.jpg`
3. **View Locations**: Check `http://your-domain.com/map/image.jpg` for tracked data

### Example URLs

- **Image View**: `http://localhost:8000/view/download.jpg`
- **Map View**: `http://localhost:8000/map/download.jpg`

## 🏗️ Project Structure

```
location-image-tracker/
├── main.py                 # FastAPI application
├── requirements.txt        # Python dependencies
├── locations_log.jsonl     # Location data logs
├── templates/
│   ├── view.html          # Image viewing page
│   └── map.html           # Map visualization
├── static/
│   └── images/            # Image storage
├── LICENSE                # MIT License
├── CONTRIBUTING.md        # Contribution guidelines
└── README.md             # This file
```

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

### Ways to Contribute

- 🐛 **Bug Fixes**: Improve stability and error handling
- ✨ **Features**: Add new functionality
- 🎨 **UI/UX**: Enhance design and user experience
- 📚 **Documentation**: Improve guides and comments
- 🔧 **Maintenance**: Update dependencies and code quality

## 📋 Development

### Running Tests

```bash
# Install dev dependencies
pip install -r requirements-dev.txt

# Run tests
pytest
```

### Code Style

This project follows:
- **PEP 8** for Python code
- **Consistent HTML/CSS/JS** formatting
- **Descriptive naming** conventions

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚖️ Legal & Ethical Guidelines

- **Always obtain consent** before collecting location data
- **Inform users** about data collection practices
- **Respect privacy laws** in your jurisdiction
- **Use responsibly** for educational/research purposes only

## 🙏 Acknowledgments

- Built with [FastAPI](https://fastapi.tiangolo.com/)
- Maps powered by [Leaflet](https://leafletjs.com/)
- Fonts from [Google Fonts](https://fonts.google.com/)

## 📞 Support

- 📧 **Issues**: [GitHub Issues](https://github.com/your-username/location-image-tracker/issues)
- 💬 **Discussions**: [GitHub Discussions](https://github.com/your-username/location-image-tracker/discussions)

---

**Remember**: With great power comes great responsibility. Respect privacy. Always ask. Never deceive. 🔒
