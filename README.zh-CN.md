# geo-keyword-builder

`geo-keyword-builder` 是一个用于 **GEO（Generative Engine Optimization / 生成式引擎优化）关键词、Prompt、实体和问题集群构建** 的 skill。

它的目标不是简单生成传统 SEO 关键词，而是帮助你找到：

- 用户会向 AI 搜索 / 生成式引擎提出的问题；
- AI 为了回答这些问题可能展开的 query fan-out；
- 哪些实体、竞品、功能、使用场景和对比关系需要覆盖；
- 哪些内容更容易被 AI 答案引用、总结或推荐；
- 应该创建哪些页面、FAQ、对比页、案例页、榜单页或第三方声誉资产。

## 适合使用的场景

- 做 GEO / AEO / LLMO 关键词研究；
- 为 ChatGPT、Gemini、Perplexity、Copilot、Claude、Google AI Overviews 做 prompt cluster；
- 为品牌或产品规划 AI 搜索可见度；
- 从传统关键词升级到“AI 会回答的问题”；
- 制定内容 brief、对比页、FAQ、实体页和第三方提及策略。

## 文件结构

```text
geo-keyword-builder/
├── SKILL.md
├── README.zh-CN.md
├── templates/
│   ├── input-brief.md
│   ├── output-report.md
│   └── geo-keyword-table.csv
├── schema/
│   └── geo-keyword-record.schema.json
└── examples/
    └── example-output.md
```

## 快速使用方式

把整个 `geo-keyword-builder` 文件夹放进你的 skills 目录，然后用类似下面的指令调用：

```text
Use geo-keyword-builder to build a GEO keyword and prompt map for [brand/product/topic].
Target audience: [audience]
Market: [country/language]
Competitors: [competitors]
Goal: [awareness/leads/sales/authority]
Output depth: standard
```

## 推荐输入

- 品牌 / 产品 / 网站；
- 行业或细分市场；
- 目标用户；
- 目标地区和语言；
- 主要竞品；
- 业务目标；
- 已有内容或 URL；
- 希望输出 quick / standard / deep。

## 推荐输出

- Executive Summary；
- Assumptions；
- Priority GEO Clusters；
- GEO Keyword / Prompt Table；
- Query Fan-out Map；
- Entity Map；
- Content Briefs；
- Quick Wins；
- Earned Media Opportunities；
- Measurement Plan；
- Next Actions。
