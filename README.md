# 四足机器人强化学习论文精读

中文方法论网页，面向巡检机器人初版 baseline 的论文理解与复现。

## 选择阅读版本

仓库保留两份独立讲解，可按需要选择：

| 版本 | 在线阅读 | 仓库文件 | 内容说明 |
| --- | --- | --- | --- |
| 原版论文精读 | [打开原版](https://chensrfurina.github.io/FYP_ref_paper/) | [index.html](./index.html) | 原有讲解，保留原文、搜索、展开内容与交互演示。 |
| 新版四篇详细讲解 | [打开新版](https://chensrfurina.github.io/FYP_ref_paper/quadruped-rl-paper-guide.html) | [quadruped-rl-paper-guide.html](./quadruped-rl-paper-guide.html) | 逐篇详解教师—学生框架、奖励公式、网络结构和训练流程，包含官方代码核对、四篇比较与巡检 baseline 路线。 |

两份 HTML 都可下载后直接用浏览器打开，支持离线阅读。新增版本不覆盖原版页面，原来的在线地址保持有效。新版核对日期：2026-10-19。

## 内容

- Rapid Locomotion via Reinforcement Learning（2205.02824v1）
- Robot Parkour Learning（2309.05665v2）
- Extreme Parkour with Legged Robots（2309.14341v1）
- Toward Reliable Sim-to-Real Predictability for MoE-based Robust Quadrupedal Locomotion（2602.00678v4）

逐篇解释教师—学生、PPO、奖励、网络、训练与部署，附有方法比较、巡检 baseline 建议、复现实验和原始来源。论文事实、官方代码配置和项目建议分别标注；未进行策略训练或实机实验。

## 阅读

- GitHub Pages：https://chensrfurina.github.io/FYP_ref_paper/
- 本地直接打开 `index.html`，无需安装依赖或连接网络。
- 支持章节搜索、深入内容展开、三个奖励公式交互演示、手机阅读和打印。

## 来源与版本

网页第 12 节列出全部原论文、项目页、官方仓库与锁定代码快照。

核对日期：2026-10-16。论文和代码版权归原作者。本仓库提供独立中文解释与教学示意，不转载论文全文、插图或训练权重。
