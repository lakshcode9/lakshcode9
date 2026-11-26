<div align="center">

<a href="https://lakshpujary.tech"><img src="./banner.svg" width="100%" alt="Laksh Pujary. LLM systems for real businesses. Mangaluru, India." /></a>

<a href="https://github.com/lakshcode9">
  <img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=500&size=20&duration=3000&pause=1000&color=FF5A3D&center=true&vCenter=true&width=640&lines=AI+receptionist+for+a+hotel+phone+line;Online+store+for+a+streetwear+brand;Research+pipeline+that+publishes+itself;Learning+AI+evaluation" alt="Typing intro" />
</a>

<br/>

<a href="https://lakshpujary.tech"><img src="https://img.shields.io/badge/lakshpujary.tech-FF5A3D?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" /></a>
<img src="https://img.shields.io/badge/Open%20to-AI%20eval%20%26%20contract%20work-17191E?style=for-the-badge" alt="Open to work" />

</div>

<br/>

## About

I build LLM systems for small businesses, and I care most about one failure mode: **an AI that says it did something it didn't.**

Most of my work is the part around the model: tool boundaries, business rules kept out of the prompt, audit trails, and tests that catch confident wrong answers before a customer hears them.

<br/>

## Featured work

<table>
<tr>
<td width="50%" valign="top">

### [hotel-ai-reception](https://github.com/lakshcode9/hotel-ai-reception)
Self-hosted AI receptionist for a hotel phone line. The model **cannot** report success the backend didn't confirm.

- Tools return `Result<T, E>`, passed to the model verbatim
- Business rules are DB rows that stay inert until a human approves them
- Every state change is audited · 26 tests, one or more per guarantee
- Tests caught a retrieval false positive: *"do you have a helipad?"* matched pool FAQs on the word "have"

![TypeScript](https://img.shields.io/badge/TypeScript-17191E?style=flat-square&logo=typescript&logoColor=FF5A3D) ![Node](https://img.shields.io/badge/node%3Atest-17191E?style=flat-square&logo=nodedotjs&logoColor=FF5A3D) ![LLM](https://img.shields.io/badge/LLM%20tool%20calling-17191E?style=flat-square)

</td>
<td width="50%" valign="top">

### [guild](https://github.com/lakshcode9/guild)
The full online store for a streetwear retailer in Karnataka.

- Next.js 16 storefront + Django REST API
- Razorpay payments, Shiprocket shipping
- OTP checkout, returns, order management

![Next.js](https://img.shields.io/badge/Next.js-17191E?style=flat-square&logo=nextdotjs&logoColor=FF5A3D) ![Django](https://img.shields.io/badge/Django-17191E?style=flat-square&logo=django&logoColor=FF5A3D) ![Tailwind](https://img.shields.io/badge/Tailwind-17191E?style=flat-square&logo=tailwindcss&logoColor=FF5A3D)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [trend-brief-engine](https://github.com/lakshcode9/trend-brief-engine)
Automated research pipeline, run on a weekly cron.

- Scores Google Trends + Reddit signals
- Researches each trend with Perplexity
- Renders PDF reports with Puppeteer and publishes them to Gumroad

![Node](https://img.shields.io/badge/Node.js-17191E?style=flat-square&logo=nodedotjs&logoColor=FF5A3D) ![Perplexity](https://img.shields.io/badge/Perplexity-17191E?style=flat-square&logo=perplexity&logoColor=FF5A3D) ![Puppeteer](https://img.shields.io/badge/Puppeteer-17191E?style=flat-square&logo=puppeteer&logoColor=FF5A3D)

</td>
<td width="50%" valign="top">

### [n8n](https://github.com/lakshcode9/n8n)
Self-hosted n8n on Render, free.

- Custom Dockerfile: ffmpeg, Python, yt-dlp
- Supabase Postgres so workflows survive restarts
- Uptime keep-alive setup

![Docker](https://img.shields.io/badge/Docker-17191E?style=flat-square&logo=docker&logoColor=FF5A3D) ![Supabase](https://img.shields.io/badge/Supabase-17191E?style=flat-square&logo=supabase&logoColor=FF5A3D) ![Render](https://img.shields.io/badge/Render-17191E?style=flat-square&logo=render&logoColor=FF5A3D)

</td>
</tr>
</table>

<br/>

## Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=ts,py,js,nodejs,nextjs,react,tailwind,django,fastapi,postgres,supabase,docker,vercel&perline=13" alt="Stack" />

<sub><b>AI:</b> LLM APIs (OpenAI-compatible, Perplexity, OpenRouter) · tool calling · retrieval · agent orchestration · n8n</sub>

</div>

<br/>

## Currently

- Learning how to evaluate AI agents and model outputs, and applying for evaluation work
- Doing CS50P alongside an AI engineering curriculum: RAG, embeddings, evals, fine-tuning

<br/>

<div align="center"><sub><a href="https://lakshpujary.tech">lakshpujary.tech</a></sub></div>
