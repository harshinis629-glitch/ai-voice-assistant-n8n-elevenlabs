🎙️ Voice Assistant using n8n and ElevenLabs

📖 Overview

This project demonstrates a simple AI voice assistant workflow built using n8n automation and ElevenLabs.
The system accepts audio input, converts it into text, processes the request, and generates a response in both text and audio format.

---

🔁 Workflow Architecture

Below is the automation workflow created in n8n.

<img width="1937" height="601" alt="Screenshot 2026-03-08 223432" src="https://github.com/user-attachments/assets/01cd0a3a-d743-4e70-8f76-b641dc537366" />


The workflow begins with a Webhook trigger, which receives the user request and processes the audio using ElevenLabs services.

---

🎤 Example Voice Input and Assistant Voice Response



📝 Text Transcript

The spoken audio is converted into text using speech-to-text processing.

<img width="1452" height="528" alt="Screenshot 2026-03-08 222913" src="https://github.com/user-attachments/assets/b5a2f34d-f11a-4c72-a433-0cc8f9753e17" />

<img width="1267" height="504" alt="Screenshot 2026-03-08 222927" src="https://github.com/user-attachments/assets/887c4f13-7ecf-4f81-903d-fcdf4df4e2e4" />

<img width="1457" height="684" alt="Screenshot 2026-03-08 222949" src="https://github.com/user-attachments/assets/793f5998-0abb-4755-9cfd-e721faa0974c" />

🛠 Technologies Used

- n8n – Workflow automation
- ElevenLabs – Speech-to-text and text-to-speech
- Webhook API – Input trigger
- JSON Workflow Export – Project configuration

---



🎯 Purpose

This project demonstrates how AI speech technologies can be integrated with workflow automation to build a simple voice assistant system
