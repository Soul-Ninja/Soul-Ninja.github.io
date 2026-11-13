---
source_url: "https://killianherzer.com/?ref=onepagelove"
type: design-notes
title: "Reference site design notes (killianherzer.com)"
captured_at: 2026-11-13
---

# Reference site design notes: killianherzer.com

Observed by browsing the site. This is the style reference for Aman Joshi's profile website, not content to copy.

## Concept
- The portfolio is framed as a surveillance / investigation case file. The visitor is an "investigator", the developer is the "subject", projects are "evidence".
- One-page site, listed on One Page Love. FR / EN language toggle.

## Loading screen
- Full-screen boot sequence: "SIGNAL TRACING..." with a large percentage counter (00% to 100%), then "ACCESS GRANTED".
- Animated glowing red oscilloscope waveform across the screen that flattens as loading completes.
- Fake terminal log lines bottom-left (RESOLVING_HOST, ESTABLISHING_SECURE_LINK, HANDSHAKE_COMPLETE, PRELOADING_IMAGES, RESOURCES_LOADED).
- HUD decorations: cursor X/Y coordinates top-left, radar dial, latitude readout, "ENCRYPTED" tag flipping to "DECRYPTED", corner brackets.

## Visual system
- Near-black background (#0d0d0d range) with subtle film grain / noise.
- Single accent colour: saturated red, with glow. One secondary cyan used only for the custom cursor tag.
- Typography pairing: high-contrast serif display (project titles, "SUBJECT PROFILE") with a geometric sans for body and uppercase monospace-style labels with underscores (COMPETENCE_ANALYSIS_REPORT, EQUIPMENT_INVENTORY).
- Thin 1px borders, bracket corners, bordered tag chips, greyscale imagery with red overlays.
- Custom cursor: small square with a label tag following the pointer.

## Sections
1. Projects as a horizontal slider of tall greyscale cards, each labelled "EVIDENCE #01..", with a Slider / List view toggle and an "EVIDENCE ARCHIVE - 08 FILES" counter.
2. "SUBJECT PROFILE" dossier: case file number, status, photo with scan overlay, key/value fields (CLASS: DEV_FULLSTACK, XP_LEVEL, LANG_1, LANG_2), red "SYSTEM_ALERT - OPEN TO WORK" box.
3. "COMPETENCE_ANALYSIS_REPORT": one-sentence positioning statement with highlighted keywords.
4. "ACADEMIC_LOG [EDUCATION]" and experience as bracketed timeline entries with year chips.
5. "EQUIPMENT_INVENTORY": hard skills and soft skills as chips.
6. Contact framed as a warning panel ("DANGER: HIGH").
- Persistent extras: live clock, "LIVE FEED" status, visitor counter ("Nth investigator on this case"), Awwwards honours ribbon, optional "3D VERSION / IMMERSIVE_MODE" switch.

## Motion
- Scroll-driven reveals, smooth scrolling, text fading in per section.
- Tech used by the reference per its own copy: React, Next.js, TypeScript, Three.js / React Three Fiber, GSAP.

## Takeaways for Aman's site
- A strong single narrative concept carried through every label is what makes the reference memorable.
- Aman's own themes (API security, BOLA detection, misinformation detection, privacy-first offline tools, OS internals) suit a similar "security console / threat analysis" framing without copying the case-file concept directly.
