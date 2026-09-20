# JARVIS – AI Personal Assistant

JARVIS is an AI-powered personal assistant application designed to interact with users through a modern web interface. It connects an AI model with a local bridge that can handle supported local actions and communication between the web application and the local environment.

## Features

- 🤖 AI-powered conversational assistant
- 💬 Interactive chat interface
- 🔌 Local WebSocket bridge
- 🌐 Browser-based interface
- 🎙️ Speech/voice fallback support
- 🧩 Modular bridge architecture
- 🔒 Local actions are disabled by default for safety

## Tech Stack

- React
- TypeScript
- Vite
- Node.js
- WebSocket
- JavaScript/TypeScript
- AI model integration

## Project Structure

```text
jarvis/
├── bridge/          # Local WebSocket bridge
├── public/          # Public assets
├── src/             # Frontend source code
├── scripts/         # Project scripts
├── package.json     # Dependencies and scripts
├── vite.config.ts   # Vite configuration
└── README.md        # Project documentation
