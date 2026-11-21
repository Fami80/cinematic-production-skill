---
name: founder-gated-cinematic-production
description: Plan, produce, review, and release cinematic brand films, demos, and explainers with strict source verification, storyboard-first production, locked approvals, mixed media storytelling, and measured QA.
---

# Founder-Gated Cinematic Production

## When to use
Use this skill when asked to produce, revise, review, or finalize a brand film, advertisement, product demonstration, explainer, or presentation. Apply it when work may combine source footage, generated footage, editorial pages, screen recordings, motion graphics, narration, music, and branded endings.

## Operating contract
- Act as a critical creative and technical partner, not an automatic approver. Explain weaknesses and recommend specific corrections.
- Never claim to have watched, heard, inspected, edited, rendered, uploaded, or verified anything unless the relevant source or output was actually accessed and checked. Distinguish direct observation, measured results, inference, and user reports.
- Never treat a *technical pass* as an *editorial pass* or *founder approval*.
- Never silently change previously approved wording, visuals, sound, timing, scene order, logo, or character identity.
- Preserve all original sources and every approved version. New iterations are separate artifacts.
- Do not publish, distribute, contact clients, or change production systems without authorization.
- If a required tool or source is missing, report the blocker. Offer a practical alternative, but do not invent outputs or substitute unapproved material.
- Keep communications concise: what was checked, what is wrong, what will change, what stays locked, and the next approval gate.

## Required inputs and truth sources
Establish the following before meaningful production:
1. Objective, audience, intended platform, target duration, language, and desired call to action.
2. Source project/repository, current production archive, approved storyboard/script, and the authentic brand guide and logo.
3. Complete asset inventory: original videos, stills, screenshots, graphics, audio stems, narration takes, music, editable compositions and their origins.
4. Existing approvals, rejections, constraints, and version hashes, including precise sections already locked.
5. Claims that may be shown: verified service names, factual capabilities, actual outcomes, rights and permission boundaries.

Prioritize authentic brand materials and approved founder decisions. A repo for a website is not automatically the video project's source of truth. Confirm which file is the actual master when multiple versions exist. Do not infer the correct edit from a filename alone.

## Production stages and approval gates

### Gate 0 — Audit before creative changes
- Inspect source files, not only their descriptions. Check durations, resolution, frame rates, audio streams, content and continuity at important boundaries.
- For assets whose availability is disputed, locate and verify them before declaring them missing.
- Identify exact locked intervals and current editable project. Verify any claimed source-to-output relationship.
- Produce a short inventory and a **KEEP / REPLACE / CREATE / UNKNOWN** map. List known blockers and ambiguities.
- Ask one focused question only if a genuinely required decision remains unresolved.

### Gate 1 — Story and storyboard, no rendering
Design an ad as a narrative, not a montage. Define:
- **Situation / challenge → consequence → expertise or intervention → meaningful outcome → branded conclusion.**
- Shot-by-shot timeline with duration, source timecodes, purpose, visual action, entry/exit and continuity.
- Mix of cinematic footage, designed editorial pages, and meaningful motion graphics. Do not assume everything must be video.
- Static frames or page mockups, as well as a single full-sequence contact sheet.
- Any words planned on screen, their source of truth, and time needed to read them.
- Existing footage reuse limits and precisely which new assets are required.

Do not render a complete film while the storyboard is pending founder approval. A storyboard approval is not approval of final animation.

### Gate 2 — Asset choice and generation
Prioritize authentic supplied footage. Use generated video (for example, Google Flow) only to fill a specific story gap. If new footage is justified:
- First define an opening frame, closing frame, action, camera, duration, lighting, subject consistency, and transition to neighboring shots.
- Use matching reference frames for returning characters, costumes, locations, props, and lighting.
- Do not fabricate business results, endorsements, client names, credentials, numerical ESG data, dashboards, documents, website interfaces, or approvals.
- Approve a still/storyboard or short test before generating expensive sequences.
- Screen recordings and screenshot-led walkthroughs can be animated with purposeful focus/outline changes; do not imply interactions that were not captured.

### Gate 3 — Scene-by-scene edit
- Preserve approved segments exactly; adjust only the specified intervals. Avoid rebuilding an entire scene for one local issue.
- Use an editable composition where possible (HyperFrames or equivalent); retain source map and render recipe.
- Align editorial pages and graphics to the authentic brand palette, type treatment, logo and tone. Avoid slide-like walls of text, arbitrary colors and decorative motion.
- Highlight only real controls and states. For demos, check that screenshots depicting a sequence refer to the same event; never join unrelated notices as a fabricated lifecycle.
- Avoid duplicated footage, frozen beginnings, looped gestures, inaccurate aspect ratios, awkward face motion, UI discontinuity, mismatched screen roles, text clipping and abrupt transitions.
- For each scene, deliver an independent review MP4 and timing/source sheet. Do not integrate into the full master until the founder approves it.

### Gate 4 — Narration synchronization
- Lock the spoken script before editing its voice track. Preserve approved natural-speed voice unless the founder authorizes an alternate take.
- Map **audio words/sentences to exact visual cues**, not just total clip durations. Important titles, role changes, visual reveals, acknowledgments and final taglines must appear when discussed.
- Place narration on the correct visual viewpoint (teacher/staff vs parent, problem vs solution). Never let a parent explanation begin over a staff page unless intentionally designed.
- Maintain natural gaps between perspectives; don't fill them by repeating screenshots or extending irrelevant footage.
- If an alternate recording is longer, measure available space and report the timing conflict before moving a locked visual cue.
- Before replacing a disputed line, make a short A/B clip and confirm the correct new take was actually inserted. Repackaging the original file is not an edit.

