# 🏋️ AI Real-time GYM Coach

An AI-powered fitness coaching application that uses Computer Vision and Pose Estimation to monitor workouts in real time and provide voice-based feedback.

## ✨ Features

- Real-time webcam monitoring using Streamlit WebRTC.
- Pose detection using MediaPipe and OpenCV.
- Supports Squats, Push-ups, Biceps Curls, Shoulder Press, and Lunges.
- Tracks exercise angles, posture, sets, and repetitions.
- AI-generated coaching feedback using Groq API.
- Voice feedback using Google Text-to-Speech (gTTS).
- Workout history and analytics using SQLite and Pandas.
- Personalized workout goals.

## 🛠️ Technologies Used

- Python
- Streamlit
- MediaPipe
- OpenCV
- Streamlit WebRTC
- Groq API
- gTTS
- SQLite
- Pandas

## 📂 Project Structure

```text
AI-Real-time-GYM-Coach/
├── main.py
├── data.db
├── requirements.txt
├── packages.txt
├── project_structure.txt
└── .env
```

## ⚙️ Installation

**1. Clone the repository**

```bash
git clone https://github.com/harsh-v16/AI-Real-time-GYM-Coach.git
cd AI-Real-time-GYM-Coach
```

**2. Create and activate a virtual environment**

```bash
python -m venv .venv
.venv\Scripts\activate
```

**3. Install dependencies**

```bash
pip install -r requirements.txt
```

**4. Configure your `.env` file**

```env
GROQ_API_KEY=your_groq_api_key
```

**5. Run the application**

```bash
streamlit run main.py
```

## 👨‍💻 Author

**Harsh Chaudhary**

- [GitHub](https://github.com/harsh-v16)
- [LinkedIn](https://www.linkedin.com/in/harsh-chaudhary-6ba5b8395)

---

⭐ If you like this project, consider giving it a star!
