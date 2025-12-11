🦅 Vespa – Fast, Scalable Search & Recommendation Engine

A Production-Ready Platform for Search, Retrieval, Ranking, and AI Applications

📌 Overview

Vespa is an open-source, high-performance search and machine learning serving engine created by Yahoo.
It is designed for real-time text search, vector search, recommendation systems, and large-scale AI inference.

Unlike traditional search engines, Vespa can:

Store and retrieve documents + embeddings

Perform dense vector search (ANN)

Execute hybrid ranking (text + embeddings + ML models)

Run ML models directly inside the engine

Scale to billions of documents

Vespa is used in production by companies like Yahoo, Spotify, artists, e-commerce platforms, and enterprise AI systems.

🚀 Key Features
🔍 1. Full-Text Search

Inverted indexes

BM25 ranking

Faceting and filtering

🧠 2. Vector Search (Dense Retrieval)

Store embeddings (OpenAI, ColPali, SBERT, etc.)

Perform ANN search (HNSW index)

🧮 3. Hybrid Ranking

Combine text + embeddings + ML scoring:

rank = bm25(text) + dot(query_vector, doc_vector)

⚙️ 4. Machine Learning Model Execution

Vespa can run:

ONNX neural networks

Tree models

Ranking pipelines

🏗️ 5. Real-Time Updates

Low-latency document writes

Near real-time indexing

Perfect for dynamic applications


