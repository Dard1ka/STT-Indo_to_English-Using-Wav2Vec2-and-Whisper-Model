# STT-Indo_to_English-Using-Wav2Vec2-and-Whisper-Model
🗣️ STT-Indo_to_English — Real-Time Speech Recognition & Translation using Wav2Vec2 and Whisper
This project is a real-time Speech-to-Text (STT) and translation application that converts Indonesian speech into English text, powered by Wav2Vec 2.0 for transcription and Google Translate API for translation. Built using Streamlit, this app allows users to record their voice directly in the browser and instantly see the recognized text and its English translation.

🚀 Features : 

  🎤 Real-time voice recording via microphone

  🧠 Speech recognition using Wav2Vec2 (fine-tuned model)

  🌍 Text translation from Indonesian to English using Google Translate

  ⚙️ Built with Streamlit

  💻 Runs on CPU or GPU (automatically detected)

🧰 Tech Stack
  Python, Streamlit, Torch, Transformers, Librosa

  Model: Pretrained or fine-tuned Wav2Vec2.0

  Translation: deep-translator

📂 Project Structure

  ├── wav2vec2model

  --->├── app.py                    # Main Streamlit Wav2Vec2 app
  
  ├── whispermodel

  --->├── app.py                    # Main Streamlit whisper app
  
  ├── requirements.txt          # List of dependencies

  └── README.md

📦 Installation & Running
    
  1. Clone the repo
       ```bash
       git clone https://github.com/Dard1ka/STT-Indo_to_English-Using-Wav2Vec2-and-Whisper-Model.git
       cd STT-Indo_to_English-Using-Wav2Vec2-and-Whisper-Model
       ```
       
  2. Install dependencies
       ```bash
       pip install -r requirements.txt
       ```
       
  3. Run the Streamlit app
       ```bash
       streamlit run app.py
       ```

🧪 Example Usage

  Open the web UI

  Adjust the recording duration

  Click "Mulai Rekaman"

  View:

  📝 Transcription (in Bahasa Indonesia)

  🌍 Translation (in English)

🔐 Notes

  Requires a stable internet connection for translation using Google Translate.

  The speech model should be compatible with Indonesian language input (you can fine-tune Wav2Vec2 for better accuracy).

📄 License

  MIT License © 2025

