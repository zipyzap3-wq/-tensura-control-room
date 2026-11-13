# POLLINATIONS RUNTIME INTEGRATION — VOLUME 1 CRAFT LAB

> WORKFLOW LADDER: 00 Control → 01 Source intake → 02 Craft extraction → 03 Continuity separation → 04 Character/time-state awareness → 05 AU integration → 06 Test planning → 07 Test scene → 08 Runtime draft → 09 Review → 10 Revision → 11 Independent audit → 12 Evidence → 13 User approval → 14 Canon boundary → 15 Improvement.
> FILE POSITION: Stages 01–10, runtime bridge. PURPOSE: Define the Pollinations code agent as a supporting craft-research runtime inside the one unified skill. PREREQUISITES: SKILL.md, both Tensura workflows, source map, and Dropbox schema. REQUIRED ACTIONS: Use the actual Volume 1 files, process batches ≤3, preserve source, store derived notes, and report limits. STATUS: Runtime repository exists; deployment not verified. NEXT: agent.ts in the Pollinations runtime repository, then controlled ingestion test.

## Runtime repository
https://github.com/zipyzap3-wq/tensura-volume1-craft-agent
Entry point: https://github.com/zipyzap3-wq/tensura-volume1-craft-agent/blob/main/agent.ts
The runtime repo currently exists but is private. Pollinations code-agent publishing requires a public GitHub repository with a root-level agent.ts. Do not change visibility or claim deployment without explicit user authorization and successful Pollinations registration.

## Correct Pollinations architecture
- Code agents load one self-contained agent.ts from the repository root/default branch.
- Pollinations provides the Vercel AI SDK `ai` and `@ai-sdk/openai-compatible`; arbitrary package.json dependencies are not installed by the code-agent runtime.
- Use `model(id)`, `respond(config)`, and `mcp.tools(server)` in the supported callback.
- Use Pollinations' `computer` MCP server for the caller's persistent `/workspace` filesystem. This is the persistent workspace service.
- Do not confuse `computer` with `machines`: Machines provisions separately billed Linux sandboxes and requires the account machines permission. It is not the ordinary persistent Computer workspace.
- MCP calls and model calls can consume Pollen. Do not claim no-cost or unlimited operation.

## Runtime responsibilities
1. Inspect `/workspace/tensura-volume1-craft-lab/PROGRESS.md`.
2. Ingest Volume 1 chunks 001–015 in order, no more than three per user-requested batch.
3. Read each complete raw file from the Control Room Volume 1 source directory. If a fetch or read fails, mark BLOCKED.
4. Keep per-chunk craft observations concise and non-infringing; no long quotations, close paraphrase, or substitute retelling.
5. Maintain a ledger with all seven states: QUEUED, OPENED, READ IN FULL, EXTRACTED, BOUNDARIES CHECKED, RECONCILED, VERIFIED.
6. Synthesize the transferable craft profile only after all 15 chunks are VERIFIED.
7. Create original test scenes only from a user-provided or already approved premise; review and revise against a recorded rubric.
8. The runtime is not the story canon repository, does not approve chapters, and does not directly write to Dropbox.

## Dropbox connection boundary
Pollinations hosted code agents do not inherit the user's private Dropbox connector. The Pollinations Computer workspace is private to the Pollinations caller and is not the user's Dropbox. The unified skill must use the connected Dropbox app to create/read/write the user-owned knowledge database and transfer only derived, source-linked research notes. Do not create a public Dropbox link as a workaround. Record exact transfer evidence.

## Deployment checklist
- [ ] Root agent.ts contains the integrated instructions and uses the correct Computer MCP server.
- [ ] The GitHub repository is public (requires explicit user authorization).
- [ ] Pollinations dashboard registration completed by the account owner.
- [ ] First runtime call succeeds and confirms model/tool configuration.
- [ ] First batch reads full source files and writes progress/analysis records.
- [ ] Transfer to Dropbox completed through the connected Dropbox integration and verified.
- [ ] Runtime usage/cost behavior reported from actual account evidence.
