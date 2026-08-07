# modern-editorial-cover

一个用于生成高级编辑感人物拼贴封面提示词的 Claude skill。

它固定采用杂志式截图拼贴、真人抠图和超大黑色中文标题，并提供浅色底与黑色底两种模式。适合小红书、公众号、教程、知识分享、求职和设计资源类封面。

## 安装

```bash
git clone https://github.com/yanliudesign/modern-editorial-cover.git ~/.claude/skills/modern-editorial-cover
```

也可以下载仓库后，将整个目录放入：

```text
~/.claude/skills/modern-editorial-cover/
```

## 使用

安装后，直接描述封面需求，例如：

```text
帮我做一个高级编辑拼贴风封面，标题是“设计师洗眼睛”，副标题是“6个审美网站”。
```

Skill 会依次确认标题、人物照片、内容素材、背景模式和人物情绪，最终输出完整的中文图片生成提示词与负面约束。

## 字体说明

Skill 会优先建议新青年体风格的中文超粗黑体，但不包含任何字体文件。实际使用字体前，请自行确认已安装并拥有相应授权。