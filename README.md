# Vibecoding 网页 UI 设计 Skill

面向不同类型网页的通用 UI 设计与前端实施 Skill。根据产品目标和真实内容决定信息结构、版式、排版、配色、组件及响应式方案。以六组参考颜色为起点，跨组组合、变调并引入新色相；内含 30 套撞色灵感，也能继续生成新方案。不预设业务按钮。

## 安装

在系统终端运行交互式安装命令，按提示选择 AI 编程工具和安装范围：

```bash
npx --yes skills add strive7781/vibecoding-color
```

若要在当前电脑的所有受支持工具中安装：

```bash
npx --yes skills add strive7781/vibecoding-color --all -g --copy
```

安装后，按工具自身的方式调用 `vibecoding-ui-design`，或直接描述网页设计任务。支持的工具以 [Skills CLI 列表](https://github.com/vercel-labs/skills/blob/main/docs/agents.md) 为准。需要单独粘贴提示词时，使用 [通用提示词模板](references/prompt-template.md)。

若此前安装过旧版 `vibecoding-color-direction`，先在原安装范围卸载旧名称，再安装新版；例如全局安装可运行 `npx --yes skills remove vibecoding-color-direction -g -y`。

## 内容

- [SKILL.md](SKILL.md)：通用网页 UI 设计与实施流程。
- [通用提示词模板](references/prompt-template.md)：按项目事实填写，无固定页面或按钮文案。
- [撞色实验室](references/color-lab.md)：从六组种子色出发的组合方法、30 套扩展示例和落地检查。
- [六套参考配色](references/palettes.md)：仅在用户指定或适合项目时采用。

配色案例整理自[《HiHi小壮｜Vibecoding网站高级感配色技巧》](https://tcnp23cimv5i.feishu.cn/wiki/VirIwMNz1i6IoVkSEZxcjhZ1nlh)；通用页面设计流程是基于这些视觉原则扩展的实施指导。
