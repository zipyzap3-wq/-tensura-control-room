# KNOWLEDGE BASE SCHEMA — THE WEAKEST GOD / VOLUME 1 CRAFT DATABASE

> WORKFLOW LADDER: 00 Control → 01 Source intake → 02 Chronology/craft extraction → 03 Continuity → 04 Character state → 05 AU integration → 06 Arc → 07 Chapter → 08 Draft → 09 Review → 10 Audit → 11 Presentation → 12 Revision → 13 Approval → 14 Canon → 15 Improvement.
> FILE POSITION: Stages 01–05. PURPOSE: Define structured, provenance-linked records stored in Dropbox and used by the unified skill. PREREQUISITES: SOURCE_LIBRARY_MAP.md and DROPBOX_DATABASE_SPEC.md. REQUIRED ACTIONS: Stable IDs, exact provenance, state separation, uncertainty, and verified ingestion. STATUS: Schema defined; no records or ingestion are falsely claimed. NEXT: Create the Dropbox root after confirmation, then process Volume 1 chunks.

## Core integrity rules
- Every source-derived record points to exact repository, branch, path, chunk, and page/section locator where available.
- Keep source text immutable and outside the derived-notes database; the database stores concise analysis and structured facts, not full copyrighted source chunks.
- Separate direct source observation, interpretation, AU fact, inference, proposal, secret, and unresolved contradiction.
- Track when a fact becomes true and when each character can know it.
- Keep Volume 1 craft observations separate from Volume 6/7 story facts and AU canon.
- Corrections supersede prior records without silently erasing history.
- Never invent page numbers, read states, source citations, or approvals.

## Record types
**SourceChunk:** source_id, repo, branch, path, volume, chunk_number, page_range, source_hash, ingestion_state, read_evidence, previous_boundary, next_boundary.
**CraftObservation:** craft_id, source_refs, locator, craft_domain, observation, abstract_principle, interpretation, confidence, uncertainty, originality_guard.
**CraftProfile:** profile_version, source_coverage, scene_architecture, dialogue_functions, humour_mechanics, POV, exposition, action_clarity, emotional_rhythm, transitions, serial_structure, test_results.
**Event:** event_id, source_refs, chronology_position, participants, location, preconditions, event_fact, causes, outcome, consequences, setup_payoffs, certainty, canon_layer.
**Character:** character_id, name, source_refs, appearance, personality, voice, motives, abilities, limits, relationships, secrets, status.
**CharacterTimeState:** state_id, character_id, valid_from/to_event, appearance, available_abilities, injuries, equipment, location, goals, knowledge_ids, relationship_state, source_refs, confidence.
**KnowledgeClaim:** knowledge_id, character, claim, learned_at_event, method, confidence, source_refs, secret_flag, first_permitted_use.
**Ability:** ability_id, name, owner, canon_layer, first_known_event, function, activation, cost, limits, counters, evolution, source_refs, uncertainty.
**Location:** location_id, name, description, geography, environment, rules, connected_events, source_refs.
**Relationship:** relationship_id, characters, valid_from/to_event, type, trust, tension, knowledge_between, interaction_evidence, canon_layer.
**Divergence:** divergence_id, source_event, AU_change, cause, affected_characters, changed_outcomes, downstream_consequences, approval_status, decision_ref.
**Uncertainty:** uncertainty_id, question, conflicting_evidence, interpretations, confidence, resolution_status, requires_author_decision.
**ChapterPacket:** packet_id, chapter_id, purpose, source_range, read_ahead, timeline, POV, cast, knowledge_constraints, scene_goals, conflicts, turns, consequences, continuity_risks, approval_status.
**DraftAuditApproval:** version_identity, repository_path, commit/ref, audit_findings, reviewer, exact_approved_version, approval_evidence, canon_promotion_target.
**ExecutionRecord:** run_id, task_scope, workflow_stage, actions, artifacts, blockers, next_action, user_approval_state.

## Dropbox layout
- 00_CONTROL/README_AND_DATABASE_STATUS
- 01_SOURCE_CATALOG/VOLUME_01
- 02_CRAFT_ANALYSIS/CHUNKS
- 03_CRAFT_PROFILE
- 04_STORY_SOURCE_MAPS
- 05_EVENTS_AND_CHRONOLOGY
- 06_CHARACTERS_AND_TIME_STATES
- 07_KNOWLEDGE_AND_ABILITIES
- 08_LOCATIONS_AND_RELATIONSHIPS
- 09_AU_DIVERGENCES_AND_UNCERTAINTY
- 10_CHAPTER_PACKETS_AND_DRAFT_INDEX
- 11_AUDITS_AND_APPROVALS
- 12_EXECUTION_AND_HANDOFFS

Use Markdown/CSV/JSON/Paper records as supported by the connected Dropbox surface. A linked Markdown knowledge library is structured and searchable but is not SQLite. Do not claim SQLite, embeddings, vector search, automatic sync, or live query support unless an actual implementation is created and tested.
