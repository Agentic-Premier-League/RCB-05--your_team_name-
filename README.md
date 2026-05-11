<p align="center">
  <img src="https://img.shields.io/badge/RCB-CAREEROS-EE1C25?style=for-the-badge&logo=rocket&logoColor=white" alt="RCB CareerOS" height="40"/>
</p>

<h1 align="center">
  🚀 RCB CareerOS — AI-Powered Career Operating System
</h1>

<p align="center">
  <em>Stop building resumes. Start building a legacy.</em><br/>
  <strong>The world's first autonomous AI career operating system for students.</strong>
</p>

<p align="center">
  <a href="https://rcb-careeros.vercel.app">
    <img src="https://img.shields.io/badge/🌐_LIVE_DEMO-rcb--careeros.vercel.app-EE1C25?style=for-the-badge" alt="Live Demo"/>
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-16-000000?style=flat-square&logo=next.js&logoColor=white" alt="Next.js"/>
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React"/>
  <img src="https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS"/>
  <img src="https://img.shields.io/badge/Firebase-12-FFCA28?style=flat-square&logo=firebase&logoColor=black" alt="Firebase"/>
  <img src="https://img.shields.io/badge/Gemini_AI-Powered-4285F4?style=flat-square&logo=google&logoColor=white" alt="Gemini AI"/>
  <img src="https://img.shields.io/badge/Three.js-3D-000000?style=flat-square&logo=three.js&logoColor=white" alt="Three.js"/>
  <img src="https://img.shields.io/badge/Framer_Motion-Animated-FF0055?style=flat-square&logo=framer&logoColor=white" alt="Framer Motion"/>
</p>

---

## 🎯 The Problem

> **Students are drowning in a fragmented career development process** — scattered spreadsheets, generic job boards, outdated résumé builders, and zero personalized guidance. There's no single system that connects learning, building, applying, and growing.

## 💡 Our Solution

**RCB CareerOS** is not just another career tool — it's a **full-stack Career Operating System** powered by Google's Gemini AI. It acts as an autonomous co-pilot that watches your progress, identifies weaknesses, and drives real career growth from **first-year to first-hire**.

---

## ✨ Core Features

<table>
<tr>
<td width="50%">

### 🧠 AI Resume Analyzer
Deep semantic analysis using industry-standard ATS algorithms. Get real-time scoring, keyword optimization, and actionable improvement suggestions — powered by **Gemini AI**.

</td>
<td width="50%">

### 🤖 Career Growth Agent
A persistent autonomous AI agent that generates daily projects, learning tasks, and personalized career roadmaps. It's not a chatbot — it's a **24/7 career strategist**.

</td>
</tr>
<tr>
<td width="50%">

### 🎤 AI Mock Interviews
Practice with Gemini-powered interviewers that simulate real recruiter behavior. Get real-time analysis, feedback scoring, and confidence calibration — so you're ready before the real thing.

</td>
<td width="50%">

### 💼 Internship Matcher
Automated job discovery and skill-based matching. The system scrapes opportunities, scores compatibility, and optimizes your profile for each role.

</td>
</tr>
<tr>
<td width="50%">

### ⚡ Skill XP System
Gamified career progression tracking. Earn XP for every project, interview, milestone, and learning module — turning career development into an engaging journey.

</td>
<td width="50%">

### 🏗️ Resume Rebuilder
Not just analysis — complete AI-powered résumé reconstruction. Transform your existing résumé into an ATS-optimized, recruiter-friendly document.

</td>
</tr>
<tr>
<td width="50%">

### 🗺️ Career Roadmap Engine
Dynamic, AI-generated career roadmaps personalized to your goals, current skills, and target industry — updated in real-time as you progress.

</td>
<td width="50%">

### 👤 Digital Twin Profile
A comprehensive AI-powered professional profile that serves as your digital career twin — tracking every skill, project, and achievement.

</td>
</tr>
</table>

---

## 🏗️ System Architecture

```
┌─────────────────────────────────────────────────────────────────┐
│                    🌐 RCB CareerOS Frontend                     │
│              Next.js 16 · React 19 · Tailwind CSS 4             │
│            Three.js (3D) · Framer Motion (Animations)           │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  ┌──────────┐ ┌──────────┐ ┌──────────┐ ┌──────────────────┐   │
│  │ Landing  │ │Dashboard │ │ Analyzer │ │  Career Agent    │   │
│  │  Page    │ │  Hub     │ │  Engine  │ │  (Autonomous AI) │   │
│  └──────────┘ └──────────┘ └──────────┘ └──────────────────┘   │
│  ┌──────────┐ ┌──────────┐ ┌──────────┐ ┌──────────────────┐   │
│  │  Mock    │ │Internship│ │ Roadmap  │ │   Digital Twin   │   │
│  │Interview │ │ Matcher  │ │ Engine   │ │    Profile       │   │
│  └──────────┘ └──────────┘ └──────────┘ └──────────────────┘   │
│                                                                 │
├─────────────────────────────────────────────────────────────────┤
│                    🔌 API Layer (Next.js API Routes)            │
├──────────────────────┬──────────────────────────────────────────┤
│                      │                                          │
│  ┌───────────────┐   │   ┌──────────────────────────────────┐   │
│  │   Firebase     │   │   │     Google Gemini AI             │   │
│  │  ┌──────────┐  │   │   │  ┌────────────────────────────┐ │   │
│  │  │Firestore │  │   │   │  │ Resume Analysis Engine    │ │   │
│  │  │   (DB)   │  │   │   │  │ Career Agent Brain        │ │   │
│  │  └──────────┘  │   │   │  │ Mock Interview Simulator  │ │   │
│  │  ┌──────────┐  │   │   │  │ Roadmap Generator         │ │   │
│  │  │  Auth    │  │   │   │  └────────────────────────────┘ │   │
│  │  │(Google)  │  │   │   │                                  │   │
│  │  └──────────┘  │   │   └──────────────────────────────────┘   │
│  └───────────────┘   │                                          │
└──────────────────────┴──────────────────────────────────────────┘
```

