# 🐾 Hakimi Court - Warm Mediation Platform  
## 哈基米法庭 - 暖心调解平台  

---

## 📜 Project Overview / 项目概述  

A web-based conflict resolution simulation tool that uses AI sentiment analysis to provide fair mediation suggestions. Designed for educational and entertainment purposes, helping users understand conflict resolution principles through immersive role-playing scenarios.  

基于Web的冲突解决模拟工具，采用AI情感分析技术提供公平调解建议。专为教育和娱乐设计，帮助用户通过沉浸式角色扮演理解冲突解决原则。

---

## 🎮 Key Features / 核心功能  

| 功能 | Features |
|------|----------|
| **双角色模拟** | Dual-role simulation with adjustable conflict intensity |
| **情感分析系统** | Real-time sentiment analysis of user inputs |
| **多结局生成** | Dynamic judgment results based on weighted parameters |
| **历史记录** | Account-based case history management |
| **可视化报告** | Interactive responsibility distribution charts |

---

## 🛠️ Technical Stack / 技术架构  

mermaid
pie
    title 技术构成 / Technology Composition
    "HTML5" : 35
    "CSS3" : 25
    "JavaScript" : 30
    "Chart.js" : 5
    "LocalStorage" : 5


---

## 🚀 Installation / 部署指南  

### 方法一：GitHub Pages（推荐）/ Method 1: GitHub Pages (Recommended)

bash
1. 访问仓库：https://github.com/yourusername/hakimi-court
   Visit repository: https://github.com/yourusername/hakimi-court
2. Settings → Pages → 选择main分支
   Settings → Pages → Select main branch
3. 5分钟后访问生成的自定义域名
   Access generated custom domain after 5 minutes


### 方法二：本地运行 / Method 2: Local Run

bash
1. 克隆仓库：git clone https://github.com/yourusername/hakimi-court
   Clone repository: git clone https://github.com/yourusername/hakimi-court
2. 打开浏览器访问：file:///path/to/hakimi_court_ui.html
   Open browser to access: file:///path/to/hakimi_court_ui.html


---

## 📖 Usage Guide / 使用指南  

### 1. Account System / 账户系统
- 创建账户后所有数据本地加密存储  
  All data encrypted and stored locally after account creation
- 支持多账户切换（账户间数据完全隔离）  
  Support multi-account switching (complete data isolation between accounts)

### 2. Core Process / 核心流程

mermaid
graph TD
    A[选择角色<br/>Choose Role] --> B[输入事实描述<br/>Input Facts]
    B --> C[情感表达<br/>Express Feelings]
    C --> D{AI分析<br/>AI Analysis}
    D --> E[责任分布图<br/>Responsibility Chart]
    E --> F[修复建议<br/>Repair Suggestions]


### 3. History Records / 历史记录
- 点击右上角时钟图标查看过往案例  
  Click clock icon in top-right corner to view past cases
- 每个案例包含：  
  Each case includes:
  - 时间戳 / Timestamp
  - 角色立场 / Role Position
  - 关键情感词云 / Key Emotion Word Cloud

---

## 🤝 Contributing / 贡献指南  

We welcome the following types of contributions:  
我们欢迎以下类型的贡献：

- 🐛 Bug修复 / Bug fixes
- 🎨 界面优化 / UI optimization
- 📝 文档完善 / Documentation improvement
- 🧠 新功能提案 / New feature proposals

### Development Standards / 开发规范
1. Use ESLint to maintain consistent code style  
   使用ESLint保持代码风格统一
2. New features must include unit tests  
   新增功能需包含单元测试
3. Run `npm run lint` before submission  
   提交前运行`npm run lint`

---

## 📜 License / 许可证  

This project adopts the MIT license:  
本项目采用MIT许可证：

text
Copyright (c) 2025 Hakimi Court Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.


---

## 📸 Screenshots / 截图  

| 功能界面 / Feature Interface | Preview / 预览 |
|---------------------------|---------------|
| 登录界面 / Login | ![Login](screenshot_login.png) |
| 分析结果 / Analysis Results | ![Analysis](screenshot_analysis.png) |
| 历史记录 / History | ![History](screenshot_history.png) |

---

## 📌 Important Notes / 注意事项  

- Data completely stored in local browser (regular backup recommended)  
  数据完全存储在本地浏览器（建议定期备份）
- Complete data isolation between different accounts  
  不同账户间数据完全隔离
- Suitable for users aged 18+  
  适合18岁以上用户使用

---

---

> **Made with ❤️ by the Hakimi Court Team**  
> **由哈基米法庭团队用心制作**
