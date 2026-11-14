# Vibecoding 网站配色 Skill

基于六套参考配色，为具体网站选择颜色、定义语义变量、生成可复制提示词，并核对视觉层级与可读性。

## 安装到 AI 编程工具

本仓库采用通用的 `SKILL.md` 格式，适用于支持 [Agent Skills](https://agentskills.io) 的编程助手。`skills` CLI 会根据目标工具放置技能文件。

在当前 AI 编程工具的终端安装，或由 CLI 自动检测本机工具：

```bash
npx --yes skills add strive7781/vibecoding-color --skill vibecoding-color-direction -g -y
```

安装到 `skills` CLI 支持的全部 AI 编程工具：

```bash
npx --yes skills add strive7781/vibecoding-color --all -g
```

`--all` 会为 CLI 支持的所有代理创建安装项，包括当前没有运行的工具。若只需指定几个工具，可重复使用 `-a`，例如 `-a codex -a claude-code -a cursor`。可先用 `npx --yes skills add strive7781/vibecoding-color --list` 只查看仓库中的技能。支持范围以 [Skills CLI 的代理列表](https://github.com/vercel-labs/skills/blob/main/docs/agents.md)为准；不能加载 Skill 的工具可直接使用 [提示词模板](references/prompt-template.md)。

安装后，在支持 Skill 的编程助手中提出网站配色需求，或明确指定 `vibecoding-color-direction`。Skill 入口是 [SKILL.md](SKILL.md)，配色表和提示词模板在 `references/`。

## 来源

配色及基础方法整理自[《HiHi小壮｜Vibecoding网站高级感配色技巧》](https://tcnp23cimv5i.feishu.cn/wiki/VirIwMNz1i6IoVkSEZxcjhZ1nlh)。本 Skill 增加了实施规则与基于 [WCAG 2.2](https://www.w3.org/TR/WCAG22/) 的可读性检查。
