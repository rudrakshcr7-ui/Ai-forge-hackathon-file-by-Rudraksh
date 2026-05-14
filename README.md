# CareerForge AI — Interview Readiness Evaluator

> **AI CareerForge Hackathon Submission** | Built for the "Build the Future of Interview Readiness" challenge

An AI-powered web application that evaluates a student's interview readiness across 5 dimensions in under 2 minutes — providing a personalized score, skill heatmap, and improvement roadmap.

---

## 🎥 Demo Video

> [📹 

---

## 🚀 Live Demo

>CareerForge is a zero-setup AI web application that runs instantly in the browser.
---

## 🎯 Problem Statement

Millions of students enter the job market unprepared. They only discover gaps in their interview preparation *after* failed interviews — when it's too late.

**CareerForge AI** gives students an objective "Interview Readiness Score" with personalized improvement plans *before* they face real recruiters.

---

## ✨ Features

| Feature | Description |
|---|---|
| 📄 Resume Analysis | AI evaluates ATS compatibility, keyword relevance, formatting, and achievement quality |
| ⚡ Technical Assessment | Skill depth evaluation + live coding aptitude question |
| 🗂️ Portfolio Evaluation | GitHub, portfolio website, and project count analysis |
| 🎙️ Communication Scoring | Self-assessment of confidence, clarity, and pressure handling |
| 📊 Readiness Dashboard | Overall score (0–100), category breakdown, grade (A–F) |
| 🗺️ Improvement Roadmap | 5 personalized, prioritized action items |
| 🛠️ Skill Heatmap | Visual breakdown of strong vs weak skill areas |

---

## 🧠 How It Works

1. **User fills a 5-step form** (takes under 2 minutes)
2. **Claude AI analyzes** the complete profile across all dimensions
3. **Results dashboard** shows score, grade, strengths, weaknesses, and roadmap

### Evaluation Dimensions

```
Overall Score = Resume (25%) + Technical (25%) + Portfolio (25%) + Communication (25%)
```

### Grading System

| Grade | Score | Label |
|---|---|---|
| A | 85–100 | Excellent |
| B | 70–84 | Good |
| C | 55–69 | Average |
| D | 40–54 | Needs Work |
| F | 0–39 | Not Ready |

---

## 🛠️ Tech Stack

- **Frontend:** Vanilla HTML5, CSS3, JavaScript (ES6+)
- **AI Engine:** Anthropic Claude API (claude-sonnet-4-20250514)
- **Design:** Custom dark-theme UI with CSS animations
- **Fonts:** Sora, JetBrains Mono (Google Fonts)
- **Deployment:** Static HTML — runs in any browser

---

## 📁 Project Structure

```
careerforge-ai/
├── index.html      ← Complete application (single file)
└── README.md       ← This file
```

---

## 🎬 Demo Flow

1. Enter profile details
2. Paste/upload resume
3. Select technical skills
4. Add GitHub & portfolio
5. AI generates readiness score
6. Receive roadmap + recommendations

---

## ⚙️ Setup & Usage

### Option 1 — Open directly
1. Download `index.html`
2. Open in any modern browser (Chrome, Firefox, Edge)
3. Enter your Anthropic API key
4. Fill the evaluation form
5. Get your score!

### Option 2 — Run with local server
```bash
# Python
python -m http.server 8000

# Node.js
npx serve .
```
Then open `http://localhost:8000`

### Getting an API Key
1. Go to [console.anthropic.com](https://console.anthropic.com)
2. Sign up for a free account
3. Generate an API key
4. Paste it into the app

> **Note:** Your API key is never stored or sent anywhere except directly to Anthropic's API.

---

## 🏗️ Architecture

User → Frontend UI → Claude API → AI Evaluation Engine → Dashboard

---

## 🔮 Future Scope

- Voice-based mock interviews
- Real GitHub repository analysis
- AI-generated interview questions
- Recruiter dashboard
- Resume upload parsing
- AI benchmarking against industry candidates
- For hackathon simplicity, API calls are made client-side.Production version would use a secure backend proxy.

---

## 🌐 Hosted Version

https://your-app.vercel.app

---

## 🤖 AI Evaluation Engine

Claude AI analyzes:
- resume quality
- technical readiness
- communication confidence
- portfolio depth
- interview pressure handling

The system uses structured prompting to generate:
- readiness scores
- personalized feedback
- skill heatmaps
- improvement roadmaps

---

## ⚡ Performance Goals

- Evaluation completed in under 2 minutes
- Lightweight frontend
- Fast AI response pipeline
- Mobile responsive experience

---

## 💡 Why CareerForge Matters

Most students only realize their weaknesses after failing interviews.

CareerForge AI helps students identify skill gaps early and prepare strategically before placement season.

---

## 🏆 Evaluation Criteria Addressed

| Criteria | How We Address It |
|---|---|
| **Impact (20%)** | Solves real problem — students know their gaps before interviews |
| **Innovation (20%)** | AI-generated personalized roadmap + skill heatmap |
| **Technical Execution (20%)** | Clean code, Claude API integration, robust fallback |
| **User Experience (25%)** | Dark futuristic UI, under-2-minute flow, mobile responsive |
| **Presentation (15%)** | Video demo linked above |

---

## 👨‍💻 Author

Built with ❤️ for the **AI CareerForge Hackathon** by **UnsaidTalks Education**

---

## 📄 License

MIT License — free to use and modify
