# 王蓉静｜AI 产品与 AI Coding 作品集

> 把 AI 做成可感知的产品。

## 优先查看

### **[打开正式在线作品集 →](https://yixun-ai-portfolio.vercel.app/)**

作品集从产品判断、交互设计与 Prompt 出发，呈现如何将模糊的 AI 概念进一步实现为可以体验、验证和持续迭代的产品。每个案例均包含问题背景、核心判断、产品机制、个人贡献与在线 Demo。

## Selected Work

| 顺序 | 项目 | 方向 | 在线体验 | 源码 |
| --- | --- | --- | --- | --- |
| 01 | **Aether 2.0** | 多模态 AI 创作与作品交流 | [Demo](https://aether-2-psi.vercel.app/) | [GitHub](https://github.com/YiXun-13468878779/aether2.0) |
| 02 | **HARNESS / CITY** | AI Agent 系统与交互可视化 | [Demo](https://deepseek-harness-city.vercel.app/) | [GitHub](https://github.com/YiXun-13468878779/deepseek-harness-city) |
| 03 | **LLM Agent 社会仿真实验** | 计算社会科学与多智能体机制研究 | [预览研究演示](https://yixun-ai-portfolio.vercel.app/research/llm-agent-society.pdf) | — |
| 04 | **MindNest** | AI 知识管理与研究 Agent | [Demo](https://mindnest-alpha.vercel.app/) | [GitHub](https://github.com/YiXun-13468878779/mindnest) |
| 05 | **AI 助手的记忆系统** | AI 记忆透明度与控制权 | [Demo](https://memory-usage-summary.nocode.host/) | — |
| 06 | **GSB Studio** | 对话模型人工评估闭环 | [Demo](https://gsb-studio.vercel.app/) | [GitHub](https://github.com/YiXun-13468878779/gsb-studio) |

## 代表项目

### Aether 2.0｜灵魂对话

面向原生艺术创作的多模态 AI 交流空间。产品不要求用户进入页面后立刻作画，而是让对话自然抵达创作，再结合此前交流与作品整体进行回应，引导同一段旅程中产生多轮对话和多幅作品。

### HARNESS / CITY｜可演化的插件城市

将 DeepSeek Harness 的 255 个官方包和 788 条 peer 依赖重建为可探索的空间城市、依赖图谱与运行时实验室，尝试用交互方式解释复杂 Agent 架构，而不是停留在目录和连线层面。

### LLM Agent 社会仿真实验｜机会如何转化为回报

以 120 个 Agent、5 个社群和 15 轮信任博弈检验桥接位置的真实作用。研究同时设置 Rule / Random 基线与机制消融，区分结构机会、模型能力和关系稳定化。案例页支持直接预览与下载 5 页研究演示，但不公开论文原文。

### GSB Studio｜模型评估工作台

把数据集、评估标准、双盲 G / S / B 判断、一致性检验、分歧仲裁和结果报告组织成闭环，让“模型是否真的变好”成为可复检、可追溯的证据。

## 我关注的产品问题

- AI 是否真正理解了用户，而不仅是快速生成答案；
- 模型能力如何通过清晰、自然且有边界的交互被用户感知；
- 复杂技术如何被转化为可以探索和验证的产品体验；
- 主观判断如何沉淀成支持决策的可靠数据。

## 仓库内容

这是作品集网页的可独立部署静态版本：

```text
index.html                  作品集首页
projects/                   六个项目的独立案例页面
  aether-2/
  harness-city/
  agent-society-simulation/
  mindnest/
  memory-control/
  gsb-evaluation/
demos/                      HARNESS / CITY 离线交互页面
research/                   可在线预览与下载的研究演示 PDF
styles.css                  全站视觉样式
vercel.json                 Vercel 路由配置
404.html                    静态站点回退页面
portfolio-html-source.zip   可下载的完整 HTML 源码包
```

## 本地预览

源码不依赖构建工具，可以直接打开 `index.html`，也可以使用任意静态服务器：

```bash
npx serve .
```

## 部署

当前正式版本托管在 Vercel。根页面和每个案例均拥有独立地址，项目卡片中的 Demo 按钮会跳转到对应的在线产品。

## About

王蓉静，西安交通大学。关注 AI 产品、AI 交互与 AI Coding，擅长从具体体验问题中形成产品判断，并借助多模型协作、Agent 工作流和 AI Coding 将想法实现为可运行原型。

[GitHub 主页](https://github.com/YiXun-13468878779) · [在线作品集](https://yixun-ai-portfolio.vercel.app/)

© 2026 王蓉静
