<div align="center">

# Ziton

### Embodied-AI data & tooling · Unreal Engine gameplay

C++ / Python engineer. Nearly 3 years building **motion-capture data pipelines**, cross-platform
SDKs and **UE gameplay systems** — now applying that same pipeline work to humanoid robot learning.

**📍 Shanghai · open to roles in embodied-AI data / robot learning and UE gameplay**

<a href="https://ziton.vercel.app"><img src="https://img.shields.io/badge/Blog-ziton.vercel.app-000000?style=flat-square&logo=vercel&logoColor=white" alt="Blog"></a>

</div>

---

## What I've shipped

Personal projects, built end to end. Every number below is measured on held-out data or in-sim, and reproducible from the repo.

| Project | Headline result | Stack |
|---|---|---|
| **[g1-motion-imitation](https://github.com/alertform/g1-motion-imitation)**<br/>Human mocap → Unitree G1 humanoid | Walks **30 s without falling** — **30.9×** the zero-action baseline, **4.36 cm** root drift.<br/>Contact/limit audit keeps **68 of 77** clips (438k frames); PPO across **4096 parallel envs on one RTX 4060**. | `Python` `MuJoCo MJX` `JAX / Brax` |
| **[agentic-search](https://github.com/alertform/agentic-search)**<br/>Local RAG + web, model-routed | 22k chunks: **hit@5 100%**, retrieval **p50 213 ms**.<br/>Hand-written LangGraph state machine, BM25 + vector RRF hybrid retrieval, ACL filtering, golden-set eval. Local path **fully offline, zero API keys**. | `Python` `LangGraph` `Chroma` `FastAPI` |
| **[lora-function-calling](https://github.com/alertform/lora-function-calling)**<br/>QLoRA on a single 8 GB GPU | Held-out 300, base → tuned: exact-call **89.7% → 94.3%**, tool-name 96.3% → 99.3%, invalid JSON 2.7% → **0**.<br/>Qwen2.5-7B in 4-bit nf4 on an RTX 4060. | `Python` `PEFT` `TRL` `bitsandbytes` |
| **[ue5-multiplayer-action](https://github.com/alertform/ue5-multiplayer-action)**<br/>Lyra-style multiplayer demo, UE 5.5 | Full **GAS** stack, 4-stage root-motion katana combos with per-swing Motion Warping, **server-side lag compensation** with favor-the-shooter rewind, prediction-correction metrics, deathmatch loop, BehaviorTree AI.<br/>Backed by a headless UE Automation suite. | `C++` `UE 5.5` `GAS` `UnLua` |

---

## Background

| | |
|---|---|
| **2026.04 – now** | Full-time on personal projects — humanoid motion imitation, agent tooling, model fine-tuning. |
| **2024.08 – 2026.04** | **Optical motion-capture company** · UE / SDK developer.<br/>C++ SDKs and DCC plugins across **7 platforms** (UE / Unity / MotionBuilder / Blender / C4D / Maya / OpenVR); coordinate-system conversion and skeleton retargeting; OSC / VMC realtime + replay pipelines; StretchSense glove and OpenVR device integration, multi-source fusion and time sync; Qt / PySide6 capture and monitoring tools. |
| **2023.06 – 2024.07** | **Game studio** · UE developer.<br/>Single-player UE4 C++: inventory / equipment systems, AI (custom BehaviorTree nodes + AIPerception + a hand-rolled FSM), tank combat demo. |
| **2019.09 – 2023.06** | **BSc, Information & Computing Science** · Wuhan Institute of Technology · CET-6 |

---

## Skills

```text
Languages    C++17 · Python · Rust · TypeScript · Lua
Robotics     MuJoCo / MJX · JAX + Brax PPO · motion retargeting (differential IK) · ROS 2 (DDS / QoS)
Mocap data   OSC / VMC · coordinate transforms · skeleton retargeting · multi-source fusion & time sync
AI / Agents  MCP · function calling · LangGraph · RAG (hybrid retrieval, ACL, eval) · QLoRA / PEFT
Engines      Unreal Engine 5 · GAS · replication & lag compensation · editor tooling & plugins
Desktop      Qt Widgets / PySide6 · Tauri · React · cross-platform packaging
Systems      multithreading & thread safety · CMake · Docker · Linux · TCP / WebSocket / JSON-RPC / SSE
```

---

<div align="center">

📫 **[ziton.vercel.app](https://ziton.vercel.app)** · [github.com/alertform](https://github.com/alertform)

</div>
