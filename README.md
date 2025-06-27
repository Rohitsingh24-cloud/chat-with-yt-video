# chat-with-yt-video
A powerful Retrieval-Augmented Generation (RAG) system that allows users to interactively ask questions based on the content of any YouTube video. It leverages the Google Gemini 1.5 API for natural language generation and FAISS for vector-based semantic search.

📌 Features
🔍 Extracts and processes YouTube video transcripts
🧠 Uses FAISS for fast and accurate chunk retrieval
🤖 Powered by Google Gemini 1.5 (Pro/Flash) for conversational response generation
🛠️ Built with LangChain and Python for easy integration and expansion
📦 Modular and open-source, ready to deploy or extend
✅ Accepts any YouTube video URL
✅ Uses transcript extraction via YouTubeTranscriptAPI


🧠 Tech Stack
Layer	Tool/Library
Language Model         :  	Gemini 1.5 via google.generativeai
Embeddings	           :    GoogleGenerativeAIEmbeddings
Vector Store           :   	FAISS
Chunking & RAG         :   	LangChain
Transcript Parsing	   :    YouTubeTranscriptAPI
Backend                :    python(Google Colab)




🚀 Use Cases

1).  Summarize or query educational videos
2).  Ask context-aware questions on lectures, tech talks, or interviews
3).  Build educational assistants or video-based AI tutors

