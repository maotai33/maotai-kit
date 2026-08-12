# maotai-kit 🐱 猫太版 AI 技能包

猫太（maotai33）的创业内容 AI 技能包，共 **12 个技能**（11 个基础技能 + 1 个导航总入口）。

把这几年做创业培训、内容创作积累下来的方法论，做成了 AI 可调用的技能。装好之后，跟 AI 说一句「帮我起个标题」「这个爆款为什么火」，它就能直接用这套方法干活。

## 一键安装（推荐）

```bash
npx -y skills add maotai33/maotai-kit --all
```

这一条命令会把全部 12 个技能装到你电脑上所有检测到的 AI 编程代理（Claude Code、Cursor、Qwen Code、OpenCode 等）。

装好后，在 AI 工具里输入：

```
/maotai-all
```

就能看到完整技能清单，按需选用。

## 技能清单

| 技能 | 干什么 |
|---|---|
| `/maotai-all` | 导航总入口，列出所有技能帮你选 |
| `/maotai-title` | 起吸引人的标题/选题 |
| `/maotai-content` | 内容诊断，看选题/结构/表达哪里有问题 |
| `/maotai-hook` | 写抓人的开头/钩子，3 秒留住人 |
| `/maotai-resonate` | 找打动人的金句和共鸣表达 |
| `/maotai-aicheck` | 检测 AI 痕迹，让内容更像真人写的 |
| `/maotai-benchmark` | 对标分析，和优秀案例比找差距 |
| `/maotai-deconstruct` | 爆款拆解，看它为什么火 |
| `/maotai-diagnosis` | 诊断 |
| `/maotai-knowledge` | 知识库/语料库，把素材变成可复用的库 |
| `/maotai-content-system` | 内容结构化系统，把大量内容搭成系统工程 |
| `/maotai-skill-cleaner` | 清理本地不干净的 skill |

## 单独安装某个技能

如果你只想要某一个技能：

```bash
npx -y skills add maotai33/maotai-kit --skill maotai-title
```

把 `maotai-title` 换成你想要的技能名即可。

## 手动安装（不会命令行）

1. 点击页面右上角绿色 **Code** 按钮 → **Download ZIP**
2. 解压后，把 `skills/` 文件夹里的每个子文件夹，复制到你 AI 工具的 skills 目录（比如 `~/.claude/skills/`）
3. 重启 AI 工具，输入 `/maotai-all`

## 作者

**猫太** · 义乌创业者 · 创业培训

> 内容是你的资产，我们把它变成能反复用的库。

GitHub: [@maotai33](https://github.com/maotai33)
