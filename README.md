# Regulatory Penalty Tracker

The Regulatory Penalty Tracker is an AI-powered system designed to analyze regulatory penalties and provide meaningful insights.

It helps users to:
- Understand penalty descriptions
- Get actionable recommendations
- Generate structured reports
- Find similar past penalties using AI-based search

---

## AI Service

The AI service is implemented inside the `ai-service` folder.

It includes:
- LLM-based analysis using Groq API
- Vector search using ChromaDB
- Sentence-transformer embeddings
- Redis caching (optional)
- Security headers for API protection
- Docker support for containerization

---

## Project Structure

regulatory-penalty-tracker/
│
├── ai-service/
│ ├── app.py
│ ├── README.md
│ ├── Dockerfile
│ ├── .env.example
│ ├── prompts/
│ └── Screenshots/
│
└── README.md


---

## How to Run

Navigate to the AI service folder:

```bash
cd ai-service

Follow the setup instructions in:

ai-service/README.md