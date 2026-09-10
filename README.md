# -python-

大数据与人工智能课程作业仓库。

## 📂 目录结构

```
-python-/
├── README.md                       # 本文件
│
├── .workbuddy/skills/              # ⭐ WorkBuddy 官方技能包（核心作业）
│   ├── concept-learning-generator/      # 概念学习资料生成器（核心作业）
│   │   ├── SKILL.md                     # 技能说明书
│   │   ├── assets/                      # 资源文件
│   │   └── references/                  # 参考资料
│   │
│   ├── concept-learner/                 # 层层递进式刷题技能
│   │   ├── SKILL.md
│   │   └── scripts/
│   │       └── skill.py                 # 刷题程序（5关20题，可运行）
│   │
│   └── agent-skill-101/                 # Agent Skill 概念讲解技能
│       ├── SKILL.md
│       ├── assets/
│       └── references/
│
└── agent-skill-一分钟速通.html         # Agent Skill 可视化学习页
```

## 🎯 作业说明

本仓库包含三个 **WorkBuddy Agent Skill**：

1. **`concept-learning-generator`（核心作业）**：概念学习资料生成器。输入课程中的任一概念/术语，输出包含 6 个部分的结构化学习资料：一句话定义、核心直觉、生活化类比、工作机制、代码示例、自测练习。
2. **`concept-learner`**：层层递进式刷题技能，覆盖 Python 入门 → 机器学习与 AI 共 5 关、20 题。
3. **`agent-skill-101`**：讲解 Agent Skill 核心概念的技能。

## 🚀 运行刷题技能

```bash
python .workbuddy/skills/concept-learner/scripts/skill.py
```
