<div align="center">

  <!-- Header Banner -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,2,3&height=190&section=header&text=Kunal%20Gupta&fontSize=42&fontColor=ffffff&animation=fadeIn" width="100%" alt="Kunal Gupta Header" />

  <!-- Animated Typing Tagline -->
  <a href="https://portfolio-website-chi-gilt.vercel.app">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=650&lines=Full-Stack+Developer+%7C+MERN+Stack;Frontend+%26+Backend+Engineer;Next.js+%2B+TypeScript+%2B+Node.js;Real-Time+Apps+with+Socket.IO+%26+Redis" alt="Typing Tagline" />
  </a>

  <p align="center">
    <b>Full-Stack Developer specializing in the MERN stack, TypeScript, and real-time distributed web systems.</b><br />
    Building high-performance cloud applications, developer tooling, and clean user interfaces.
  </p>

  <!-- Navigation Badges -->
  <p align="center">
    <a href="https://portfolio-website-chi-gilt.vercel.app"><img src="https://img.shields.io/badge/Portfolio-Live_Site-2563EB?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio"/></a>
    <a href="mailto:kunal.gmail.91165@gmail.com"><img src="https://img.shields.io/badge/Email-kunal.gmail.91165-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
    <a href="https://github.com/Kunal-Gupta28"><img src="https://img.shields.io/badge/GitHub-Kunal--Gupta28-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
  </p>

</div>

---

### About Me

* **Full-Stack Engineering**: Proficient in architecting end-to-end applications across the full JavaScript/TypeScript ecosystem using **React**, **Next.js (App Router)**, **Node.js**, **Express**, and **MongoDB**.
* **Real-Time Architectures**: Experienced in designing low-latency, event-driven web features with **Socket.IO**, **WebSockets**, and **Redis** for state caching and pub/sub.
* **Developer Tooling & Performance**: Hands-on experience integrating in-browser WASM compilation (**WebContainers**), **Monaco Editor**, and AI models (**Google Gemini API**).
* **Location & Background**: Based in New Delhi, India. Engineering graduate from **Delhi Technological University (DTU)**.

---

### Currently Building & Exploring

* **Building**: Low-latency collaborative workspaces, real-time dispatch systems, and performant Next.js dashboards.
* **Exploring**: In-browser WebAssembly execution runtimes, distributed caching with Redis, and AI-assisted developer workflows.

---

### Tech Stack

<div align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=html,css,js,ts,react,nextjs,tailwind,redux,nodejs,express,mongodb,redis,git,github,postman,vercel&perline=8" alt="Tech Stack Icons" />
  </a>
</div>

---

### GitHub Analytics & Activity

<div align="center">
  <p>
    <a href="https://github.com/Kunal-Gupta28?tab=repositories"><img src="https://img.shields.io/badge/Public_Repositories-10-38BDF8?style=flat-square&logo=github" alt="Repositories"/></a>
    <a href="https://github.com/Kunal-Gupta28"><img src="https://img.shields.io/github/stars/Kunal-Gupta28?style=flat-square&logo=github&label=Stars%20Received&color=EAB308" alt="Stars Received"/></a>
    <a href="https://github.com/Kunal-Gupta28"><img src="https://img.shields.io/github/followers/Kunal-Gupta28?style=flat-square&logo=github&label=Followers&color=2563EB" alt="Followers"/></a>
  </p>

  <br />

  <table align="center" border="0">
    <tr>
      <td align="center" valign="middle">
        <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Kunal-Gupta28&theme=tokyonight" alt="GitHub Profile Details" />
      </td>
      <td align="center" valign="middle">
        <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Kunal-Gupta28&theme=tokyonight" alt="Top Languages Breakdown" />
      </td>
    </tr>
    <tr>
      <td colspan="2" align="center">
        <img src="https://streak-stats.demolab.com?user=Kunal-Gupta28&theme=tokyonight&hide_border=true&background=0D1117&stroke=0D1117&ring=38BDF8&fire=38BDF8&currStreakLabel=38BDF8" alt="GitHub Contribution Streak" />
      </td>
    </tr>
  </table>
</div>

---

### Featured Projects

#### 1. [ChatCraft](https://github.com/Kunal-Gupta28/ChatCraft) — Real-Time Collaborative Cloud IDE & AI Development Workspace
* **What it does**: Full-stack collaborative cloud IDE allowing developers to create, edit, transpile, and execute code directly in the browser with zero server compilation overhead and an integrated context-aware Gemini AI assistant.
* **Tech Stack**: `React 18`, `Node.js`, `Express`, `Socket.IO`, `WebContainers (WASM)`, `Monaco Editor`, `MongoDB`, `Redis`, `Google Gemini API`, `Tailwind CSS`.
* **Key Technical Implementations**:
  * Multi-user live project synchronization, cursor tracking, and collaborative state management via modular Socket.IO handlers.
  * In-browser runtime using StackBlitz `@webcontainer/api` with fallback in-browser Babel transpilation for Safari and mobile devices.
  * Context-aware `@ai` assistant integration for in-editor code refactoring and bug generation.
  * Secure JWT authentication with Redis token blacklisting for reliable logout invalidation.
