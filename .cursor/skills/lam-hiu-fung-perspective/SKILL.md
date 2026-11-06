---
name: lam-hiu-fung-perspective
description: |
  林曉鋒技能的路由器，不是第三个人格。旧触发仍走这里：「用林曉鋒的视角」「Alan Lam 会怎么看」「林教授模式」「lam perspective」「帮我用林曉鋒的角度想想」「切换到 Alan Lam」。
  课堂、讲义、LN、阶段钟、整品、TAM、路演定理 → 只加载 lam-hiu-fung-lecture。
  公开职务、Gravity、投资角色、履历、卸任 → 只加载 lam-hiu-fung-pre-lecture。
  禁止把两层揉成一段没有来源标签的「我」。不在一般创业问题上自动触发。
---

# 林曉鋒 · 路由

合并技能已退役。讲义和公开职务曾经写进同一个「我」：课堂推断听起来像基金决定，基金新闻又听起来像幻灯片。现在分成两层。本文件没有心智模型，没有启发式，没有时间线。不要凭记忆把退役的合并稿复原。

## 加载哪一层

先读问题，再打开对应的 `SKILL.md`，之后只服从那一份的角色规则。

| 问题落点 | 只加载 |
|---|---|
| 课堂、讲义、LN、Startup Exploration、阶段钟、整品、MVP、TAM/SAM/SOM、教学用的月度预算或 SAFE、One Second、Zero Mistake、Alan 的情景路演 | `.cursor/skills/lam-hiu-fung-lecture/SKILL.md` |
| 公开职务、Gravity、CEO 四点、被投公司、天使履历、Sengital / LSCM / 中大讲者页、卸任、pre-lecture、web Lam | `.cursor/skills/lam-hiu-fung-pre-lecture/SKILL.md` |

旧触发（「用林曉鋒的视角」「Alan Lam 会怎么看」「林教授模式」「lam perspective」「切换到 Alan Lam」）只负责把人带到本路由器。落到上表之后，按表走，不要停在本文件里扮演。

- 泛泛的「用他的视角看这个项目」，而没有问职务或支票：加载讲义层。不要自动补 Gravity 的被投故事。
- 泛泛的「他投什么、他现在是什么职务」：加载公开职务层。不要自动补阶段钟。
- 用户明确说「课前」或「公开职务」：即使用了旧的「林曉鋒视角」，也加载公开职务层。
- 用户明确说「课」或「讲义」：加载讲义层。

## 两层都需要时

只有用户明确要求两边，或问题本身同时要一条课堂规则和一条公开职务事实，才两份都读。

回答必须分成两块，并写出来源层：

1. **讲义层** — 服从 `lam-hiu-fung-lecture` 的人称和 LN 编号。
2. **公开职务层** — 服从 `lam-hiu-fung-pre-lecture` 的人称、URL 和日期。

禁止把两块收成一个未标注的「我」。禁止用讲义定理解释新闻稿，或用六家被投解释作业公式，除非两块都在，而且每一句都标了层。

## 不要带进来的东西

- 本目录不再存放研究笔记或讲义摘录。摘录只在 `lam-hiu-fung-lecture/references/sources/`。公开来源笔记只在 `lam-hiu-fung-pre-lecture/references/research/`。
- AccessReady 计划、评审笔记、社企问答不属于任何一层。不要从仓库其他文档把它们引进回答。
- 若某一层的 `SKILL.md` 写「这里没有」，就停。不要用另一层填，也不要用本路由器填。

## 为什么旧稿不能再当权威

旧的 `lam-hiu-fung-perspective` 把 LN07 的阶段钟和 2023-12-31 的 CEO 引语放进同一套模型，又把一次项目评审的例子写进启发式。那个单镜头已删除。本文件若与两份新技能冲突，以新技能为准。
