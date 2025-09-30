# 📻 VidSynth AI — YouTube RAG Chatbot & Note Generator

**VidSynth AI** lets you transform any YouTube video into **chatbot conversations** or **structured notes**.  
Just paste a YouTube URL, and the app will fetch the transcript, process it, and either:

- 🤖 **Chat with Video** — Ask questions and get precise answers grounded in the video content.  
- 📝 **Notes For You** — Extract key topics and generate concise, well-structured notes.  

👉 Try it live here: [VidSynth AI on Streamlit](https://youtube-rag-live-class.streamlit.app/)

---

## 🚀 Features
- Paste any YouTube video URL and fetch its transcript.
- Automatic translation if the video is not in English.
- Choose between **Chat with Video** or **Generate Notes** modes.
- Chunking + embeddings + vector search for accurate retrieval.
- Interactive **Streamlit UI** with chat history support.

---


## 🛠️ Tech Stack
- **Frontend / UI**: Streamlit
- **Transcript**: YouTube Transcript API
- **LLM**: Google Gemini (`gemini-2.5-flash-lite`)
- **Embeddings**: OpenAI (`text-embedding-3-small`)
- **Vector Store**: Chroma
- **Frameworks**: LangChain, Python

---

## ⚡ How It Works
1. Extracts transcript from YouTube video.
2. (Optional) Translates to English.
3. Splits transcript into chunks and creates embeddings.
4. Stores embeddings in Chroma DB.
5. Depending on user choice:
   - **Notes For You** → Extracts key topics & structured notes.
   - **Chat with Video** → Allows interactive Q&A over video content.

---

## 🌐 Live Demo
👉 [https://youtube-rag-live-class.streamlit.app/](https://youtube-rag-live-class.streamlit.app/)

---
