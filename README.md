# AI-Powered Interview Evaluation

## Description
This project is an AI-powered system that conducts virtual interviews. It evaluates candidates in real-time using webcam and microphone inputs, transcribes audio using Whisper models, and generates AI-driven questions and feedback based on the candidate's resume and job description.

## Features
- Real-time webcam and audio processing
- Automatic speech recognition with Whisper (small → medium)
- Gemini AI generates interview questions from JD + resume
- Text-to-speech feedback while keeping webcam live
- Draws only main face contours (eyes, lips, outline)
- Supports PDF and DOCX resume uploads
- Hybrid system using MediaPipe or OpenCV fallback

## Requirements
- Python 3.8+
- OpenCV (`cv2`)
- MediaPipe (`mediapipe`) 
- SoundDevice (`sounddevice`)
- Whisper (`whisper`)
- PyPDF2, python-docx
- pyttsx3 (for local TTS)
- Google Gemini API key (for AI question generation)

## Installation
```bash
pip install opencv-python mediapipe sounddevice scipy pyttsx3 PyPDF2 python-docx whisper google-generativeai
