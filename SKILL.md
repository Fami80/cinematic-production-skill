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
- Identify the exact *reviewed artifact*: filename, path, SHA-256, duration, render version, and relevant timestamps. GitHub descriptions, screenshots, or an editable project can disagree with the actual exported MP4.
- Maintain a shot-level approval ledger with **source file, source in/out, output in/out, approval state, approval evidence, and any restrictions**. Asset approval does not imply every excerpt or variation is approved.
- Preflight every proposed output segment against that ledger. **Rejected assets and intervals must fail the build**, even when they remain in an old timeline, cache, or referenced project. Unknown or pending shots can appear only in clearly labeled exploratory previews, never as silently approved material.
- Ask one focused question only if a genuinely required decision remains unresolved.

### Choose the visual grammar for the actual business goal
Before committing to a mixed-media formula, determine what the film needs the audience to do:
- **Product demonstration or instruction:** interface recordings, screenshot-led steps, annotation, editorial pages, and precise narration-to-action sync can carry the story.
- **Consultancy, reputation, or brand advertising:** prioritize authentic moving footage, human expertise, place, emotion, and narrated meaning. Use graphics and titles sparingly; let voiceover explain services while footage keeps moving.
- Do not apply a previous project's visual recipe blindly to a new industry, buyer, or audience. An attractive capability diagram may fit a website or long explainer but interrupt a 45–50-second cinematic advertisement.
- Brand and tagline can appear **over live moving footage** if contrast, safe margins, legibility, and logo integrity are preserved. A blank-color end card is not mandatory.
- When the creative premise materially changes (for example, introducing a new opening shot), revisit previously proposed *structural* locks with the founder. Never silently violate an approved interval, but don't preserve an obsolete storyboard structure merely because an earlier draft assumed it.
- Treat percentages such as "mostly footage" as creative targets, not universal QA rules. Assess pacing, credibility, and narrative progress before adding explanation screens.

### Audience comprehension gate for service-led short films
- Define what an unfamiliar target buyer must be able to explain after the opening, rather than judging the film only on cinematic polish. For a service-led commercial, test three questions: **What does this company do? What problem can it solve? How can it help my business?**
- Set explicit, project-specific comprehension checkpoints. A useful brief for a ~40–50-second service advertisement is: identify the core service within the first **10–15 seconds**, communicate the relevant problem and mechanism of help by **30 seconds**, then use the remaining time for credibility, memorability, and a clear next action. Treat these timings as a brief-specific target, not a universal runtime formula.
- Lead with verified buyer-relevant meaning. Atmospheric location or brand imagery can stay when it reinforces the message, but it must not postpone the first concrete explanation of the offer. Avoid vague lines that fit any consultancy (for example, generic promises of a sustainable future) in place of specific, substantiated services.
- Write an **audience-comprehension map** alongside the storyboard: at each checkpoint, list the exact spoken/on-screen evidence that answers each buyer question and the footage reinforcing it. Flag any question answered only by implication or by a late end card.
- When revising an approved cinematic master for clarity, audit and reuse existing approved shots, narration, music, logo and editable timeline first. Present a **minimal-change comparison** (KEEP / RETIME / REVOICE / REPLACE / CREATE) and the resulting timing map before rendering or modifying locked material. No general instruction to improve comprehension overrides existing founder approval gates.
- For informal validation, show the candidate without explanation to people representative of the audience, stop at the prescribed checkpoint, and ask the three open questions. Record responses and note whether they accurately identify the offer; a small test is directional feedback, not a statistically valid comprehension percentage.
- Score **cinematic craft** and **buyer comprehension** separately. Technical QA, beautiful imagery, or the founder's familiarity with the business do not demonstrate that a first-time viewer understands the offer.

### Gate 1 — Story and storyboard, no rendering
Design an ad as a narrative, not a montage. Define:
- **Situation / challenge → consequence → expertise or intervention → meaningful outcome → branded conclusion.**
- Shot-by-shot timeline with duration, source timecodes, purpose, visual action, entry/exit and continuity.
- Mix of cinematic footage, designed editorial pages, and meaningful motion graphics. Do not assume everything must be video.
- Static frames or page mockups, as well as a single full-sequence contact sheet.
- Any words planned on screen, their source of truth, and time needed to read them.
- Existing footage reuse limits and precisely which new assets are required.

