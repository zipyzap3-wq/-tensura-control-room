# DROPBOX DATABASE SPECIFICATION — THE WEAKEST GOD

> WORKFLOW LADDER: 00 Control → 01 Source intake → 02 Knowledge extraction → 03 Chronology/craft → 04 Character state → 05 AU integration → 06 Planning → 07 Production → 08 Draft → 09 Review → 10 Audit → 11 Presentation → 12 Revision → 13 Approval → 14 Canon → 15 Improvement.
> FILE POSITION: Stage 00–02 database design. PURPOSE: Define the actual Dropbox destination and records for the Tensura Volume 1 craft database and story knowledge library. PREREQUISITES: User request to build a Dropbox database; source map and knowledge schema. REQUIRED ACTIONS: Create the named Dropbox folder only after explicit confirmation of the exact path; populate it with structured derived records; verify every write. STATUS: Design ready; Dropbox folder and records NOT CREATED. NEXT: Obtain confirmation for the proposed root path, create it, then populate the database.

## Proposed Dropbox root
`/Tensura-The-Weakest-God/`

Proposed database folder:
`/Tensura-The-Weakest-God/Volume-1-Craft-and-Story-Knowledge-Base/`

This location is a proposal until the user confirms and Dropbox returns a successful folder-creation result. Do not claim it exists before then.

## Purpose
A durable, user-owned Dropbox knowledge base for:
- Volume 1 craft-analysis records and the transferable craft profile.
- Exact source inventory and ingestion progress for all 15 Volume 1 chunks.
- Source-linked story facts, chronology, character states, knowledge, abilities, locations, relationships, AU divergences, uncertainty, chapter packets, audits, approvals, and execution handoffs.
- Links back to the authoritative GitHub source and story repositories.

## Database content rules
- Do not copy the full Volume 1 source text into Dropbox. Preserve original source files in GitHub; store concise derived craft observations and structured records in Dropbox.
- Every derived fact has an exact source locator and a confidence/uncertainty field.
- Craft notes from Volume 1 are not AU canon.
- Story facts from Volume 6/7 or Take Two are scoped to the correct project, branch, and timeline.
- Drafts remain non-canon until explicit approval.
- Never store API keys, private credentials, or account secrets.
- Do not publish public Dropbox links to bridge Pollinations' lack of access to the user's private Dropbox connector.

## Proposed folder structure
00_CONTROL/
01_SOURCE_CATALOG/VOLUME_01/
02_CRAFT_ANALYSIS/CHUNKS/
03_CRAFT_PROFILE/
04_STORY_SOURCE_MAPS/
05_EVENTS_AND_CHRONOLOGY/
06_CHARACTERS_AND_TIME_STATES/
07_KNOWLEDGE_AND_ABILITIES/
08_LOCATIONS_AND_RELATIONSHIPS/
09_AU_DIVERGENCES_AND_UNCERTAINTY/
10_CHAPTER_PACKETS_AND_DRAFT_INDEX/
11_AUDITS_AND_APPROVALS/
12_EXECUTION_AND_HANDOFFS/

## Population sequence
1. Create the confirmed root and child folders.
2. Add a database README with the exact returned Dropbox path and source authority links.
3. Add the Volume 1 source catalog and progress ledger with all 15 chunks QUEUED.
4. Ingest at most three chunks per user-requested batch; read complete files, extract craft observations, boundary-check, reconcile, and verify.
5. After all 15 chunks are verified, synthesize the craft profile and run original-scene evaluation.
6. Add story-source maps and any story records only when the relevant story sources have actually been read.
7. Reconcile Pollinations runtime notes into Dropbox using the connected Dropbox app; log each transfer and verify it.
8. Keep this database separate from the story repository's approved canon files.

## Actual capability boundary
A folder of structured Markdown/CSV/JSON/Paper files is a Dropbox knowledge database, but not automatically SQLite or a vector database. Use those labels only if a real database engine/index is created and tested. Pollinations Computer storage is not Dropbox and must not be described as such.
