# measured-words

*分寸 (fencun) · a sense of measure for AI writing*

分寸 is a Chinese word built from two units of length: knowing the measure of what your position allows you to say.

Left alone, an AI draft speaks as a detached analyst who owes the reader nothing — grading the reader's own product, handing their company a strategy, ranking third parties as winners and losers. Before anything another person will read, this skill checks:

- **Head** — the piece has a thesis, a structure, and an argument; without those, tone-polishing produces polite nonsense.
- **Seat** — who will read this, what the writer is to them, and what that position gives them standing to say.
- **Names** — every party the draft mentions is described through analysis, not verdicts.
- **Frame** — the categories, tiers and headings place people too; nobody the piece files under a label should read it as being put below the others.
- **Travel** — the draft is read once more as if forwarded to each person named in it, and the regrettable lines are fixed.
- **Prose** — written register, concrete over abstract, the thesis stated plainly; hedging is a posture toward the reader's territory, not a house style.

The checks are the method, not the vocabulary: findings come back in plain language, sorted by what the writer has to decide, with the line quoted and located. None of the terms above appear in what the writer reads.

Worked examples (fictional): [references/cases.md](references/cases.md).

## Install

**skills CLI**

```bash
npx skills add silviazeng/measured-words --global
```

Drop `--global` for project-only; add `--agent '*'` for all agents.

**Claude Code plugin**

```
/plugin marketplace add silviazeng/measured-words
/plugin install measured-words@measured-words
```

**claude.ai / Claude Desktop** — Skills → Add from GitHub → `silviazeng/measured-words`, or upload the repo ZIP as a skill.

**Manual** — copy `SKILL.md` and `references/` into your agent's skill folder, e.g. `~/.claude/skills/measured-words/`.

## What it is not

Not a flattery filter — generic praise is as naive as generic criticism. Not a ban on analysis — keep the structure, change the seat it is spoken from. Not a ban on honesty toward the writer — the blunt read goes in a private note, not the version that ships.

---

## 中文说明

**分寸**，由两个长度单位构成的词，指知道自己所处的位置允许自己说什么。凡是将由他人阅读的文字——提交给公司的方案、致上级的邮件、LinkedIn 内容、行业分析——动笔之前，先完成以下检查：

- **立论**：论点、结构、论据是否完整，有缺则先行补足。
- **身份**：谁会读到此文，作者以何种身份落笔，该身份允许陈述什么。
- **提及各方**：对文中提及的各方，删去评判，保留分析。
- **框架**：分类、层级、标题同样在为各方定位；凡被归入某一标签者，不应读出自己被置于他人之下。
- **传播**：设想此文被转发至文中任何一人，修正会令作者事后追悔的语句。
- **文字**：书面语，具体胜于空泛，论点直陈；试探语气仅用于涉及读者职权之处，而非全文的默认腔调。

以上是方法，不是术语：反馈须用平实语言写成，按作者需要决断的性质排序，逐条引用原句并标明出处。上述任何一个词都不应出现在作者读到的文字里。

安装方式见上文 Install 一节；手动安装即将 `SKILL.md` 与 `references/` 复制至 `~/.claude/skills/measured-words/`。

## License

MIT © 2026 Silvia Zeng
