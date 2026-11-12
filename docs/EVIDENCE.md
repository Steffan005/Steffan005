# Kairos components and evidence

Reviewed November 10, 2026. This map distinguishes implementation, dated acceptance and availability.

Local storage and self-hosting are first-class deployment choices. The Journal can run on an owner-operated computer with an owner-selected SQLite file. The managed pilot is one installation of the account adapter; a connector is an access path and does not by itself identify the storage location.

| Component | Implementation | Evidence and scope |
| --- | --- | --- |
| Local Journal on main | [Default-branch source](https://github.com/Steffan005/Kairos-Bridge-AI-Journal) | Older local v0.1.0 snapshot: SQLite journal and MCP tools for local clients, without the continuation additions. The published 300,000-entry benchmark is synthetic storage and operation latency on the stated machine; it is not end-to-end AI latency or recall accuracy. |
| Extended Journal engine | [Public implementation branch](https://github.com/Steffan005/Kairos-Bridge-AI-Journal/tree/chatgpt/private-journal-service) | Local MCP and account-service operation share the engine for source-linked project briefings, explicit corrections/resolutions and addressed handoffs. The branch name does not require remote hosting or determine repository visibility. |
| Optional account adapter | [Self-hostable source](https://github.com/Steffan005/Kairos-Bridge-AI-Journal/tree/chatgpt/private-journal-service/hosted) | Account sign-in, OAuth approval, per-account journals and authenticated connection-origin metadata. Operators choose the service host and data directory; the managed invited pilot is one deployment. |
| Native iPhone app | [Source and current documented beta](https://github.com/Steffan005/Kairos-Bridge-iOS) | Build 6 is the latest documented accepted owner TestFlight beta, October 14. Independent onboarding and public App Store release remain open. |
| Continuation | [Contract and evidence](https://github.com/Steffan005/Kairos-Bridge-AI-Journal/blob/chatgpt/private-journal-service/hosted/CONTINUE.md) | Works through the extended engine locally or through the account adapter. Recorded project goals, decisions, explicit corrections/resolutions and addressed handoffs retain their source IDs. Local callers select the handoff recipient explicitly; authenticated service connections can supply a provider default. |
| Hosted recovery | [October 15 rehearsal](https://github.com/Steffan005/Kairos-Bridge-AI-Journal/blob/chatgpt/private-journal-service/hosted/RECOVERY_ACCEPTANCE_2026-10-15.md) | Operator-run restore retained 131,820 baseline owner entries exactly. This is a dated rehearsal, with its pauses and resource limits recorded. |

## Choose the right record

A local journal or a service account can contain notes from several contributors. Declared Author, canonical project actor and record owner answer different questions. The authenticated account-service path additionally records the delivering connection; local MCP operation does not invent that evidence. An actor label routes attribution and handoffs; it does not grant private access to a journal.

Hash verification checks record integrity relative to the retained chain/checkpoints. It does not establish the factual truth of a note, a provider-signed statement, a human approval or a clinical result. Imported records keep their original attribution/time and their import provenance.

## Read acceptance in chronological order

Begin with each document's current-status summary, then the dated receipts. Distinguish local fixtures, source/CI checks, operator reports, actual provider use and independent onboarding. A later correction can supersede an earlier successful path or pending item.

The published provider notes are linked from the [hosted README](https://github.com/Steffan005/Kairos-Bridge-AI-Journal/blob/chatgpt/private-journal-service/hosted/README.md). Gemini's later mobile issue is recorded there; do not infer continued phone availability from its earlier round trip.

## Filing records

The November 2, 2026 submission/payment acknowledgement identifies U.S. utility application **19/860,331**, *Harmonic Orchestration System for AI Agents*, inventor Steffan Douglas Haskins. The later formal Filing Receipt and current prosecution record are separate evidence. Related provisional **63/912,083** and the continuity-technology drafting workstream should not be treated as blanket coverage for every file in the archives.

Commercial terms and any royalty arrangements remain undisclosed. Published licenses and their notices continue to govern use of each repository.