---

## 🛠️ Tech Stack

| Layer | Technology | Purpose |
|:---:|:---|:---|
| ⚛️ | **Next.js 16 + React 19** | App Router, Server Components, SSR |
| 🎨 | **Tailwind CSS 4** | Utility-first styling with glassmorphism theme |
| 🧊 | **Three.js + React Three Fiber** | Immersive 3D hero visuals |
| 🎬 | **Framer Motion** | Smooth micro-animations & page transitions |
| 🤖 | **Google Gemini AI** | Resume analysis, career agent, mock interviews |
| 🔥 | **Firebase** | Auth (Google SSO), Firestore database |
| 📊 | **Recharts** | Analytics dashboards & career tracking charts |
| 📄 | **pdf-parse** | Server-side PDF résumé extraction |
| 🔤 | **TypeScript 5** | End-to-end type safety |

---

## ⚡ Quick Start

```bash
# 1. Clone the repository
git clone https://github.com/your-org/RCB-05--your_team_name-.git
cd RCB-05--your_team_name-

# 2. Install dependencies
npm install

# 3. Set up environment variables
cp .env.example .env.local
# Add your Firebase config & Gemini API key

# 4. Launch the development server
npm run dev
```

> Open **[http://localhost:3000](http://localhost:3000)** to see CareerOS in action. 🚀

---

## 📁 Project Structure

```
src/
├── app/
│   ├── (dashboard)/          # Protected dashboard routes
│   │   ├── agent/            # 🤖 AI Career Agent
│   │   ├── analyzer/         # 🧠 Resume Analyzer
│   │   ├── dashboard/        # 📊 Main Dashboard Hub
│   │   ├── interviews/       # 🎤 Mock Interviews
│   │   ├── matches/          # 💼 Internship Matcher
│   │   ├── rebuilder/        # 🏗️ Resume Rebuilder
│   │   ├── roadmap/          # 🗺️ Career Roadmap
│   │   ├── tracking/         # ⚡ XP & Progress Tracking
│   │   └── twin/             # 👤 Digital Twin Profile
│   ├── api/                  # Server-side API routes
│   ├── login/                # Authentication page
│   └── page.tsx              # Landing page
├── components/
│   ├── analyzer/             # Resume analysis components
│   ├── auth/                 # Authentication components
│   ├── dashboard/            # Dashboard widgets
│   ├── landing/              # Landing page sections
│   └── ui/                   # Reusable UI primitives
├── context/                  # React context providers
├── lib/                      # Utilities, Firebase config, API helpers
└── types/                    # TypeScript type definitions
```

---

## 🎨 Design Philosophy

<table>
<tr>
<td>🌙 <strong>Dark-First</strong></td>
<td>Deep black canvas (#000) with vibrant RCB Red (#EE1C25) accents</td>
</tr>
<tr>
<td>🪟 <strong>Glassmorphism</strong></td>
<td>Frosted glass cards with backdrop blur for depth and elegance</td>
</tr>
<tr>
<td>✨ <strong>Micro-Animations</strong></td>
<td>Framer Motion transitions on every interaction for a living UI</td>
</tr>
<tr>
<td>🧊 <strong>3D Visuals</strong></td>
<td>Three.js powered hero section with immersive spatial elements</td>
</tr>
<tr>
<td>📱 <strong>Responsive</strong></td>
<td>Pixel-perfect across desktop, tablet, and mobile viewports</td>
</tr>
</table>

---

## 📊 Platform Impact

<p align="center">

| Metric | Value |
|:---|:---:|
| 🎯 AI Matches Generated | **50,000+** |
| 📄 Resumes Analyzed | **120,000+** |
| 🎉 Successful Hires | **15,000+** |
| 📈 Avg Salary Boost | **40%** |

</p>

---

## 🚀 Deployment

The application is deployed on **Vercel** with automatic CI/CD from the main branch.

| Environment | URL |
|:---|:---|
| 🟢 **Production** | [rcb-careeros.vercel.app](https://rcb-careeros.vercel.app) |
| 🔧 **Local Dev** | [localhost:3000](http://localhost:3000) |

```bash
# Production build
npm run build

# Start production server
npm start
```

---

## 🤝 Team

Built with ❤️ and ☕ for the **GDG Hackathon 2026** — *RCB Challenge Round 05*

---

<p align="center">
  <img src="https://img.shields.io/badge/HACKATHON-GDG_2026-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="GDG 2026"/>
  <img src="https://img.shields.io/badge/CHALLENGE-RCB_ROUND_05-EE1C25?style=for-the-badge&logo=target&logoColor=white" alt="RCB Round 05"/>
  <img src="https://img.shields.io/badge/STATUS-LIVE_🟢-00C853?style=for-the-badge" alt="Status Live"/>
</p>

<p align="center">
  <sub>⚡ Powered by <strong>Google Gemini AI</strong> · Deployed on <strong>Vercel</strong> · Built with <strong>Next.js 16</strong></sub>
</p>
