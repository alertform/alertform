<div align="center">

# Ziton

**✳&nbsp; AI-native tooling · Unreal Engine · Robot learning**

I build agents, retrieval systems and model fine-tunes — plus UE gameplay and the motion-capture
data plumbing behind them. Everything here is a personal project, built end to end and measured.

<a href="https://ziton.vercel.app"><img src="https://img.shields.io/badge/Blog-CC785C?style=for-the-badge&logo=vercel&logoColor=F0EEE6&labelColor=191919" alt="Blog"></a>
<a href="https://github.com/alertform?tab=repositories"><img src="https://img.shields.io/badge/Repositories-191919?style=for-the-badge&logo=github&logoColor=F0EEE6&labelColor=191919" alt="Repositories"></a>

</div>

---

## ✳&nbsp; Tech

|  |  |
|---|---|
| **Languages** | ![C++](https://img.shields.io/badge/C%2B%2B17-CC785C?style=flat-square&logo=cplusplus&logoColor=EBDBBC&labelColor=191919) ![Python](https://img.shields.io/badge/Python-CC785C?style=flat-square&logo=python&logoColor=EBDBBC&labelColor=191919) ![Rust](https://img.shields.io/badge/Rust-CC785C?style=flat-square&logo=rust&logoColor=EBDBBC&labelColor=191919) ![TypeScript](https://img.shields.io/badge/TypeScript-CC785C?style=flat-square&logo=typescript&logoColor=EBDBBC&labelColor=191919) ![Lua](https://img.shields.io/badge/Lua-CC785C?style=flat-square&logo=lua&logoColor=EBDBBC&labelColor=191919) |
| **AI / Agents** | ![LangGraph](https://img.shields.io/badge/LangGraph-CC785C?style=flat-square&logo=langchain&logoColor=EBDBBC&labelColor=191919) ![Transformers](https://img.shields.io/badge/Transformers-CC785C?style=flat-square&logo=huggingface&logoColor=EBDBBC&labelColor=191919) ![PEFT](https://img.shields.io/badge/QLoRA%20%2F%20PEFT-CC785C?style=flat-square&logo=pytorch&logoColor=EBDBBC&labelColor=191919) ![Ollama](https://img.shields.io/badge/Ollama-CC785C?style=flat-square&logo=ollama&logoColor=EBDBBC&labelColor=191919) ![MCP](https://img.shields.io/badge/MCP-EBDBBC?style=flat-square) ![RAG](https://img.shields.io/badge/RAG%20%C2%B7%20hybrid%20retrieval-EBDBBC?style=flat-square) |
| **Engines / Desktop** | ![Unreal](https://img.shields.io/badge/Unreal%20Engine%205-CC785C?style=flat-square&logo=unrealengine&logoColor=EBDBBC&labelColor=191919) ![Tauri](https://img.shields.io/badge/Tauri-CC785C?style=flat-square&logo=tauri&logoColor=EBDBBC&labelColor=191919) ![React](https://img.shields.io/badge/React-CC785C?style=flat-square&logo=react&logoColor=EBDBBC&labelColor=191919) ![Qt](https://img.shields.io/badge/Qt%20%2F%20PySide6-CC785C?style=flat-square&logo=qt&logoColor=EBDBBC&labelColor=191919) ![GAS](https://img.shields.io/badge/GAS%20%C2%B7%20replication-EBDBBC?style=flat-square) |
| **Robotics / Sim** | ![ROS2](https://img.shields.io/badge/ROS%202-CC785C?style=flat-square&logo=ros&logoColor=EBDBBC&labelColor=191919) ![MuJoCo](https://img.shields.io/badge/MuJoCo%20%2F%20MJX-EBDBBC?style=flat-square) ![JAX](https://img.shields.io/badge/JAX%20%2B%20Brax%20PPO-EBDBBC?style=flat-square) ![Retargeting](https://img.shields.io/badge/motion%20retargeting-EBDBBC?style=flat-square) |
| **Systems** | ![Docker](https://img.shields.io/badge/Docker-CC785C?style=flat-square&logo=docker&logoColor=EBDBBC&labelColor=191919) ![Linux](https://img.shields.io/badge/Linux-CC785C?style=flat-square&logo=linux&logoColor=EBDBBC&labelColor=191919) ![CMake](https://img.shields.io/badge/CMake-CC785C?style=flat-square&logo=cmake&logoColor=EBDBBC&labelColor=191919) ![Git](https://img.shields.io/badge/Git-CC785C?style=flat-square&logo=git&logoColor=EBDBBC&labelColor=191919) ![Concurrency](https://img.shields.io/badge/multithreading%20%C2%B7%20SSE%20%C2%B7%20JSON--RPC-EBDBBC?style=flat-square) |

---

## ✳&nbsp; GitHub

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=alertform&theme=gruvbox">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=alertform&theme=solarized" alt="Profile details">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=alertform&theme=gruvbox">
  <img height="200" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=alertform&theme=solarized" alt="Repos per language">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=alertform&theme=gruvbox">
  <img height="200" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=alertform&theme=solarized" alt="Most commit language">
</picture>

</div>

---

## ✳&nbsp; Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### [g1-motion-imitation](https://github.com/alertform/g1-motion-imitation)

Human mocap → **Unitree G1** humanoid. GMR differential-IK retargeting, a contact/limit audit
that keeps **68 of 77** clips (438k frames), then DeepMimic-style PPO in MuJoCo MJX —
**4096 parallel envs on one RTX 4060**.

> Walks **30 s without falling** — 30.9× the zero-action baseline, 4.36 cm root drift.
> Write-up covers 15 iterations, including the two bugs that silently invalidated the first six.

`Python` `MuJoCo MJX` `JAX / Brax`

</td>
<td width="50%" valign="top">

### [agentic-search](https://github.com/alertform/agentic-search)

Dual-channel agentic search — local RAG **+** web, with the model routing each query itself.
Hand-written LangGraph state machine (no prebuilt react agent), BM25 + vector RRF hybrid
retrieval, ACL filtering, semantic cache, golden-set eval.

> 22k chunks: **hit@5 100%**, p50 **213 ms**. Local path fully offline on Ollama + Chroma — zero API keys.

`Python` `LangGraph` `Chroma` `FastAPI`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [ue5-multiplayer-action](https://github.com/alertform/ue5-multiplayer-action)

Lyra-style multiplayer action demo on **UE 5.5**. Full GAS stack, 4-stage root-motion katana
combos with per-swing Motion Warping, lock-on and block/parry, a complete deathmatch loop and
BehaviorTree AI coordinated by a server attack-token director.

> Server-side **lag compensation** with favor-the-shooter rewind, plus prediction-correction
> metrics. Backed by a headless UE Automation suite.

`C++` `UE 5.5` `GAS` `UnLua`

</td>
<td width="50%" valign="top">

### [lora-function-calling](https://github.com/alertform/lora-function-calling)

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

Currently poking at physics simulation and robot learning, and at what agents can actually
author inside a game engine.

<a href="https://ziton.vercel.app"><img src="https://img.shields.io/badge/ziton.vercel.app-CC785C?style=flat-square&logo=vercel&logoColor=F0EEE6&labelColor=191919" alt="Blog"></a>

</div>
