# Open TapNow & Lovart

English | [简体中文](README.md)

**KardoFlow**: An open-source alternative to TapNow & Lovart.

While those are excellent products worth using, they can be expensive, data isn't stored locally, and privacy risks exist. I built this project in my spare time to address these issues. Technical discussions are welcome!

**NOT FAKE OPEN SOURCE!**
**NOT FAKE OPEN SOURCE!**
**NOT FAKE OPEN SOURCE!**

*(Honesty Alert: The code is currently a mess and I'm too embarrassed to show it all just yet. Please provide feedback and raise issues. Once optimized, I'll fully open it up to make secondary development a breeze.)*

## Features

#### v1.0.1231-pre
✅ **1. Workflows:** Batch generation of marketing images, marketing videos, AI manga, and AI short dramas.
✅ **2. Image Cards:** Supports multiple excellent models like Nano Banana, MJ, etc.
✅ **3. Video Cards:** Supports top-tier models like Sora2, Veo3, Kling, etc.
✅ **4. Text Cards:** Supports Gemini3 Pro, GPT-5.2, and other leading models.
✅ **5. Table Cards:** Data collection, updates, and analysis.
✅ **6. Deployment:** Supports both Cloud Managed (kardo.1mx.cn) and Local Installation.
✅ **7. Flexible Chaining:** Multi-card linking to create rich creative content. Simpler than N8N, more direct than Coze.

#### v1.1.2026 (Estimated Release: 2026.01.31)
⌛️ **1. Model Vendor Comparison:** Choose cheaper and more stable model providers to lower costs.
⌛️ **2. New Integrations:** Support for excellent models from Hailuo (MiniMax) and ByteDance.
⌛️ **3. Advanced Editing:** Multi-image and video editing capabilities.
⌛️ **4. Professional Directing:** Lens settings, storyboarding, and scripting capabilities.
⌛️ **5. Audio Cards:** Music, vocals, and sound effect generation.
✅ **6. UX:** Multi-language support, Light theme, and System theme synchronization.
✅ **7. System:** Software upgrade and update capabilities.
✅ **8. Tools:** Web search, targeted crawling, video splitting, and custom tool integration.
⌛️ **9. Digital Humans:** Real-time API calls and scheduled tasks for digital avatars.
⌛️ **10. Templates:** Default workflows for custom batch short dramas and manga.
⌛️ **11. Prompt Engineering:** Advanced prompting capabilities to quickly generate viral videos.

## Showcase

Achieve high-quality AI short dramas, AI movies, e-commerce marketing images, sales videos, and livestreaming plans by linking cards.
**Intelligent Agent Cards include:** Text, Image, Table, Audio, Video, and Analysis.

![alt text](4d60e2c420997e44f8ff94e2243de508.png)

### AI Short Dramas & AI Movies (Creation Time: ~15 mins)
![alt text](64cbaed552938f934a114cf098786d84.jpg)
<video controls src="https://github.com/user-attachments/assets/a7499fd3-0a50-4b7b-b1a7-6067284697da" title="Title"></video>

### E-commerce Product Images (Creation Time: ~1 min)
![alt text](0ea40210ad30d8f26778bf2d43b0d379.png)
### Marketing Sales Images (Creation Time: ~1.5 mins)
![alt text](9e96a4de0123a949240b893b377d5af8.png)
### Sales Videos (Creation Time: ~1 min)
![alt text](1a08885c5db841f120ce431a5fd5d4f2.png)
<video controls src="https://github.com/user-attachments/assets/4d2b42dc-b640-44d8-84f6-de224c766abf" title="Title"></video>

- **And much more waiting for you to explore!**
- Viral TikTok transition videos for low-follower accounts...
- Natural dancing videos...
- "Be water my friend" scenarios, and more...

## How We Make Money
- **Model Aggregation:** Revenue from stable model supplier integrations helps cover development and operation costs.
- **Cloud Managed Version:** Licensing, white-labeling, and maintenance services. White-label users can request custom features.
- **Content Creation:** We generate and publish our own high-quality AI dramas and marketing videos to platforms for creator rewards.
- **Enterprise Services:** Custom integration and R&D for enterprise clients.

### Tech Stack
- **Backend:** Python FastAPI (WebSocket for event streaming)
- **Workflow Engine:** LangGraph (Agent Loops / Serial & Parallel / Checkpoints)
- **Local Database:** SQLite + sqlite-vss (Lightweight RAG)
- **Frontend:** React + Vite + React Flow (Canvas / DAG)

### Engineering Architecture
- **desktop**
  - **backend:** Desktop backend (FastAPI) & App Launcher (pywebview)
    - `app.py`: REST/WS + Static Hosting + SQLite Persistence (workflows/nodes/edges)
    - `launch_desktop.py`: One-click launch (dev/production), runs backend in a sub-thread
    - `pyproject.toml`: uv project config (provides desktop-backend/desktop-app/desktop-dev scripts)
    - `data/supra.db`: Local SQLite DB (auto-created on run)
  - **frontend:** Desktop frontend (React + Vite + React Flow)
    - `src/App.tsx`: Canvas + Run Events + Right-side Property Panel
    - `src/Canvas.tsx`: Node categories, connection cutting/re-linking, toolbar, resizing
    - `src/Inspector.tsx`: Node property editing
    - `vite.config.ts`: Dev proxy and build output to `../dist`

**NOT FAKE OPEN SOURCE!**
**NOT FAKE OPEN SOURCE!**
**NOT FAKE OPEN SOURCE!**

Again, the code is messy right now. Please test it, break it, and give feedback. I'll polish it before the full source release to ensure a smooth developer experience.

**Download from the world's largest developer community (GitHub):**
https://github.com/libn-net/open_tapnow_lovart/releases/tag/pre-1.0.0

## Community
**Note:** KardoFlow Technical Discussion
*For usage and technical exchange only. No ads or marketing spam, please.*

![alt text](503eb1ce5a373112b3461debf9052d16.png)
![alt text](8a1714ab2395ac4b5cc8e5756663289a.jpg)
