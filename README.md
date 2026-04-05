# 🎬 ai video search engine

> search any video by what you **see** and what you **hear** — powered by clip · faiss · whisper · blip-2 · pyscenedetect

![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat&logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-2.0-orange?style=flat&logo=pytorch)
![CLIP](https://img.shields.io/badge/OpenAI-CLIP-green?style=flat)
![Gradio](https://img.shields.io/badge/Gradio-Live%20Demo-purple?style=flat)

---

## 🚀 live demo
🔗 [open in google colab](https://colab.research.google.com/github/tanvi-13-610/ai-video-search-engine/blob/main/ai_video_search_engine.ipynb)

---

## 📌 what it does
upload any video and search it using natural language — finds exact frames and spoken moments matching your query across multiple videos simultaneously.

---

## 🛠 tech stack

| component | tool |
|---|---|
| visual embeddings | openai clip (vit-b/32) |
| vector search | faiss |
| audio transcription | openai whisper |
| frame captioning | salesforce blip-2 |
| scene detection | pyscenedetect |
| ui | gradio |
