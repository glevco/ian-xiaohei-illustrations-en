# Image Generation Prompt Template

Generate each image separately. Replace the variables using the article's content; do not combine several images into one.

```text
Generate one standalone 16:9 landscape illustration for an English article.

Visual DNA:
Pure white background. Minimalist black hand-drawn line art. Slightly wobbly pen lines. Lots of empty white space. Sparse red/orange/blue handwritten English annotations. Clean, absurd product-sketch feeling. No gradients, shadows, paper texture, complex background, commercial vector style, presentation infographic look, cute mascot poster, children's illustration, or realistic UI.

Required recurring character:
Xiaohei, a small solid-black absurd creature with white dot eyes, tiny thin legs, a blank serious expression, and a slightly uneven hand-drawn body shape. Xiaohei must perform the core conceptual action. Make Xiaohei serious, deadpan, and slightly bizarre, never cute or decorative.

Theme:
{article illustration theme}

Structure type:
{workflow / part of a system / before and after / character states / conceptual metaphor / method layers / route map / short comic sequence}

Core idea:
{the central idea this image should communicate}

Composition:
{specific scene: where Xiaohei is, what Xiaohei is doing, the main objects, and how information flows}

Suggested elements:
{element 1} / {element 2} / {element 3} / {element 4}

English handwritten labels:
{label 1} / {label 2} / {label 3} / {label 4} / {optional label 5}

Color use:
Black for main line art and Xiaohei. Orange for the main flow, paths, and arrows. Red only for key warnings, problems, or results. Blue only for secondary notes, feedback, or system state.

Constraints:
All visible text must be English, including tiny labels and text on objects. One image explains only one core structure. Keep the main subject around 40%–60% of the canvas. Preserve at least 35% blank white space. Use at most 5–8 short handwritten English labels, preferably 1–4 words each. Do not write a title in the top-left corner or put the structure type on the image. Avoid formal diagrams, course slides, and dense explainers. Do not copy prior examples or reuse known compositions unless explicitly requested; invent a fresh visual metaphor for this article. Keep it clear without becoming an instruction sheet, interesting without being childish, and strange but clean.
```

## Image editing prompts

Remove a top-left title:

```text
Edit the provided image. Remove only the handwritten title "{text to remove}" and its underline from the top-left corner. Fill that area with the same clean white background. Preserve everything else exactly: characters, labels, paths, line style, composition, aspect ratio, and image quality. Do not add any new text or objects. Keep all visible text in English.
```

Strengthen the surreal character action:

```text
Regenerate this illustration with the same core meaning and simple layout, making Xiaohei more central to the conceptual action. Xiaohei should perform the strange work that explains the idea. Keep it clean, sparse, hand-drawn, and never cute. Keep all visible text in English.
```
