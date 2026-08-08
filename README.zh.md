<div align="center">

**中文** · [English](./README.md)

# 📰 Modern Editorial Cover

---

**高级编辑拼贴封面 Skill —— 真人 · 截图 · 超大中文标题。**

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

把人物照片与真实截图组织成高级编辑拼贴封面提示词。Skill 会根据素材数量自动选择构图，同时固定视觉语言，避免每次生成的风格漂移。

```text
1  提供标题        →  锁定文案与信息层级
2  提供人物照片    →  保留真实五官并确认情绪
3  提供 1–6 张截图 →  组织克制有序的编辑拼贴
4  选择浅色或黑色  →  输出最终提示词与负面约束
```

## 案例

<table>
	<tr>
		<td width="50%" align="center">
			<img src="docs/examples/editorial-cover-01.png" alt="六个设计审美网站编辑拼贴封面" width="100%">
			<br><strong>设计审美网站</strong>
		</td>
		<td width="50%" align="center">
			<img src="docs/examples/editorial-cover-02.png" alt="求职必备 Skill 编辑拼贴封面" width="100%">
			<br><strong>求职必备 Skill</strong>
		</td>
	</tr>
</table>

## 能做什么

| 系统 | 视觉方向 |
|---|---|
| **画幅** | 默认 `3:4` 竖版，适合小红书与公众号封面 |
| **层级** | 标题第一、人物第二、内容截图第三 |
| **字体** | 纯黑超粗中文展示字体，字距紧凑 |
| **浅色模式** | 暖白、象牙白、淡灰或极浅米色 |
| **黑色模式** | 近黑背景，黑色标题放在浅色纸张底托上 |
| **构图** | 根据 1–2、3–4、5–6 张素材采用确定性布局 |
| **输出** | 完整中文图片生成提示词与负面约束 |

## 安装

将仓库克隆到 skills 目录：

```bash
git clone https://github.com/yanliudesign/modern-editorial-cover.git ~/.claude/skills/modern-editorial-cover
```

也可以下载仓库后，将整个目录放入：

```text
~/.claude/skills/modern-editorial-cover/
```

## 立即使用

安装后，直接描述封面需求：

```text
帮我做一个高级编辑拼贴风封面，标题是“设计师洗眼睛”，
副标题是“6个审美网站”。
```

Skill 会一次询问一个缺失信息：标题、人物照片、内容素材、背景模式和人物情绪。最后输出可直接使用的中文提示词，包含准确文案、构图、层级、材质、安全区和负面约束。

## 五条视觉规则

1. **只用真实素材。** 截图卡片来自用户提供的素材，不凭空虚构无关界面。
2. **只有两种背景。** 每张封面只使用克制浅色底或近黑色底。
3. **标题始终纯黑。** 黑色模式下，标题放在暖白或浅灰纸张色块上。
4. **编辑感而非装饰感。** 用纸张层次、克制箭头、胶带和网格，拒绝 emoji 海洋、霓虹渐变与装饰性 3D 小物。
5. **人物身份不走样。** 保留真实五官，不让文字或拼贴元素遮挡脸部。

## 字体说明

Skill 可建议使用新青年体气质的中文超粗黑体，但不会打包任何字体文件，也不代表字体可免费商用。实际使用前，请确认字体已安装并拥有相应授权。

## 目录结构

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

## 开源协议

MIT —— 欢迎 fork、修改，并发展成你自己的编辑封面系统。

Created by [Dreameryanyan](https://www.linkedin.com/in/yanliudesign/) ·
[LinkedIn](https://www.linkedin.com/in/yanliudesign/) ·
[X](https://x.com/yanliudreamer)