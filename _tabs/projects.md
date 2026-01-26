---
layout: page
icon: fas fa-cubes
order: 2
title: Projects
---

# 🚀 Projects

---

## 🤖 Machine Learning Projects

### T5 Sentiment Analysis MLOps Pipeline
![MLOps](https://img.shields.io/badge/MLOps-Airflow-017CEE?style=flat)
![T5](https://img.shields.io/badge/Model-T5-FF6F00?style=flat)
![AWS](https://img.shields.io/badge/Cloud-AWS-232F3E?style=flat)
![Docker](https://img.shields.io/badge/Container-Docker-2496ED?style=flat)

End-to-end MLOps pipeline with custom T5 architecture deployed on AWS SageMaker Serverless Inference:

- 🎯 Designed custom **T5 Encoder** with **Sentiment Gate** mechanism using learnable attention and **REINFORCE algorithm** to focus on sentiment-bearing tokens, achieving **91.17% accuracy** on **SST-2 dataset** (67K+ samples)
- 🤖 Built fully automated **Apache Airflow** pipeline orchestrating data validation, training, evaluation, packaging, and deployment workflows with email notifications
- ☁️ Deployed to **AWS SageMaker Serverless Inference** with auto-scaling, integrated **Lambda** proxy and **API Gateway** for public REST API access
- 🐳 Containerized entire pipeline using **Docker** with custom Airflow image including AWS CLI and ML dependencies for reproducible deployments

🔗 [GitHub Repository](https://github.com/SambasBoyyyy/Streamlined-T5-Sentiment-Classification-via-Custom-Architecture-AWS-Serverless-and-Airflow)

---

### Bangla SSC Book RAG System
![RAG](https://img.shields.io/badge/Architecture-RAG-00C853?style=flat)
![AWS](https://img.shields.io/badge/Cloud-AWS-232F3E?style=flat)
![LangChain](https://img.shields.io/badge/Framework-LangChain-121212?style=flat)

Scalable Retrieval-Augmented Generation system for Bengali SSC educational content with cloud-native architecture:

- 🔍 Engineered **hybrid RAG pipeline** with custom **Bengali Sentence-BERT** (l3cube-pune) on **Amazon SageMaker Real-Time Endpoints** for low-latency embedding generation
- 🦙 Integrated **Amazon Bedrock** with **Llama 3 8B** for serverless text generation and built custom **LangChain pipeline** with **ChromaDB**/**OpenSearch** for context-aware retrieval

🔗 [GitHub Repository](https://github.com/SambasBoyyyy/Bangla-RAG)

---

### ShobdoTori: Regional-to-Standard Bangla Speech Recognition
![ASR](https://img.shields.io/badge/Task-ASR-E91E63?style=flat)
![Whisper](https://img.shields.io/badge/Model-Whisper-10A37F?style=flat)
![Wav2Vec2](https://img.shields.io/badge/Model-Wav2Vec2-3776AB?style=flat)

AI Hackathon project under **Televerse 1.0** organized by **CUET (Department of ETE)**, focused on transcribing regional Bangladeshi dialects into standard Bangla:

- 🗣️ Developed **ASR model** to convert **20 regional dialects** into formal Bangla text using **Whisper** and **Wav2Vec2**
- 📊 Processed and curated **3,800+ audio samples** with **phoneme alignment** and **data augmentation**
- 📈 Post-processed transcriptions using **n-gram KenLM**; evaluated with **Normalized Levenshtein Similarity (NLS)**

🔗 [GitHub Repository](https://github.com/SambasBoyyyy/ShobdoTori-Regional-to-Standard-Bangla-Speech-Recognition)

---

### DSE Stock MCP Server
![MCP](https://img.shields.io/badge/Protocol-MCP-FF6B6B?style=flat)
![TypeScript](https://img.shields.io/badge/Language-TypeScript-3178C6?style=flat)
![Docker](https://img.shields.io/badge/Deploy-Docker-2496ED?style=flat)

Model Context Protocol server providing real-time stock market data for Dhaka Stock Exchange:

- 📡 Built **MCP-compliant server** using **TypeScript** with **real-time price tracking** and **historical OHLC data** retrieval for seamless **Claude Desktop/Cursor** integration
- 🐳 **Dockerized** backend with **FastAPI**, hosted on **Railway**, and published as **npm package** with robust symbol resolver supporting all DSE-listed companies

🔗 [GitHub Repository](https://mcpmarket.com/server/dse-stock)

---

### TimeClip-AI
![Transformers](https://img.shields.io/badge/Architecture-Transformers-FF6F00?style=flat)
![I3D](https://img.shields.io/badge/Features-I3D-9C27B0?style=flat)

Real-Time Action Classification and Time Segmentation in Full-Length Videos Using Anchor Transformers for Online Temporal Action Localization:

- ⏱️ Accurately classify actions in streaming or full-length videos
- 🎯 Precise time segmentation for action localization
- 🏗️ Novel architecture for efficient and robust processing
- 📊 Compatible with EGTEA, EPIC-Kitchen100, THUMOS'14 datasets
- ⚡ Ready-to-use I3D features for seamless training and testing

---

### Z-PRUNER: Post-Training Pruning of Large Language Models
![LLM](https://img.shields.io/badge/Task-LLM_Compression-8B5CF6?style=flat)
![Pruning](https://img.shields.io/badge/Method-Pruning-F59E0B?style=flat)

Post-training pruning framework designed for large language models (LLMs):

- 🔧 Requires no retraining or fine-tuning after pruning
- ⚡ Maintains competitive perplexity and inference efficiency after 50% sparsity
- 🤖 Supports major transformer-based models like LLaMA and OPT

---

## 📱 Cross-Platform Applications

### TASALIGO APP
![Flutter](https://img.shields.io/badge/Framework-Flutter-02569B?style=flat)
![Firebase](https://img.shields.io/badge/Backend-Firebase-FFCA28?style=flat)
![E-commerce](https://img.shields.io/badge/Type-E--commerce-4CAF50?style=flat)

A comprehensive e-commerce platform for wholesale foods featuring:

- 🔍 Implemented customized search method and order management system
- 📦 Developed real-time inventory tracking and notification system
- 🏪 Designed scalable architecture supporting multiple vendor management

---

### ESTIBAFY PLATFORM
![Flutter](https://img.shields.io/badge/Framework-Flutter-02569B?style=flat)
![Realtime](https://img.shields.io/badge/Database-Realtime-FFCA28?style=flat)

A client-worker connection platform for container management operations:

- 📍 Built real-time tracking system using Firebase Realtime database for container operations and worker management
- 💬 Implemented chat functionality for seamless communication between clients and workers
- 👥 Designed a client-admin-worker hierarchy for optimal worker-task assignment
