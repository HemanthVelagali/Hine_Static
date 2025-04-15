# MindEase - Mental Health Support App

A modern, offline-capable mental health support application that provides AI-powered assistance and tools for mental wellness.

## Features

- 🧠 Offline AI-powered mental health support
- 🌙 Dark/Light mode support
- 🔒 Secure user authentication
- 💬 AI-based conversation support
- 📱 Responsive design for all devices

## Tech Stack

- Python (Flask)
- HTML5/CSS3
- JavaScript
- Ollama (for offline LLM)
- LLaMA 3.1 (8B Parameters)

## Prerequisites

- Python 3.8+
- Ollama installed
- LLaMA 3.1 model downloaded

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/mindease.git
cd mindease
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up environment variables:
```bash
cp .env.example .env
# Edit .env with your configuration
```

5. Run the application:
```bash
python app.py
```

## Project Structure

```
mindease/
├── app.py                 # Main application file
├── requirements.txt       # Python dependencies
├── .env.example          # Example environment variables
├── static/               # Static files
│   ├── main.css          # Main stylesheet
│   └── login.css         # Login/Register styles
├── templates/            # HTML templates
│   ├── main.html         # Main page
│   ├── login.html        # Login page
│   └── register.html     # Registration page
└── README.md            # Project documentation
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Ollama](https://ollama.com/) for providing the offline LLM capabilities
- [LLaMA](https://ai.meta.com/llama/) for the AI model
- [Inter](https://fonts.google.com/specimen/Inter) font family 