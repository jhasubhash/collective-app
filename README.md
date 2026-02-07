<p align="center">
  <img src="images/app-icon.png" alt="Collective" width="128" height="128">
</p>

<h1 align="center">Collective</h1>

<p align="center">
  <strong>AI-Powered Collaborative Knowledge Management</strong>
</p>

<p align="center">
  <a href="https://github.com/jhasubhash/collective-app/releases">Download</a> •
  <a href="https://jhasubhash.github.io/collective-app">Website</a>
</p>

<p align="center">
  <img src="images/welcome.png" alt="Collective App" width="800">
</p>

---

## Features

### AI Chat
Ask questions about your documents and get instant answers with source citations. The AI understands context and finds relevant information across all your indexed documents.

<p align="center">
  <img src="images/Collaborate seameless on a shared space.png" alt="AI Chat" width="700">
</p>

### Bring Your Own LLM
Connect to local models like Ollama or LM Studio for complete privacy. Or use cloud providers like OpenAI, Claude, and Gemini.

<p align="center">
  <img src="images/Connects your local llm as well as cloud.png" alt="LLM Configuration" width="700">
</p>

### P2P Collaboration
No central server needed. Connect directly with teammates using peer IDs. Share documents in real-time and keep your data within your network.

<p align="center">
  <img src="images/p2p connection for sharing.png" alt="P2P Network" width="500">
</p>

### Dark Mode
Switch to dark mode for a comfortable viewing experience. Reduce eye strain during late-night sessions.

<p align="center">
  <img src="images/dark mode.png" alt="Dark Mode" width="700">
</p>

---

## Download

Download the latest release for macOS (Apple Silicon):

[**Download v0.0.9**](https://github.com/jhasubhash/collective-app/releases/latest)

### Installation

1. Download the `.dmg` file
2. Drag Collective to Applications
3. If you see "damaged and can't be opened", run in Terminal:
   ```bash
   xattr -cr /Applications/Collective.app
   ```
4. Open Collective from Applications

---

## Requirements

- **macOS** 11 (Big Sur) or later
- **Apple Silicon**
- **For AI features**: Use [Ollama](https://ollama.ai) or [LM Studio](https://lmstudio.ai) for local models, or connect to cloud providers with your API key

---

## Tech Stack

| Component | Technology |
|-----------|------------|
| Backend | Rust + Tauri |
| Frontend | React + TypeScript |
| Storage | SQLite |
| Networking | libp2p |
| AI/Embeddings | fastembed |

