> # WORKFLOW LADDER | TENSURA CLEAN-SLATE PROJECT
> **File ID:** POLLI-002 | **Stage:** 00-15 | **Status:** EXPERIMENTAL / NON-CANON
> **Full ladder:** 00 control → 01 source intake → 02 craft extraction → 03 continuity → 04 character/time-state → 05 AU integration → 06 arc planning → 07 chapter planning → 08 draft → 09 review → 10 revision → 11 independent audit → 12 evidence → 13 user approval → 14 canon promotion only after approval → 15 self-evolution.
> **Purpose:** Explain the isolated Pollinations Volume 1 Craft Lab and its activation requirements.
> **Prerequisites:** Read this file, inspect agent.ts, and verify the Volume 1 source archive.
> **Required actions:** Register the GitHub code agent in Pollinations My Models; test ingestion in bounded batches; verify saved workspace outputs.
> **Completion evidence:** Pollinations returns a callable model ID; a real ingestion call creates verified chunk notes; a controlled writing test and rubric report are saved.
> **Next destination:** Pollinations dashboard -> Add Agent -> Code Agent -> repository URL below.
> **Stop conditions:** No API/account access, missing source chunks, unavailable computer MCP, or failed runtime deployment.
> **Approval boundary:** This is a non-canon experiment. Nothing here authorizes changes to source files or story canon.

# Tensura Volume 1 Craft Lab

**Isolated Pollinations code-agent experiment.**

Repository: https://github.com/zipyzap3-wq/-tensura-control-room  
Test branch: `pollinations-agent-test`  
Agent entry point: `agent.ts`  
Source archive: `PROJECTS/TENSURA_WORKFLOW_LADDER/04_SOURCE_MATERIAL/VOLUME_01/`

## What it is built to do

1. Read the actual Volume 1 chunk files, three at a time, rather than pretending a filename or summary equals reading.
2. Extract high-level narrative craft observations without copying or reconstructing the novel.
3. Build a persistent craft profile in the Pollinations computer workspace.
4. Use that profile to create original fanfiction scenes when given a premise.
5. Review and revise drafts against a concrete rubric.
6. Keep all outputs experimental and non-canon until the user explicitly approves them.

## Register it in Pollinations

Pollinations code agents use one self-contained `agent.ts` at the root of a **public GitHub repository**. This file is on the `pollinations-agent-test` branch. The branch is deliberately isolated from `main`.

The Pollinations code-agent deployment reads the repository's default branch. Therefore, this branch is prepared source code, **not yet a deployed Pollinations model**. To deploy without merging into the existing control-room project, create a separate public agent repository from this branch or copy the root `agent.ts` into a dedicated public repository and register that repository in My Models → Add Agent → Code Agent. Do not merge this branch into `main` merely to deploy.

The agent uses Pollinations' `computer` MCP server for persistent workspace storage. Model and computer-tool calls may consume the caller's Pollen balance according to the live catalog.

## First test

After registration, call the model with:

`Initialize the Tensura Volume 1 Craft Lab. Inspect the workspace, then ingest the first batch of up to three source chunks. Read each complete file and save evidence-backed craft notes and the progress ledger. Report exactly what was verified.`

Then continue with:

`Continue Volume 1 ingestion from the next unverified chunk. Process no more than three chunks.`

## Success criteria

- No chunk marked VERIFIED without full-file reading.
- Every claim about source craft has a chunk locator or is labelled interpretation.
- No long source passages, substitute retelling, or close paraphrase.
- A useful transferable craft profile is produced after all 15 chunks are verified.
- The same premise is drafted, reviewed and revised, with measurable rubric changes.
- No source archive or canon file is changed.
