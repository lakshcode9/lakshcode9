<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24c6dc&height=220&section=header&text=Laksh%20Pujary&fontSize=64&fontColor=ffffff&fontAlignY=38&desc=AI%20that%20can%27t%20lie%20about%20what%20it%20did&descSize=18&descAlignY=60&animation=fadeIn" width="100%" alt="Laksh Pujary" />

<a href="https://github.com/lakshcode9">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=900&color=24C6DC&center=true&vCenter=true&width=640&lines=Self-taught+engineer+%C2%B7+Mangaluru%2C+India;LLM+systems+for+real+businesses;Tool+boundaries.+Audit+trails.+Tests.;Building+toward+AI+evaluation+work" alt="Typing intro" />
</a>

<br/>

<a href="https://lakshpujary.tech"><img src="https://img.shields.io/badge/lakshpujary.tech-0f0c29?style=for-the-badge&logo=googlechrome&logoColor=24c6dc" alt="Website" /></a>
<img src="https://img.shields.io/badge/Open%20to-AI%20eval%20%26%20contract%20work-302b63?style=for-the-badge" alt="Open to work" />

</div>

<br/>

## 🧠 About

I build LLM systems for small businesses, and I care most about one failure mode: **an AI that says it did something it didn't.**

Most of my work is the part around the model: tool boundaries, business rules kept out of the prompt, audit trails, and tests that catch confident wrong answers before a customer hears them.

<br/>

## 🛠️ Featured work

<table>
<tr>
<td width="50%" valign="top">

### [🏨 hotel-ai-reception](https://github.com/lakshcode9/hotel-ai-reception)
Self-hosted AI receptionist for a hotel phone line. The model **cannot** report success the backend didn't confirm.

- Tools return `Result<T, E>`, passed to the model verbatim
- Business rules are DB rows that stay inert until a human approves them
- Every state change is audited · 26 tests, one or more per guarantee
- Tests caught a retrieval false positive: *"do you have a helipad?"* matched pool FAQs on the word "have"

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Node](https://img.shields.io/badge/node%3Atest-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![LLM](https://img.shields.io/badge/LLM%20tool%20calling-302b63?style=flat-square)

</td>
<td width="50%" valign="top">

### [🛍️ guild](https://github.com/lakshcode9/guild)
The full online store for a streetwear retailer in Karnataka.

- Next.js 16 storefront + Django REST API
- Razorpay payments, Shiprocket shipping
- OTP checkout, returns, order management

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [📈 trend-brief-engine](https://github.com/lakshcode9/trend-brief-engine)
Automated research pipeline, run on a weekly cron.

- Scores Google Trends + Reddit signals
- Researches each trend with Perplexity
- Renders PDF reports with Puppeteer and publishes them to Gumroad

![Node](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Perplexity](https://img.shields.io/badge/Perplexity-1FB8CD?style=flat-square&logo=perplexity&logoColor=white) ![Puppeteer](https://img.shields.io/badge/Puppeteer-40B5A4?style=flat-square&logo=puppeteer&logoColor=white)

</td>
<td width="50%" valign="top">

### [⚙️ n8n](https://github.com/lakshcode9/n8n)
Self-hosted n8n on Render, free.

- Custom Dockerfile: ffmpeg, Python, yt-dlp
- Supabase Postgres so workflows survive restarts
- Uptime keep-alive setup

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white) ![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)

</td>
</tr>
</table>

<br/>

## 💻 Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=ts,py,js,nodejs,nextjs,react,tailwind,django,fastapi,postgres,supabase,docker,vercel&perline=13" alt="Stack" />

<sub><b>AI:</b> LLM APIs (OpenAI-compatible, Perplexity, OpenRouter) · tool calling · retrieval · agent orchestration · n8n</sub>

</div>

<br/>

## 🌱 Currently

- 🎯 Building toward **AI evaluation work**: testing agent and model outputs against ground truth, not vibes
- 📚 Working through **CS50P** and a structured AI engineering curriculum (RAG, embeddings, evals, fine-tuning)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24c6dc,50:302b63,100:0f0c29&height=120&section=footer" width="100%" alt="" />