Do not render a complete film while the storyboard is pending founder approval. A storyboard approval is not approval of final animation.

### Brand-asset provenance and archival
- Verify the **actual artwork**, not merely its filename. A historical, client-internal filename can be misleading; record explicit founder/brand-owner confirmation before accepting or rejecting logo identity.
- Distinguish a committed image binary from a JSON manifest, asset-storage pointer, favicon, thumbnail, or screenshot. A reference alone is not a usable original logo file.
- Archive founder-confirmed original SVG/PNG artwork in a discoverable dedicated brand-assets folder when authorized. Keep originals byte-for-byte unchanged; produce transparent-background, recolored, or video-optimized derivatives separately and label their approval status.
- Prefer scalable vector artwork for large-screen branding. Before compositing, inspect transparency, white background rectangles, color profiles, and contrast against the actual moving end-frame, not a generic swatch.
- Document origin, filename, rights/approval evidence, intended usage, and any still-missing binary. Never claim both formats were uploaded if only one was verified.

### Gate 2 — Asset choice and generation
Prioritize authentic supplied footage. Use generated video (for example, Google Flow) only to fill a specific story gap. If new footage is justified:
- First define an opening frame, closing frame, action, camera, duration, lighting, subject consistency, and transition to neighboring shots.
- Use matching reference frames for returning characters, costumes, locations, props, and lighting.
- Do not fabricate business results, endorsements, client names, credentials, numerical ESG data, dashboards, documents, website interfaces, or approvals.
- Approve a still/storyboard or short test before generating expensive sequences.
- Screen recordings and screenshot-led walkthroughs can be animated with purposeful focus/outline changes; do not imply interactions that were not captured.
- **Identity continuity is a hard constraint for generated inserts.** Record a reference cast/wardrobe/position map, including exact number of visible people and hands, before generating from a previously approved scene. Inspect the result across the *entire* clip; an accurate first frame does not prove continuity in later frames.
- When a wide generated continuation repeatedly invents extra participants or changes wardrobe, **change the composition instead of repeating the same prompt**. Prefer a motivated detail cutaway (such as hands and an unbranded document) tied to the approved location, while avoiding faces and other elements the model cannot preserve reliably.
- For high-risk generated motion, use a **still-first approval gate**: create and inspect the exact opening image at target composition before spending generation credits. Approval of that still permits only the specified motion test, not integration or release.
- Specify visible-object limits (hands, fingers, participants, props), permitted movement, camera boundaries, and **forbidden emergent content** such as pseudo-text, added charts, logos, or extra limbs. Check for these at multiple timestamps during QA, especially near the end.
- If the output contains defects, test a conservative crop at final delivery resolution before commissioning another generation; reject salvage if it exposes artifacts, loses essential context, or visibly reduces sharpness. A passing technical decode cannot overrule these editorial failures.
- Maintain **asset provenance** when a new generation supersedes another: verify the exact exported binary and project/version before judging it, and withdraw mistaken QA reports rather than transferring their conclusions to the new clip.

### Source-first correction for generated operational footage
- For generated imagery depicting client operations, conduct a **still-image truth-and-credibility gate before motion generation**: inspect PPE and site-role plausibility, authentic identity marks, visible dashboard text, measurements, percentages, warning states, and implied client outcomes. Passing anatomy and full-decode checks does not establish business credibility.
- **Do not remove every label merely to avoid fabricated results**: an empty or abstract monitor can be as implausible as an invented KPI. Prefer a believable facility-owned interface with neutral category labels and status layout, but no asserted client metrics, savings, performance improvements, or unverified system alerts. Keep screen text legible or deliberately non-prominent, not semi-readable nonsense.
- Never synthesize or approximate a client's official logo, including on workwear; either composite the verified brand asset exactly with permission or use unbranded clothing/equipment. A consulting firm's logo does not belong on a customer's facility display without evidence.
- If material branding/data defects originate in a generated **starting frame**, prefer correcting that source still and regenerating the shot over laborious frame-by-frame repair of defective moving footage. Inspect the entire new motion clip for text drift, gestural artifacts and interface mutations, then judge it **inside the full edit** before replacing a locked interval.
- Maintain the approved shot as a fallback until the corrected replacement is explicitly accepted; scope any replacement to its exact timecode and verify unchanged picture/audio outside that interval.

