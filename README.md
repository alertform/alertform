# Hi, I'm Ziton 👋

I build **AI-native tooling** in my spare time — agents, retrieval systems, model
fine-tuning, and the plumbing that keeps them reliable. Everything here is a personal project.

Lately I've been poking at **physics simulation and robot learning** out of curiosity.

## Featured Projects

| Project | What it is | Stack |
|---------|------------|-------|
| [agentic-search](https://github.com/alertform/agentic-search) | Local RAG + web-search agent. Hand-written LangGraph state machine (no prebuilt react agent), BM25 + vector RRF hybrid retrieval with ACL filtering, golden-set evaluation. 22k chunks: hit@5 100%, p50 213 ms, fully offline and key-free. | Python · LangGraph · Chroma · FastAPI |
| [lora-function-calling](https://github.com/alertform/lora-function-calling) | QLoRA fine-tune turning a 7B model into a function-calling specialist on a single 8 GB consumer GPU. Held-out eval, base vs tuned: exact call 89.7% → 94.3%, invalid JSON 2.7% → 0. | Python · PEFT · TRL · bitsandbytes |
| [g1-motion-imitation](https://github.com/alertform/g1-motion-imitation) | Teaching a Unitree G1 humanoid to physically execute human mocap: differential-IK retargeting, then DeepMimic-style RL on GPU-parallel physics (4096 envs on one consumer GPU). Walks 30 s without falling — 25× the zero-action baseline, root drift 4.5 cm. Write-up covers 12 iterations, including the two bugs that silently invalidated the first six. | Python · MuJoCo MJX · JAX / Brax |
| [ue5-multiplayer-action](https://github.com/alertform/ue5-multiplayer-action) | Third-person multiplayer action demo: GAS, server-authoritative hit detection, lag compensation with per-attacker rollback. | C++ · UE5 · GAS |

## What I work with

```text
Languages    C++17 · Python · Rust · TypeScript
AI / Agents  MCP · function calling · LangGraph · RAG (hybrid retrieval, eval) · QLoRA / PEFT
Engines      Unreal Engine 5 · GAS · editor tooling & plugins
Desktop      Tauri · React · cross-platform packaging
Robotics     MuJoCo / MJX · JAX + Brax PPO · motion retargeting · sim-to-real basics
Systems      multithreading · streaming I/O · TCP / WebSocket / JSON-RPC / SSE
```

---

📫 [Blog](https://ziton.vercel.app) · [GitHub](https://github.com/alertform)