* **Links**: [GitHub Repository](https://github.com/Kunal-Gupta28/ChatCraft) | [Live Demo](https://chat-craft-xi.vercel.app)

---

#### 2. [Pairora (Milanzo)](https://github.com/Kunal-Gupta28/Milanzo) — Scalable Real-Time Matchmaking & Messaging Platform
* **What it does**: Production-grade real-time matchmaking and discovery web platform engineered with a decoupled 2-tier architecture, low-latency direct messaging, and geospatial matching algorithms.
* **Tech Stack**: `Next.js 14 (App Router)`, `TypeScript`, `Node.js`, `Express`, `Socket.IO`, `Redis (ioredis)`, `MongoDB`, `TanStack Query`, `Tailwind CSS`, `Argon2id`.
* **Key Technical Implementations**:
  * Multi-socket scaling utilizing `@socket.io/redis-adapter` for decoupled real-time event broadcasting and user presence.
  * Geospatial privacy design calculating server-side proximity without exposing raw GPS coordinates over client APIs.
  * High-security layer featuring `Argon2id` hashing, sliding rate limits (`express-rate-limit` + `ioredis`), and anti-contact leakage heuristic detection.
* **Links**: [GitHub Repository](https://github.com/Kunal-Gupta28/Milanzo)

---

#### 3. [Kubik](https://github.com/Kunal-Gupta28/Kubik) — Full-Stack Real-Time Ride Booking Platform
* **What it does**: End-to-end ride booking and dispatch platform connecting riders and drivers with real-time dispatch matching, live geolocation tracking, and automated fare calculations.
* **Tech Stack**: `React`, `Node.js`, `Express`, `MongoDB`, `Socket.IO`, `Google Maps API`, `Tailwind CSS`, `GSAP`, `JWT`.
* **Key Technical Implementations**:
  * Continuous WebSocket GPS streaming updating live vehicle markers on the rider map in real time.
  * Multi-vehicle dynamic fare estimation factoring in route distance, travel duration, and surge parameters.
  * Synchronized trip state machine with 4-digit OTP verification for secure ride commencement and completion.
* **Links**: [GitHub Repository](https://github.com/Kunal-Gupta28/Kubik) | [Live Demo](https://kuber-tau.vercel.app)

---

#### 4. [NovaBank](https://github.com/Kunal-Gupta28/NovaBank) — Modern Digital Banking & Financial Management Dashboard
* **What it does**: High-performance digital banking product interface providing multi-account balance visualization, transaction ledger filtering, and payment transfer workflows.
* **Tech Stack**: `Next.js 15+`, `React 19`, `TypeScript`, `Tailwind CSS v4`, `Chart.js`, `Lucide React`.
* **Key Technical Implementations**:
  * Interactive financial analytics and balance growth visualizations powered by Chart.js.
  * Modular App Router architecture separating authenticated user portals, transfer forms, and transaction ledgers.
  * Responsive, accessible layout engineered with custom CSS tokens and strict TypeScript interfaces.
* **Links**: [GitHub Repository](https://github.com/Kunal-Gupta28/NovaBank)

---

#### 5. [Portfolio Website](https://github.com/Kunal-Gupta28/Portfolio-website) — Interactive 3D Developer Portfolio
* **What it does**: Engineering portfolio featuring interactive 3D WebGL scenes, 60FPS scroll animations, case study modals, and a serverless contact email pipeline.
* **Tech Stack**: `Next.js 16 (App Router)`, `React 18`, `Tailwind CSS v4`, `Spline 3D WebGL`, `GSAP ScrollTrigger`, `Framer Motion`, `Nodemailer`.
* **Key Technical Implementations**:
  * Spline WebGL shader initialization with custom fallback skeletons and zero hydration mismatch wrappers.
  * Pinned GSAP ScrollTrigger case study transitions and serverless contact API endpoint via Nodemailer.
* **Links**: [GitHub Repository](https://github.com/Kunal-Gupta28/Portfolio-website) | [Live Demo](https://portfolio-website-chi-gilt.vercel.app)

---

### Engineering Principles

* **Decoupled & Scalable Architecture**: Structuring clean separation between UI components, global state, and backend service layers.
* **Type Safety & Reliability**: Leveraging TypeScript, Zod schema validation, and defensive API design.
* **Real-Time Performance**: Utilizing WebSockets and Redis pub/sub to minimize network latency and unnecessary polling.
* **Polished User Experience**: Combining semantic HTML, responsive Tailwind tokens, and micro-interactions for snappy interfaces.

---

### Connect With Me

<div align="center">
  <a href="https://portfolio-website-chi-gilt.vercel.app"><img src="https://img.shields.io/badge/Portfolio-Visit_Website-2563EB?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio" /></a>
  &nbsp;
  <a href="mailto:kunal.gmail.91165@gmail.com"><img src="https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  &nbsp;
  <a href="https://github.com/Kunal-Gupta28"><img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</div>

<br />

<div align="center">
  <sub>Designed & engineered by <b><a href="https://github.com/Kunal-Gupta28">Kunal Gupta</a></b></sub>
</div>
