# 🛠️ TODO – V-JEPA2 Action Recognition App

This document outlines the features and improvements planned for the V-JEPA2 Gradio app project. Contributions and ideas are welcome!

---

## ✅ Completed

- [x] Integrate V-JEPA2 model from HuggingFace
- [x] Build basic Gradio interface for video upload
- [x] Dummy linear probe for action prediction
- [x] Display predicted action and confidence
                                      
---

## 🔜 Planned Features

### 🧠 Model Improvements
- [ ] Replace dummy probe with trained classifier (e.g., on UCF101 or Kinetics-400)
- [ ] Allow selecting different V-JEPA2 model variants (Base, ViTH, ViTL)
- [ ] Add support for batch video processing

### 🎥 Video Processing
- [ ] Predict multiple actions across video segments (sliding window inference)
- [ ] Visualize frame-level predictions over a timeline
- [ ] Display keyframes or thumbnails for each prediction window

### 📊 UI Enhancements
- [ ] Add confidence bar chart of top-N classes
- [ ] Show intermediate extracted frames used for inference
- [ ] Real-time progress bar during processing

### 🌍 Deploy & Share
- [ ] Host the app on Hugging Face Spaces (Gradio/Streamlit)
- [ ] Add GitHub Actions for CI/CD
- [ ] Create a short demo video (.gif or .mp4) for README

### 📦 Additional Features
- [ ] Integrate with CLIP for zero-shot action description
- [ ] Compare embeddings with other models (e.g., VideoMAE, X3D)
- [ ] Generate captions using LLMs based on visual embeddings

---

## 💡 Future Ideas

- [ ] Convert app into a web service/API for third-party integrations
- [ ] Build a dataset from user-uploaded videos for fine-tuning
- [ ] Add audio-aware models using AVHubert or similar
- [ ] Add voice interaction (e.g., “What’s happening in this video?”)
- [ ] Integrate a chatbot to explain predictions
- [ ] Use V-JEPA2 features to detect anomalies in surveillance videos
- [ ] Support real-time webcam streaming for live action detection
- [ ] Extend to image-only JEPA for photo-based understanding
- [ ] Use V-JEPA2 + Whisper combo for multimodal summarization

---

## 🧪 Experiments (Optional Ideas)

- [ ] Add audio analysis (if video has audio)
- [ ] Use V-JEPA2 features in downstream tasks like gesture recognition
- [ ] Multimodal captioning using LLM + JEPA embeddings

