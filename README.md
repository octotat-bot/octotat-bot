# Mukund Mangla

I build LLM and machine learning systems, with a focus on making their answers checkable: citations, refusals, evaluation and honest test splits.

Computer science undergraduate at Newton School of Technology (B.Tech, graduating 2028). Completed a remote AI/ML internship at Mindenious in 2026. **Open to internships.**

[LinkedIn](https://www.linkedin.com/in/mukundmangla) · [Email](mailto:manglamukund123@gmail.com) · [LeetCode](https://leetcode.com/u/Hakka123/)

## Now

**Repetite**, an iOS fitness and food tracker in SwiftUI, with HealthKit and SwiftData. Food logging routes fast, simple entries to Groq and harder ones to Gemini, trading speed against accuracy. It is in private use on-device and has not launched.

## Selected work

| Project | What it does | The engineering problem | Stack |
|---|---|---|---|
| [RepoMind](https://github.com/octotat-bot/RepoMind) | Ask questions about any GitHub repo and get answers that cite exact files and line ranges | Vector search kept returning chunks from one file, so retrieval got a reranker with per-file diversity and identifier splitting | FastAPI, Next.js, FAISS, Ollama |
| [Marginalia](https://github.com/octotat-bot/Marginalia) | PDF Q&A with page-level citations that refuses when the document has no answer | Small models wrote refusals with citations attached, so a third guardrail normalises them into real refusals | LangChain, Chroma, FastAPI, Streamlit |
| [Water quality prediction](https://github.com/octotat-bot/aml-dl-project) | Predicts a water quality index for Indian river stations and compares linear, Random Forest and XGBoost models | Random splits mislead here, so models are tested on unseen stations across 10 partitions, with feature leakage labelled | scikit-learn, XGBoost, SHAP |
| [DreamSignal](https://github.com/octotat-bot/DreamSignal) | Records, transcribes and analyses dreams from voice | Pipeline stages run across three services and stream live to the UI over SSE | React, Express, FastAPI, Whisper, Gemini |
| [Smart Resume Analyzer](https://github.com/octotat-bot/intern-skillorbit) | Scores a resume against a target role, with the evidence behind each point | Scoring stays deterministic and reproducible, and the optional LLM layer can only use retrieved, cited sources | Flask, spaCy, React, Gemini |
| [Trailboard](https://github.com/octotat-bot/TrailBoard) | Real-time collaborative whiteboard | CRDT schema designed so concurrent drags, recolours and typing all survive, with persistence across restarts | Yjs, WebSockets, LevelDB, TypeScript |

More full-stack work: [Ember](https://github.com/octotat-bot/ember) (real-time restaurant operations), [Balancio](https://github.com/octotat-bot/balancio) (shared expenses with debt simplification), [Personal-Portfolio](https://github.com/octotat-bot/Personal-Portfolio) (scroll-driven portfolio site).

## Tools

- **ML and LLM:** Python, scikit-learn, XGBoost, PyTorch, LangChain, FAISS, Chroma, Ollama, Groq, Gemini
- **Backend:** FastAPI, Flask, Node.js, Express, PostgreSQL, MongoDB, SQLite
- **Frontend and mobile:** React, Next.js, TypeScript, Tailwind CSS, SwiftUI
- **Infrastructure:** Docker, Vercel, Render
