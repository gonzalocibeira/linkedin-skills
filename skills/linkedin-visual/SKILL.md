---
name: linkedin-visual
description: Create or refine an actual static image, looping GIF, or multipage PDF carousel for a LinkedIn post. Use with supplied copy, an existing visual, or a post drafted by linkedin-post.
---

Start with the supplied post or resolve the referenced draft. Identify the one thing the reader should see. Use the author's current art direction, approved assets and relevant past corrections to infer language, aspect ratio, visual style, branding and text density. Apply a past correction to the choice it addressed. Keep author-specific examples and preferences in the current user's context. With no history, choose a readable composition suited to the subject and proceed.

Form a one-sentence concept before rendering. Present it for review only when requested. Honor the requested format. If the author leaves it open, use a still for a single telling moment, a GIF for a visible change, or a PDF when readers benefit from moving through steps at their own pace.

- **Static image.** Build around one focal point. Choose framing to suit the author's preference and subject. Use illustrations for an editorial scene, authentic imagery for a documented event, and typeset overlays for exact wording, commands or figures. If the post describes a specific interaction, depict the relevant action and screen accurately.
- **Looping GIF.** Plan the starting state, action, result and return. Use genuine footage for a real demonstration or make the illustrative nature clear. Allow time to read the result and design the transition back to the first frame. Export an animated GIF at the requested dimensions and cadence, accounting for GIF timing precision.
- **PDF carousel.** Give each page one job. For a walkthrough, open with the problem, show the decision or method, then finish with an outcome readers can use. Choose another sequence when the post calls for it. Use a consistent page size, large type and generous margins. Export one ordered multipage PDF.

Let the visual add information the caption alone cannot convey. Preserve exact strings and approved design choices. For targeted revisions, edit the existing asset and keep the elements the author liked. Inspect screenshots, tabs, URLs, labels and backgrounds for private details. Use sanitized examples where needed and make proposed features recognizable as concepts.

## Default export quality

Apply these production targets unless the author specifies different dimensions, cadence or delivery constraints. Preserve the composition's aspect ratio.

- **Stills:** Render with at least 1080 pixels on the short edge (1920 × 1080 for landscape 16:9). Use PNG for fine type, diagrams and UI. Check photographic exports for compression artifacts. Source or render sufficient detail at the intended size; enlarging a blurry source does not meet the target.
- **GIFs:** Render with at least 1080 pixels on the short edge and author motion at 24 frames per second. Encode an infinite loop. For 24 fps, distribute 40 ms and 50 ms frame delays to track the timeline (five 40 ms delays and one 50 ms delay per six frames). Longer holds may combine identical frames. Decode the export and check dimensions, moving-frame timing, total duration and infinite-loop metadata. Watch two full cycles for a visible jump, unintended pause, flicker or color banding. For a size budget, shorten or simplify the animation before sacrificing resolution or cadence.
- **PDF carousels:** Use consistent page dimensions, vector text and graphics where practical, and raster imagery sharp at a 1080-pixel-wide page preview. At a 360-pixel-wide preview, target at least 16 pixels for essential body text. Split a dense page to preserve readability. Render every page and check order, clipping and legibility without zoom.

Preview the finished asset at 360 pixels wide and check it against the post. Correct defects before delivery. If a constraint prevents meeting a target, report the actual export settings and the shortfall. Disclose any checks that could not be performed.
