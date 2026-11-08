# Awesome-Virtual-Workshop-Interactive-Training

# Awesome Virtual Workshop & Interactive Training

> A curated list of top Virtual Workshop and Interactive Training platforms — both SaaS/Hosted commercial solutions and open-source alternatives for collaborative whiteboarding, live polling, quizzes, and session planning.  
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Miro](#miro)
  - [Mural](#mural)
  - [Kahoot! 360](#kahoot-360)
  - [Mentimeter](#mentimeter)
  - [Slido](#slido)
  - [SessionLab](#sessionlab)
- [Open-Source Software](#-open-source-software)
  - [draw.io (diagrams.net)](#drawio-diagramsnet)
  - [AFFiNE](#affine)
  - [NeoBoard (NeoToolSuite)](#neoboard-neotoolsuite)
  - [Pulse (Nextcloud)](#pulse-nextcloud)
  - [ClassQuiz](#classquiz)
  - [Claper](#claper)
  - [open.mentimeter](#openmentimeter)
  - [Educates](#educates)
  - [OpenFresk](#openfresk)
  - [SessionPlan](#sessionplan)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Virtual Workshop and Interactive Training platforms. These are not open-source but are included as reference points for feature comparison.

### Miro
**Type:** Collaborative whiteboard and visual workspace  
Miro is the most widely adopted virtual whiteboard for workshops, brainstorming, and remote collaboration. It offers an infinite canvas, templates, sticky notes, voting, timers, and integrations with video conferencing tools. It is the de facto standard for facilitators running visual sessions online [citation:10].

### Mural
**Type:** Visual collaboration and whiteboarding  
Mural provides a digital whiteboard designed for design thinking, agile ceremonies, and workshop facilitation. It includes structured templates, facilitation features like private mode and timers, and integrations with tools like Jira and Slack. Often compared directly against Miro as a primary alternative [citation:1].

### Kahoot! 360
**Type:** Gamified quizzes and interactive training  
Kahoot! is the leading gamified quiz platform for live training, workshops, and classrooms. Participants join via a PIN on their own devices and compete on a leaderboard. Kahoot! 360 adds corporate training features, advanced reporting, and integrations for enterprise learning and development.

### Mentimeter
**Type:** Live polling and audience interaction  
Mentimeter lets presenters create interactive slides with polls, word clouds, quizzes, and Q&A that audiences respond to from their phones. It is widely used in workshops, training sessions, and conferences to gather real-time input and engagement.

### Slido
**Type:** Q&A and live polling for meetings  
Slido (now part of Cisco) focuses on live Q&A, polls, and quizzes that integrate directly into video conferencing tools like Zoom, Teams, and Webex. It is commonly used in virtual workshops and training sessions to keep audiences engaged and collect questions.

### SessionLab
**Type:** Workshop and training session planning  
SessionLab is a dedicated tool for designing workshop agendas and training flows. It provides a library of facilitation methods and templates, drag-and-drop timeline planning, and automatic time recalculation when activities are adjusted. A free tier is available [citation:10][citation:11].

---

## 🟩 Open-Source Software

Self-hosted, community-driven Virtual Workshop and Interactive Training tools. The open-source ecosystem is fragmented across whiteboarding, polling, quizzes, and session planning rather than unified workshop suites.

### draw.io (diagrams.net)
**Stack:** JavaScript / Electron | **License:** Apache-2.0  
A feature-rich diagram editor with real-time collaboration, offline usage, and cloud storage support [citation:1]. While not a full workshop platform, it provides a free and open-source alternative to Miro/Mural for creating flowcharts, network diagrams, and structured visual content during workshops. No registration required and no user tracking.

### AFFiNE
**Stack:** TypeScript | **License:** MIT  
An open-source, privacy-focused workspace combining note-taking, project management, Kanban boards, and an interactive whiteboard [citation:1][citation:7]. Positioned as a hybrid of Notion and Miro, it can be self-hosted for complete data control and runs smoothly offline. Still maturing (mobile experience and integrations are less developed than commercial tools), but offers a unified workspace for workshops that need both documentation and visual collaboration.

### NeoBoard (NeoToolSuite)
**Stack:** (Check repository) | **License:** Open Source (free for private use)  
A collaborative whiteboard widget for Element (Matrix) messenger, enabling brainstorming, presentations, training sessions, and process documentation directly within a secure messaging environment [citation:5]. Supports parallel and asynchronous collaboration, with boards usable as standalone applications. Commercial and on-premise hosting require contacting the vendor.

### Pulse (Nextcloud)
**Stack:** PHP / JavaScript | **License:** Open Source (Nextcloud app)  
A self-hosted alternative to Kahoot!, Mentimeter, and Slido that runs inside Nextcloud [citation:8]. Supports live polls (multiple choice, word clouds, scales, ranking), quizzes with nicknames and leaderboards, and presenter views with QR codes. **Important caveat:** The app is explicitly labeled as "vibe-coded" — written by AI coding agents without independent human code review or security audit. Evaluate before relying on it for sensitive sessions [citation:8].

### ClassQuiz
**Stack:** (Check repository) | **License:** MPL-2.0  
An open-source Kahoot! alternative designed primarily for teachers and educational settings [citation:9][citation:15]. Users can create quizzes and play them remotely with others. One of the more established open-source quiz platforms, with 733 GitHub stars as of late 2026 [citation:9].

### Claper
**Stack:** (Check repository) | **License:** (Check repository)  
An open-source audience interaction tool positioned as an alternative to Slido, AhaSlides, and Mentimeter [citation:2]. Supports live polls and audience engagement during presentations. Available for self-hosting.

### open.mentimeter
**Stack:** React / Node.js / Socket.io | **License:** MIT  
A local-first Mentimeter alternative designed to run entirely over a local network with zero cloud dependencies [citation:14]. The presenter's laptop acts as the server; participants connect via browser. Features include live multiple-choice quizzes with speed bonuses, word clouds, Q&A with upvoting, a presenter remote view, and Excel export. Ideal for offline or privacy-sensitive training environments.

### Educates
**Stack:** Go / Kubernetes | **License:** Apache-2.0  
A platform for hosting hands-on, interactive workshop environments where each participant gets an isolated session with step-by-step instructions, integrated terminals, and an embedded VS Code editor [citation:6]. Workshop content is authored in Markdown and can be deployed on Kubernetes at scale or locally with Docker. Suited for technical training (Kubernetes, DevOps, programming) rather than general facilitation workshops.

### OpenFresk
**Stack:** Ruby on Rails / PostgreSQL | **License:** MIT  
A self-hosted platform for deploying and managing interactive "Fresque" workshops for non-profit organizations [citation:12]. Supports workshop scheduling, participant registration, ticketing/payments (Stripe, PayPal), and collaborative exercises with feedback collection. **Caveat:** Last release was a year ago with no active maintainers listed, so evaluate maintenance status before production use [citation:12].

### SessionPlan
**Stack:** Web (URL-based) | **License:** Open Source (per project)  
A free, privacy-first alternative to SessionLab where the entire workshop plan is stored in the URL itself — no account, no server, no tracking [citation:11]. Provides a visual timeline with drag-and-drop blocks that auto-adjust times. Still rough around the edges but functional for facilitators wanting a zero-overhead planning tool.

---

## 📊 Comparison at a Glance

| Software | License | Type | Self-Hosted | Best For |
|----------|---------|------|-------------|----------|
| **Miro** | Proprietary | Whiteboard | ❌ | General visual collaboration |
| **Mural** | Proprietary | Whiteboard | ❌ | Design thinking workshops |
| **Kahoot! 360** | Proprietary | Gamified quizzes | ❌ | Corporate training quizzes |
| **Mentimeter** | Proprietary | Live polling | ❌ | Audience interaction |
| **Slido** | Proprietary | Q&A + polls | ❌ | Meeting engagement |
| **SessionLab** | Proprietary | Session planning | ❌ | Workshop agenda design |
| **draw.io** | Apache-2.0 | Diagramming | ✅ | Visual diagrams in workshops |
| **AFFiNE** | MIT | Workspace + whiteboard | ✅ | Notes + visuals combined |
| **NeoBoard** | Open Source | Whiteboard widget | ✅ (private) | Element/Matrix users |
| **Pulse** | Open Source | Polls + quizzes | ✅ (Nextcloud) | Kahoot/Menti alternative |
| **ClassQuiz** | MPL-2.0 | Quizzes | ✅ | Education-focused quizzes |
| **Claper** | Open Source | Audience interaction | ✅ | Slido alternative |
| **open.mentimeter** | MIT | Local polls/quizzes | ✅ (local network) | Offline/privacy training |
| **Educates** | Apache-2.0 | Hands-on labs | ✅ (K8s) | Technical training |
| **OpenFresk** | MIT | Workshop management | ✅ | Non-profit Fresque workshops |
| **SessionPlan** | Open Source | Session planning | ✅ (URL) | Privacy-first agenda design |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Virtual Workshop or Interactive Training tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source. Note that the open-source ecosystem is fragmented across whiteboarding, polling, quizzes, and planning tools rather than unified workshop platforms.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
