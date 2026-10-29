# Hi, I'm Matthew Amiadamen

Final-year Computer Science student at **Dublin City University**. I build AI systems that real people use: agentic platforms on AWS, real-time computer vision, and geospatial tools. Lately I'm pointing all of it at **neural decoding**. What I most want to build is the machine learning behind brain-computer interfaces: the models that turn noisy neural signals into something a person can use.

- 🧠 Building a **cross-subject SSVEP brain-computer interface**, working through the ML from the maths up: covariance matrices, Riemannian geometry, CCA, and why a model trained on one brain fails on another.
- 🤟 **Lámha** helps students learn Irish Sign Language and runs in post-primary schools around Dublin.
- 🔐 Working on **Mayfain**, a verified-identity layer that lets AI agents act for people through sanctioned MCP integrations, without seeing their raw data.
- ⚙️ Day to day: LLM routing on Amazon Bedrock, vector search and embeddings, multi-tenant PostgreSQL with row-level security, and event-driven jobs on ECS and EventBridge.

---

## Things I've built

**Cross-subject SSVEP BCI** *(in progress)*: decodes which flickering target someone is looking at from their EEG, without calibrating on them first. The core ML problem is that every brain is different, so a decoder trained on one person drifts on the next. I'm comparing three transfer-learning answers to that: Euclidean Alignment (whitening each subject's covariance so their data lines up), Riemannian Alignment (doing the same on the curved space covariance matrices actually live in) and stCCA (transferring spatial and temporal templates). All three run under leave-one-subject-out evaluation on the Tsinghua SSVEP Benchmark (35 subjects, 40 targets). Then the real question: do the rankings from 64-channel lab EEG still hold on a 4-channel consumer montage like the OpenBCI Ganglion? My bet is that Riemannian Alignment's edge shrinks there, because the covariance structure it exploits thins out with so few channels.

**GrianView**: tells any Belfast homeowner whether their roof suits solar, using the city's public LiDAR data. Built with a PhD researcher at Queen's University Belfast: ArcGIS solar radiation over 52,872 buildings, a 5-factor suitability scorer, live 3D rendering in Three.js, and an LLM layer that writes plain-language payback and CO₂ reports.

**Lámha**: won the Create It track at Craicathon. Real-time Irish Sign Language recognition in the browser (MediaPipe hand landmarks and a custom KNN classifier) at 85% accuracy, with no paid APIs. Now used as a learning tool in Dublin-area schools.

**Mayfain**: a trust layer between people, their AI agents and the institutions they deal with. Agents act for a person through sanctioned integrations built with institutions, using MCP, rather than scraping forms, and sensitive details stay protected the whole way. Selected as one of 10 teams for Pressure Cooker at Dublin AI Week 2026.

**Cabhar**: NLP complaint triage (spaCy, scikit-learn) for a UN SDG 8 platform at DCU, routing workplace-exploitation reports to the right NGOs at 98% accuracy.

**Parallel**: a game theory engine that gives each actor in a scenario its own AI agent and runs them in parallel across isolated Daytona sandboxes.

---

## Recognition

- 🥇 **Bloomberg bpuzzled, 1st place**: team Cubits scored 8/9, at the time the highest score by any Irish university team in the competition's history.
- 🏆 **Craicathon, Create It track winner** (Lámha).
- 🚀 **Pressure Cooker, Dublin AI Week 2026**: one of 10 teams selected (Mayfain).

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/matthew-amiadamen)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:matthewamiadamen@gmail.com)

---

## Tech Stack

**Languages**

![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)

**Frameworks**

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Node.js](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![.Net](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white)

**DevOps**

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![Webpack](https://img.shields.io/badge/webpack-%238DD6F9.svg?style=for-the-badge&logo=webpack&logoColor=black)
![Gunicorn](https://img.shields.io/badge/gunicorn-%298729.svg?style=for-the-badge&logo=gunicorn&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

**AI / Tooling**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-%23EA4B71.svg?style=for-the-badge&logo=n8n&logoColor=white)

**Design**

![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![Framer](https://img.shields.io/badge/Framer-black?style=for-the-badge&logo=framer&logoColor=blue)
