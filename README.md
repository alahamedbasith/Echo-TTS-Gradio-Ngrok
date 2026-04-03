# Echo-TTS Colab Setup

A clean and reliable Google Colab notebook for running **Echo-TTS** with Gradio interface and stable public access via Ngrok.

### About Echo-TTS

**Echo-TTS** is a high-quality diffusion-based Text-to-Speech model capable of realistic voice cloning from a short audio reference.

- **Model**: [jordand/echo-tts-base](https://huggingface.co/jordand/echo-tts-base)
- **Official GitHub**: [jordandare/echo-tts](https://github.com/jordandare/echo-tts)
- **Audio Quality**: 44.1kHz
- **Strengths**: Natural prosody, good voice cloning, up to ~30 seconds generation

### Features

- Easy one-click setup in Google Colab
- User-friendly Gradio web interface
- Stable public URL using **Ngrok** (avoids common Gradio share failures)
- Automatic model downloading on first run
- Optimized for free Colab (T4 GPU)

### Created By

**Ahamed Basith**  
*(Colab Notebook Setup & Ngrok Integration)*

### Usage

1. Open Google Colab and create a new notebook.
2. Copy and run the setup code (provided separately in your Colab notebook).
3. When prompted, paste your free Ngrok authtoken.
4. Wait for the models to download (first run takes 1–2 minutes).
5. Open the public Ngrok link shown in the output.
6. Use the Gradio interface to input text and upload a reference audio for voice cloning.

### Notes

- First run is slower due to model download (~2–4 GB).
- Subsequent runs are much faster.
- The app supports voice cloning from reference audio up to 2 minutes long.
- Best results with clear, high-quality reference audio.

### License

- Model weights are released under **CC-BY-NC-SA-4.0** (Non-commercial use only).
- Please respect the license and avoid misuse (deception, impersonation, misinformation, etc.).

### Credits

- Model & Research: Jordan Darefsky
- Hugging Face Repository: [jordand/echo-tts-base](https://huggingface.co/jordand/echo-tts-base)
- Original Code: [jordandare/echo-tts](https://github.com/jordandare/echo-tts)
- Colab Notebook: Ahamed Basith

---

Made for personal and research use only.
