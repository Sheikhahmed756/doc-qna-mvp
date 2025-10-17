# 📘 InsightDoc

**Tagline:** Ask questions and get instant answers from your documents — powered by AI.

InsightDoc is a simple AI-powered web app that lets users upload a PDF document (manual, report, contract, etc.) and ask natural-language questions about its content. The system extracts text from the file, processes it, and uses a language model to generate accurate answers based on the uploaded content.

## 🎯 MVP Goals

- Allow user signup/login
- Upload a single PDF (≤ 5 MB)
- Extract text from PDF
- Store document text in a database
- Ask a question about the document and get an AI-generated answer
- Simple, clean web interface

## 🧩 Tech Stack (Free-tier Tools)

| Purpose | Tool / Platform |
|----------|-----------------|
| Frontend UI | **Bolt.new** or **Bubble** |
| Backend logic | **Replit** or **Vercel Serverless Functions** |
| Database + Auth + File Storage | **Supabase** (Free Tier) |
| AI / Embeddings | **OpenAI API** (using free trial credits) |
| Hosting | **Vercel** |
| Version Control | **GitHub** |

## 🚀 Next Steps

1. Set up Supabase project (DB, Auth, Storage)
2. Build frontend upload + chat UI
3. Integrate backend PDF parser
4. Connect OpenAI API for Q&A
5. Deploy on Vercel (free tier)
