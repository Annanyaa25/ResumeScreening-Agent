# ResumeScreening-Agent
An AI-powered Resume Screening Agent that ranks resumes against a Job Description using TF-IDF matching, keyword extraction, and a Gradio web interface. Designed for extension with GPT, Claude, Gemini, LangChain, and vector databases like Pinecone or ChromaDB.
The ResumeScreening Agent is an AI-powered resume analysis and ranking system designed to automate the initial stages of recruitment. This notebook implements a complete working prototype that accepts a Job Description (JD), ingests multiple resumes (PDF, DOCX, TXT), extracts text content, and computes semantic relevance scores to determine how well each resume matches the job requirements.

At its core, the system uses TF-IDF vectorization combined with cosine similarity to measure textual alignment between resumes and the job description. It also includes keyword extraction to identify required skills and responsibilities, generating additional metrics such as keyword coverage and matched skill highlights. These metrics combine into a final ranking score, enabling recruiters to instantly identify the top candidates.

The interface is built using Gradio, allowing users to interact with the model through a clean web-based UI without needing technical knowledge. Users can:

Paste the job description

Upload multiple resumes

Automatically generate ranked results

View detailed scoring breakdowns

See matched skills and missing gaps

Beyond the notebook implementation, this project is architected for real-world scalability. It is compatible with advanced AI frameworks and LLMs:

LLMs: OpenAI GPT, Anthropic Claude, Google Gemini

Agent frameworks: LangChain, CrewAI, LlamaIndex

Vector databases: Pinecone, ChromaDB, Weaviate, FAISS

Storage systems: Firebase, Supabase, Notion DB, Google Sheets

Integrations: Zapier, Google Calendar, Notion API, Sheets API

A production version of this system can perform semantic embedding of resumes, enable recruiter collaboration, support continuous JD/resume indexing, and integrate automated interview scheduling.

This notebook serves as a practical, portfolio-ready demonstration of building an AI-driven HR automation tool. It combines NLP, information retrieval, text processing, and interactive UI elements—making it a strong project for academic submissions, interviews, GitHub showcases, or real HR workflows.
