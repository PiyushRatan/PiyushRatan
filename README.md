<h1 align="center">Piyush Ratan</h1>

<p align="center">
Class 12 Student &nbsp;·&nbsp; Full-Stack Developer &nbsp;·&nbsp; AI/ML Learner
<br/>
📍 Farrukhabad, Uttar Pradesh &nbsp;·&nbsp; 🌐 <a href="https://piyushratan.in">piyushratan.in</a>
</p>

---

## About

I'm 15 and in Class 12. I build web apps and AI systems in my spare time — starting from fundamentals, not shortcuts.

My current focus is understanding machine learning from the math up: matrix algebra, loss functions, and working toward neural networks from first principles. On the web side, I've built and shipped production systems for real users.

---

## Projects

### AI / ML

**Darpan360 — Chatbot-as-a-Service Platform** · [darpan360.in](https://darpan360.in) · [GitHub](https://github.com/PiyushRatan/OnlineChatbotIntegration)

Users can create domain-specific AI bots and embed them into any third-party website via a sandboxed widget. Built with a multi-layer AI routing system:

- **Layer 1 — Generation:** Routes to Google Gemini for fast responses
- **Layer 2 — Rate Limit Handling:** Auto key-rotator intercepts `429` errors and hot-swaps API keys
- **Layer 3 — Provider Failover:** Falls back to Groq (Llama 3) for ~99.9% uptime
- **Layer 4 — Session Cleanup:** Node Cron job garbage-collects abandoned sessions older than 4 hours
- **Security:** Dynamic CORS policy cross-references Bot ID against `allowedDomains` on every preflight — returns `403` to unauthorized origins

`React · Vite · TailwindCSS · Framer Motion · Node.js · Express · MongoDB Atlas · Firebase Auth`

---

**NCERTGPT** *(in progress)*
RAG-based Q&A system over NCERT Class 12 textbooks.
Pipeline: PDF → text extraction → chunking → vector embeddings → retrieval → NLP query layer.
`Python · RAG · Vector DB · Embeddings · NLP`

---

**CyberAlert — Spam & Phishing Detector** · [GitHub](https://github.com/PiyushRatan/CyberAlert)
Classifies and scores scam/phishing messages using AI with prompt engineering for severity analysis.
`Python · Flask · AI APIs · Prompt Engineering`

---

**Regression Models — ML from Foundations**
Implemented and compared Linear Regression, Decision Tree, and Random Forest on real datasets.
Evaluated using MSE, MAE, and R².
Currently working through the math: OLS derivation (β̂ = (XᵀX)⁻¹Xᵀy), loss geometry, gradient descent next.
`Python · scikit-learn · NumPy · Pandas · Matplotlib`

---

**Audio-to-Text Pipeline**
End-to-end speech-to-text system using AI APIs with structured backend processing and response handling.
`Python · Flask · API Integration`

---

### Web

**ReadAble — Accessibility Tool** · [GitHub](https://github.com/PiyushRatan/ReadAble)
OCR + text-to-speech + translation for users with reading or visual difficulties.
`JavaScript · APIs · HTML · CSS`

**PCM Syllabus Tracker** · [GitHub](https://github.com/PiyushRatan/PCM-Syllabus-Tracker)
Study progress tracker for Class 11/12 Physics, Chemistry, and Mathematics.

---

### Deployed

| Site | Description |
|------|-------------|
| [darpan360.in](https://darpan360.in) | Chatbot-as-a-Service AI platform |
| [sdrpintercollege.com](https://sdrpintercollege.com) | School website — full frontend + backend |
| [brothersproductionnoida.web.app](https://brothersproductionnoida.web.app) | Business website |
| [vaultera.in](https://vaultera.in) | Personal project platform |
| [piyushratan.in](https://piyushratan.in) | Portfolio |

---

## Tech Stack

**Languages:** `Python` `JavaScript` `C` `HTML` `CSS`

**Web & Backend:** `React` `Vite` `Node.js` `Express` `Flask` `Firebase` `Supabase` `MongoDB Atlas` `MySQL` `TailwindCSS` `Framer Motion` `Render` `Vercel`

**AI / ML:** `scikit-learn` `Pandas` `NumPy` `Matplotlib` `Plotly` `RAG Pipelines` `Vector Databases` `Prompt Engineering` `Google Gemini` `Groq (Llama 3)` `Multi-Provider Failover`

**Tools:** `Git` `GitHub` `Figma`

---

## Currently Learning

- ML foundations: OLS → Gradient Descent → Neural Networks
- MLOps: notebook-to-production model deployment
- Backend scalability and system design

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/piyushratan)
[![X](https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white)](https://x.com/piyush__ratan)
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/xpiyush_ratan)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:piyushratan.tech@gmail.com)

---

## GitHub Stats

![](https://github-readme-stats.vercel.app/api?username=PiyushRatan&theme=dark&hide_border=false&include_all_commits=false&count_private=false)
![](https://github-readme-stats.vercel.app/api/top-langs/?username=PiyushRatan&theme=dark&hide_border=false&layout=compact)
![](https://nirzak-streak-stats.vercel.app/?user=PiyushRatan&theme=dark&hide_border=false)
