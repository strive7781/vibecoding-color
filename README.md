# Vibecoding 网站配色 Skill

基于六套参考配色，为具体网站选择颜色、定义语义变量、生成可复制提示词，并核对视觉层级与可读性。

## 安装到 Codex

在终端执行：

```bash
npx --yes skills add strive7781/vibecoding-color --skill vibecoding-color-direction -g -a codex -y
```

此命令从本仓库安装指定 Skill 到用户级 Codex 技能目录。也可先用 `npx --yes skills add strive7781/vibecoding-color --list` 只查看可安装的技能。

如果希望用 Git 管理更新，在 Windows PowerShell 中手动克隆：

```powershell
git clone https://github.com/strive7781/vibecoding-color.git "$env:USERPROFILE\.codex\skills\vibecoding-color-direction"
```

更新通过 Git 克隆的 Skill：

```powershell
git -C "$env:USERPROFILE\.codex\skills\vibecoding-color-direction" pull --ff-only
```

安装后在 Codex 中提出网站配色需求，或明确指定 `$vibecoding-color-direction`。Skill 入口是 [SKILL.md](SKILL.md)，配色表和提示词模板在 `references/`。

## 来源

配色及基础方法整理自[《HiHi小壮｜Vibecoding网站高级感配色技巧》](https://tcnp23cimv5i.feishu.cn/wiki/VirIwMNz1i6IoVkSEZxcjhZ1nlh)。本 Skill 增加了实施规则与基于 [WCAG 2.2](https://www.w3.org/TR/WCAG22/) 的可读性检查。
