Face Recognition Platform with Real-Time AI Q&A (RAG-powered)
A web-based system for live face registration and recognition using webcam input, integrated with an AI chatbot that answers queries about face data through Retrieval-Augmented Generation (RAG).

Features
Face Registration
Real-time face detection via webcam

Assign and register multiple unique faces with names

Store face embeddings and metadata (name, timestamp) in MongoDB

Live Face Recognition
Continuous webcam feed scanning

Recognize multiple faces simultaneously from stored data

Display bounding boxes and names on the video feed

AI Chat Interface (RAG)
Embedded React chat widget for querying face data

Supports questions such as:

"Who was the last person registered?"

"When was [Name] registered?"

"How many people are registered?"

Powered by LangChain, FAISS, and OpenAI LLM via WebSocket communication between React, Node.js, and Python backend

Technology Stack
Layer	Technologies
Frontend	React.js
Backend	Node.js (API + WebSocket server)
Face Recognition	Python (insightface, opencv, onnxruntime)
Data & ML	numpy, pandas, scikit-learn
RAG	LangChain, FAISS, chromadb, tiktoken, OpenAI
