# Industry-Keyword-Research
📄Use this skill to turn a vague curiosity such as "I want to understand ChatGPT" or "Which AI
application direction should I do?" into an auditable industry report. The default method is:
write the Day-1 hypothesis, gather tiered evidence, extract a 100-keyword map, build the market
and competitive logic, pressure-test the numbers, then produce a report or deck-ready storyline.
This is a research and strategy skill, not a stock recommendation skill. Treat stock prices,
ETF moves, valuation changes, earnings reactions, and sector rotation as market-expectation
signals. Do not give buy/sell instructions, price targets, or personalized financial advice.
#Workflow
Frame the brief and write the Day-1 answer.
Identify the user's target: beginner learning, industry report, project direction,
investment-signal reading, expert interview prep, or deck/PDF output.
Identify scope: industry/topic, geography, time horizon, audience level, and whether the
user needs the output in Chinese, English, or bilingual form.
Write an explicit provisional answer before deep research. Research is responsible for
falsifying or revising this answer, not for collecting evidence that flatters it.
Draft a Ghost Deck: a pure action-title outline before any visual layout.

Gather current evidence through a Source Bar.
For recent or fast-changing topics, browse or otherwise use current sources. Prefer primary
sources: company filings, earnings calls, official product docs, policy documents, academic
papers, reputable industry reports, and named expert commentary.
Use market data only as a signal layer. Note date ranges and distinguish facts from
interpretation.
Classify every important source as T1/T2/T3/T4. Pricing requires T1. Market size requires at
least T2. User pain requires real user/practitioner language when possible.
If browsing is unavailable, state the limitation and mark freshness risk explicitly.

Build the 100-keyword industry map.
Generate a candidate pool of 120-160 terms, then select exactly 100.
Cluster terms into 5-8 categories by relationship strength, not by superficial alphabetic or
textbook order.
For each category, explain the strategic question it answers.
For each keyword, provide one sentence that defines the term in the context of this industry.
Add "strong / medium / weak-emerging" relationship strength when the user asks for keyword
connections or prioritization.

Explain the industry for a beginner.
Start with the "100 keywords method": learning the vocabulary reveals the industry's actors,
value chain, constraints, business models, risks, and unsolved problems.
Avoid jargon-first explanations. Define hard terms using plain language, then add the
strategic implication.

Build the research argument.
Provide one collective thesis sentence that defines what these 100 keywords say about the
industry as a whole.
Identify 3-5 core tensions, such as cost vs. capability, adoption vs. regulation, supply
bottleneck vs. demand growth, or product novelty vs. durable distribution.
Separate "what is already obvious" from "where there may still be information advantage."
Use bottom-up sizing for TAM/SAM/SOM and unit economics; use top-down numbers only as a
cross-check. Show formulas, units, assumptions, and judgment calls.
Use competitive heatmaps and Good/Better/Best tiers when comparing products or players.

Map people and conversations.
Identify leading experts, builders, researchers, investors, analysts, and creators only after
checking current relevance when the user asks for "recent", "head", "top", or "now".
For each person or account, explain what to learn from them. Avoid empty name-dropping.
Generate expert interview topics that would interest a real insider: unresolved tradeoffs,
non-consensus data, bottlenecks, customer behavior, regulatory constraints, economics, and
second-order effects.

Reverse-plan project directions.
Convert the research into 3 project directions: safe/core, aggressive/early, and watchlist.
Score each direction on trend strength, evidence quality, timing, user pain, execution fit,
competitive intensity, monetization path, and downside risk.
For the chosen direction, create a 7/30/60/90-day plan with validation experiments, success
metrics, kill criteria, and the next information to monitor.

Verify before delivery.
Recalculate all key numbers, especially market size, pricing, gross margin, conversion,
payback, and return period.
Look for duplicate counting, unit mismatch, inconsistent denominators, optimism bias, and
unsupported conversion assumptions.
If multi-agent or subagent tools are available, run a separate skeptical verification pass.
Otherwise perform a second-pass audit with the same skeptical checklist.
If producing files, store sources, claims, assumptions, calculations, and verification status
in data.json or an equivalent structured artifact.

Hand off to deck production when requested.
If the user asks for slides, a PDF, a McKinsey deck, or an executive report, use this skill
for the research structure and then use mckinsey-deck for the visual deck engine.
Keep research headlines as action-title conclusions so they can become deck slide titles.
Do not deliver a deck that fails source, number, logic, or visual QC.

