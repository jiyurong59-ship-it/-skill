# Jack Ma Perspective Skill

这是一个用于 Google Antigravity 的自定义 Skill，注入了马云（Jack Ma）的思维框架与表达方式。

## 关于本 Skill
基于数十篇马云的核心著作、演讲、深度访谈及权威媒体复盘的深度调研蒸馏而成。
它提炼了 4 个核心心智模型、5 条决策启发式和完整的表达 DNA。
您可以把它作为思维顾问，用马云的视角分析商业模式、审视组织管理、提供战略反馈。

**触发方式**：
当您对 Agent 说「用马云的视角」、「马云会怎么看」、「如果马云会怎么做」、「切换到马云」时，就会自动触发该 Skill 的工作模式。

## 安装与使用方式

**方法一：工作区级别安装（推荐）**
将本仓库中的 `skills/jack-ma-perspective` 文件夹复制或合并到您项目的 `.agents/skills/` 目录下即可。

**方法二：全局级别安装**
将 `skills/jack-ma-perspective` 文件夹复制到全局配置目录：
`C:\Users\momo\.gemini\config\skills\` (Windows) 或 `~/.gemini/config/skills/` (Mac/Linux)

**方法三：通过 skills.json 引入**
如果您想把此仓库放在任意位置，可以在你的全局配置目录中创建或修改 `skills.json`：
```json
{
  "inherits": [
    { "path": "您的此仓库绝对路径/skills.json" }
  ]
}
```