### Motion-tracked document and surface graphics
- Treat text or graphics placed onto a **moving physical surface** (paper, screen, sign, packaging) as a perspective-sensitive composite, not a simple 2D overlay. Translation and uniform scaling are insufficient when the surface tilts, narrows, rotates, bends, or changes foreshortening.
- Before approving the shot, verify stable **four-corner planar/perspective tracking**, correct occlusion by hands or other objects, matching surface texture, lighting, motion blur, and legibility over the **entire intended interval**, especially the moment of strongest angle change.
- Stop and mark the composite **REJECTED** if text drifts, floats, flickers, crosses the paper edge onto the table, or cannot be tracked reliably. A full-decode or black-frame PASS never establishes visual integration.
- Do not conceal a failed track with a rough crop, flat rectangular overlay, or invented data. Test a short diagnostic A/B; if no reliable perspective track is available, use a **separately designed and approved physical detail shot** or the original clean footage instead.
- A distinct document insert must earn its place in the narrative and visually match the neighboring live footage; require a still-first approval gate, truthful non-client-specific wording, and a join review before generating motion or adding runtime.

### Rough-assembly approval and transition audit
- An approved clip or story concept does **not** authorize its neighboring or intervening shots. Before assembly, reconcile every source interval against the approval log; explicitly flag **approved**, **rejected**, **pending**, and **unreviewed** footage. Never slip rejected material into a new assembly.
- Audit each join using the last frames of shot A and first frames of shot B, plus normal-speed playback. Record the exact outgoing/incoming timecodes, camera direction and speed, framing, light, color, subject scale, visual geography, and sound continuity.
- When a cut feels rough, first look for a **better cut point or match-on-action** in the originals. Do not blanket-apply cross-dissolves, speed ramps, zooms or AI transitions to hide incompatible shots.
- Check the film's **story progression after every join**. Jumping from a consultation back to undirected paperwork may feel like narrative regression even if technically clean.
- Preserve the subject and purpose of a shot: a distinctive launch/acceleration should connect to footage with coherent motion direction and apparent velocity; a fast city approach followed by a static or backward-moving view can feel discontinuous.
- At a visual-assembly review, deliver a timestamped **transition audit** listing each seam's KEEP / RETIME / REPLACE recommendation and exact source in/out candidates. Resolve ordinary seam issues in the editable timeline. Make a short A/B preview only when a material issue cannot be resolved from the approved sources and a founder decision is genuinely required before proceeding; do not turn routine editing into repeated preview rounds.
- For every seam, check the **last 0.5–1 second before and first 0.5–1 second after** the cut at both normal speed and frame level. Report motion vector, apparent speed, camera angle, focal scale, horizon/eyeline, subject position, light/color, action continuity, sound bridge, and narrative logic. Use tighter windows for rapid cuts.
- Mark a seam **PASS** only when the change of place, action, camera, and pace feels intentional at normal speed; a technically clean decode is not evidence of smooth editing. Flag unreviewed seams explicitly.
- Distinguish **hard cut, match cut, motivated dissolve, and intentionally disruptive cut**. Choose the least intrusive treatment that serves the story; a dissolve is not a default repair for mismatched geography or motion.
- When the final frames of two approved clips cannot form a credible join, first try other approved source trims and editorial treatments while keeping locked content intact. Ask for a bridge shot or founder decision only when no credible edit is possible from approved material and the unresolved seam materially blocks the film. A founder-approved clip can remain locked while its *placement and neighboring transitions* are revised under review.
- Never call a complete visual assembly “approved” when the founder approved only one component (for example, a centered boardroom interval or falcon transition). Treat remaining joins and questionable source clips as pending until reviewed.

