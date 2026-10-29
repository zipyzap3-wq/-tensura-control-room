# Living Story Method: Project Adapter
**Applies to:** Tensura Control Room dashboard  
**Method version:** LSM 1.0.0

## Scope
This repository is a workflow dashboard, not the story archive itself. Use the Living Story Method to improve the writing prompts, checklist language, chapter-planning fields, and narrative quality guidance that the dashboard presents. The actual story repository remains the authority for canon and continuity.

## Dashboard-facing principles
- Distinguish a scene's viewpoint, goal, conflict, turn, consequence, and unresolved thread.
- Make POV selection and viewpoint switches explicit fields in planning prompts.
- Keep character knowledge, relationship changes, and continuity checks visible.
- Label examples/placeholders as examples, never as verified story facts.
- Keep prompts compact enough to be useful on a phone and exportable as clean text/JSON.
- Keep user notes, local-storage behavior, and the dashboard's capabilities accurately described.

## Hard guardrails
Do not treat this dashboard as automatically connected to the story repository. Do not copy private story drafts into it without explicit need and authorization. Do not alter application code solely because the writing method exists; apply the method to narrative-facing functionality when the code is deliberately being worked on.

## Prompt checklist
A generated chapter prompt should remind the writer to read the actual previous chapter, check canon and character knowledge, choose POV, plan scene changes, preserve approved decisions, and run a continuity review.

## Character creation and appearance modules
Before creating or substantially revising a major or recurring character, read:
- `WRITING_METHOD/ENGINES/CHARACTER_FORGE.md`
- `WRITING_METHOD/ENGINES/LIVING_APPEARANCE_METHOD.md`

These are required companion modules to the LSM master protocol, not optional inspiration.

For each newly created major character, produce and maintain:
1. A **Character Forge dossier** covering motives, contradictions, independent agency, goals, worldview, limits, skills, history, relationships, behavior under pressure, voice fingerprint, arc, narrative function, and continuity.
2. A **Full Appearance Dossier** with concrete physical details and stable visual anchors.
3. A **Reader-Facing Description** that introduces the character naturally through the active viewpoint, not as a pasted checklist.
4. A **Visual Reference Specification** for consistent illustrations or image generation when visual references are useful.

Do not leave appearance at generic labels such as “handsome,” “beautiful,” “sharp eyes,” or “black hair.” Define facial structure, hair construction and texture, body proportions, complexion, movement, wardrobe, distinguishing features, and continuity locks at the level appropriate to the project. Do not invent details that contradict source canon or locked project facts. Mark unknowns as unknown rather than silently deciding them.

Use full dossiers as reference material, not as prose to dump into a chapter. Reveal details selectively through the viewpoint character's attention, action, proximity, and scene purpose. Track outfit, injury, grooming, transformation, and other temporary or permanent changes across chapters. Project canon, user-approved designs, source-canon constraints, and existing character locks override generic craft advice.
