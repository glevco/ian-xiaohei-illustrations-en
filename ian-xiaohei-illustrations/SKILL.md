---
name: ian-xiaohei-illustrations
description: Design and generate English article illustrations in Ian's surreal, hand-drawn Xiaohei style. Use for article, blog, post, Notion, workflow, or methodology illustrations; visual metaphors; illustration plans and shot lists; and edits such as removing titles. Uses a pure white background, sparse red/orange/blue English annotations, and the recurring Xiaohei character.
---

# Ian Xiaohei Surreal Article Illustrations

## Purpose

Design and generate 16:9 landscape illustrations for English articles. Turn a key insight, process, structure, state, or metaphor into a clean, imaginative, surreal hand-drawn explanation. Avoid commercial illustration, presentation infographics, cute cartoons, and dense instruction sheets.

The recurring character is Xiaohei: a small solid-black creature with white dot eyes, thin legs, and a blank expression, earnestly doing something absurd but meaningful. Xiaohei must perform the scene's central action.

Use English for all plans, prompts, labels, annotations, captions, and delivery notes. All visible text in generated or edited images must be English. Translate any source-language wording into natural English before including it in an output.

## References

Read only the references needed for the task:

- `references/style-dna.md`: visual style, colors, lettering, and exclusions.
- `references/xiaohei-ip.md`: Xiaohei's appearance, personality, actions, and exclusions.
- `references/composition-patterns.md`: structure types, original metaphors, and rules against copying examples.
- `references/prompt-template.md`: prompt template for an individual image.
- `references/qa-checklist.md`: review and iteration after generation.
- `assets/examples/`: occasional visual calibration only, outside the default generation workflow. Do not copy their compositions, objects, or labels.

## Workflow

### 1. Understand the article

Read the user's article, link, Notion page, Markdown file, or screenshot. Identify:

- The central argument.
- Paragraphs that introduce a shift in understanding.
- Ideas that benefit from a visual explanation.
- Passages that work best as text and need no illustration.

Choose conceptual anchors instead of spacing images evenly: a key insight, two breakpoints, an input/output feedback loop, branching, before/after comparisons, repurposing one source, a path to the next step, common pitfalls, or a change in a character's state.

### 2. Plan the illustrations

If the user asks only for illustration planning, provide a shot list. For each image, specify:

- Placement after a particular paragraph.
- Theme.
- Core idea.
- Structure type.
- Xiaohei's action.
- Suggested elements.
- Suggested English labels.

Aim for 4–8 images by default, or 1–3 for a short article. Even long articles rarely need more than 9. Use enough illustrations to support the text without turning it into a picture book.

### 3. Generate individual images

When the user explicitly requests generation, proceed with the built-in `image_gen` tool, one call per image. Do not combine multiple deliverables into a single image.

Each image explains one core structure. Every prompt must specify:

- A 16:9 landscape illustration for an English article.
- A pure white background.
- Black hand-drawn line art.
- Sparse red/orange/blue handwritten English annotations.
- Generous whitespace.
- Xiaohei performing the central action.
- No presentation infographic, commercial illustration, childish cuteness, complex architecture diagram, or structure-type title in the top-left corner.

Invent a strange but coherent metaphor from the current article. Examples calibrate visual density and Xiaohei's participation. Do not reuse the conveyor-belt breakpoints, Xiaohei pulling strings, source-material fish, stamping toolbox, or pitfalls path unless the user explicitly requests that composition.

### 4. Review and iterate

Apply `references/qa-checklist.md`. Regenerate or edit when:

- Xiaohei is merely decorative.
- The composition is crowded.
- The image resembles a formal flowchart or presentation slide.
- Labels are excessive, misspelled, unreadable, or not in English.
- The top-left corner has a title such as "Common pitfalls", "Workflow", or "System architecture".
- The style is overly cute, childish, or rigid.
- The background is not clean white.

### 5. Save and deliver

When working in a workspace, copy final images to:

```text
assets/<article-slug>-illustrations/
```

Name them sequentially:

```text
01-topic-name.png
02-topic-name.png
```

Keep original generated files. Do not overwrite existing assets unless the user requests replacement.

## Delivery

Keep the initial strategy brief and precise. After generation, report:

- How many images were generated.
- The purpose of each image.
- Saved paths.
- Which images are strongest and which are optional.

Keep discussion of style theory brief; let the images speak for themselves.