### Shot-to-shot lighting and color continuity before picture lock
- A technically valid, visually strong individual shot does not establish a consistent look across the assembled film. Before picture lock, audit **exposure, highlight and shadow detail, contrast, white balance, color temperature, saturation, skin tones, and brand-color fidelity** at every scene boundary.
- Compare representative frames from both sides of each cut at native and delivery resolution, then assess the transition at normal playback speed. Note the exact timestamps and separate **intentional location/time-of-day contrast** (for example, golden-hour exterior versus cooler industrial interior) from distracting mismatches.
- Use **restrained per-shot adjustments** rather than a single blanket LUT or forcing every environment into the same warmth. Protect natural skin tones, realistic practical lighting, highlight detail, and approved logo/brand colors; do not grade a scene into a different time of day without authorization.
- Prefer correcting the smallest affected source interval in the editable master, keeping approved originals and previous review exports untouched. When changing already-approved imagery, submit an explicit before/after comparison and seek the applicable founder approval before locking the revised picture.
- Treat automated exposure/color metrics as supporting evidence only. A measurement or sampled-frame review cannot substitute for a full normal-speed visual continuity check. Record any playback limitation and leave picture-lock approval pending if required viewing was not possible.
- For picture-first workflows, perform the **full visual continuity and grade review while the film is silent**, before locking the picture; add narration/music only after that gate, unless the founder explicitly changes the workflow.

### Complex-effect feasibility and stop rule
- Before committing to a spatial overlay, tracked service network, or other complex cinematic effect, audit the **actual source resolution, frame rate, camera motion, parallax, occlusion, available tracking/compositing tools, and readable screen time**. A convincing still or keyframed 2D approximation is not proof that the proposed effect can be integrated in motion.
- State the intended **audience takeaway** and the visual action that communicates it. Require a short, normal-speed proof of the hardest technical join (including entry and exit), not just attractive isolated frames, before treating the effect as a viable production direction.
- Set an explicit revision budget and **stop condition** for costly or uncertain treatments. If successive proofs fail on the same fundamental issue, do not keep adding lines, labels, glow, or superficial polish. Reassess feasibility and compare a simpler footage-and-narration approach on buyer comprehension, cinematic credibility, and production risk.
- Preserve failed proofs and their QA as learning evidence, clearly marked **not approved**. Choosing the simpler edit is an editorial decision, not permission to discard the story objective or lower quality standards.
- Once a direction is selected, prioritize **verified service meaning, a natural spoken script, and purposeful shot progression** over further decorative effects. Judge cinematic craft and first-time buyer understanding separately in the complete review candidate.

### Efficient editorial execution
- Avoid open-ended generation, approval, and preview loops. Reuse the available approved material and solve ordinary pacing, cut-point, and transition issues in the edit before considering new footage or another review artifact.
- Keep one editable master timeline as the production source of truth, with source references, timings, and shot-level approval/rejection/pending status. Preserve original media and previously approved outputs; never erase their history or silently reclassify them.
- Make routine editorial choices autonomously within the approved brief: select the strongest usable intervals, trim, order, and join shots, and make minor pacing or continuity adjustments. Do not ask the founder to choose between near-identical technical options. Do not change locked creative content or invent claims, assets, or approvals.
- Make one complete, normal-speed full-sequence visual review the default review deliverable once the edit is coherent. Include the source/timing map and a concise QA summary. Use isolated scene or seam previews only when they answer a specific unresolved question that cannot be decided safely in the master edit.
- Escalate only a substantiated release-blocking issue or a decision reserved to the founder. State the exact asset/version and timestamps, show the evidence and material impact, and summarize reasonable edit-level fixes tried. Record minor imperfections and continue when they do not make the film materially misleading or unusable.
- These efficiency defaults do not waive source verification, locked-asset boundaries, required approval gates, or explicit approval before publishing, distribution, or final release.

