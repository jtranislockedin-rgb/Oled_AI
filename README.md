# Oled_AI
AI-driven assistant for response, real-time user interaction

# The Problem
Imagine staring at a test question you don't know the answer to.Imagine a girl talking to you for the first time in your life. Imagine a crowd of faces staring into your soul. You freeze. You are nervous. Your hands are sweaty, knees weak, arms are heavy. Tick tock tick tock. Your time is running out... Times up. When it comes time to perform, and you find out that the lights are too bright, the stage is too big, the silence is too loud. You realize that you are by yourself. Not alone but lonely. No one will come to save you. Who will come save you unless it is yourself? You are on your own. Until. There it is. Oled_AI.

# Welcome Oled_AI
![Oled_AI pic]()

# How it works
- Button press puts Raspberry Pi into the "listening state". Raspberry Pi records audio locally in the souddevice library. Raspberry Pi sends the .wav file to OpenAI's Whisper model to convert speech into text.
- Pressing the button again enters the Raspberry Pi into the "thinking state" where the Raspberry Pi sends the text to OpenAI's language model via API.
