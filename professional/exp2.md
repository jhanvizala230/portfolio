---
layout: default
title: "MLops Engineer"
permalink: /professional/exp2/

---

**Role:** Machine Learning Engineer  
**Duration:** Nov 2024 – May 2025
**Company:** Vosyn, Toronto, Canada (Remote)

### Multilingual, Multispeaker TTS Model Development

Project Goal:To develop a modular multilingual and multispeaker Text-to-Speech (TTS) system capable of translating any given text in supported languages into high-quality audio with the desired speaker accent and characteristics. The system aimed to:

- Support dynamic language translation with realistic speaker accents.
- Improve speech naturalness, fidelity, and intelligibility.
- Seamlessly integrate into a larger production pipeline with scalable cloud deployment.
- Optimize cloud costs and training efficiency without sacrificing performance.

My Role : 
As the lead intern on this module, I was responsible for both the core modeling work and team leadership, focusing on improving architecture, scalability, and efficiency:

Architecture Enhancement:
Modified the original VITS architecture by introducing a custom synthesizer layer, enabling support for multilingual and multispeaker synthesis. This allowed the model to learn from custom combined datasets featuring a mix of languages, phonemes, and diverse speaker profiles.

Data Preparation:
Created a 10GB custom dataset by aggregating and preprocessing various open-source datasets. The dataset contained audio samples, transcripts, and phoneme annotations, ensuring compatibility with the modified TTS architecture.

Training Infrastructure:
Trained the model on Google Vertex AI using T4 GPUs with an n1-standard-16 machine configuration. Leveraged Docker-based isolation for training and testing environments, enabling reproducibility and seamless deployment through Vertex AI pipelines.

Evaluation & Optimization:
Implemented evaluation metrics including Mean Opinion Score (MOS) and Word Error Rate (WER) using phoneme sequence alignment. Achieved a 6.7% improvement in MOS over previous baselines. Introduced checkpoint-based fine-tuning to reduce cloud training cost by approximately 15%.

Team Leadership:
Managed and mentored a team of 5 junior engineers, overseeing model development tasks, reviewing code, and ensuring knowledge sharing and consistent progress within the team.

Tech Stack : 
Modeling & Machine Learning:
PyTorch, Modified VITS (with Synthesizer Layer), NumPy, SciPy, Librosa

Data Engineering:
FFmpeg, custom preprocessing scripts for phoneme extraction and audio alignment, Pandas

Cloud & Deployment:
Google Cloud Platform (Vertex AI, Firestore, Cloud Storage), Vertex AI Pipelines, Docker, n1-standard-16 machine with T4 GPU

Evaluation Metrics:
Mean Opinion Score (MOS), Phoneme Sequence Error (PSEQ), Word Error Rate (WER)

DevOps & Workflow Automation:
Git, Docker (separate training and testing containers), CI/CD for pipeline integration

Collaboration & Management:
Team leadership, code reviews, sprint planning, mentorship sessions with Notion

## Multilingual YouTube Transcript Summarization & Search System

🔹 Project Goal
To build a multilingual, scalable system for processing and analyzing YouTube video content, focused on:

Extracting transcripts from any language.

Summarizing long video content using chunked transcript analysis.

Storing semantic embeddings of summarized content for search and retrieval.

Enabling searchable video playback based on summaries.

(Planned/future scope): Translation of transcripts and synchronized audio generation to match and overlay translated content with specific video segments.

This tool is intended to improve global accessibility, cross-language discovery, and context-aware video navigation.

 My Role
As the primary designer and developer of this platform module, I led:

Framework Design & Transcript Pipeline:
Architected a pipeline using the YouTube API to fetch video metadata and multilingual transcripts. The system could handle videos up to 1 hour long, with transcript sizes spanning hundreds of lines.

Multilingual Summarization with Gemini 3:
Integrated Google’s Gemini 3 model for multilingual summarization. Due to the long length of transcripts, I chunked transcripts and mapped each chunk to a video frame window, generating frame-level summaries and associating each with its duration and timecode.

Semantic Search via Vector DB:
Generated semantic embeddings from summaries and stored them in a FAISS vector database, enabling efficient query-based video segment retrieval.

Metadata Mapping:
Each summary chunk was mapped to its corresponding video frame range and duration, enabling future extension toward synchronized translated playback.

Cloud Deployment on Vertex AI:
The system was deployed on Google Vertex AI using a T4-based VM (n1-standard-16), with containerized workloads for each processing stage using Docker. Vertex AI pipelines were used to manage and automate the training and summarization stages.

Team Collaboration:
Worked independently with guidance from senior engineers and contributed architectural feedback to the broader platform team.

🔹 Tech Stack Used
Transcript & Video Handling:
YouTube Data API, Pytube, Whisper (as fallback), FFmpeg

Summarization & NLP:
Google Gemini 3 model (via API), LangDetect, text chunking strategies

Embedding & Semantic Search:
Sentence-Transformers, FAISS (Vector DB), cosine similarity search

Cloud & Orchestration:
Google Cloud Platform – Vertex AI (T4 GPU), Firestore, Cloud Storage, Vertex AI Pipelines, Docker

Backend:
Python, FastAPI, modular microservices design


