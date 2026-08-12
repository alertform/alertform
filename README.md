<div align="center">

# Hi, I'm Ziton 👋

### AI-native tooling · Unreal Engine · Robot learning

I build agents, retrieval systems and model fine-tunes — plus UE gameplay and the motion-capture
data plumbing behind them. Everything here is a personal project, built end to end and measured.

<a href="https://ziton.vercel.app"><img src="https://img.shields.io/badge/Blog-ziton.vercel.app-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Blog"></a>
<a href="https://github.com/alertform?tab=repositories"><img src="https://img.shields.io/badge/Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositories"></a>

</div>

---

## 🧰 Tech

|  |  |
|---|---|
| **Languages** | ![C++](https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Lua](https://img.shields.io/badge/Lua-2C2D72?style=flat-square&logo=lua&logoColor=white) |
| **AI / Agents** | ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-6E56CF?style=flat-square) ![Hugging Face](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![PEFT](https://img.shields.io/badge/QLoRA%20%2F%20PEFT-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white) ![RAG](https://img.shields.io/badge/RAG%20%C2%B7%20hybrid%20retrieval-4B8BBE?style=flat-square) |
| **Engines / Desktop** | ![Unreal](https://img.shields.io/badge/Unreal%20Engine%205-0E1128?style=flat-square&logo=unrealengine&logoColor=white) ![GAS](https://img.shields.io/badge/GAS%20%C2%B7%20replication-313131?style=flat-square) ![Tauri](https://img.shields.io/badge/Tauri-24C8D8?style=flat-square&logo=tauri&logoColor=black) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Qt](https://img.shields.io/badge/Qt%20%2F%20PySide6-41CD52?style=flat-square&logo=qt&logoColor=white) |
| **Robotics / Sim** | ![MuJoCo](https://img.shields.io/badge/MuJoCo%20%2F%20MJX-1F6FEB?style=flat-square) ![JAX](https://img.shields.io/badge/JAX%20%2B%20Brax%20PPO-8A2BE2?style=flat-square) ![ROS2](https://img.shields.io/badge/ROS%202-22314E?style=flat-square&logo=ros&logoColor=white) ![Retargeting](https://img.shields.io/badge/motion%20retargeting-0F766E?style=flat-square) |
| **Systems** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Concurrency](https://img.shields.io/badge/multithreading%20%C2%B7%20SSE%20%C2%B7%20JSON--RPC-555555?style=flat-square) |

---

## 📊 GitHub

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=alertform&show_icons=true&hide_border=true&include_all_commits=true&theme=github_dark&title_color=58a6ff&icon_color=58a6ff">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=alertform&show_icons=true&hide_border=true&include_all_commits=true&theme=graywhite" alt="Ziton's GitHub stats">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=alertform&layout=compact&hide_border=true&langs_count=6&theme=github_dark&title_color=58a6ff">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=alertform&layout=compact&hide_border=true&langs_count=6&theme=graywhite" alt="Top languages">
</picture>

</div>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🤖 [g1-motion-imitation](https://github.com/alertform/g1-motion-imitation)

Human mocap → **Unitree G1** humanoid. GMR differential-IK retargeting, a contact/limit audit
that keeps **68 of 77** clips (438k frames), then DeepMimic-style PPO in MuJoCo MJX —
**4096 parallel envs on one RTX 4060**.

> Walks **30 s without falling** — 30.9× the zero-action baseline, 4.36 cm root drift.
> Write-up covers 15 iterations, including the two bugs that silently invalidated the first six.

`Python` `MuJoCo MJX` `JAX / Brax`

</td>
<td width="50%" valign="top">

### 🧠 [agentic-search](https://github.com/alertform/agentic-search)

Dual-channel agentic search — local RAG **+** web, with the model routing each query itself.
Hand-written LangGraph state machine (no prebuilt react agent), BM25 + vector RRF hybrid
retrieval, ACL filtering, semantic cache, golden-set eval.

> 22k chunks: **hit@5 100%**, p50 **213 ms**. Local path fully offline on Ollama + Chroma — zero API keys.

`Python` `LangGraph` `Chroma` `FastAPI`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎮 [ue5-multiplayer-action](https://github.com/alertform/ue5-multiplayer-action)

Lyra-style multiplayer action demo on **UE 5.5**. Full GAS stack, 4-stage root-motion katana
combos with per-swing Motion Warping, lock-on and block/parry, a complete deathmatch loop and
BehaviorTree AI coordinated by a server attack-token director.

> Server-side **lag compensation** with favor-the-shooter rewind, plus prediction-correction
> metrics. Backed by a headless UE Automation suite.

`C++` `UE 5.5` `GAS` `UnLua`

</td>
<td width="50%" valign="top">

### 🎯 [lora-function-calling](https://github.com/alertform/lora-function-calling)

QLoRA fine-tune turning **Qwen2.5-7B** into a function-calling specialist on a **single 8 GB
consumer GPU** (RTX 4060). 4-bit nf4 + gradient checkpointing + paged optimizer + seq-packing.

> Held-out eval, base → tuned: exact-call **89.7% → 94.3%**, tool-name 96.3% → 99.3%,
> invalid JSON 2.7% → **0**.

`Python` `PEFT` `TRL` `bitsandbytes`

</td>
</tr>
</table>

---

<div align="center">

**Currently** poking at physics simulation and robot learning, and at what agents can actually
author inside a game engine.

📫 [ziton.vercel.app](https://ziton.vercel.app)

</div>
