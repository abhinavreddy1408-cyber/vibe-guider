# vibe-guider // SYSTEM ONLINE

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![React](https://img.shields.io/badge/React-19-61DAFB.svg?logo=react)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.8-blue.svg?logo=typescript)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-6.0-646CFF.svg?logo=vite)](https://vitejs.dev/)
[![Gemini API](https://img.shields.io/badge/Google%20GenAI-SDK-orange.svg)](https://ai.google.dev/)


![Vibe Guider Dashboard](image_0.png)

> "The Vibe Guider workspace is ready. Select a module to begin operations."

## ░░ Initialize

**VIBE_GUIDER** is an advanced, retro-futuristic terminal interface designed as a unified workspace for multi-modal AI operations. It streamlines access to specialized AI agents ranging from high-speed conversational models to deep reasoning and real-time web-grounded research tools.

The interface combines a cyberpunk aesthetic with real-time system monitoring to provide a powerful, immersive user experience.

---

## ░░ System Modules // Features

VIBE_GUIDER is categorized into distinct operational modules, allowing users to select the right tool for the task.

### ⚡ FAST_ANSWERS (ID: 00)

**Status:** Speed: MAX
Engineered for ultra-low latency interactions. This module utilizes the **Flash Lite** model to provide near-instantaneous responses for quick queries where speed is paramount.

### 💬 PRO_ASSISTANT (ID: 01)

**Status:** Model: G3-PRO
The standard interface for complex tasks. Powered by the **Gemini 3 Pro** model, this assistant handles sophisticated instructions, code generation, and detailed creative writing.

### 🌍 GROUNDED_SEARCH (ID: 02)

**Status:** Web: CONNECTED
Bridges the gap between static knowledge and current events. This module features real-time web data injection via **Google Search**, ensuring responses are grounded in the most up-to-date information available.

### 🧠 THE_RESEARCHER (ID: 03)

**Status:** Reasoning: HIGH
A deep reasoning agent designed for complex logic and multi-step analysis. Use this module for breaking down difficult problems, strategic planning, or in-depth investigations.

### 📹 VIDEO_ANALYSIS (ID: 04)

**Status:** Vision: ON
A dedicated multimodal processing pipeline capable of analyzing video content. (Specific capabilities dependent on implementation).

### 📘 SYS_MANUAL (ID: 05)

Access documentation regarding system architecture and usage guidelines.

---

## ░░ Interface Specs

The VIBE_GUIDER UI is built for efficiency and immersion:

- **Terminal Aesthetic:** Green monochrome CRT-style visuals with scanlines and a grid overlay.
- **Live Monitoring:** Real-time tracking of system resources (CPU / MEM usage).
- **Modular Design:** Clear, card-based navigation for easy switching between different AI agent capabilities.

---

## ░░ Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or pnpm
- Google Gemini API Key

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/abhinavreddy1408-cyber/vibe-guider.git
   cd vibe-guider
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up Environment Variables:**
   Create a `.env` file in the project root:
   ```env
   VITE_GEMINI_API_KEY=your_gemini_api_key_here
   ```

4. **Launch development server:**
   ```bash
   npm run dev
   ```
   Open `http://localhost:5173` in your browser.

---

## 📂 Project Structure

```
vibe-guider/
├── components/           # CRT terminals, HUD layouts, and chat widgets
│   ├── ChatInterface.tsx # Conversational AI interaction window
│   ├── Dashboard.tsx     # Module navigation and CPU/memory telemetry
│   ├── VideoAnalyzer.tsx # Multimodal video comprehension workbench
│   └── MarkdownRenderer.tsx # Cyberpunk formatted text renderer
├── services/             # Gemini API communication handlers
│   └── geminiService.ts  # @google/genai SDK integration
├── types.ts              # System state and message type definitions
├── index.html            # Web entry point with CRT shader filters
└── package.json
```

---

## 🔮 Future Improvements

- [ ] WebGL-accelerated 3D CRT curvature and phosphor glow effects.
- [ ] Direct audio-in / audio-out streaming via Gemini Multimodal Live API.
- [ ] Exportable session transcripts in encrypted JSON format.

---

## 📄 License

Distributed under the [MIT License](LICENSE).

---

## 📬 Contact

**Abhinav Reddy** — [@abhinavreddy1408-cyber](https://github.com/abhinavreddy1408-cyber)  
Project Link: [https://github.com/abhinavreddy1408-cyber/vibe-guider](https://github.com/abhinavreddy1408-cyber/vibe-guider)
