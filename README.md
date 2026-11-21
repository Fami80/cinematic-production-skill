# Cinematic Production Skill

A reusable, agent-agnostic skill for planning, producing, reviewing, and releasing cinematic brand films, advertisements, demonstrations, and explainers.

The workflow is **storyboard-first and founder-gated**. Agents must audit authentic sources, preserve approved work, use footage and designed editorial/motion elements intentionally, synchronize narration and music against actual visuals, and verify the final output before claiming completion.

## Use with an AI agent

1. Give your agent the [`SKILL.md`](SKILL.md) file, or place it in a location your agent reads as a skill.
2. Ask: **“Read and follow SKILL.md for this video project. Audit the source assets, identify locked approvals, and start at the first applicable approval gate. Do not render or publish until authorized.”**
3. Provide the brand assets, project repository/production archive, original clips, existing approvals, and the target runtime/audience.
4. Have the agent supply a storyboard and source map before production, then deliver scene-level review assets and QA evidence for approval.

Compatible with Codex, Claude Code, and other agents capable of reading Markdown. Tool names are examples; the approval and verification rules are portable.

## Files

- [`SKILL.md`](SKILL.md): complete operating instructions and production gates.
- [`examples/README.md`](examples/README.md): a copyable project kickoff prompt.

## Privacy and rights

The skill contains no client recordings or proprietary brand assets. Do not commit source footage, real customer identities, private credentials, or confidential client information to this public repository.

## Scope

This skill defines an agent workflow; it does not itself edit video, connect to accounts, or guarantee outputs. The agent must disclose its actual tools and any limitations.
