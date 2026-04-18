---
name: ehsan-editorial
description: Design photorealistic infographic-style editorial collage illustrations from a user topic. Use when the user wants a cutout photo-composite aesthetic, needs concept extraction from a topic, wants candidate visual elements to choose from, and then needs final image-generation prompts and composition directions for mix-and-match scene building.
---

# EHSAN EDITORIAL

## Overview

Use this skill to turn a topic into a structured, image-ready editorial collage concept in the style of photoreal cutout infographics (monochrome base, selective accent color, layered circles/shapes, halftone texture, documentary/business-news tone).

When executing, always keep the process interactive: extract concepts, present options, wait for selection, then produce final generation and compositing directions.

## Workflow

1. **Capture intent and constraints**
   - Ask for topic, audience, and intended message (explain, compare, warn, persuade, celebrate).
   - Ask output constraints: aspect ratio, platform, preferred accent colors, text/no text, brand sensitivity, and legal/safety constraints.

2. **Extract visual elements from topic**
   - Convert the topic into 4 element groups:
     - **Actors** (people, institutions, roles)
     - **Objects** (devices, documents, tools, symbols)
     - **Places/contexts** (offices, factories, courtrooms, server rooms)
     - **Data cues** (charts, labels, prices, callouts)
   - Produce 2-3 narrative angles (e.g., “conflict,” “comparison,” “process”).

3. **Offer selectable concept boards**
   - Provide 3 concise concept options. For each option include:
     - One-sentence editorial thesis
     - Subject stack (foreground/midground/background)
     - Color approach (grayscale + 1 accent, or grayscale + 2 accents max)
     - Recommended headline/callout style
   - Ask the user to choose one option or combine parts.

4. **Generate image prompts by layer**
   - Create modular prompts for each required layer:
     - Primary human subjects (cutout-ready)
     - Secondary contextual objects
     - Background architecture/context
     - Abstract graphical overlays (circles, halftone fields, grain)
     - Optional label/text bubble plates
   - Require clean separation and transparent or easily maskable backgrounds.

5. **Compose and mix-match plan**
   - Provide explicit assembly order:
     - background shapes/textures → environment → objects → people → overlays → labels
   - Define depth, overlaps, shadows, edge treatment, and visual hierarchy.
   - Keep collage believable: consistent light direction, scale, and perspective logic.

6. **Deliver final production package**
   - Return:
     - Final master prompt (for full-scene generation)
     - Layer prompts (for manual compositing)
     - Negative prompt (to prevent painterly/cartoon look)
     - Quick variation knobs (accent color, crop, density, seriousness)

## Output Format

Use this structure in responses:

1. **Topic Breakdown** (actors, objects, contexts, data cues)
2. **Concept Options A/B/C**
3. **Selected Direction Summary**
4. **Layered Prompt Set**
5. **Composition Blueprint**
6. **Final Master Prompt + Negative Prompt**
7. **3 Fast Variants**

## Style Rules for This Aesthetic

- Prefer photoreal people/objects with clean cutout edges.
- Use mostly grayscale foundations and one bold accent color.
- Add tactile editorial texture: soft paper grain, halftone dots, distressed gradients.
- Use geometric backplates (circles/ovals/rectangles) to group narrative clusters.
- Keep typography minimal, bold, and functional; avoid decorative fonts.
- Avoid over-crowding; prioritize one primary story moment.
- Keep tone documentary/editorial rather than cinematic fantasy.

Read `references/prompt-patterns.md` for reusable prompt templates and quality checks.
