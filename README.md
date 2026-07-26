<h1 align="center">Hi, I'm Parth Roy <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28px"></h1>

<h3 align="center">Full Stack Developer and AI Engineer · 8+ Years Experience</h3>

<p align="center">
  Full Stack Product Engineering &nbsp;·&nbsp; Real-time Conversational AI &amp; WebRTC
</p>

<p align="center">
  <a href="https://www.upwork.com/freelancers/~019c81064069d2076f"><img src="https://img.shields.io/badge/Upwork-6FDA44?style=for-the-badge&logo=Upwork&logoColor=white" alt="Upwork" /></a>
  <a href="https://www.linkedin.com/in/royparth/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=LinkedIn&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://medium.com/@idea.to.implementation"><img src="https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white" alt="Medium" /></a>
  <a href="mailto:royparth94@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=Gmail&logoColor=white" alt="Email" /></a>
  <a href="https://omnikit.live"><img src="https://img.shields.io/badge/OmniKit.live-FF4F00?style=for-the-badge&logo=rocket&logoColor=white" alt="OmniKit.live" /></a>
</p>

---

## About

I work across two halves of the same problem: **building the product** and **making the AI inside it actually work**.

Most of what I ship is multi-tenant SaaS — dashboards, APIs, admin consoles, integrations, billing, deploys — with real-time AI as the feature people are paying for. Doing both means the AI isn't a demo bolted onto a prototype, and the product isn't a thin shell around someone else's API. Shipped end to end for **10K+ businesses**.

### 🧱 Full Stack Engineering

- **Frontend** — Next.js/React dashboards, multi-tenant admin panels, embeddable chat & voice widgets, React Native SDKs, design systems in Tailwind/MUI/Chakra
- **Backend** — NestJS, Express, FastAPI and Django services; REST + GraphQL APIs, webhook pipelines, microservices, background workers, third-party integrations (Meta, WhatsApp, telephony providers)
- **Data** — Postgres, MongoDB, Redis, MySQL; schema design, migrations, multi-tenant data isolation
- **Platform** — Docker, Nginx, AWS (EC2/Lambda), GitHub Actions, zero-downtime CI/CD, on-prem deployments, logging & observability

### 🤖 AI Engineering

- **Voice agents** — full STT · LLM · TTS pipelines plus native realtime models (Gemini Live, OpenAI Realtime). Barge-in, turn detection, sub-second greetings, warm transfer, call routing
- **Telephony** — Asterisk/PBX provisioning, SIP trunking, WebRTC media servers, outbound campaign dialers
- **Agent engineering** — tool orchestration over MCP, RAG, prompt/context budgeting, workflow builders, and the observability work that keeps agents from quietly regressing
- **Visual & video AI** — live avatar video agents, computer vision, face recognition, image pipelines

Off the keyboard, I travel. 🌍

---

## What I'm Building Now

### 🧑‍💼 AI Avatar — current focus

Real-time conversational avatars that run on **both GPU and CPU**. The GPU path serves LAM-based avatar models on CUDA/PyTorch; the CPU path runs the same pipeline through **ONNX Runtime**. Most talking-avatar stacks assume an accelerated instance — degrading cleanly to CPU means it deploys on commodity hardware and on-prem, where the customer's budget and data-residency rules actually live.

Around it: an avatar management API, a streaming TTS WebSocket service, and an embeddable, brandable avatar chat widget.

---

## By the Numbers

<p align="center">
  <img src="https://img.shields.io/badge/Pull_Requests-2%2C417-1F6FEB?style=for-the-badge&logo=github&logoColor=white" alt="2417 pull requests" />
  <img src="https://img.shields.io/badge/Merged-2%2C317_(96%25)-8957E5?style=for-the-badge&logo=git&logoColor=white" alt="2317 merged" />
  <img src="https://img.shields.io/badge/Commits-11%2C539-238636?style=for-the-badge&logo=git&logoColor=white" alt="11539 commits" />
  <img src="https://img.shields.io/badge/Since-Feb_2022-8B949E?style=for-the-badge&logo=github&logoColor=white" alt="active since Feb 2022" />
</p>

<p align="center"><sub>Across public and private repositories. Most day-to-day work lives in private client and company repos, so the contribution graph below reflects only a slice of it.</sub></p>

---

## Featured Work

### 🌐 [OmniKit.live](https://omnikit.live/) — AI Omnichannel Communication Platform

