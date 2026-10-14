<div align="center">

# 🎬 subtitle-correction

## 字幕只改错别字，时间轴一格都不动
## Fix every ASR typo without touching a single timestamp

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

专门修语音识别生成的字幕文件：只改错字和术语，严格保留时间轴、字幕编号和条目数量。开始修正前它会先向你索取领域术语——专有名词、技术框架、行业词汇，然后按这个领域的上下文做模式感知的修正。它内置的常见错误模式包括中文谐音混淆、专业术语误识、中英文混排和代码标识符拼写，比如把框架名听成谐音、把口头说出的 underscore 写进变量名。输出统一加 -corrected 后缀，并附带一个校验脚本：可以校验结构是否完整保留、生成字级彩色 diff、输出 HTML diff 报告供 review。

### ✨ 能做什么

- 只改内容：绝不改时间戳、绝不改字幕编号，也不合并或拆分条目
- 修正前先索取领域术语，按该领域上下文统一纠正全篇
- 覆盖四类错误：谐音混淆、专业术语误识、中英混排、代码标识符
- 口头描述转代码格式：underscore 转下划线、dot 转点号，识别 camelCase / snake_case
- 附带校验器：validate 检查结构保留，diff 出字级彩色对比，一键生成 HTML 报告
- 长字幕分块处理并跨块保持上下文，输出声称全篇术语一致

### 📦 包含的技能

- `subtitle-correction` —— 见 [`subtitle-correction/SKILL.md`](subtitle-correction/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/subtitle-correction.git
cp -r subtitle-correction/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

Corrects speech-recognition errors in subtitle files while leaving the timeline completely untouched. Before it edits anything it asks you for domain terminology — proper nouns, technical frameworks, industry vocabulary — then applies pattern-aware corrections using that context. Its built-in error patterns cover Chinese homophone confusion, misheard technical terms, mixed Chinese-English text and code identifier spelling, for instance a framework name heard as a homophone or an spoken underscore that belongs inside a variable name. Output is saved with a -corrected suffix, and a bundled validation script checks that structure was preserved, prints a character-level colored diff and generates an HTML diff report for review.

### ✨ What it does

- Content-only fixes: timestamps and subtitle numbers stay identical, and entries are never merged or split
- Collects domain terminology first and applies consistent corrections driven by that context
- Covers four error classes: homophones, misheard technical terms, mixed Chinese-English text and code identifiers
- Turns spoken forms into code: underscore becomes _, dot becomes ., with camelCase and snake_case recognized
- Bundled tool validates preserved structure, prints a character-level colored diff and generates an HTML report
- Handles long files in chunks with cross-chunk context so terminology stays consistent throughout

### 📦 Skills included

- `subtitle-correction` — [`subtitle-correction/SKILL.md`](subtitle-correction/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/subtitle-correction.git
cp -r subtitle-correction/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
