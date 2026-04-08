# 🐾 Get Shit Done

> **真正的 AI 提效不是用 AI 取代打工人，而是用 AI 把打工人从 SHIT 里解放出来**

[![Stars](https://img.shields.io/github/stars/lvjin12321/Get_Shit_Done?style=social)](https://github.com/lvjin12321/Get_Shit_Done)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

---

## 🎯 这是什么？

**Get Shit Done** 是一个 **打工人 AI 工具箱**，收集各种能让你少加班、少受罪的 AI 技能。

**核心理念：**

```
❌ 错误的 AI 提效：用 AI 取代打工人 → 打工人失业
✅ 正确的 AI 提效：用 AI 把打工人从 SHIT 里解放出来 → 打工人准时下班
```

**什么是 SHIT？**

- **S**tupid Tasks（愚蠢的任务）：填表、写周报、整理会议纪要
- **H**eavy Workload（重复劳动）：同样的格式调 100 遍
- **I**nvisible Work（隐形工作）：格式调整、文档排版、邮件回复
- **T**ime Wasters（时间浪费）：明明 5 分钟能搞定，偏要搞 5 小时

**我们的目标：**

用 AI 干掉这些 SHIT，让你：
- ✅ 准时下班
- ✅ 少受窝囊气
- ✅ 把时间花在真正有价值的事情上

---

## 🧰 工具箱

### 已上线技能

| 技能 | 描述 | 状态 |
|------|------|------|
| [📝 报告老油条](skills/report-master/) | 自动生成各种职场报告，100% 还原模板格式 | ✅ 已上线 |
| 🔜 下一个技能 | 你来决定 | 🚧 开发中 |

### 技能特点

- **格式完美**：严格按模板格式，无需二次加工
- **内容安全**：不吹牛、能交差、不糊弄
- **省时省力**：5 分钟搞定 1 小时的活

---

## 🚀 快速开始

### 使用方式 1：OpenClaw Skill

如果你有 OpenClaw，把技能目录放入 `skills/` 文件夹即可使用。

### 使用方式 2：独立脚本

每个技能都有独立的 Python 脚本，可以直接运行：

```bash
# 安装依赖
pip install -r requirements.txt

# 运行技能
python skills/report-master/scripts/generate_report.py --title "工作周报" --output report.docx
```

### 使用方式 3：在线服务（Coming Soon）

我们正在开发在线服务，不用安装，打开网页就能用。

---

## 📦 项目结构

```
Get_Shit_Done/
├── README.md                    # 本文件
├── LICENSE                      # MIT 许可证
├── requirements.txt             # 公共依赖
│
├── skills/                      # 所有技能
│   ├── report-master/           # 报告老油条
│   │   ├── SKILL.md
│   │   ├── README.md
│   │   └── scripts/
│   │
│   └── your-skill/              # 你的技能（欢迎贡献）
│       └── ...
│
└── docs/                        # 文档
    └── contributing.md          # 贡献指南
```

---

## 🤝 贡献

**欢迎贡献新技能！**

如果你有好的想法或者已经写好了技能，欢迎提交 Pull Request。

**贡献指南：**

1. Fork 本仓库
2. 在 `skills/` 目录下创建你的技能文件夹
3. 参考 `skills/report-master/` 的结构
4. 提交 Pull Request

**技能要求：**

- ✅ 解决打工人的真实痛点
- ✅ 能真正节省时间
- ✅ 格式/输出质量过关
- ✅ 有清晰的 README 说明

---

## 💬 社区

- 💡 有想法？提 [Issue](https://github.com/lvjin12321/Get_Shit_Done/issues)
- 🔧 有代码？提 [Pull Request](https://github.com/lvjin12321/Get_Shit_Done/pulls)
- 📢 有吐槽？也可以提 Issue

---

## 📄 许可证

MIT License - 想怎么用就怎么用，但别说是我教的 😉

---

## 🌟 支持我们

如果这个工具箱帮到了你：

1. **点颗 Star** ⭐ - 这是最大的支持！
2. **分享给同事** - 独乐乐不如众乐乐
3. **贡献技能** - 让更多人受益

---

<p align="center">
  <strong>🐾 Get Shit Done —— 让打工人准时下班</strong>
</p>

<p align="center">
  <em>真正的 AI 提效，是把打工人从 SHIT 里解放出来</em>
</p>
