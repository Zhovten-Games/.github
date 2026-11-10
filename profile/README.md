<details>
<summary>How did I end up here?</summary>

Through the mysterious will of the Great Random.

More precisely: the Phantom Draft horror blog has been retired, and its root URL now redirects to zhovten.games — the public home of Zhovten Games.

If you followed an old link and landed here, nothing is broken.

If you are looking for something from Phantom Draft, write to us.
If it still exists in the archive, we will gladly send it.
</details>

## Focus

Zhovten Games is an independent game development studio combining narrative design, production and systems engineering. We connect game mechanics, narrative structure and monetisation into coherent, implementable player experiences.

We develop our own original projects and work with other game teams as a project-based external development partner.

We help studios design and implement narrative-driven game systems — core loops, progression and story structures that work in real production, not just on paper.

### Experience

Our background includes HOPA titles, including shipped projects in the *Whispered Secrets* and *Mystery Case Files* franchises, mobile game design with in-game economies, and startup projects where we worked across design, production and technical decision-making.

### Services

* Narrative design & story consulting: story structure, quests, dialogue, pacing and tone.
* Systems-driven narrative: aligning progression, mechanics and emotional beats.
* Gameplay systems design support, working closely with technical implementation.
* Monetisation and game economy design for premium, hybrid and mobile projects: economy loops, pricing logic and live-ops hooks.

### Strengths

* Structuring complex yet readable quest logic, branching and progression.
* Translating narrative ideas into systems that teams can realistically implement and maintain.
* Owning the pipeline from concept and documentation to implementation-ready designs.

---

## Team

### Oksana Dubinetska

**Lead Game Designer / Founder**

Leads narrative design, story structure, quest logic and production coordination across projects.

[GitHub](https://github.com/FOP-Oksana-Dubinetska) · [Studio Profile](https://zhovten.games/authors/oksana-dubinetska/)

### Sam Starling

**External Game Development Partner**

Leads gameplay systems architecture, technical implementation and system-level integration.

[GitHub](https://github.com/pan-canon) · [Studio Profile](https://zhovten.games/authors/sam-starling/)

---

## 📡 Project Updates

### 🎃 Halloween 2026 — One Year of Zhovten Games

This October, InterDead's narrative architecture became a working technical system.

Three lines now define the current production baseline:

| Layer | What changed |
| --- | --- |
| **Narrative Core** | The portable C++20 core executes game states, rules, time, knowledge and interactions through one authoritative boundary. |
| **Playable Projections** | Console and WebAssembly expose the same underlying system; the current closed beta supports focused narrative and gameplay testing. |
| **InterDead Workshop** | A private production workspace connects project documents, their relationships, development tools and game builds. |

The current architectural direction is:

Narrative source
→ C++20 Game Core
→ Console / WebAssembly
→ Unreal Engine (planned)

By New Year, we aim to release the first public beta of the game's narrative core: a playable WebAssembly slice covering the first two chapters. This remains a development target, dependent on content readiness and the current testing cycle. Our broader annual review is planned for the end of December; the first Unreal Engine implementation is a further goal for 2027.

→ **[Read the complete Halloween 2026 anniversary update on zhovten.games](https://zhovten.games/blog/one-year-of-zhovten-games-halloween-2026/)**

<details>
<summary>☂️Summer 2026 — Umbrella Update</summary>

This summer was mostly about turning several parallel experiments into one development pipeline.

Three lines converged:

| Layer | What changed |
| --- | --- |
| **Literate Programming** | Research into reproducible source generation and executable documentation returned directly to the game-development pipeline. |
| **Scenario → Game Core** | InterDead moved toward a separate linguistic scenario source and an independent C++ Game Core with multiple projections. |
| **IRONCREED** | The studio's recurring engineering work became a public applied IT and engineering practice whose methods return to Zhovten Games. |

The current architectural direction is:

Scenario
→ C++ Game Core
→ Unreal
→ Web / WASM

The GDD is close to completion, the scenario has been written, and the next major stage is implementation of the executable game core.

→ **[Read the complete Summer 2026 Umbrella Update on zhovten.games](https://zhovten.games/blog/summer-2026-umbrella-update/)**

</details>

<details>
<summary>☂️February 2026 — Umbrella Update</summary>

February was not about individual publications — it was about restructuring the project architecture.

Layer	What changed
Canon as a Contract	Canon discipline formalized through a public wiki and SSOT
Reproducible Artifact Pipeline	Video pipeline: ASR → LLM → FFmpeg
Communication Architecture	Unified project voice through the system character Niro

Results: 65–75% reduction in video production time, stronger stylistic control, and a unified project communication layer.

→ **[Read the complete February Umbrella Update on zhovten.games](https://zhovten.games/blog/february-umbrella-update)**

Cases included in this update
* **[Case 1 — Canon discipline](https://zhovten.games/blog/why-canon-contract-interdead/)**
* **[Case 2 — Artifact pipeline](https://zhovten.games/blog/video-artifact-pipeline-interdead/)**
* **[Case 3 — Communication architecture](https://zhovten.games/blog/niro-communication-architecture/)**

The complete cases and their source links are preserved in the studio publication archive.
</details>