### Gate 3 — Scene-by-scene edit
- Preserve approved segments exactly; adjust only the specified intervals. Avoid rebuilding an entire scene for one local issue.
- Use an editable composition where possible (HyperFrames or equivalent); retain source map and render recipe.
- Align editorial pages and graphics to the authentic brand palette, type treatment, logo and tone. Avoid slide-like walls of text, arbitrary colors and decorative motion.
- Highlight only real controls and states. For demos, check that screenshots depicting a sequence refer to the same event; never join unrelated notices as a fabricated lifecycle.
- Avoid duplicated footage, frozen beginnings, looped gestures, inaccurate aspect ratios, awkward face motion, UI discontinuity, mismatched screen roles, text clipping and abrupt transitions.
- Keep scene-level review artifacts available when specifically useful, but do not require a separate MP4 for every scene. A coherent full-sequence review candidate may be assembled in the editable master with pending material clearly labeled and tracked; never describe it as approved or publishable. Do not promote pending material into a release candidate until the applicable approval gate is met.
- Before rendering, produce an **assembly preflight** listing every ordered source excerpt and its approval state. After rendering, inspect whether the export actually contains those excerpts; project timelines and render manifests alone are insufficient.
- Never overwrite the approved previous export. Keep review outputs in uniquely named folders with a traceable source map.

### Gate 4 — Narration synchronization
- Lock the spoken script before editing its voice track. Preserve approved natural-speed voice unless the founder authorizes an alternate take.
- Map **audio words/sentences to exact visual cues**, not just total clip durations. Important titles, role changes, visual reveals, acknowledgments and final taglines must appear when discussed.
- Place narration on the correct visual viewpoint (teacher/staff vs parent, problem vs solution). Never let a parent explanation begin over a staff page unless intentionally designed.
- Maintain natural gaps between perspectives; don't fill them by repeating screenshots or extending irrelevant footage.
- If an alternate recording is longer, measure available space and report the timing conflict before moving a locked visual cue.
- Before replacing a disputed line, make a short A/B clip and confirm the correct new take was actually inserted. Repackaging the original file is not an edit.

### Gate 5 — Sound design and mix
- Finish/approve the narration-only master before final music placement, except where the creative direction explicitly calls for retaining production ambience throughout visual previews.
- Treat **source/environmental audio**, **narration**, **music**, and **sound effects** as separate tracks or intentions. “Silent review” must be defined precisely: no added narration/music is compatible with retaining useful source ambience; do not silently discard an approved falcon, metro, or location sound.
- Audition environmental audio before describing it as wind, wingbeats, bird calls, etc. An embedded audio stream proves only that audio exists, not what it contains. Mark unlistened audio as unverified.
- Build natural audio bridges across visual cuts: trim noise bursts, preserve ambience or introduce a motivated handoff, and use short fades where suitable. Do not let source sound overpower future narration.
- Use separate voice/music stems where feasible. Do not amplify an already mixed master when only narration should increase.
- Let music support the story: under dialogue, dynamically duck it; in actual speech pauses, raise it gently; build toward emotional reveals without masking words.
- Control unusually prominent musical passages individually instead of lowering all music indiscriminately. Use cautious EQ, compression, gain automation and true-peak safety.
- Preserve the speaker's identity and natural timbre; AI restoration only when needed and checked for artifacts.
- Verify loop/crossfade and ending music behavior across the **entire** master, not only a 20–45-second comparison.
- Review at matched playback volume. Report integrated LUFS, true peak and any limitations; numbers never replace listening.

### Gate 6 — Full assembly and final QA
For a **release candidate**, assemble only founder-approved scene files in the approved narrative order. An exploratory rough assembly may contain explicitly flagged pending placeholders solely for founder review. Maintain a manifest with each file path, exact version, source/output timecodes, hash, approval evidence, and audio treatment. Never promote a rough assembly into a release by relabeling it.

