<div align="center">

# Ziton

<a href="https://ziton.vercel.app"><img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=21&duration=2600&pause=700&color=CC785C&center=true&vCenter=true&width=640&height=44&lines=AI-native+tooling;Unreal+Engine+gameplay;Robot+learning;Motion-capture+data+pipelines" alt="AI-native tooling · Unreal Engine gameplay · Robot learning · Motion-capture data pipelines"></a>

I build agents, retrieval systems and model fine-tunes — plus UE gameplay and the motion-capture
data plumbing behind them. Everything here is a personal project, built end to end and measured.

<a href="https://ziton.vercel.app"><img src="https://img.shields.io/badge/Portfolio%20%C2%B7%20Blog-CC785C?style=for-the-badge&logo=vercel&logoColor=F0EEE6&labelColor=191919" alt="Portfolio and blog"></a>
<a href="https://github.com/alertform?tab=repositories"><img src="https://img.shields.io/badge/Repositories-191919?style=for-the-badge&logo=github&logoColor=F0EEE6&labelColor=191919" alt="Repositories"></a>

</div>

---

## ✱&nbsp; GitHub

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=alertform&bg_color=00000000&color=CC785C&title_color=CC785C&line=CC785C&point=EBDBBC&area=true&area_color=CC785C&hide_border=true&custom_title=Contribution%20activity" alt="Contribution activity graph">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/alertform/alertform/output/snake.svg?v=2">
  <img src="https://raw.githubusercontent.com/alertform/alertform/output/snake-light.svg?v=2" alt="Contribution snake">
</picture>

</div>

---

## ✱&nbsp; Featured Projects

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

</div>
