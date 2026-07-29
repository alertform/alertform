# Hi, I'm Ziton 👋

I build **AI-native tooling** — agents, retrieval systems, and the plumbing that keeps them
reliable — on top of a background in **C++ engine and cross-platform SDK work**.

## Featured Projects

| Project | What it is | Stack |
|---------|------------|-------|
| [UnrealAgentMCP](https://github.com/alertform/UnrealAgentMCP) | A native MCP server running **inside** the Unreal Editor process — AI agents drive UE 5.5 directly, no bridge process. Three-tier permissions (ReadOnly / SafeWrite / Destructive), full JSONL audit trail, transactional undo, 62 engine automation tests. Built before the engine shipped its own MCP support. | C++ · UE 5.5 · JSON-RPC 2.0 |
| [agentic-search](https://github.com/alertform/agentic-search) | Local RAG + web-search agent. Hand-written LangGraph state machine (no prebuilt react agent), BM25 + vector RRF hybrid retrieval with ACL filtering, golden-set evaluation. 22k chunks: hit@5 100%, p50 213 ms, fully offline and key-free. | Python · LangGraph · Chroma · FastAPI |
| [lora-function-calling](https://github.com/alertform/lora-function-calling) | QLoRA fine-tune turning a 7B model into a function-calling specialist on a single 8 GB consumer GPU. Held-out eval, base vs tuned: exact call 89.7% → 94.3%, invalid JSON 2.7% → 0. | Python · PEFT · TRL · bitsandbytes |
| [LuoXiaoHeiPet](https://github.com/alertform/LuoXiaoHeiPet) | Cross-platform AI desktop pet — streaming chat, tool calling, multi-provider routing, three-layer memory, TTS, 10+ animated states. | Rust · Tauri 2 · React |
| [ue5-multiplayer-action](https://github.com/alertform/ue5-multiplayer-action) | Third-person multiplayer action demo: GAS, server-authoritative hit detection, lag compensation with per-attacker rollback. | C++ · UE5 · GAS |

## What I work with

```text
Languages    C++17 · Python · Rust · TypeScript
AI / Agents  MCP · function calling · LangGraph · RAG (hybrid retrieval, eval) · QLoRA / PEFT
Engines      Unreal Engine 5 · GAS · editor tooling & plugins
Desktop      Qt / PySide6 · Tauri · cross-platform packaging
Systems      multithreading · real-time data pipelines · TCP / WebSocket / JSON-RPC / DDS
```

Day job so far: cross-platform C++ SDKs and plugins for an optical motion-capture company
(7 platforms — UE, Unity, MotionBuilder, Blender, C4D, Maya, OpenVR), plus ROS 2 work on a
drone-swarm ground station.

---

📫 [Blog](https://ziton.vercel.app) · [GitHub](https://github.com/alertform)