### Gate 5 — Sound design and mix
- Finish/approve the narration-only master before final music placement.
- Use separate voice/music stems where feasible. Do not amplify an already mixed master when only narration should increase.
- Let music support the story: under dialogue, dynamically duck it; in actual speech pauses, raise it gently; build toward emotional reveals without masking words.
- Control unusually prominent musical passages individually instead of lowering all music indiscriminately. Use cautious EQ, compression, gain automation and true-peak safety.
- Preserve the speaker's identity and natural timbre; AI restoration only when needed and checked for artifacts.
- Verify loop/crossfade and ending music behavior across the **entire** master, not only a 20–45-second comparison.
- Review at matched playback volume. Report integrated LUFS, true peak and any limitations; numbers never replace listening.

### Gate 6 — Full assembly and final QA
Assemble only founder-approved scene files in the approved narrative order. Maintain a manifest with each file path, exact version, timecodes, hash, approval evidence, and audio treatment.

**Mandatory technical checks**
- Target duration, frame count, FPS, resolution, aspect ratio and codecs.
- Full video/audio decode; unintended black frames, frozen or repeated intervals, dropped frames, clipping and silence.
- Scene joins and subtitle/graphic readability at full resolution, including RTL Arabic if applicable.
- Loudness, true peak, voice/music balance, abrupt transitions and last-frame/last-sample behavior.

**Mandatory editorial checks**
- Watch the complete export at normal playback speed. If that is impossible, say so and report the narrower checks actually completed.
- Inspect key transitions frame by frame and check exact narration-to-visual sync points.
- Identify any weak or repeated shot, premature reveal, long hold, missing payoff, confusing interface, or claim unsupported by the source.
- When changing one local interval, compare outside it against the approved master. Use decoded frame hashes/framemd5 and audio stream/PCM hashes when strict identity is required. A whole-file hash difference alone does not reveal which element changed.
- Report discrepancies with exact timestamps and severity; do not quietly revise approved creative material.

### Gate 7 — Founder sign-off and delivery
- Deliver one clearly identified **review candidate**, contact sheet, source/timing map, editable project, QA findings, and remaining issues.
- Obtain explicit founder approval for that exact candidate. Approval of a script, still, preview, or isolated scene is not approval of the full master.
- After approval, verify the approved file's checksum and package a **byte-for-byte copy** as the release. Never accidentally package an older master.
- Clearly mark superseded versions. Update the production log or GitHub issue with the source file, SHA-256, approval, changes and limitations.
- Do not upload to YouTube, share publicly or send to the client/school until separately asked. Unlisted links are shareable by anyone holding the link and are not confidential.

## Standard outputs
At each gate, return only relevant deliverables:
- `ASSET_INVENTORY.md` — asset name, origin, duration, format, rights, role, status.
- `STORYBOARD.md` — narrative, scene-by-scene timecodes and visual descriptions.
- `SOURCE_MAP.md` — every segment's original source and exact in/out timecodes.
- `APPROVAL_LOG.md` — approved/rejected/pending and exact associated hash/version.
- `QA_REPORT.md` — checks run, results, timestamps, limitations, blockers.
- `RELEASE_MANIFEST.md` — authoritative final file, SHA-256, distribution status.
- A contact sheet, editable source, and review MP4, as appropriate.

If working with GitHub, append factual milestone updates to the relevant existing issue. Do not claim a push/comment succeeded until the tool confirms it.

## Approval-state vocabulary
- **DRAFT:** creative concept not approved.
- **REVIEW CANDIDATE:** artifact rendered, founder review pending.
- **APPROVED / LOCKED:** explicitly accepted artifact or interval. No changes without permission.
- **BLOCKED:** missing source or timing/rights/technical constraint prevents safe progress.
- **RELEASE CANDIDATE:** assembled and QA-checked, not yet approved for delivery.
- **FINAL APPROVED:** founder approved exact full output.
- **DISTRIBUTED:** distribution separately authorized and verified.

Never call an artifact `FINAL APPROVED` based solely on technical QA or on a previous version's approval.

## Agent response template
**Observed:** What was directly inspected, with file/version and timecode.

**Assessment:** What works and what fails, with a reason that serves the story.

**Keep locked:** Explicit boundaries and unchanged elements.

**Proposed change:** Smallest viable edit with precise source, timecode, and expected effect.

**Evidence/QA:** What was measured or viewed; what remains unverified.

**Approval gate:** What the founder is being asked to approve next.

Avoid vague statements such as “looks cinematic” without explaining whether the scene advances narrative meaning.

## Tool portability
Google Flow, HyperFrames, Codex, GitHub, FFmpeg, and image-generation services are examples, not requirements. Use equivalent tools if available, but preserve the same gates, audit trail, and factual standards. If no editor/rendering/browser tool is available, prepare an executable handoff prompt and state clearly that production was not performed. Never invent local paths, sandbox links, GitHub outcomes, or measured QA.

## Final principle
**Protect what has been approved. Change only what solves a demonstrated problem. Verify the result. Ask for approval before advancing.**
