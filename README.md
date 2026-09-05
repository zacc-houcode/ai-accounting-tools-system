# 工作流程与 AI 团队 · 四个工具

`index.html` 一个档案，**双击就能开**。不用装东西、不用上网、没有帐号。
你画的东西存在自己电脑的浏览器里，不会传到任何地方。

| 工具 | 做什么 |
|---|---|
| 🛠️ 工作流程建造器 | 画流程：模块、步骤、或者（Or）、循环（Loop），标 Audit 点，写清楚谁负责、要什么工具和资料。可以放大看、导出 PNG 或 JSON。不想从零画，用「✨ AI 帮你画流程」：说一遍平常怎么做 → 复制提示词 → 贴进你自己的 Claude → 把它回的 JSON 贴回来，整条流程就画好了 |
| 🤖 AI Agent 团队建造器 | 部门长期用的那一支团队：5 个现成 Agent（指挥、连接、流程、技能、训练），再加上你自己的岗位。「✨ AI 帮你建 Agent」跟流程建造器一样：复制提示词 → 贴进你自己的 Claude → 把 JSON 贴回来，卡片自动建好。导出 `AI-TEAM-SYSTEM.md` |
| 🛡️ 审计系统 | 每个 Audit 点设紧急度（High / Mid / Low）、AI 做完要交出什么、不通过怎么办。生成一个可以直接用的审计台 `console.html` |
| 📦 导出整套体系 | 一键把团队、全部流程、Project 指令范本、安装核对清单、审计台打包成 `AI-SYSTEM-BUNDLE.md`，交给 Claude Code 建出来 |

## 怎么下载

- 按上方绿色的 `Code` → `Download ZIP`，解压后双击 `index.html`；
- 或者 `git clone https://github.com/zacc-houcode/ai-accounting-tools-system.git`。

## 怎么用

1. 双击 `index.html`，在**工作流程建造器**把一条流程画清楚，风险最高的那一步勾上 Audit。
2. 到 **AI Agent 团队建造器**，看一遍现成的五个 Agent，再加上你部门要的岗位。
3. 到 **审计系统**，给每个 Audit 点设紧急度、写清楚 AI 做完要交出什么给你查。
4. 到 **导出整套体系**，下载 `AI-SYSTEM-BUNDLE.md`，在 Claude Code 开一个空资料夹，把它交给 Claude，说「照这份建，先给我 Plan」。

> 这四个工具是**用来设计**的，本身不是 Claude Plugin。
> 你在这里想清楚，再交给 Claude Code 去打造 Plugin。

## 审计台

审计台是一个独立网页。在「审计系统」按「下载审计台 HTML」拿到 `console.html`，
放进流程资料夹的 `audit/` 里，双击就能打开：逐项看 AI 交了什么、通过还是退回、
写退回原因、留下审计轨迹、导出 CSV。审计记录只存在打开它的那台电脑上。

## 更新

工具改了，重新下载一次 `index.html` 就好。你自己画的流程存在浏览器里，不会被覆盖。
换电脑或清了浏览器资料之前，记得先用「导出 JSON」把流程带走。
