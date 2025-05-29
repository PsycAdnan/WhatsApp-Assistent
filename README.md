# 🤖 WhatsApp Assistant

A simple yet powerful Python-based voice assistant that lets you send WhatsApp messages or initiate chats for calling using natural voice commands. Perfect for hands-free messaging and automation!

---

## 📌 Features

- 🎤 Voice-controlled message input using Google's speech recognition
- 💬 Send WhatsApp messages instantly
- 📞 Open WhatsApp chats to initiate calls
- 🗂️ Save frequently used numbers as named contacts
- 🧠 Text-to-speech feedback for user instructions
- 🖥️ User-friendly terminal interaction for confirmations and input

---

## 🛠️ Tech Stack

- **Python 3.x**
- [pyttsx3](https://pypi.org/project/pyttsx3/) – Text-to-Speech
- [SpeechRecognition](https://pypi.org/project/SpeechRecognition/) – Voice Input
- [PyWhatKit](https://pypi.org/project/pywhatkit/) – WhatsApp Control via Web
- Web Browser (to open WhatsApp Web)

---

## 🚀 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/WhatsappAsssistent.git
cd WhatsappAsssistent
2. Install Dependencies
bash
Copy
Edit
pip install pyttsx3 SpeechRecognition pywhatkit pyaudio
Note: If you're on Windows and pyaudio fails to install, use:

bash
Copy
Edit
pip install pipwin
pipwin install pyaudio
3. Run the Assistant
bash
Copy
Edit
python assistant.py
Make sure you are logged into WhatsApp Web in your default browser for proper functioning.

💡 How It Works
The assistant will ask you to type the contact number.

It will ask for confirmation via text input.

You'll be asked whether you want to send a message or make a call.

For messages, the assistant listens for your voice input and sends it instantly.

For calls, it opens the WhatsApp chat so you can make the call manually.

🧠 Future Improvements
Build a GUI using Tkinter or PyQt

Schedule WhatsApp messages

Fetch chat history

Sync and manage contacts via CSV or Google Contacts

Add local speech synthesis and offline recognition

📋 Example Use Case
bash
Copy
Edit
$ python assistant.py

🤖 "Please type the phone number including country code"
> +1234567890

🤖 "Is this correct? Type yes or no:"
> yes

🤖 "Do you want to send a message or make a call?"
🎤 (user says "message")

🤖 "What message should I send?"
🎤 (user says "Hello, how are you?")

📩 Message sent successfully!
📂 File Structure
bash
Copy
Edit
WhatsappAsssistent/
│
├── assistant.py          # Main script with logic
├── contacts.json         # (Optional) Store frequently used contacts
├── README.md             # Project documentation
└── requirements.txt      # Package requirements (optional)
📄 License
This project is licensed under the MIT License. Feel free to use, modify, and distribute it.
