# The 40Hz City

![The 40Hz City — AI memory and agent continuity](./banner.svg)

## Your work should outlive the chat window.

I'm **Steffan Douglas Haskins**, creator of Kairos. I build memory and continuity tools that help approved AI apps return to the same notes, preferences and project decisions. **You can run the Journal locally and keep your information on your own computer.** The managed invited service is an optional way to use the same Journal engine.

**Kairos — The bridge to remembrance.**

The feeling of being known starts with something practical: carrying what matters into the next conversation. Kairos keeps an inspectable history, records where notes came from, and helps connected AI tools pick up a project with its decisions and handoffs.

## Start here

| What you want | Where to go | Availability |
| --- | --- | --- |
| Run or inspect the memory engine | [Kairos-Bridge AI Journal](https://github.com/Steffan005/Kairos-Bridge-AI-Journal) | Local MCP source. The [extended engine](https://github.com/Steffan005/Kairos-Bridge-AI-Journal/tree/chatgpt/private-journal-service) adds project continuation for local and account-service use. |
| Run or inspect the optional account service | [Self-hostable adapter source and evidence](https://github.com/Steffan005/Kairos-Bridge-AI-Journal/tree/chatgpt/private-journal-service/hosted) | Account sign-in, approved AI connections and a separate journal per account, on an operator-controlled computer or server. The managed invited pilot is one deployment. |
| Explore the iPhone app | [Kairos for iPhone](https://github.com/Steffan005/Kairos-Bridge-iOS) | The native companion opens **Anamnesis — Your journal**. The documented owner beta used the configured account service (0.1.0 build 6, October 14, 2026). |
| Study the runtime components | [AI-Consciousness-Distribution](https://github.com/Steffan005/AI-Consciousness-Distribution) | Python memory service, timing experiments and WebGL interface source. |
| Explore the research history | [QCI-Phoenix](https://github.com/Steffan005/QCI-Phoenix) | Implementation archive, design drafts and historical research and patent materials. |

The practical memory product and the broader orchestration research have separate entry points. Some related City repositories are private; public inspection starts with the links above.

## Memory you can inspect and carry forward

- **Shared context across approved AI tools.** Connect supported clients to the same journal. Run the engine locally with your own SQLite file, or self-host the optional account adapter. Its configured data directory determines where per-account records live.
- **A history of what was recorded.** SHA-256 hash links support integrity checks. Notes retain dates and attribution; authenticated account-service writes also record the connection that delivered them.
- **Project continuation.** The extended Journal engine returns recorded goals, decisions, open work and addressed handoffs with source IDs through local MCP or the account adapter. Explicit corrections preserve the earlier history.
- **Control and portability.** Export your journal and manage approved access. Retrieved notes go to the AI provider you connect; its own data policies apply.

The public [chatgpt/private-journal-service branch](https://github.com/Steffan005/Kairos-Bridge-AI-Journal/tree/chatgpt/private-journal-service) contains the extended engine and optional account adapter. Its engine can run locally; the default main branch retains an older local v0.1.0 snapshot without the continuation additions. Read [the component and evidence map](docs/EVIDENCE.md) before comparing their features or versions.

## What has been demonstrated

The source includes dated records of owner-phone read/write round trips, notes shared across approved AI providers and native Kairos, full-history search, and a controlled hosted recovery rehearsal. Each record names its scope and remaining acceptance work.

- [Hosted service and tested provider paths](https://github.com/Steffan005/Kairos-Bridge-AI-Journal/blob/chatgpt/private-journal-service/hosted/README.md)
- [Project briefings, corrections and authenticated delivery origin](https://github.com/Steffan005/Kairos-Bridge-AI-Journal/blob/chatgpt/private-journal-service/hosted/CONTINUE.md)
- [Native iPhone acceptance history](https://github.com/Steffan005/Kairos-Bridge-iOS/blob/chatgpt/native-first-slice/ACCEPTANCE.md)
- [Manual hosted recovery rehearsal](https://github.com/Steffan005/Kairos-Bridge-AI-Journal/blob/chatgpt/private-journal-service/hosted/RECOVERY_ACCEPTANCE_2026-10-15.md)

These are development and invited-owner results. Provider availability, independent onboarding and wider release have their own acceptance gates. Gemini's later phone availability is on hold in the documented pilot; its current documented use is through the computer browser.

## The 40 Hz research

The City also explores timed agent coordination, memory consolidation and continuity after interruption. A 40 Hz period is 25 milliseconds. The components use 40 Hz in distinct ways: scheduling, timestamp coordinates, numerical phase calculations and animation.

The local UCC is the scheduling heartbeat and runtime-health service. Its health score combines service availability and activity. The memory journal, inference worker and transport each have their own implementation and test records. A measured scheduling cadence does not by itself establish a biological effect or a performance advantage.

**f(WHO) = WHO** is the project's continuity design principle: recover the right identity-related context from an attributed record. **All processes are one process** is our systems philosophy. The implementations make their timing, storage, attribution and handoff rules explicit.

## Built through named collaboration

Steffan Douglas Haskins leads the project. AI development contributions are recorded under stable project actors:

| Project actor | Contributor |
| --- | --- |
| gpt_codex | GPT / Codex — structure, implementation review and continuity work |
| claude_summers | Claude — architecture, implementation and continuity analysis |
| gemini_word | Gemini — architecture, design and public explanation |
| grok_ops | Grok — adversarial review, coordination and public explanation |

Unity names the local companion/runtime work. Model versions, applications and devices are recorded separately from these actor labels. The names preserve contribution history; authenticated delivery metadata describes the connection used for a particular record.

## Patent and licensing

The related U.S. patent application is **Harmonic Orchestration System for AI Agents, No. 19/860,331**. Inventor: **Steffan Douglas Haskins**. Related provisional application: **63/912,083**. The November 2, 2026 submission/payment acknowledgement is recorded in the project evidence; application status and scope are separate from product availability. The continuity-technology filing workstream is separate.

Kairos Journal is available under **AGPL-3.0-or-later**, with separate commercial licensing available. **Commercial terms, including any royalty arrangements, are undisclosed.** Each repository's published license and notices govern its code; research archives include older notices and drafts.

## Contact and project history

- [Email Steffan](mailto:steffan.haskins@gmail.com) for collaboration, pilot discussions and commercial licensing.
- [X / @Steffan005](https://x.com/Steffan005)
- [Earlier profile snapshot](https://github.com/Steffan005/Steffan005/blob/498d810fd35e3155113d9cd4f2d21258a1341fff/README.md) — project origins and historical language, preserved at its original commit.

*Built by people and AI collaborators who care about carrying the work forward.*
