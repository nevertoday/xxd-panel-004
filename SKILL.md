---
name: xxd-panel-004
description: "XXD Panel 004｜Urban Single-Line Journal: pairs a believable, lived-in scene of a city, street, landmark or other theme with a modern line poster distilled from it — thin, precise single lines and clear geometric perspective that keep the skyline, street front, signs or transport recognisable, an orderly rhythm of detail, a theme-specific one-ink or very small palette, and a headline at the top with a subtitle such as the local name, address, coordinates or year, with street text kept accurate. Outputs PNG top-bottom or left-right comparisons, design-only images, or phone/tablet/desktop/watch wallpapers, from one photo or a folder. The brief is written around a named place or theme, so street, landmark and object photos with clear structure fit best. Use when the user invokes xxd-panel-004 or asks for single-line city posters, modern line-art travel posters or urban brand line drawings from a photo."
---

# XXD Panel 004

Create finished PNG artwork from the current user-supplied photograph or image directory. Read `references/original-prompt/zh-CN.md` completely immediately before every generation. That Chinese source brief is the sole creative and aesthetic authority; never summarise, translate, blend, or replace it with this file, a README, a sample, or another Panel.

Read `references/soldier-runtime.md` completely immediately before building every generation request. It is the sole family runtime contract for parameters, preference reuse, directory batches, preflight, prompt assembly, bitmap execution, output isolation, and acceptance. This Skill must not write a second art direction or a second runtime.

## Panel-specific overlay

Panel 004 may start from a theme, place, street, address, coordinates, or a reference image. Treat explicit factual material as the reality anchor. When a real place is named and current facts matter, verify them through an available browsing/research route before prompting; do not invent location features. The source brief still controls all visual decisions.

These overlay rules add to `references/soldier-runtime.md`. They never replace the source brief or the family runtime contract.

Write every selected final PNG directly inside one fresh task directory under `~/Desktop/xxd/xxd-panel-004/` (or the explicit `--out` root). Use collision-safe filenames; do not create source, mode, or size subdirectories and do not generate an automatic contact sheet.

## References

- `references/soldier-runtime.md` — family runtime contract used at generation time
- `references/original-prompt/zh-CN.md` — canonical source brief used at runtime
- `references/original-prompt/README.md` — translation index and authority note
- `references/runtime-preferences.md` — safe delivery-preference reuse
- `references/sample-workflow.md` — sample-artwork maintenance only; never a runtime prerequisite
- `references/xxd-panel-004-prompt.zh-CN.md` and `.en.md` — delivery adapter notes matching the family runtime blocks
