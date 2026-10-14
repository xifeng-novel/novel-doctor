# 网文推审 · 去AI味诊断 / Novel-Doctor

**中文** ↓ ｜ **English** ↓

> 把「黑箱」里的拒签理由，翻译成作者能听懂的大白话。
> Translating the "black box" rejection reasons of Chinese web-novel platforms into plain language.

[![SkillHub](https://img.shields.io/badge/SkillHub-已上架-blue)](https://skillhub.cn/)
[![License](https://img.shields.io/badge/license-MIT-green)](./LICENSE)
[![Skill Version](https://img.shields.io/badge/version-2.1.2-orange)](./SKILL.md)

---
---

# 中文文档

## 这个技能解决什么问题

- 投稿被拒，平台只回一句「不符合要求」，**不给理由**
- 自己读觉得还行，读者三章就划走，**不知道问题出在哪一段**
- 知道文里有「AI 味」，但**不知道具体哪句话是 AI 味、该改成什么**
- 花钱找人看稿，对方回你「节奏有点慢、情绪不够」，**等于没说**

这个技能**不帮你写字，而是按一套成文的物理写作铁律，逐句审你的字**。

## 它输出什么

用户粘贴正文（前 3 章约 2000 字即可开始，发完整稿件更准），直接返回一份结构化诊断报告：

**① 12 项量化体检**

| 指标 | 说明 |
|---|---|
| 抽样字数 / 平均句长 | 建议 12–20 字/句，过长易被跳读 |
| 旁白句占比 | 「他没动」「他感到恐惧」「这意味着」这类替读者下结论的句子 |
| 情绪与程度概括词命中数 | 非常、猛地、突然、震惊、愤怒…… |
| 静态书面词命中数 | 面无表情、喃喃自语、横陈、淌血…… |
| 器官-动词错配数 | 指甲「掐」进皮肉、汗「砸」在地上这类物理错误 |
| 拟声词滥用数 | 咔咔咔、轰隆隆 |
| 破折号数量 | 超 3 处即列入硬伤 |
| **物理感知总分** | XX/100，**主观评级**（不是精确计分，允许 ±10 分误差） |

**② 硬伤清单** —— 每条标注 `位置 + 类型 + 原文 + 判定依据 + 改法`
**③ 修改范例** —— 挑最典型的一段，给出「AI 味 → 人味」的逐句改写示范
**④ 3 个立竿见影的动作** —— 不讲理论，直接给可执行清单

## 诊断标准从哪来

内置 **《物理感知写作技能手册》全文铁律**，共十节：

1. **核心铁律 6 条** —— 作者必须「寄生」在角色身体里 / 禁止旁白 / 禁用情绪与程度概括词 / 禁止静态书面词 / 禁止滥用拟声词 / 严格限制破折号
2. **器官-动词匹配表** —— 手掐脖子、指甲扎抠刺、脚踩迈退、牙齿牙关咬紧、眼睛眯起睁大……**每个器官只有唯一匹配的动作**
3. **液体物理反应法则** —— 低处滴落只能用「落」「滴落」，不能用「砸」
4. **声音描写的物理法则** —— 不用拟声词堆砌、不用比喻，写声音对身体的物理作用
5. **主语省并与互动衔接法则** —— 连续动作省主语；视线交汇用一句动词连接
6. **恐惧必须有来源** —— 恐惧来自认知落差，不是直接写「他很怕」
7. **空间逻辑必须严密**
8. **每章必检清单 12 条**
9. **铁律落地对照表** —— 14 条「典型 AI 句 → 物理感知改法」
10. **改写动作规范**

配套**平台侧标准**：黄金三章、前 300 字生死线、完读率、追更比、书架比、主线崩坏、话疗、战斗一笔带过。

## 效果示例

> **用户**：帮我诊断小说推审，2 万字签约被拒了。
>
> **技能**：收到。签约被拒最常见的原因是「黄金三章」没立住，我先按前 300 字生死线、主角能动性、钩子分布、物理感知人味四项查。
> 请把前 3 章发我（约 2000 字即可开始）；想一次性看全篇，直接发整本。
>
> *（用户粘贴第 1 章）*
>
> **量化体检**（每一项都附原文位置，可自行核对）：抽样 2140 字｜平均句长 27.4 字（偏长，建议 12–20）｜旁白句占比 31%｜情绪概括词 9 处｜静态书面词 5 处｜器官-动词错配 3 处｜破折号 6 处｜**物理感知总分 41/100（主观评级，允许 ±10 分误差）**

**硬伤清单（节选）**

| 位置 | 类型 | 原文 | 依据 | 改法 |
|---|---|---|---|---|
| 第3段 | 旁白 | 他感到一阵恐惧 | 铁律二·禁止旁白；铁律三·禁用情绪词 | 他后颈的汗毛立起来，脚趾在鞋里蜷了一下 |
| 第7段 | 动词错配 | 指甲掐进皮肉 | 指甲只能扎/抠/刺，不能掐 | 指甲抠进皮肉 |
| 第11段 | 液体失真 | 汗砸在地上 | 低处滴落不能用「砸」 | 汗从下颌滴落，落到砖面上 |

> **修改范例**
> 原文：他非常震惊地看着眼前的一切，仿佛不敢相信这是真的。
> 改写：他僵在原地，嘴唇动了动，没出声。半晌，他往后退了半步，手在衣角擦了一下。

## 改写对照示例（节选）

| 类型 | ❌ AI 味写法 | ✅ 物理感知改法 |
|---|---|---|
| 情绪命名 | 他非常震惊。 | 他僵在原地，嘴唇动了动，没出声。 |
| 情绪命名 | 他感到恐惧。 | 他后颈的汗毛立起来，脚趾在鞋里蜷了一下，往后贴住墙。 |
| 程度概括 | 他猛地转过头。 | 他转过头，脖子上的筋绷起来。 |
| 静态书面词 | 面无表情地看着他。 | 他看着对方，嘴角没动，眼睛没眨。 |
| 静态书面词 | 喃喃自语。 | 嘴唇一直在动，声音低得听不清字。 |
| 旁白结论 | 没人敢靠近。 | 最近的那个人退了两步，其余人的脚都钉在原地。 |
| 旁白结论 | 这意味着他完了。 | 他把手里的单子翻过来，又翻回去，纸边被捏出褶。 |
| 拟声词 | 咔咔咔，骨头响。 | 骨节一节一节顶开，震动顺着脊椎传到后槽牙。 |
| 拟声词 | 轰隆隆的雷声。 | 雷声从屋顶压下来，耳膜发闷，桌上的碗沿在抖。 |
| 动词错配 | 指甲掐进皮肉。 | 指甲抠进皮肉。 |
| 动词错配 | 瞳孔骤缩。 | 眼睛眯起，视线模糊了一下。 |
| 液体失真 | 汗砸在地上。 | 汗从下颌滴落，落到砖面上，没有一点声音。 |
| 液体失真 | 血晕开了。 | 血在砖面上散开，边缘一圈一圈地伸出去。 |
| 主语堆叠 | 我抬头看向他们。他们也看向我。 | 我抬起头，视线和他们撞在一起。 |

## 怎么用

**方式一：在 SkillHub 安装（推荐，免配置）**
搜索「**网文推审·去AI味诊断**」，安装后用自然语言触发：

- 帮我诊断小说推审
- 我的小说一股 AI 味
- 番茄 8 万字被拒了怎么办
- 帮我改改标点排版
- 旁白太多怎么改

技能内置 **39 条触发词**，覆盖 9 类真实问法。维护原则：**宁专勿宽**，每条都限定在「小说/网文/稿件」语境，避免与其它技能冲突。

**方式二：手动安装（任何支持 SKILL.md 的 Agent）**
1. 下载 [`SKILL.md`](./SKILL.md)
2. 放进你的 Agent 技能目录（路径因客户端而异，按客户端文档放置）
3. 重新加载技能列表

> 本技能是**纯文本技能**：不执行命令、不读写本地文件、不发起网络请求。

## 适合谁 / 不适合谁

**适合**：番茄 / 起点 / 晋江 / 七猫等平台的签约期、推审期作者；被拒了拿不到理由、想定位到「哪一段哪一句」的人；想按硬标准逐句排查 AI 味的人。

**不适合**：想找人**代写正文**的（本技能只诊断和示范改写，不代笔）；想要「审核包过」承诺的（平台审核无公开标准）；期待「改完必过」的（诊断能解决文本硬伤，解决不了选题和市场）。

## 关于「AI 味」的立场

AI 味不是语法错误，是**风格问题**——过于书面化、对仗工整、面面俱到。

它的本质是**文字恐怖谷**：句子通顺、辞藻华丽、语法完美，但就是没有活人情绪和温度。读者读它像吃别人嚼碎的肉，没味道还费劲。

所以本技能的判断标准不是「这句写得好不好」，而是「**这句像不像一个活人在具体处境里写出来的**」。

## FAQ

**Q：和「AI 写作工具」有什么区别？**
那些工具是**帮你写字**；这个技能是**审你的字**。它不生成正文。

**Q：用了之后签约/推审一定能过吗？**
**不能承诺。** 只做**文本层**诊断——解决旁白、AI 味、动词错配、排版标点，解决不了选题方向和市场口味。

**Q：会改我的剧情吗？**
**不会。** 只改「怎么说」，不改「说什么」。剧情、人设、情节走向一律不动。

**Q：支持英文文本吗？**
标准源自中文写作实践，最适用于**中文小说**。英文可诊断物理层规则（旁白、动词错配），但平台侧指标不适用。

**Q：要发多少字？**
**前 3 章（约 2000 字）就能开始**做快速体检；发完整稿件则追加主线审查、爽点密度、人设一致性。

**Q：真的免费吗？**
完全免费，**不限章节、不限字数、不需要付费解锁**。

**Q：会上传我的稿子吗？**
**不会。** 技能声明 `permission: 无`——不读写本地文件、不发起网络请求、不落盘任何稿件。

---
---

# English

## What this is

A free **SKILL.md** skill that diagnoses Chinese web-novel manuscripts the way an experienced editor would — and rewrites AI-flavored prose into prose that reads like a human wrote it.

**It does not write for you. It audits what you already wrote.**

> **Scope note**: this skill targets **Chinese web-novel platforms** (Fanqie 番茄, Qidian 起点, Jinjiang 晋江, Qimao 七猫). Its trigger phrases and platform metrics are Chinese-specific. The physical-perception layer, however, is language-agnostic.

## The problem it solves

- A submission is rejected with one line — *"does not meet requirements"* — **with no reason given**
- The author re-reads the draft, thinks it's fine, then readers drop off by chapter three — **and they don't know which paragraph is the problem**
- They suspect their prose reads like AI, but **don't know which sentences, or what to change them into**
- They pay for a review and get *"the pacing is a bit slow, the emotion isn't quite there"* — **which tells them nothing**

## What it outputs

Paste your text (first 3 chapters / ~2,000 characters is enough to start), get back a structured report:

**1. 12-item quantitative checkup** — sample size, average sentence length, narration-sentence ratio, emotion/degree intensifier hits, static literary-word hits, organ-verb mismatch count, onomatopoeia overuse, em-dash count, and a final **physical-perception score (XX/100)**.

**2. Defect list** — every entry tagged `location + type + original text + rule violated + suggested rewrite`.

**3. Rewrite demonstration** — the most representative passage rewritten sentence by sentence.

**4. Three immediately actionable fixes** — no theory.

## Where the standard comes from

The skill embeds the *Physical-Perception Writing Handbook* (《物理感知写作技能手册》), ten sections:

1. **Six core rules** — parasitize the character's body / no narration / no emotion or degree words / no static literary words / no onomatopoeia abuse / strictly limit em-dashes
2. **Organ–verb matching table** — each organ has exactly one correct verb set
3. **Liquid physics** — liquid falling from a low height may "fall" or "drip", never "slam"
4. **Sound physics** — no onomatopoeia stacking, no metaphor; write the sound's physical effect on the body
5. **Subject omission & gaze linkage** — drop repeated subjects; join two gazes with one verb
6. **Fear must have a source** — fear comes from a cognitive gap, not from writing "he was afraid"
7. **Spatial logic must hold**
8. **12-point per-chapter checklist**
9. **Rule-to-rewrite mapping table** — 14 AI sentence patterns and their rewrites
10. **Rewrite action guidelines**

Plus Chinese platform-side criteria: the "golden three chapters", first-300-characters line, completion rate, follow-to-read ratio, plot collapse, dialogue-only pacing.

## Example

> **User**: Diagnose my novel submission — rejected at the 20,000-word contract stage.
>
> **Skill**: Understood. The usual cause is the golden-three-chapters failing to hold readers. I'll check the first-300-characters line, protagonist agency, hook distribution, and physical-perception humanity. Send the first 3 chapters (~2,000 characters is enough to start).
>
> *(user pastes chapter 1)*
>
**Checkup**: 2,140 characters | average sentence 27.4 chars (long; 12–20 recommended) | narration ratio 31% | emotion/degree words 9 | static literary words 5 | organ-verb mismatches 3 | em-dashes 6 | **physical-perception score 41/100**

**Defects (excerpt)**

| Location | Type | Original | Rule violated | Rewrite |
|---|---|---|---|---|
| ¶3 | Narration | 他感到一阵恐惧 | Rule 2 no narration; Rule 3 no emotion words | 他后颈的汗毛立起来，脚趾在鞋里蜷了一下 |
| ¶7 | Organ-verb mismatch | 指甲掐进皮肉 | Fingernails only dig/pick/pierce | 指甲抠进皮肉 |
| ¶11 | Liquid physics | 汗砸在地上 | Low drips may not "slam" | 汗从下颌滴落，落到砖面上 |

## Before / After (excerpt)

| Type | ❌ AI-flavored | ✅ Physical-perception rewrite |
|---|---|---|
| Naming emotion | 他非常震惊。 | 他僵在原地，嘴唇动了动，没出声。 |
| Naming fear | 他感到恐惧。 | 他后颈的汗毛立起来，脚趾在鞋里蜷了一下，往后贴住墙。 |
| Degree adverb | 他猛地转过头。 | 他转过头，脖子上的筋绷起来。 |
| Static literary word | 面无表情地看着他。 | 他看着对方，嘴角没动，眼睛没眨。 |
| Narrated conclusion | 没人敢靠近。 | 最近的那个人退了两步，其余人的脚都钉在原地。 |
| Onomatopoeia | 咔咔咔，骨头响。 | 骨节一节一节顶开，震动顺着脊椎传到后槽牙。 |
| Organ-verb mismatch | 瞳孔骤缩。 | 眼睛眯起，视线模糊了一下。 |
| Liquid physics | 汗砸在地上。 | 汗从下颌滴落，落到砖面上，没有一点声音。 |
| Split gazes | 我抬头看向他们。他们也看向我。 | 我抬起头，视线和他们撞在一起。 |

## Usage

**Option 1 — Install from [SkillHub](https://skillhub.cn/)** (recommended, zero configuration). Search for **「网文推审·去AI味诊断」**, install, then trigger in Chinese natural language, e.g. 帮我诊断小说推审 / 我的小说一股 AI 味 / 番茄 8 万字被拒了怎么办.

**Option 2 — Manual install.** Download [`SKILL.md`](./SKILL.md), place it in your agent's skills directory (path varies per client), and reload the skill list.

> Text-only skill: runs no commands, reads/writes no local files, makes no network requests.

## Who it's for / not for

**For**: authors in the contract or review stage on Chinese web-novel platforms; writers rejected without a reason who want to locate *the paragraph, the sentence*; writers wanting a hard standard to audit AI-flavored prose against.

**Not for**: anyone wanting **ghostwriting** (this diagnoses, it does not write your manuscript); anyone wanting a **"guaranteed approval"** promise (platform review has no public standard); anyone expecting *"fix it and it will definitely pass"*.

## A note on "AI flavor"

AI flavor is not a grammar error — it is a **style** problem: overly literary, neatly parallel, exhaustive.

Its essence is a **textual uncanny valley**: fluent sentences, ornate vocabulary, flawless grammar, and yet no living emotion. So the criterion applied is not *"is this sentence well written?"* but *"does this read like a living person writing from inside a specific situation?"*

## FAQ

**How is this different from AI writing tools?** Those **write for you**; this **audits your writing**. It generates no prose.

**Will my submission definitely pass?** **No promise.** Text-level diagnosis only — it fixes narration, AI flavor, verb mismatches and punctuation; it cannot fix topic choice or market taste.

**Will it change my plot?** **No.** It changes *how* things are said, never *what* is said.

**Does it support English text?** The standard derives from Chinese writing practice; Chinese fiction fits best. English text can be diagnosed against the physical-layer rules, but the platform metrics do not apply.

**How much text should I send?** **The first 3 chapters (~2,000 characters)** is enough to start; a full manuscript gets the deep pass.

**Is it really free?** Yes — no chapter limit, no word limit, no paywall.

**Does it upload my manuscript?** **No.** `permission: none` — no file access, no network requests, no persistence.

---
---

## 版本记录 / Changelog

| 版本 | 变更 |
|---|---|
| **2.1.2** | 量化体检改为「写数量必须写位置」，物理感知总分改为主观评级；新增单次 8000 字上限与分批提交引导；新增异常处理第 1 条（非正文先说明）；新增《新手最常犯的 10 个错》附录 |
| **2.1.1** | 概述重构：新增面向用户的「这个技能能帮你什么」；移除会公开显示的内部维护备注 |
| **2.1.0** | 内置《物理感知写作技能手册》全文铁律；触发词 9 → 39 条；移除本地支付脚本调用，改为纯 SKILL.md 运行；量化体检 5 项 → 12 项，新增物理感知总分；新增上架元数据（author / pricing / permission / dependency）|
| 2.0.2 | 签约期与推审期双阶段诊断；排版与标点诊断 |
| 2.0.0 | 首个公开版本 |

### 规划中 / Roadmap

- 补充「短剧剧本」场景模式（物理感知层可直接复用）
- 将禁用词表与动词匹配表拆分为独立参考文件，便于增量维护
- 输出固定格式的质检报告模板（逐项 ✅/❌ 打勾 + 修复优先级）

## 仓库结构 / Repository structure

| 文件 | 说明 |
|---|---|
| [`SKILL.md`](./SKILL.md) | 技能本体 / the skill itself（39 触发词 + 物理感知十节 + 12 项体检）|
| `README.md` | 本文档，中英双语 / this bilingual document |
| [`LICENSE`](./LICENSE) | MIT |

## 许可 / License

MIT。技能文本可自由使用、修改、分发；诊断标准源自《物理感知写作技能手册》。
MIT — free to use, modify and redistribute. The diagnostic standard derives from the *Physical-Perception Writing Handbook*.

## 反馈 / Feedback

- SkillHub 技能页留言 / 评分 — leave a rating on the SkillHub skill page
- GitHub Issue

