# 🎬 AI Video Search Engine

> Search any video by what you **see** AND what you **hear** — powered by CLIP · FAISS · Whisper · BLIP-2 · PySceneDetect

![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat&logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-2.0-orange?style=flat&logo=pytorch)
![CLIP](https://img.shields.io/badge/OpenAI-CLIP-green?style=flat)
![Gradio](https://img.shields.io/badge/Gradio-Live%20Demo-purple?style=flat)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat)

---

## 🚀 Live Demo
🔗 [Open in Google Colab](https://colab.research.google.com/github/tanvi-13-610/ai-video-search-engine/blob/main/ai_video_search_engine.ipynb)

---

## 📌 What it does
Upload any video and search it using natural language — the system finds the exact frames and spoken moments that match your query.

**Example:** Search `"neural networks"` across a 2.5 hour lecture → instantly returns the exact timestamp where neural networks appear on screen AND where the word is spoken.

---

## 🏗 Architecture
---

## ✨ Features

- 🔍 **Natural language visual search** — Find any scene by describing it
- 🎤 **Audio search** — Search spoken words with Whisper transcription
- 📝 **AI captions** — BLIP-2 generates descriptions for every matched frame
- 🟢 **Confidence scoring** — High / Medium / Low match confidence per result
- 📚 **Multi-video library** — Index and search across multiple videos at once
- 🎬 **Scene-aware sampling** — PySceneDetect extracts only meaningful frames
- 📥 **Export to CSV** — Download all results with timestamps and captions
- 🕓 **Search history** — Tracks last 8 queries
- ⚡ **571 frames/sec** — Sub-second retrieval across 4 AI models simultaneously

---

## 🛠 Tech Stack

| Component | Tool |
|---|---|
| Frame Extraction | OpenCV + FFmpeg |
| Scene Detection | PySceneDetect |
| Visual Embeddings | OpenAI CLIP (ViT-B/32) |
| Vector Search | FAISS (IndexFlatIP) |
| Audio Transcription | OpenAI Whisper (small) |
| Frame Captioning | Salesforce BLIP-2 (OPT-2.7B) |
| UI | Gradio |
| Runtime | Google Colab (T4 GPU) |

---

## 🚀 How to Run

1. Open the notebook in Google Colab (link above)
2. Set runtime to **T4 GPU**: `Runtime → Change runtime type → T4 GPU`
3. Run all cells top to bottom
4. Use the Gradio UI to upload a video and start searching

---

## 📊 Performance

| Metric | Value |
|---|---|
| Frames searched | 597 (Big Buck Bunny) |
| Search speed | 571 frames/sec |
| Scene detection reduction | 77% fewer frames vs 1fps |
| Models running simultaneously | 4 (CLIP + FAISS + Whisper + BLIP-2) |
| End-to-end search time | ~1.05s |

---

## 📝 Resume Bullets

- Built a **multimodal AI video search engine** combining CLIP, FAISS, Whisper, and BLIP-2 — enabling natural language search across both visual and audio content of any video
- Engineered a **scene-aware frame sampling pipeline** using PySceneDetect, reducing indexed frames by 77% while preserving semantic coverage
- Achieved **571 frames/second** retrieval across a 4-model AI pipeline with sub-second end-to-end search latency
- Deployed as a **live Gradio web app** supporting multi-video library search, CSV export, confidence scoring, and AI-generated frame captions

---

## 📁 Project Structure
---

## 🙋 Author
**Tanvi** — [github.com/tanvi-13-610](https://github.com/tanvi-13-610)
