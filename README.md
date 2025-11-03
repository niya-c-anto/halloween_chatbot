# halloween_chatbot
An interactive AI-powered horror-themed chatbot that listens to your voice, responds with eerie vocal effects, and plays in sync with a looping spooky video. It combines speech recognition, text-to-speech synthesis, audio effect processing, and a Tkinter GUI to create a haunted virtual companion experience.
Here’s a **GitHub project description (README.md)** draft for your spooky chatbot system using your uploaded files (`spooky_video_chatbot.py`, `spooky_chatbot_modified.py`, and your haunted video file):

---

# 🎃 Spooky Video Chatbot Portal

An interactive **AI-powered horror-themed chatbot** that listens to your voice, responds with eerie vocal effects, and plays in sync with a looping spooky video. It combines **speech recognition**, **text-to-speech synthesis**, **audio effect processing**, and **a Tkinter GUI** to create a haunted virtual companion experience.

---

## 🕸️ Features

* 👻 **Voice Interaction** – Speak naturally with the chatbot using your microphone.
* 🔊 **Realistic Spooky Voice Effects** – Powered by **Librosa**, **Pedalboard**, and **Pydub** for real-time voice distortion, reverb, and pitch shifts.
* 🧠 **Wikipedia-Powered Knowledge** – The chatbot retrieves facts about any topic you ask.
* 🎬 **Cinematic Background** – A looping horror video plays behind the chat, setting the mood.
* 💀 **Immersive UI** – A dark-themed Tkinter interface with animated text effects and console-like dialogue.
* 🧹 **Voice Modes** – Choose from **Demon, Ghost, Zombie, Witch**, and **Normal** modes.
* 🎧 **Background Music Support** – Add your own `spooky_background.mp3` for ambient atmosphere.
* ⚡ **Interrupt & Exit Commands** – Say or click “Interrupt” or “Exit” to end the ritual.

---

## 🧩 Project Structure

```
spooky-video-chatbot/
│
├── spooky_video_chatbot.py          # Main UI with video player and chat controls
├── spooky_chatbot_modified.py       # Voice synthesis, audio effects, and Wikipedia logic
├── Hailuo_Video_a ghost...mp4       # Background spooky looping video
├── spooky_background.mp3 (optional) # Background soundtrack
└── README.md                        # Project documentation
```

---

## ⚙️ Requirements

Make sure you have the following installed before running:

```bash
pip install opencv-python tkinter pillow pygame wikipedia SpeechRecognition librosa soundfile pydub pedalboard pywin32
```

> 🪟 **Note:** This project currently works on **Windows** due to `win32com.client` voice synthesis.

You’ll also need:

* A working **microphone and speakers**
* The **video file** placed in the same folder as `spooky_video_chatbot.py`

---

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/spooky-video-chatbot.git
   cd spooky-video-chatbot
   ```

2. Place your video file (e.g. `Hailuo_Video_a ghost or a doomsday or kalan_439813657482756103.mp4`) in the same directory.

3. Run the program:

   ```bash
   python spooky_video_chatbot.py
   ```

4. Click **Start** to begin the ritual and talk to your spooky AI companion.

---

## 🗣️ Voice Commands

| Command            | Action                                            |
| ------------------ | ------------------------------------------------- |
| “Who are you?”     | Introduces the chatbot                            |
| “Change voice”     | Switches voice effects                            |
| “Exit” / “Goodbye” | Ends the session                                  |
| Any other query    | Fetches a Wikipedia summary with spooky narration |

---

## 🧠 Tech Stack

* **Python 3.8+**
* **Tkinter** – GUI and terminal display
* **OpenCV** – Video playback
* **SpeechRecognition (Google API)** – Converts speech to text
* **PyWin32 (SAPI)** – Windows voice synthesis
* **Pedalboard** – Audio effects (reverb, distortion, filters)
* **Librosa** – Pitch shifting
* **Pydub** – Post-processing and playback
* **Wikipedia API** – Knowledge retrieval

---

## 🕷️ Preview

> 💀 When launched, you’ll see a spooky looping video with glowing green text.
> Click **Start** and speak — your eerie chatbot will answer with distorted demonic tones while showing responses on screen.

---

## 🧛 Future Enhancements

* Cross-platform voice synthesis (Mac/Linux support)
* Customizable voice effects through GUI sliders
* Integration with AI LLMs for deeper dialogue
* Multi-scene horror environments (switching videos)

---

## ⚰️ Credits

Developed by **Niya C Anto** 🦇
Inspired by horror aesthetics, real-time audio processing, and the art of interactive storytelling.