**Mandatory technical checks**
- Target duration, frame count, FPS, resolution, aspect ratio and codecs.
- Full video/audio decode; unintended black frames, frozen or repeated intervals, dropped frames, clipping and silence.
- Scene joins and subtitle/graphic readability at full resolution, including RTL Arabic if applicable.
- Assess low-resolution generated source footage at **actual final output resolution** for softness, interpolation artifacts, edge halos, or unnatural detail. Continuous movement may conceal deficiencies but does not automatically make a shot acceptable.
- Verify that the authentic logo asset and permitted service wording are used; placeholders, tiny favicons, and approximate logos are not release assets.
- Loudness, true peak, voice/music balance, abrupt transitions and last-frame/last-sample behavior.

**Mandatory editorial checks**
- Watch the complete export at normal playback speed, **with audio where audio is present**. If that is impossible, say so and report the narrower checks actually completed. Contact sheets and frame sampling cannot certify transitions or sound.
- Report quality on separate axes: **source compliance**, **story/continuity**, **visual/camera QA**, **audio QA**, and **technical integrity**. A PASS in one axis never implies the rest passed.
- Inspect key transitions frame by frame and check exact narration-to-visual sync points.
- Identify any weak or repeated shot, premature reveal, long hold, missing payoff, confusing interface, or claim unsupported by the source.
- When changing one local interval, compare outside it against the approved master. Use decoded frame hashes/framemd5 and audio stream/PCM hashes when strict identity is required. A whole-file hash difference alone does not reveal which element changed.
- Report discrepancies with exact timestamps and severity; do not quietly revise approved creative material.

### Final subtitles, CTA, and asset provenance
- Treat end-card **voice, visible tagline/logo, captions, and call to action as one composition**. If the spoken brand line exactly duplicates an already readable on-screen brand/tagline, omit its redundant burned-in subtitle when approved, while preserving the narration and all earlier captions. Confirm that the CTA is genuinely present, readable long enough, and clear of captions, logo, and platform-safe margins; don't infer its presence from a storyboard.
- Maintain distinct, explicit versions for a **clean master (no narration captions), captioned master, and sidecar subtitle file**. Keep CTA and intrinsic brand text as needed in both videos; compare frame/audio identity outside intentional subtitle differences and check each export independently.
- Record original-generation provenance for AI music and other assets (generator, creator, source file, terms/license evidence and intended use). An unrelated track with the same title is not evidence of third-party authorship; generation provenance does **not** by itself prove exclusive copyright or every commercial-use right. Keep rights-clearance status evidence-based.
- When revising music and effects, compare against the previous mix at **matched playback level** and measure both narration and music-only sections. An acceptable integrated LUFS can conceal a weak music bed; adjust stems and ducking rather than turning up the whole mix. Preserve and verify the locked picture, subtitles, and voice when changing only sound.

### Gate 7 — Founder sign-off and delivery
- Deliver one clearly identified **review candidate**, contact sheet, source/timing map, editable project, QA findings, and remaining issues.
- Obtain explicit founder approval for that exact candidate. Approval of a script, still, preview, or isolated scene is not approval of the full master.
- After approval, verify the approved file's checksum and package a **byte-for-byte copy** as the release. Never accidentally package an older master.
- Clearly mark superseded versions. Update the production log or GitHub issue with the source file, SHA-256, approval, changes and limitations.
- Do not upload to YouTube, share publicly or send to the client/school until separately asked. Unlisted links are shareable by anyone holding the link and are not confidential.

### Platform fit and distribution handoff
- Decide the **primary distribution platform from the intended buyer, message and viewing behavior**, not from video length alone. A polished widescreen business film may be best for a professional feed, site or presentation; don't assume every finished master should become a vertical short.
- Separate **intrinsic video CTA** from **clickable conversion destination**: a concise on-screen action such as "Book a Consultation" can be sufficient when the actual booking link is supplied in the platform post, profile, description, landing page, or ad action. Do not add phone, email and URL overlays merely because an illustrative mockup displays them; test end-frame legibility before modifying a signed-off film.
- For professional-feed launch, prepare platform-specific publication copy and a suitable thumbnail from verified footage, with an authoritative booking destination where available. Upload/distribute **only after explicit separate authorization**; never treat founder approval of the video or a recommended channel as permission to publish.
- Preserve the source film and its release hashes. Treat vertical cutdowns and UGC-style shorts as **separate creative campaigns** with distinct hook, format, narration, caption-safe-area and approval decisions; reuse source footage and quality gates where useful, but don't just crop widescreen footage and call it a short. Capture new platform-specific rules in a companion skill only when grounded in actual production/testing, without duplicating this cinematic skill.

