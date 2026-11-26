# Laksh Pujary

Self-taught engineer from Mangaluru, India. I build LLM systems for small businesses, and I care most about one failure mode: **an AI that says it did something it didn't.**

Most of my work is the part around the model: tool boundaries, business rules kept out of the prompt, audit trails, and tests that catch confident wrong answers before a customer hears them.

## Featured work

**[hotel-ai-reception](https://github.com/lakshcode9/hotel-ai-reception)**: a self-hosted AI receptionist for a hotel phone line, built so the model *cannot* report success the backend didn't confirm.
- Tools return `Result<T, E>`. The model receives the result verbatim, so the success phrasing is unreachable on an error.
- Escalation chains, rate floors and routing are database rows that stay inert until a human approves them.
- Every state-changing call is written to an audit log. 26 tests, at least one per product guarantee.
- The tests caught a retrieval false positive: "do you have a helipad?" matched pool FAQs on the word "have".
- Strict TypeScript, `node:test`, an OpenAI-compatible LLM adapter, a cascaded ASR → LLM → tools → TTS design.

**[guild](https://github.com/lakshcode9/guild)**: the full online store for a streetwear retailer in Karnataka.
- Next.js 16 + TypeScript frontend, Django REST backend.
- Razorpay payments, Shiprocket shipping, OTP checkout, returns.

**[trend-brief-engine](https://github.com/lakshcode9/trend-brief-engine)**: an automated research pipeline.
- Google Trends + Reddit signals are scored, then researched with Perplexity.
- It renders branded PDF reports with Puppeteer and publishes them to Gumroad on a weekly cron.

**[n8n](https://github.com/lakshcode9/n8n)**: self-hosted n8n on Render with a custom Dockerfile (ffmpeg, Python, yt-dlp), backed by Supabase Postgres.

## What I work with

- **Languages:** TypeScript, Python, JavaScript
- **Backend:** Node.js, Django / DRF, FastAPI, PostgreSQL, Supabase
- **Frontend:** Next.js, React, Tailwind
- **AI:** LLM APIs (OpenAI-compatible, Perplexity, OpenRouter), tool calling, retrieval, agent orchestration
- **Infra:** Docker, Vercel, Render, n8n

## Currently

- Building toward AI evaluation work: testing agent and model outputs against ground truth, not vibes.
- Working through CS50P and a structured AI engineering curriculum (RAG, embeddings, evals, fine-tuning).

## Contact

[lakshpujary.tech](https://lakshpujary.tech)
