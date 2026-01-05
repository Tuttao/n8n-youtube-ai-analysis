# 🎥 YouTube Video Summaries & Transcripts by AI (n8n)

An advanced **n8n automation** that analyzes YouTube videos using **Google Gemini**, generating transcripts, summaries, timestamps, scene descriptions, and social-media-ready clips from a single workflow.

## 🚀 Features
- Full video transcription
- Timestamped transcripts
- Concise summaries with actionable insights
- Scene and visual descriptions
- Viral clip extraction for social media
- Prompt-based routing using a single workflow

## 🧠 How it works
1. Manual trigger (can be replaced with webhook or scheduler)
2. Define video URL and desired output type
3. Route prompt logic using a Switch node
4. Send multimodal request to Gemini API
5. Normalize and return AI-generated output

## 🛠️ Tech Stack
- n8n (v1.82+)
- Google Gemini API
- JavaScript (Code Node)
- HTTP Requests

## ⚙️ Setup
1. Import the workflow JSON into n8n
2. Create a Google Gemini API Key
3. Set your API key in the workflow
4. Update the YouTube URL and prompt type
5. Run the workflow

## 📌 Prompt Types Supported
- `transcript`
- `timestamps`
- `summary`
- `scene`
- `clips`
