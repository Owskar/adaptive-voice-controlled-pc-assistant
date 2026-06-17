# 🎙️ Adaptive Voice Controlled PC Assistant

An intelligent voice-controlled desktop assistant built with Python and Streamlit that enables users to control their computer through natural voice commands. The assistant can automate desktop tasks, retrieve information from external APIs, manage applications, provide system information, and deliver responses through both voice and visual interfaces.

## 🚀 Features

### 🎤 Voice Recognition
- Real-time speech-to-text conversion
- Natural language command processing
- Voice-based interaction with the system
- Continuous listening mode

### 🖥️ System Control
- Open desktop applications
- Launch system utilities
- Execute system-level commands
- Control PC operations using voice

### 🌐 Web & Information Services
- Search the web
- Wikipedia integration
- WolframAlpha integration
- Weather information retrieval
- Latest news updates

### 📧 Productivity Features
- Send emails using voice commands
- Set reminders
- Take screenshots
- Type text automatically
- System status monitoring

### 🎵 Media Controls
- Play music
- Stop music
- Media management through voice

### 📊 User Interface
- Interactive Streamlit dashboard
- Real-time command logs
- Voice activity indicators
- Visual response display
- Modern and responsive UI

---

## 🏗️ System Architecture

```text
User Voice Input
        │
        ▼
Speech Recognition
        │
        ▼
Intent Classification
        │
        ▼
Command Processing Engine
        │
 ┌──────┼──────┐
 ▼      ▼      ▼
APIs  Services System
 │      │       │
 └──────┼───────┘
        ▼
Result Processing
        │
 ┌──────┴──────┐
 ▼             ▼
Text To Speech UI Output
```

---

## 🛠️ Technologies Used

### Backend
- Python 3.9+
- SpeechRecognition
- PyAudio
- PyAutoGUI
- Requests

### Frontend
- Streamlit

### APIs
- Weather API
- Wikipedia API
- WolframAlpha API
- News API

### AI / NLP
- Speech-to-Text
- Intent Classification
- Natural Language Processing
- Text-to-Speech

---

## 📂 Project Structure

```text
Adaptive_Voice_Controlled_PC/
│
├── config/
├── core/
├── logs/
├── screenshots/
├── services/
├── ui/
├── utils/
│
├── main.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/Owskar/adaptive-voice-controlled-pc-assistant.git
cd adaptive-voice-controlled-pc-assistant
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

Windows

```bash
venv\Scripts\activate
```

Linux/macOS

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

```bash
streamlit run main.py
```

The application will start in your browser.

---

## 🎯 Example Voice Commands

### Open Applications

```text
Open Notepad
Open Calculator
Open Chrome
```

### Search Queries

```text
Search Python Programming
Search Artificial Intelligence
```

### Weather

```text
Weather in Pune
Weather in Mumbai
```

### Screenshots

```text
Take Screenshot
Capture Screen
```

### Emails

```text
Send Email to John
```

### News

```text
Latest News
Show Today's Headlines
```

### System Information

```text
System Status
CPU Usage
RAM Usage
```

---

## 📋 System Requirements

### Software Requirements

- Python 3.9 or higher
- Windows 8/10/11
- Streamlit
- Speech Recognition Libraries

### Hardware Requirements

- Intel Core i3 or higher
- 4GB RAM or more
- Microphone
- Speakers
- Internet Connection

---

## 📸 Screenshots

### Home Screen

Add image:

```markdown
![Home](screenshots/home.png)
```

### Voice Command Execution

```markdown
![Commands](screenshots/commands.png)
```

### Screenshot Feature

```markdown
![Screenshot](screenshots/screenshot.png)
```

---

## 🧪 Testing

Tested functionalities:

- Voice Recognition
- Application Launching
- Weather Information
- Screenshot Capture
- Email Services
- News Retrieval
- System Monitoring
- Text-to-Speech Responses

---

## 🔮 Future Enhancements

- Multi-language support
- Offline voice recognition
- AI-powered conversation
- Smart home integration
- IoT device control
- Personalized user profiles
- Advanced NLP models
- Cross-platform support

---

## 🌟 Advantages

- Hands-free computing
- Improved accessibility
- Increased productivity
- Natural user interaction
- Automation of repetitive tasks
- Adaptive learning capabilities

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Owskar Ganbawale**

- GitHub: https://github.com/Owskar
- Full Stack Developer
- Python Developer
- AI & Automation Enthusiast

---

## ⭐ Support

If you found this project useful, consider giving it a star ⭐ on GitHub.

It helps improve visibility and motivates future development.
