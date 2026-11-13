# KNOWLEDGE BASE SCHEMA — THE WEAKEST GOD
> WORKFLOW LADDER: 00 Control → 01 Source → 02 Chronology → 03 Continuity → 04 Character state → 05 AU integration → 06 Arc → 07 Chapter → 08 Draft → 09 Review → 10 Audit → 11 Presentation → 12 Revision → 13 Approval → 14 Canon → 15 Improvement.
> FILE POSITION: Stages 01–05. PURPOSE: Define source-grounded structured research. PREREQUISITES: Source map and chunk protocol. REQUIRED ACTIONS: Stable IDs, provenance, time-state, uncertainty, canon labels. STATUS: Schema defined; no research records are falsely claimed. COMPLETION EVIDENCE: Entity definitions below. NEXT: Process actual source chunks.

## Rules
- Every source fact points to an exact repository, branch, path and chunk/page/section locator where available.
- Separate source fact, AU fact, inference, proposal, secret and unresolved contradiction.
- Keep original source text immutable.
- Track when facts become true and when each character can know them.
- Preserve corrections as superseding records; do not silently erase history.
- Never invent page numbers or source citations.

## Entities
**SourceChunk:** source_id, repo, branch, path, volume, chunk_number, page_range, hash_if_available, ingestion_state, read_evidence, previous_boundary, next_boundary.
**Event:** event_id, source_refs, chronology_position, participants, location, preconditions, event_fact, causes, outcome, consequences, setup_payoffs, certainty, canon_layer.
**Character:** character_id, name, source_refs, appearance, personality, voice, motives, abilities, limits, relationships, secrets, status.
**CharacterTimeState:** state_id, character_id, valid_from/to_event, appearance, available_abilities, injuries, equipment, location, goals, knowledge_ids, relationship_state, source_refs, confidence.
**KnowledgeClaim:** knowledge_id, character, claim, learned_at_event, method (witnessed/told/inferred/remembered/secret), confidence, source_refs, secret_flag, first_permitted_use.
**Ability:** ability_id, name, owner, canon_layer, first_known_event, function, activation, cost, limits, counters, evolution, source_refs, uncertainty.
**Location:** location_id, name, description, geography, environment, rules, connected_events, source_refs.
**Relationship:** relationship_id, characters, valid_from/to_event, type, trust, tension, knowledge_between, interaction_evidence, canon_layer.
**Divergence:** divergence_id, source_event, AU_change, cause, affected_characters, changed_outcomes, downstream_consequences, approval_status, decision_ref.
**Uncertainty:** uncertainty_id, question, conflicting_evidence, interpretations, confidence, resolution_status, requires_author_decision.
**ChapterPacket:** packet_id, chapter_id, purpose, source_range, read_ahead, timeline, POV, cast, knowledge_constraints, scene_goals, conflicts, turns, consequences, continuity_risks, approval_status.
**Draft/Audit/Approval:** version identity, repository path, commit/ref if available, audit findings, reviewer, exact approved version, approval evidence, canon promotion target.

## Suggested library layout
source_catalog / events / characters / character_states / knowledge / abilities / locations / relationships / divergences / uncertainties / chapter_packets / continuity / audits / execution.

A linked Markdown library in Dropbox or GitHub is a structured knowledge library, not automatically a database. Do not claim SQLite, embeddings, vector search, or live retrieval unless an actual database and query mechanism exist.