## Standard outputs
At each gate, return only relevant deliverables:
- `ASSET_INVENTORY.md` — asset name, origin, duration, format, rights, role, status.
- `STORYBOARD.md` — narrative, scene-by-scene timecodes and visual descriptions.
- `SOURCE_MAP.md` — every segment's original source and exact in/out timecodes.
- `APPROVAL_LOG.md` — approved/rejected/pending and exact associated hash/version; **shot-level source timecodes**.
- `TRANSITION_AUDIT.md` — each cut's outgoing/incoming frames, motion/sound/continuity findings, verdict, and proposed fix.
- `ASSEMBLY_PREFLIGHT.md` — ordered timeline checked against rejected/pending/approved asset ledger before export.
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

## Continuous skill improvement (standing founder authorization)
The founder authorizes incremental updates to this shared skill when a **verified, reusable production lesson** is identified during active collaboration. Do not wait for separate permission for ordinary quality improvements to the skill itself.

- Add only principles that apply across projects, not a client's confidential facts, raw assets, names, private paths, or temporary creative preferences.
- First verify the lesson against actual reviews, errors, approvals, or QA findings. Distinguish confirmed rules from hypotheses; do not promote guesses to mandatory practice.
- Prefer one targeted, additive change over rewriting existing instructions. Avoid duplicating or contradicting the skill; check current content before editing.
- Use a concise, descriptive commit message and verify the updated GitHub file. Briefly tell the founder what changed and why.
- New skill guidance **never retroactively authorizes production edits**, changes to locked footage, publishing, or client delivery. Existing project-specific approval gates still apply.
- If a proposed skill revision would materially weaken safeguards, authorize external action, expose confidential material, or conflict with a prior directive, request specific approval.
- Updates occur only while the agent is actively handling a task and has the required access; do not imply unattended background monitoring.

### Evidence-first storyboard lesson
- Inspect the **actual frame at each locked-to-editable boundary** before designing the continuation; project files and exports may represent different versions.
- If existing approved footage has exhausted useful report/data shots, **do not recycle them by default** merely to fill a duration. Consider an editorial page, purposeful motion graphic, different authentic shot, or a justified new generated shot.
- Review designed-page concepts as a **contact sheet alongside neighboring live footage**, not as isolated mockups. Check whether they feel cinematic in context or like disconnected slides.
- Distinguish **visual-direction approval**, **motion-prototype approval**, **scene approval**, and **full-release approval**. Each applies only to the artifact and scope actually reviewed.
- A full-resolution logo or identity asset missing from the verified source is a **release blocker**, not a reason to invent a substitute. A clearly labeled placeholder is acceptable only in an explicitly nonfinal prototype.

## End-of-project closure discipline
- When the founder asks to **finish, update the shared skill, and close**, treat these as distinct deliverables: (1) assess the actual final video, (2) record verified reusable lessons in the shared skill, and (3) report an accurate closure status. A skill commit is not a substitute for a visual/audio review.
- Give the founder a direct, evidence-based creative verdict on the **exact exported master**: what looks and sounds strong, what remains weak, and whether it is ready for sign-off. If the export cannot be opened and played, say **visual/audio verdict not completed** and do not imply the film has been watched.
- Verify the canonical skill's repository and file path instead of assuming it lives inside the client's project repository. Do not duplicate the shared skill into a client repository merely to close a task.
- In the final handoff, separate **completed and verified**, **reported but unverified**, and **outstanding** work. Cite the actual skill commit only after confirming the write. Never instruct the founder to start a new chat as a replacement for an unfinished review or skill update.
- Preserve distinctions between clean masters, captioned exports, and watermarked demonstrations; approve and deliver each only for its intended use. Keep derivative changes and checksums traceable without inferring that one export's QA covers another.

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
