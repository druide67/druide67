### Same model. Same Mac. 30 vs 71 tok/s. That's why I built asiai.

🦞 I'm **Jean-Marc** (druide67) — I build tools for local LLM inference on Apple Silicon.

**[asiai](https://github.com/druide67/asiai)** — Benchmark, monitor & compare 6 inference engines (Ollama, LM Studio, mlx-lm, llama.cpp, vllm-mlx, Exo). One CLI. Real numbers.

**[claude-whisper](https://github.com/druide67/claude-whisper)** — Your Claude Code instances can now talk to each other. 
240 lines of bash, zero daemon. The filesystem is the message bus.

Built because my AI agents needed to monitor their own inference. So I gave them asiai's API. They started monitoring themselves.

*Bench your claw!*

#### Recent discoveries
- MLX is **2.3x faster** than llama.cpp for MoE architectures on Apple Silicon
- DeltaNet KV cache stays flat from 64k to 256k context (same VRAM!)
- Same model, same Mac: **30 tok/s** on one engine, **71 tok/s** on another

[OpenClaw](https://github.com/openclaw/openclaw) contributor — multi-agent AI assistant.

Strasbourg, France | [asiai.dev](https://asiai.dev) | [@jmn67 on X](https://x.com/jmn67) | [LinkedIn](https://www.linkedin.com/in/jean-marc-nahlovsky-a178b63)


<!--
**druide67/druide67** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
