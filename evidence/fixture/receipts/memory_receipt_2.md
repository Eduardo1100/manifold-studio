# Memory Receipt: Keep the product legible in the final beat.

Skill ID: skill_demo0001
Entry kind: Accepted memory
Entry ID: mem_demo0002
Status: active
Polarity / type: preserve

## Summary

Keep the product legible in the final beat.

## Source IDs

- Template: tmpl_demo0001
- Prompt batch: batch_demo0001
- Prompt: prompt_demo0001
- Candidate: cand_demo0001
- Artifact: Not recorded
- Feedback: fb_demo0001
- Proposal: memprop_demo0002

## Provenance Chain

- Template (tmpl_demo0001): Default candidate prompt template
- Prompt batch (batch_demo0001): Develop three visual concepts for a 16-second launch film for a new citrus fragrance. No dialogue or on-screen text. Each concept should feel tactile, premium, and feasible to shoot, with one clear visual idea.
- Prompt (prompt_demo0001): Macro on a chilled bottle: condensation beads gather, merge, and run, dragging a clean line down the frosted glass. A thumb of orange peel flexes just off-axis and throws a fine mist across the light. Shallow depth, slow push, cold blue-green key.
- Candidate (cand_demo0001): feedback_added
- Artifact: missing
- Feedback (fb_demo0001): The condensation run is the whole idea -- one physical change I can actually shoot, and the beading reads expensive. But the bottle is never legible; I get texture and no product. Keep the transformation, end on the bottle.
- Proposal (memprop_demo0002): Keep the product legible in the final beat.

## Raw Ledger Fields

```json
{
  "content": "Keep the product legible in the final beat.",
  "copy_policy": "reference_only",
  "created_at": "2026-01-01 00:00:44",
  "id": "mem_demo0002",
  "memory_type": "style_dna",
  "negative_fragment": null,
  "polarity": "preserve",
  "project_id": "proj_demo0001",
  "prompt_fragment": "Keep the product legible in the final beat.",
  "scope": "skill",
  "skill_id": "skill_demo0001",
  "source_artifact_id": null,
  "source_candidate_id": "cand_demo0001",
  "source_feedback_id": "fb_demo0001",
  "source_prompt_batch_id": "batch_demo0001",
  "source_prompt_id": "prompt_demo0001",
  "source_proposal_id": "memprop_demo0002",
  "source_template_id": "tmpl_demo0001",
  "status": "active",
  "strength": "soft_preference"
}
```