> Built end-to-end by me &nbsp;·&nbsp; Powered by **[SCT Technology](https://sct.technology)**

**10K+ active businesses** &nbsp;·&nbsp; **5M+ messages processed monthly**

| Capability                         | What it does                                                                   |
| ---------------------------------- | ------------------------------------------------------------------------------ |
| 🗣️ **AI Voice Agent**              | Conversational AI with human-like NLU for handling customer calls in real-time |
| 👁️ **AI Visual Agent**             | Computer vision AI for image recognition & intelligent visual interactions     |
| 💬 **WhatsApp Bot & Campaign**     | Automated bot + bulk messaging with rich media & delivery tracking             |
| 📞 **Telephony Voice Campaign**    | Outbound AI-powered voice campaigns for lead gen & surveys                     |
| 📧 **Email Bot & Campaign**        | Intelligent email automation + marketing campaign analytics                    |
| 📱 **SMS Campaign**                | High-converting global SMS marketing with instant delivery                     |
| 📲 **Social Media Bots**           | Automated Facebook & Instagram bots for social commerce & CX                   |
| 🌐 **Web Widget**                  | Embeddable omnichannel widget supporting voice, live chat & video              |

Under the hood: realtime agent runtime, chat agent, consumer services, CRM (frontend + backend), super-admin dashboard, and on-prem deployment tooling.

### 🎥 HoloTalk — Real-time Video AI

Live conversational **video** agents for kiosks, product demos, and customer spaces — avatar streaming wired into the same realtime voice pipeline, with 3D immersive environments.

### ☎️ Voice & Telephony Infrastructure

The layer everything else sits on — Asterisk/PBX provisioning, WebRTC media servers, WebSocket call servers, streaming STT bridges (NVIDIA Riva, Google STT, Whisper), and TTS websocket services.

### 🧱 Web & Product Engineering

The full-stack surface across client work — multi-tenant admin consoles and super-admin tooling, CRM frontends and backends, operator dashboards, embeddable widget kits, REST and webhook services, microservices, AWS Lambda functions, a centralised logging service, plus hotel-booking, cab-booking and e-commerce platforms. Mobile side: React Native bot SDK, Kotlin and Java Android apps.

### 🧪 [Gemini Watermark Remover](https://watermark.omnikit.live/)

Removes Gemini's visible watermark **losslessly** by inverting the alpha-compositing equation it was applied with, rather than approximating with a model. Runs entirely client-side — nothing is uploaded. Ships as a web app, CLI, and Node/browser SDK.

### 📦 Other Products

QuickSmart.ai 🚀 &nbsp;·&nbsp; iCalls.ai 📞 &nbsp;·&nbsp; TalkingBot.ai 💬 &nbsp;·&nbsp; Gita.iCalls.ai 🙏 &nbsp;·&nbsp; CareTalk.ai 💖 &nbsp;·&nbsp; QuikLearn.ai 🎓 &nbsp;·&nbsp; Employee Connect 👥 &nbsp;·&nbsp; Dhwani.ai 🔊

---

## Open Source

| Repo | What it is |
| ---- | ---------- |
| **[voxtral-tts-server](https://github.com/parthroy/voxtral-tts-server)** `Python` | TTS inference server for real-time speech synthesis |
| **[websocket-bridge-riva](https://github.com/parthroy/websocket-bridge-riva)** `JavaScript` | WebSocket ↔ NVIDIA Riva speech bridge, Audiocodes-compatible |
| **[simli-app-next](https://github.com/sct-tech/simli-app-next)** `TypeScript` | Next.js app for Simli realtime avatar video |
| **[nodejs-boiler-ts](https://github.com/parthroy/nodejs-boiler-ts)** `TypeScript` | Production Node + TypeScript service starter |
| **[next_boilerplate](https://github.com/parthroy/next_boilerplate)** `TypeScript` | Next.js app starter |
| **[springboot-kotlin](https://github.com/parthroy/springboot-kotlin)** `Kotlin` | Spring Boot + Kotlin service scaffold |
| **[vue-3-boilerplate](https://github.com/parthroy/vue-3-boilerplate)** `JavaScript` | Vue 3 starter with Vuex, Router, persisted store |

---

## Tech Stack

|                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Languages**            | ![typescript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![javascript](https://img.shields.io/badge/JavaScript-323330?style=flat-square&logo=javascript&logoColor=F7DF1E) ![python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) |
| **Frontend**             | ![next](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![react](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![vue](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white) ![redux](https://img.shields.io/badge/Redux-593D88?style=flat-square&logo=redux&logoColor=white) ![tailwind-css](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwind-css&logoColor=white) ![material-ui](https://img.shields.io/badge/MUI-0081CB?style=flat-square&logo=mui&logoColor=white) ![chakra-ui](https://img.shields.io/badge/Chakra-319795?style=flat-square&logo=chakra-ui&logoColor=white) ![storybook](https://img.shields.io/badge/Storybook-FF4785?style=flat-square&logo=storybook&logoColor=white) ![three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=three.js&logoColor=white) ![pwa](https://img.shields.io/badge/PWA-4285F4?style=flat-square&logo=googlechrome&logoColor=white) |
| **Backend / API**        | ![nodejs](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![nestjs](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![fastapi](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![springboot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![graphql](https://img.shields.io/badge/GraphQL-E434AA?style=flat-square&logo=graphql&logoColor=white) ![sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=flat-square&logo=sequelize&logoColor=white) |
| **Data**                 | ![postgresql](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![mongodb](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![mysql](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) |
| **Cloud / DevOps**       | ![aws](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white) ![docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white) ![github-actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) ![vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) ![netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white) |
| **Mobile / Desktop**     | ![reactnative](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![flutter](https://img.shields.io/badge/Flutter-28B6F6?style=flat-square&logo=flutter&logoColor=white) ![android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white) ![electron](https://img.shields.io/badge/Electron-2C2E3B?style=flat-square&logo=electron&logoColor=white) |
| **LLM / Agents**         | ![openai](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white) ![anthropic](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white) ![gemini](https://img.shields.io/badge/Gemini_Live-4285F4?style=flat-square&logo=googlegemini&logoColor=white) ![groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logo=groq&logoColor=white) ![mcp](https://img.shields.io/badge/MCP-D97757?style=flat-square&logo=anthropic&logoColor=white) ![langchain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![langgraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white) ![huggingface](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black) |
| **Voice / Speech**       | ![livekit](https://img.shields.io/badge/LiveKit-FF4F00?style=flat-square&logo=livekit&logoColor=white) ![vapi](https://img.shields.io/badge/VAPI-5865F2?style=flat-square&logo=voice&logoColor=white) ![elevenlabs](https://img.shields.io/badge/ElevenLabs-000000?style=flat-square&logo=elevenlabs&logoColor=white) ![whisper](https://img.shields.io/badge/Whisper-412991?style=flat-square&logo=openai&logoColor=white) ![riva](https://img.shields.io/badge/NVIDIA_Riva-76B900?style=flat-square&logo=nvidia&logoColor=white) ![voxtral](https://img.shields.io/badge/Voxtral_TTS-FF7000?style=flat-square&logo=audiomack&logoColor=white) |
| **Realtime / Telephony** | ![webrtc](https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white) ![asterisk](https://img.shields.io/badge/Asterisk_PBX-F60000?style=flat-square&logo=asterisk&logoColor=white) ![sip](https://img.shields.io/badge/SIP_%2F_Trunking-005571?style=flat-square&logo=voipdotms&logoColor=white) ![websockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socket.io&logoColor=white) ![socketio](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socket.io&logoColor=white) ![simli](https://img.shields.io/badge/Simli_Avatar-6E56CF?style=flat-square&logo=webrtc&logoColor=white) |
| **ML / Vision**          | ![pytorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![tensorflow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) ![cv](https://img.shields.io/badge/Computer%20Vision-FF5722?style=flat-square&logo=opencv&logoColor=white) ![mlkit](https://img.shields.io/badge/ML_Kit-4285F4?style=flat-square&logo=google&logoColor=white) ![nlp](https://img.shields.io/badge/NLP-4285F4?style=flat-square&logo=google&logoColor=white) |
| **Testing & Design**     | ![jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white) ![mocha](https://img.shields.io/badge/Mocha-8D6748?style=flat-square&logo=mocha&logoColor=white) ![pytest](https://img.shields.io/badge/Pytest-3776AB?style=flat-square&logo=python&logoColor=white) ![figma](https://img.shields.io/badge/Figma-000000?style=flat-square&logo=figma&logoColor=white) ![adobe-xd](https://img.shields.io/badge/Adobe_XD-470137?style=flat-square&logo=adobe-xd&logoColor=white) |

---

## Achievements

🏆 **Top Rated** on Upwork (2022) &nbsp;·&nbsp; ⏫ **Rising Talent** on Upwork (2022)

<details>
<summary>Earlier recognition</summary>

<br />

- 🥇 **Winner** — Coding Competition, Avishkar Updates2k18 (2018)
- 🥇 **Winner** — Coding Competition, Code Sangram Updates2k19 (2019)
- 🥈 **1st Runner-up** — Web-a-Thon, GTU Techfest (2019)
- 🥈 **1st Runner-up** — Master's App, GTU Techfest (2019)
- 🤝 **Core Team Member** — Google Developer Student Club, SCET Surat
- 🤝 **Representative** — Training & Placement, Computer Engineering Dept., SCET Surat
- 🤝 **Core Team Member** — Coding Club, Computer Engineering Dept., SCET Surat

</details>

---

## Let's Build Something

I take on **full-stack product builds** — web apps, dashboards, APIs and mobile — and **AI engagements**: voice agents, realtime WebRTC and telephony systems, agent tooling. Best fit when you need both in one person. Greenfield or rescuing something that's stalled.

---

## GitHub Stats

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=parthroy&theme=github_dark" height="170" alt="GitHub Stats" />
  &nbsp;&nbsp;
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=parthroy&theme=github_dark" height="170" alt="Top Languages" />
  <br /><br />
  <img src="https://streak-stats.demolab.com?user=parthroy&theme=dark&hide_border=true" alt="GitHub Streak" />
</div>
