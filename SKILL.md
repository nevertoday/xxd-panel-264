---
name: xxd-panel-264
description: "XXD Panel 264｜Sketchbook Doodle: turns a photo into a distilled visual memory rather than a hand-drawn copy — a low-finish, emotionally dense naive line drawing with lo-fi doodle and raw sketchbook energy, childlike observation, loose perspective and imperfect proportions, the subject small, simplified or partly missing, coloured pencil, wax pastel, graphite and dry-brush texture on textured paper with wobbly, broken, re-corrected lines, bright clear colours from the photo (sky blue, lake teal, fresh green, warm yellow, coral orange, peach pink) over plenty of warm white, and a few small diary-like words in a slightly unsteady hand. Outputs PNG top-bottom or left-right comparisons, design-only images, or phone/tablet/desktop/watch wallpapers, from one photo or a folder. Use when the user invokes xxd-panel-264 or asks for naive doodle, lo-fi sketchbook or childlike line drawing from a photo."
---

# XXD Panel 264

Create finished PNG artwork from the current user-supplied photograph or image directory. Read `references/original-prompt/zh-CN.md` completely immediately before every generation. That Chinese source brief is the sole creative and aesthetic authority; never summarise, translate, blend, or replace it with this file, a README, a sample, or another Panel.

Read `references/soldier-runtime.md` completely immediately before building every generation request. It is the sole family runtime contract for parameters, preference reuse, directory batches, preflight, prompt assembly, bitmap execution, output isolation, and acceptance. This Skill must not write a second art direction or a second runtime.

## Panel-specific overlay

The transformed design is a private note that someone once left, not a finished commercial illustration. Use naïve line, lo-fi doodle and raw sketchbook drawing. Low finish and high emotional density are required. The subject may be reduced, weakened or partly missing. Keep imprecise perspective, imperfect proportion and a childlike way of looking. Reject polish, a complete detailed drawing and a clean vector finish.

These overlay rules add to `references/soldier-runtime.md`. They never replace the source brief or the family runtime contract.

Write every selected final PNG directly inside one fresh task directory under `~/Desktop/xxd/xxd-panel-264/` (or the explicit `--out` root). Use collision-safe filenames; do not create source, mode, or size subdirectories and do not generate an automatic contact sheet.

## References

- `references/soldier-runtime.md` — family runtime contract used at generation time
- `references/original-prompt/zh-CN.md` — canonical source brief used at runtime
- `references/original-prompt/README.md` — translation index and authority note
- `references/runtime-preferences.md` — safe delivery-preference reuse
- `references/sample-workflow.md` — sample-artwork maintenance only; never a runtime prerequisite
- `references/xxd-panel-264-prompt.zh-CN.md` and `.en.md` — delivery adapter notes matching the family runtime blocks
