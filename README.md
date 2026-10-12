# sun-yuchen-perspective

> 孙宇晨（Justin Sun / 孙哥）的思维操作系统 —— 一个可运行的 WorkBuddy 人物 Perspective Skill。

本仓库是一个**人物视角 Skill**：用孙宇晨（孙哥）的认知框架与表达方式回应问题，帮你在决策、行业趋势、认知升级上获得「孙学视角」的反馈。它不是孙宇晨本人，而是基于其公开言论蒸馏出的思维模型。

由 [女娲 · Skill 造人术](https://github.com/alchaincyf/nuwa-skill) 流程蒸馏生成。

---

## 这是什么

- **7 个核心心智模型**：认知决定命运 / 版本升级论 / 地球 online 开图 / 逐水草而居 / 薄肌=主动健康管理 / small ego / 翻译官论
- **8 条决策启发式**：早更新系统、吸收批评、开图决策、机动性优先、行为改变即智商提升、先上路后意义、多创造少消费、拒动机论
- **完整表达 DNA**：结论先行 + 反问收束 + 游戏/历史类比，可直接角色扮演
- **诚实边界**：明确标注「本人原话 vs 框架推断」、未解领域只给框架不给答案、主观非共识主张单独标注

## 目录结构

```
sun-yuchen-perspective/
├── SKILL.md                      # 主文件：角色规则 + 心智模型 + 表达DNA + 诚实边界
├── README.md                     # 本文件
├── LICENSE                       # MIT
├── .gitignore
└── references/
    ├── research/                 # 六维蒸馏调研（01-著作 / 02-对话 / 03-表达 / 04-他者 / 05-决策 / 06-时间线）
    └── sources/
        └── transcripts/          # 一手语料索引 + 核心段落锚点（节选，见下方版权说明）
```

## 安装（WorkBuddy）

```bash
# 克隆到用户级技能目录
git clone <本仓库地址> ~/.workbuddy/skills/sun-yuchen-perspective

# 重启 WorkBuddy / 新开会话后，Skill 出现在技能列表
```

> 注意：WorkBuddy 技能目录是 `~/.workbuddy/skills/`（用户级，全项目可用）。
> **不要用 `npx skills add`**——它只装到 `.claude/`、`.agents/`、`.codex/` 等目录，WorkBuddy 读不到。

## 触发方式

在对话中说以下任意一句即可激活角色扮演：

- 「用孙宇晨的视角看看…」
- 「孙哥会怎么看…」
- 「孙学 / 薄肌 / 黄毛模式」
- 「切换到孙哥」
- 「Justin Sun perspective」

一般性问答**不会**自动激活。说「退出 / 切回正常 / 不用扮演了」即退出角色。

## 核心心智模型速览

| # | 模型 | 一句话 |
|---|------|--------|
| 1 | 认知决定命运 / 认知显化论 | 财富、健康、地位都是内在认知的外显，不是资源/学历/智商决定 |
| 2 | 版本升级论 / 早更新系统 | 人生、行业、资产都是软件版本，看到更先进的就立刻更新 |
| 3 | 地球 online 游戏论 / 开图优先 | 先充分获取信息（看 100 个样本）再决策，别闷头造兵 |
| 4 | 逐水草而居 / 机动性至上 | 哪能发挥最大价值去哪，反对过早被房车婚定死 |
| 5 | 薄肌 = 主动健康管理 / 碳机一票否决 | 心肺25+肌肉25=寿命50分，肉体崩了全剧终 |
| 6 | small ego / 吸收批评 | 越成功越小 ego，被质疑先问对方有无道理 |
| 7 | 翻译官论 / 一切上网成 AI 语料 | 货币→crypto、数学→形式化证明，没被机器读=没发生过 |

> 完整证据、应用、局限与决策启发式见 `SKILL.md`。

## 来源与版权

- 核心一手语料为 **邵艾伦（Alan）× 孙宇晨** 的约 3 小时深度访谈（来源：X 视频音频）。该访谈的著作权归原作者所有。
- 本仓库为**教育性、非商业的提炼**，仅保留索引与节选段落（`references/sources/transcripts/`），未随仓库发布完整逐字稿。如需完整内容请前往原始来源。
- 提炼结论（心智模型、决策启发式、表达 DNA）由本仓库作者基于公开言论归纳，**不代表孙宇晨本人立场**。
- 角色扮演中的立场可能含其公开表达中的叙事策略，请批判性使用。

## 免责声明

- 这是一个**思维框架模拟**，不是孙宇晨本人，也不替代专业建议（投资、医疗、法律等）。
- 「薄肌 25/25 分」等数据为科普简化模型，非医学定论。
- crypto 行情、人物近况等会随时间变化，建议每 6–12 个月增量更新。

## 更新建议

蒸馏时间 **2026-10**。如发现孙宇晨有新公开表达（新访谈、新 benchmark、薄肌进展），可增量补充 `references/research/` 并同步 `SKILL.md` 的「最新动态」与「诚实边界」。

## 发布到 GitHub（维护者）

本仓库已 `git init` 并完成首次 commit。推送到 GitHub 只需两步：

1. 在 GitHub 网页 **New repository**（建议名 `sun-yuchen-perspective-skill`，**Public**，授权选 **MIT**；
   注意：**不要**勾选自动生成 README / LICENSE / .gitignore，以免与仓库内已有文件冲突）。
2. 本地终端执行（把 `<user>` 换成你的用户名）：

   ```bash
   git remote add origin https://github.com/<user>/sun-yuchen-perspective-skill.git
   git branch -M main
   git push -u origin main
   ```

   若用 SSH 密钥，把上面 URL 换成 `git@github.com:<user>/sun-yuchen-perspective-skill.git` 即可。

> 仓库根目录即技能目录本身，clone 后天然位于 `~/.workbuddy/skills/sun-yuchen-perspective`，
> WorkBuddy 重启后即可识别，无需 `npx skills`。

---

由 [女娲 · Skill 造人术](https://github.com/alchaincyf/nuwa-skill) 生成。
