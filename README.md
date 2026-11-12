# xpyi01

<p>
  <img src="assets/badge-engine.svg" alt="ENGINE L1-L8" height="20" />
  <img src="assets/badge-typescript.svg" alt="TypeScript" height="20" />
  <img src="assets/badge-mit.svg" alt="MIT" height="20" />
  <img src="assets/badge-status.svg" alt="v0.1 beta" height="20" />
</p>

**命理术数工程 · 四柱八字确定性量化引擎*子平大运流年动态信号**

> 命盘算对，模型说话。

---

## 关于

我把四柱八字当作一个可计算的系统来做，而不是一段无法复现的经验叙述。

排盘、神煞、空亡、大运流年、格局研判，逐项拆成规则；每条规则有编号、有明确的输入输出和判断边界。模型只在引擎之上负责解释与组织语言，不参与真正的推算。同一个命盘问十次，结论应当一致。

每条论断都要能追溯：落到干支、规则编号，或者具体的典籍原文。

## 核心项目

### sizhu-bazi-yishi-shentong

**四柱八字确定性引擎 + L1–L8 检索推演框架**

`TypeScript` · `MIT` · v0.1 beta · 最近更新 2026-11-11

排盘、神煞、空亡、大运流年、格局研判逐项拆成规则，输出固定结构；每条断语绑定规则编号或典籍出处。

| 层 | 职责 |
| --- | --- |
| L1 | 信息采集（出生时间、地点、历法换算） |
| L2 | 排盘落位（四柱、神煞、空亡） |
| L3 | 原局结构分析 |
| L4–L8 | 推演与检索层：岁运、规则编号、典籍条目、断语生成 |

工程目标只有一个：结论可验证、可复现、可回溯。

[源码](https://github.com/xpyi01/sizhu-bazi-yishi-shentong-v0.1-beta) · [英文版](https://github.com/xpyi01/sizhu-bazi-yishi-shentong-v0.1-beta/blob/main/README_EN.md) · [文档](https://github.com/xpyi01/sizhu-bazi-yishi-shentong-v0.1-beta/tree/main/docs) · [Issues](https://github.com/xpyi01/sizhu-bazi-yishi-shentong-v0.1-beta/issues) · [License](https://github.com/xpyi01/sizhu-bazi-yishi-shentong-v0.1-beta/blob/main/LICENSE)

## 工作方式

1. **算与说分离** —— 计算归引擎，表达归模型，边界不混。
2. **规则编号化** —— 每条判断有 ID，可被引用、可被反驳、可被单独测试。
3. **出处优先** —— 断语指向典籍原文，不做无来源的玄虚断言。
4. **多门派并存** —— 袁树珊、徐子平、韦千里等体系各自成规，不强行合并口径。

## 技术栈

TypeScript · Python · 本地大模型推理（CUDA / DeepSeek）· 文档解析与 OCR（MinerU）

## 当前在做

- 打磨 L1–L8 的分层边界与固定输出格式
- 古籍知识库的结构化归档：原文不翻译、不归纳，保留原生表述
- 多门派方法论的规则对齐与冲突标注

## 交流

有具体命盘反例、规则冲突或结论质疑，欢迎开 [Issue](https://github.com/xpyi01/sizhu-bazi-yishi-shentong-v0.1-beta/issues)。反例比赞美有用。
