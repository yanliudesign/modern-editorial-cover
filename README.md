<div align="center">

[中文](./README.zh.md) · **English**

# 📰 Modern Editorial Cover

---

**A premium editorial collage cover skill — portrait · screenshots · bold Chinese type.**

[![License](https://img.shields.io/badge/LICENSE-MIT-4c8bf5?style=flat-square&labelColor=333)](./LICENSE)
[![Version](https://img.shields.io/badge/VERSION-1.0.0-2ea44f?style=flat-square&labelColor=333)]()
[![Skills](https://img.shields.io/badge/SKILLS-1-2ea44f?style=flat-square&labelColor=333)]()
[![Stars](https://img.shields.io/github/stars/yanliudesign/modern-editorial-cover?style=flat-square&label=STARS&color=e37f2c&labelColor=333)](https://github.com/yanliudesign/modern-editorial-cover/stargazers)

[![Claude Code](https://img.shields.io/badge/Claude_Code-Skill-d97757?style=flat-square&labelColor=1a1a1a&logo=anthropic&logoColor=white)](https://claude.ai/code)
[![Codex](https://img.shields.io/badge/Codex-Skill-2ea44f?style=flat-square&labelColor=1a1a1a)]()
[![OpenCode](https://img.shields.io/badge/OpenCode-Skill-4c8bf5?style=flat-square&labelColor=1a1a1a)]()
[![OpenClaw](https://img.shields.io/badge/OpenClaw-Skill-8b5cf6?style=flat-square&labelColor=1a1a1a)]()
[![Hermes](https://img.shields.io/badge/Hermes-Skill-e879a8?style=flat-square&labelColor=1a1a1a)]()

</div>

Turn portraits and real screenshots into image-generation prompts for polished editorial collage covers. The skill keeps the visual direction consistent while adapting the composition to the number of assets you provide.

```text
1  Add your title       →  lock the copy and hierarchy
2  Add a portrait       →  preserve identity and choose the expression
3  Add 1–6 screenshots  →  build a controlled editorial collage
4  Pick light or black  →  generate the final prompt + negative constraints
```

## Examples

<table>
	<tr>
		<td width="50%" align="center">
			<img src="docs/examples/editorial-cover-01.png" alt="Editorial collage cover for six design inspiration websites" width="100%">
			<br><strong>Design inspiration websites</strong>
		</td>
		<td width="50%" align="center">
			<img src="docs/examples/editorial-cover-02.png" alt="Editorial collage cover for essential job-search skills" width="100%">
			<br><strong>Essential job-search skills</strong>
		</td>
	</tr>
</table>

## What it does

| System | Direction |
|---|---|
| **Format** | `3:4` portrait, designed for Xiaohongshu and WeChat covers |
| **Hierarchy** | Headline first, portrait second, content screenshots third |
| **Typography** | Oversized pure-black Chinese display type with tight spacing |
| **Light mode** | Warm white, ivory, pale gray, or very light beige |
| **Black mode** | Near-black field with the black headline placed on a light paper block |
| **Composition** | Deterministic layouts for 1–2, 3–4, or 5–6 supplied assets |
| **Output** | A complete Chinese image-generation prompt plus negative constraints |

## Install

Clone the repository into your skills directory:

```bash
git clone https://github.com/yanliudesign/modern-editorial-cover.git ~/.claude/skills/modern-editorial-cover
```

Or download the repository and place the whole folder at:

```text
~/.claude/skills/modern-editorial-cover/
```

## Try it

Once installed, describe the cover you want:

```text
Create a premium editorial collage cover. The title is “设计师洗眼睛”
and the subtitle is “6个审美网站”.
```

The skill asks for one missing input at a time: title, portrait, content assets, background mode, and expression. It then returns a production-ready Chinese prompt with exact copy, layout, layering, material treatment, safety margins, and negative constraints.

## Visual rules

1. **Real material only.** Screenshot cards come from the assets supplied by the user, not invented interfaces.
2. **Two background modes.** Every cover uses either a restrained light background or a near-black background.
3. **Black headline always.** In black mode, the headline sits on warm-white or pale-gray paper for contrast.
4. **Editorial, not decorative.** Paper layers, restrained arrows, tape, and grids replace emoji walls, neon gradients, and ornamental 3D objects.
5. **Identity stays intact.** The portrait keeps the subject's real facial features and never lets text or collage elements obscure the face.

## Font note

The skill can recommend New Youth-style extra-bold Chinese display lettering, but it does not bundle font files or imply commercial licensing. Confirm that any selected font is installed and properly licensed before use.

## Layout

```text
modern-editorial-cover/
├── docs/
│   └── examples/
│       ├── editorial-cover-01.png
│       └── editorial-cover-02.png
├── SKILL.md
├── README.md
├── README.zh.md
└── LICENSE
```

## License

MIT — fork it, remix it, and shape it into your own editorial system.

Created by [Dreameryanyan](https://www.linkedin.com/in/yanliudesign/) ·
[LinkedIn](https://www.linkedin.com/in/yanliudesign/) ·
[X](https://x.com/yanliudreamer)