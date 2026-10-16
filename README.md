<div align="center">

# ⚡ Automated Video Generator

**Self-hosted AI text-to-video pipeline — no watermark, no subscriptions, no API key required.**

Turn scripts into MP4 videos with AI voiceovers, Creative Commons stock media, and Remotion rendering.

[![MIT License](https://img.shields.io/github/license/Vemmba/Automated-Video-Generator?style=for-the-badge)](LICENSE)
[![Node](https://img.shields.io/badge/node-%E2%89%A518-339933?style=for-the-badge&logo=node.js)](https://nodejs.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-strict-3178C6?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org)

**Maintained by [Vemmba](https://github.com/Vemmba)**

</div>

---

## ✨ Features

- 🎬 **Text → Video** — feed a topic or script, get a finished MP4
- 🗣️ **AI voiceovers** via Edge TTS (free, no API key)
- 🖼️ **Stock media** from Openverse (Creative Commons, auto-attributed)
- 🎞️ **Remotion rendering** with subtitles, transitions, and music
- 🤖 **Agentic pipeline** — plan → visuals → voice → render, step by step
- 🖥️ **Web portal + Electron desktop app** for Windows
- 🔌 **MCP server** — drive video generation from your AI agent
- 📦 **Batch mode** for queueing many videos

## 🚀 Quick Start

**Web portal (recommended):**

```bash
git clone https://github.com/Vemmba/Automated-Video-Generator.git
cd Automated-Video-Generator
npm install
cp .env.example .env
npm run dev
```

Open `http://localhost:3001` — the Vemmba banner confirms the server is up.

**Agentic CLI:**

```bash
npm run agentic -- --topic "5 home workouts" --title "Home Workouts"
```

**Desktop app (Windows):**

```bash
npm run electron:dev        # develop
npm run electron:build      # build installer
```

**Docker:**

```bash
docker compose up --build
```

## 🛠️ Requirements

- Node.js ≥ 18
- ffmpeg (auto-downloaded on first run if missing)
- Optional: `.env` overrides — see [.env.example](.env.example)

## 📜 Key Scripts

| Command | Purpose |
| --- | --- |
| `npm run dev` | Start the web portal (dev mode) |
| `npm run agentic` | Full agentic video generation from CLI |
| `npm run generate` | Classic CLI generation |
| `npm run remotion:studio` | Open Remotion Studio |
| `npm run mcp` | Start the MCP server |
| `npm test` | Typecheck + unit tests |

Full command reference: [docs/api-reference.md](docs/api-reference.md) · [docs/QUICKSTART.md](docs/QUICKSTART.md)

## 🤝 Contributing

Issues and PRs are welcome at [github.com/Vemmba/Automated-Video-Generator](https://github.com/Vemmba/Automated-Video-Generator). See [docs/CONTRIBUTING.md](docs/CONTRIBUTING.md).

## 📄 License

MIT © [Vemmba](https://github.com/Vemmba). See [LICENSE](LICENSE).

This project is a fork of [itsPremkumar/Automated-Video-Generator](https://github.com/itsPremkumar/Automated-Video-Generator) by Premkumar (MIT). Original copyright notice is preserved in the [LICENSE](LICENSE) file as required.

<div align="center">
<sub>⚡ Built and maintained by <a href="https://github.com/Vemmba">Vemmba</a></sub>
</div>
