Patent & Research Novelty Checker – System Design
1. 🧩 System Overview
The Patent & Research Novelty Checker is an AI-driven system designed to analyze the originality of user ideas by comparing them with existing patents and research papers.
The system integrates multi-source data retrieval, vector similarity search, and generative AI analysis to provide novelty scoring, insights, and recommendations.

2. 🏗️ System Architecture
The system follows a modular layered architecture consisting of:
Presentation Layer (Frontend UI)
Application Layer (Core Logic & Processing)
AI & Search Layer (Embeddings, Vector Search, AI Analysis)
Data Source Layer (External APIs & Storage)

High-Level Architecture Flow
┌─────────────────────────────────────────────────────────────┐
│                    PRESENTATION LAYER                        │
│                    Streamlit Frontend UI                     │
└───────────────────────────────┬─────────────────────────────┘
                                │
┌───────────────────────────────▼─────────────────────────────┐
│                   APPLICATION LAYER                          │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐      │
│  │    Data      │  │    Idea      │  │   History    │      │
│  │ Collection   │  │ Preprocessing│  │ Management   │      │
│  └──────────────┘  └──────────────┘  └──────────────┘      │
└───────────────────────────────┬─────────────────────────────┘
                                │
┌───────────────────────────────▼─────────────────────────────┐
│                    AI & SEARCH LAYER                         │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐      │
│  │  Embedding   │  │   Vector     │  │     AI       │      │
│  │  Generator   │──│    Search    │──│   Analyzer   │      │
│  └──────────────┘  └──────────────┘  └──────────────┘      │
└───────────────────────────────┬─────────────────────────────┘
                                │
┌───────────────────────────────▼─────────────────────────────┐
│                    DATA SOURCE LAYER                         │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐      │
│  │   Patent     │  │  Research    │  │   Vector     │      │
│  │    APIs      │  │    APIs      │  │   Database   │      │
│  └──────────────┘  └──────────────┘  └──────────────┘      │
└─────────────────────────────────────────────────────────────┘

