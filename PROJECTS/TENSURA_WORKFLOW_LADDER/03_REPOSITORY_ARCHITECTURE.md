> # WORKFLOW LADDER | TENSURA CLEAN-SLATE PROJECT
> **Workflow version:** 1.0.0 | **Project status:** setup / non-canon | **Authority:** PROJECTS/TENSURA_WORKFLOW_LADDER/01_MASTER_WORKFLOW_LADDER.md
> **MANDATORY:** Read this block first. Identify this file's exact stage, satisfy prerequisites, record evidence, then follow its named next destination. Never skip a gate because memory or a summary seems sufficient.
> **FULL LADDER:** 00 Project control → 01 Source intake and verification → 02 Source chronology/event mapping → 03 Canon and continuity examination → 04 Character/time-state research → 05 AU integration and story direction → 06 Arc planning → 07 Chapter planning/scene outline → 08 GitHub first draft → 09 GitHub self-review/correction → 10 matching ChatGPT polished draft → 11 independent second audit → 12 workflow-path/evidence verification → 13 user review/approval → 14 canon promotion only after explicit approval → 15 self-evolution and preventive-rule integration (feedback also runs after stages 09, 11 and 12).
> **FILE POSITION:** See file-specific fields immediately below.
> **GATE:** Do not mark a stage complete without concrete evidence. If blocked, stop and record the blocker.

**File ID:** TWL-003 | **Stage:** 00 | **Status:** ACTIVE
**Purpose:** Define the clean-slate project directory inside Central Control Room.
**Prerequisites:** Master ladder and branding standard.
**Required actions:** Keep all new story material under this root; separate source, research, plans, drafts and canon.
**Completion evidence:** Directory tree exists and register maps each created file.
**Next destination:** 04_SOURCE_MATERIAL/README.md | **Next action:** Verify source inventory and imported set.

# Repository Architecture
Project root: PROJECTS/TENSURA_WORKFLOW_LADDER/

## Directory plan
- 04_SOURCE_MATERIAL/VOLUME_01 through VOLUME_07: preserved copied source chunks with provenance banners.
- 04_SOURCE_MATERIAL/SOURCE_COVERAGE_MATRIX.md, SOURCE_CHRONOLOGY.md, SOURCE_UNCERTAINTY_LOG.md.
- 05_PROJECT_AUTHORITY: canon authority, decisions, approval register.
- 06_RESEARCH/CHARACTER_DOSSIERS: one authoritative master sheet per major AU character (identity, abilities, capability rules, future growth and user idea inbox); dossier index; TIME_STATE_CARDS; knowledge matrix.\n- Character ability/capability descriptions live ONLY in master character sheets. Arc plans and chapter packets link to ability IDs and scene-local state instead of duplicating specs.
- 07_PLANNING/ARC_PLANS and CHAPTER_PACKETS; chapter planning template.
- 08_DRAFTS/CHAPTER_###: GitHub draft, first review, second audit, workflow path map.
- 09_CONTINUITY: timeline, character state, knowledge, relationships and open threads.
- 10_WORKFLOW_IMPROVEMENTS: self-evolution loop, improvement register and changelog.
- 11_TEMPLATES: file ladder, chapter packet, draft, review and path-map templates.
- 12_EXECUTION: checkpoint, file ladder register and session log.
- 13_REUSABLE_CRAFT: LSM master protocol, Character Forge and Living Appearance Method.

## Character-data organization (mandatory)\n- Each major AU character has one master character sheet under 06_RESEARCH/CHARACTER_DOSSIERS/.\n- The sheet is sole authority for full ability lists, capability descriptions, costs/limits, unlocks, growth plans, user ideas and open decisions.\n- Capture user ideas in the sheet's idea inbox first, then route them to affected plans.\n- Arc plans describe plot beats, not full power descriptions. Chapter packets use only time-state and link the sheet.\n- Never scatter a capability across files or rely on chat memory.\n\n## Isolation
This is a self-contained workspace. Do not import old story chapters, old Gobta character sheets, old AU state, old continuity or prior draft material as canon. Volumes 1-7 are source references only. Source reading and chronology must cover Volumes 1-7 in order; older volumes establish earlier character states and world events. Reusable craft methodology may be adapted without story-specific assumptions. Do not overwrite parent dashboard/LSM files. Work on existing main branch; no new branch is requested.


## Character-state dossier architecture (mandatory)
- Maintain a separate evolving dossier for every recurring/consequential canon or AU character, not just Gobta. One stable file per character plus a dossier index.
- Each dossier records current appearance, personality/attitude, voice, powers/skills/resistances/equipment/feats/limits, motives, opinions of individuals (especially Gobta), knowledge/beliefs/secrets, last interaction remembered, emotional takeaway, relationship stage and its evidence, and chapter-by-chapter state history.
- Gobta is the fused reincarnated protagonist; other characters' views and memories must reflect the person he is now, not assume he is baseline Gobta.
- **Approval-gated update:** Every chapter creates a provisional affected-character update queue. Only after the user explicitly approves that chapter do we apply dossier/knowledge/relationship/continuity updates. Approval completion includes those updates and the index/register/checkpoint as applicable. Unapproved drafts remain provisional.
- At the start of later chapter planning, consult relevant dossiers to preserve power/time-state accuracy, established interactions, recollections, changed relationships, callbacks and canon character voice.
- Full abilities of Gobta live in his master character sheet; character-state dossiers track what each character currently has/knows and what is established in-story. Keep canon-source facts separate from AU changes and inference.
- Chapters may be source-chunk adaptations or original bridge/custom chapters between consecutive source chunks. The route is strictly sequential: finish the applicable chunk/event endpoint → optional AU bridge chapter(s) → resume at the immediate next source chunk's beginning. No jumping chunks, rearranging canon events or arbitrary insertion. Record bridge placement and its handoff anchors in chronology/arc plan.
- Canon dialogue: retain source dialogue verbatim when it still fits the altered situation and character knowledge. Change/add only where AU circumstances, Gobta's presence, causal logic, voice or continuity actually require it. Do not rewrite dialogue just to make it different; do not blindly preserve dialogue contradicted by the AU. Track source dialogue provenance and adaptation rationale.