Reference Routing
Read references/100-keyword-method.md when the user asks what the McKinsey 100-keyword
method is, asks for beginner explanation, or asks how to understand an industry quickly.
Read references/mckinsey-research-system.md when the user asks for an industry research
report, market research workflow, McKinsey-style methodology, Ghost Deck, SCQA, pyramid logic,
or a boardroom-ready argument.
Read references/signal-rubric.md when the task involves trend judgment, stock/ETF/market
signals, project direction selection, or execution prioritization.
Read references/source-bar-and-validation.md when the task needs source quality, numeric
traceability, adversarial verification, calculation checks, or source registry design.
Read references/research-data-schema.md when producing files, JSON artifacts, repeatable
research pipelines, or auditable report/deck data.
Read references/output-templates.md when producing the final answer, especially for the
four common prompts: method explanation, 100 keywords, one-sentence definitions, and
influencer/expert questions. Also use it for industry-report and decision-page outputs.
Read references/expert-interviews.md when the user asks who to follow, who the head creators
are, or what to discuss with experts.
Read references/chatgpt-seed-taxonomy.md when the topic is ChatGPT or generative AI. Treat it
as a seed taxonomy, not as a substitute for fresh research.
Read references/deck-handoff.md when turning the research into a McKinsey-style deck.
#Output Standards
Use Chinese by default when the user writes in Chinese.
Use tables for 100-keyword lists unless the user asks for prose.
Make exactly 100 keyword rows when the task says "100 keywords".
Keep each keyword definition to one sentence.
Include sources and dates for current claims.
Label uncertain inferences.
Do not overfit the analysis to stock price moves; always seek at least two non-price confirming
signals.
Treat visuals as the last mile. A pretty deck does not compensate for weak evidence, broken
math, or a storyline that cannot be read from titles alone.
运用这套分析方法，能把 “我想搞懂大健康产业”“我该布局哪个 AI 应用赛道” 这类模糊的探索诉求，转化为一份可核验、可追溯的行业调研报告。标准分析流程如下： 撰写初始核心假设 分层搜集佐证论据 梳理出百词行业关键词图谱 搭建市场格局与竞争底层逻辑 对各类数据做压力校验 最终输出可直接成文报告或演示 PPT 的完整叙事框架 该工具属于产业研究与战略分析方法，并非股票荐投工具。文中仅将股价、ETF 走势、估值波动、财报市场反馈、行业板块轮动作为反映市场预期的参考信号，不提供任何买卖操作指导、目标价位预测及个性化理财建议。
一、搭建分析框架，产出首日交付稿
明确用户核心目标：行业入门学习、行业报告撰写、项目方向研判、投资信号解读、专家访谈筹备，或是 PPT 演示文稿 / PDF 报告输出。
界定分析边界：所属行业 / 细分赛道、覆盖地域、时间周期、受众专业层级；确认交付文稿语言：中文、英文或双语。
撰写前置初步结论（正式调研前输出明确预判）：调研环节负责证伪 / 修正该结论，而非单纯搜集佐证观点的素材。
草拟「底稿演示框架」：仅用行动导向标题搭建完整大纲，暂不设计视觉版式。
二、依托信源库归集最新佐证素材
针对新兴、快速迭代赛道，检索并梳理时效性素材；优先采用一手信源：企业财报、业绩电话会纪要、官方产品文档、政策文件、学术论文、权威行业白皮书、实名行业专家观点。
市场数据仅作为辅助参考维度；标注数据时间区间，严格区分客观事实与主观解读。
所有核心信源按可信度划分为 T1/T2/T3/T4 四级：定价测算必须采用 T1 一级信源；市场规模测算至少采用 T2 二级信源；用户痛点分析尽量引用从业者、真实用户原始表述。
若无法开展实时检索，需明确标注局限性，并高亮提示内容时效性风险。
三、搭建行业百词认知图谱
先生成 120–160 个候选术语池，从中精准筛选 100 个核心关键词。
依据术语关联强度聚类为 5–8 大板块，禁止按字母、教科书目录等表层逻辑分类。
针对每一大类，说明该板块可解答何种战略核心问题。
每个关键词配一句行业语境专属定义。
若用户要求标注关键词关联度 / 优先级，补充标注关联强度：强关联、中等关联、新兴弱关联。
四、面向行业新手做通俗产业解读
以「百词分析法」为切入点：吃透行业术语，即可理清行业参与主体、产业链、发展约束、商业模式、潜在风险与待解决行业痛点。
避免开篇堆砌专业术语：先用大白话解释晦涩概念，再补充对应的战略商业价值。
五、构建完整调研论证逻辑
提炼一句总论点，概括 100 个关键词共同指向的行业核心格局。
梳理 3–5 组核心行业矛盾，例如：成本控制 vs 产品性能、市场渗透率 vs 监管约束、供给瓶颈 vs 需求增长、产品创新力 vs 成熟分销渠道。
区分「行业公认常识」与「存在信息差、具备研判优势的细分领域」。
采用自下而上测算逻辑推导总潜在市场（TAM）、可服务市场（SAM）、可获取市场（SOM）与单体经济模型；自上而下测算仅用作交叉校验。完整列明计算公式、计量单位、测算假设与主观判断依据。
产品 / 竞品对比时，使用竞争热力图与「达标 / 优秀 / 顶尖」三级分层框架。
六、梳理行业核心人物与访谈议题
仅在用户需求含「近期、负责人、头部、当下」限定词时，才筛选当下具备行业影响力的专家、创业者、研究员、投资人、分析师、行业创作者。
对每位人物 / 账号，说明可借鉴的核心洞察，杜绝无意义罗列人名。
设计内行关心的访谈议题：未达成共识的行业取舍、非一致预期数据、产业链瓶颈、客户真实行为、监管约束、商业模式收益、次生连锁影响。
七、反向推演落地项目方向
基于调研成果输出三类项目路径：稳妥核心赛道、激进早期赛道、观察跟踪赛道。
对每条路径从八大维度打分：趋势强度、佐证素材质量、落地窗口期、用户痛点强度、团队落地匹配度、行业竞争烈度、变现路径清晰程度、下行风险。
针对选定路径，制定 7/30/60/90 天落地规划，包含验证实验、成功衡量指标、项目终止判定标准、后续重点跟踪信息。
八、交付前复核校验
重新核算全部核心数值：市场规模、定价、毛利率、转化效率、回本周期、投资回报周期。
排查重复统计、单位不统一、计算基准不一致、乐观预估偏差、无依据转化假设四类问题。
若支持多智能体 / 子工具，单独启动一轮质疑式复核；若无，则基于同一套核查清单完成二次审计。
若输出文件类成果，将全部信源、核心论断、测算假设、复核状态统一存入 data.json 或同类结构化归档文件。
九、向 PPT 制作环节移交成果（用户要求时执行）
若用户需要幻灯片、PDF、麦肯锡风格演示文稿、高管汇报材料，先依托本套调研框架完成分析，再调用麦肯锡演示文稿引擎生成可视化版式。
所有调研结论保留行动导向标题，可直接复用为单页幻灯片标题。
交付前完成四重质检：信源合规、数据准确、逻辑自洽、视觉规范，未通过质检不得输出演示文稿。
信源调取规范
#用户询问「麦肯锡百词分析法是什么」「行业入门讲解」「快速吃透行业方法」，调取参考文档：references/100-keyword-method.md
用户索要行业报告、市场调研流程、麦肯锡研究方法论、底稿演示框架、SCQA 结构、金字塔逻辑、董事会级论证体系，调取参考文档：references/mckinsey-research-system.md
任务涉及趋势判断、个股 / ETF / 市场信号、项目路径筛选、落地优先级排序，调取参考文档：references/signal-rubric.md
需做信源分级、数值可追溯、对抗式复核、计算校验、信源归档设计，调取参考文档：references/source-bar-and-validation.md
输出文件、JSON 结构化素材、可复用调研流程、可溯源报告 / 演示文稿数据，调取参考文档：references/research-data-schema.md
产出最终交付材料，尤其四类高频需求：方法论解读、百词关键词表、术语单句释义、行业专家访谈问题；同时适配行业报告、决策页输出模板，调取参考文档：references/output-templates.md
用户询问行业重点人物、头部创作者、与专家访谈沟通要点，调取参考文档：references/expert-interviews.md
议题为 ChatGPT / 生成式 AI 时，调取参考文档：references/chatgpt-seed-taxonomy.md，仅作为基础分类框架，不能替代全新调研素材。
将分析内容转化为麦肯锡风格演示文稿时，调取参考文档：references/deck-handoff.md
#交付输出规范
用户使用中文提问，默认全文输出中文；用户使用英文提问则输出英文。
百词关键词清单统一采用表格呈现，用户明确要求纯文字除外。
关键词任务必须严格输出 100 行关键词条目。
每条关键词释义控制为单句。
所有时效性观点必须标注对应信源与发布日期。
存疑推论明确标注「不确定性判断」。
分析不可过度贴合股价走势解读，每项趋势结论至少搭配两项股价以外的佐证信号。
视觉版式仅作为最后优化环节；美观的演示文稿无法弥补素材薄弱、计算错误、逻辑断裂，或标题无法独立传递核心观点的缺陷。
