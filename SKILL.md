---
name: measured-words
description: "分寸 (fencun) — knowing what your position lets you say, and who else will read it. Run before drafting anything another person will read on the user's behalf: interview slides or talking points, a deck or memo for a company, a message to a hiring manager or an executive, a LinkedIn profile, post, or article, an industry write-up or field guide, a competitive comparison, a cover letter, an outreach DM. Use it whenever a draft names a real company, product, or person, or will be seen by a manager, colleague, customer, or the public, even if the user only asks for slides, a summary, an analysis, or a post and says nothing about tone. 适用于任何将由他人阅读的文字：面试材料、提交给公司的方案、致上级的邮件、LinkedIn、行业分析。It checks the piece has a thesis, then establishes the seat the user writes from and what happens when the document travels. It prevents the default failure of writing as a detached analyst who grades the reader's own products, tells their company what to do, and ranks third parties as winners and losers the user may later face."
license: MIT
metadata:
  version: "1.4.0"
---

# measured-words · 分寸

分寸 is a Chinese word built from two units of length. It means knowing the measure of what your position allows you to say. The closest English is *a sense of measure*, or *measured words*.

## The problem this fixes

Left alone, a draft comes out in the voice of an outside analyst who owes the reader nothing: it grades the reader's product line, tells their company what it should do, and sorts the rest of the industry into winners and losers. That voice is fine for a consultant's internal memo. It is wrong for almost everything a person actually sends, because the writer is nearly always inside a relationship: a candidate to a hiring manager, a new hire to a VP, a guest describing the host's house. Two things go wrong at once when that is ignored:

1. **The reader in the room is insulted.** A proposal that calls the prospective customer's current system "outdated" and then lists what their company "should do" is condescending to the people who built and run that system, however correct the analysis.
2. **The document travels.** Industries are small. A field guide framed as "who can stop whom" reads fine today and becomes an embarrassment the day the writer interviews with, sells to, or sits in a meeting with one of the companies on the losing side of that framing.

Both failures have the same root: nobody asked who the writer is to this reader, and who else will read it. This skill asks before the draft, not after.

## Step 0 — Does the piece have a head? (triage, before anything else)

Before checking tone, check that there is something worth toning. Three questions, each answered yes or no:

- **Thesis**: can the piece's point be stated in one sentence?
- **Structure**: does it follow an arc a reader can track?
- **Argument**: is the evidence present, or are there leaps?

If any answer is no, fix that first and say so. Polishing the seat of a piece with no head produces polite nonsense. Only when all three pass does the rest of this skill apply.

## Step 1 — Name the seat

Answer four questions briefly, in your own reasoning — not in what you hand back:

- **Reader**: who reads this first? Name the role, and the person if known. "Leadership" is not an answer; "the sales VP who joined two months ago" is.
- **Seat**: what is the writer to that reader? Candidate, new hire, peer, former investor, vendor, stranger on the internet.
- **Standing**: given that seat, what does the writer have the right to say? What would be presumptuous?
- **Travel**: who else plausibly sees this? Forwarded to the CEO, shown to a competitor, indexed by search, read by a future interviewer at a company named inside it.

Standing is the part that gets skipped. A rough map:

| Seat | Has standing to | Does not have standing to |
|---|---|---|
| Candidate → hiring manager | Show understanding of their market; ask sharp questions; bring outside signal (what customers, channels, competitors are doing) | Grade their products or pricing; hand them a strategy; use "you should" |
| New hire → manager / VP | Bring observations and options; propose things to test; ask what they already know | Redirect the company; imply the current approach is wrong |
| Former investor → founder | Share patterns from other companies; offer help | Tell them their business is mispriced |
| Author of a public piece → the industry | Describe structure, positioning, trade-offs | Rank real companies as winners and losers; predict who "gets stopped" |

If the seat is unclear, ask one question before drafting. It is cheaper than a draft that has to be thrown away.

## Step 2 — The reader's own company: describe what they built, not what's wrong with it

When the reader works at the company being discussed, the frame is **what they have built and where the openings are**, never **what is wrong with them**.

- Product characterizations that are pejorative from the inside (cheap, low-end, commodity, follower, lagging, me-too) do not appear — and not elsewhere in the document either, even about something unrelated. A reader scanning a page about their own company reads the word as being about them. If price is the point, the neutral version is "cost-competitive," "priced for volume," or the actual number. A weakness surfaces as a question ("How are you thinking about X?") or an area to explore, not a verdict.
- "You should" becomes "I'd want to understand," "one thing I'd test," or "a question I'd bring to the team." Recommendations from a candidate or new hire are hypotheses offered, not instructions handed down.
- The company's actual achievements get named specifically. Not flattery: a sentence that shows the writer knows what they did (a flagship customer, a certification, the segment they own) is the credibility the rest of the document rides on. Empty praise ("a leader in innovation") is its own kind of naive; skip it.
- Numbers and rankings about the reader's own company are stated only the way the reader would state them. "Third globally, behind X" is fine if that is how they describe themselves; "trails X and Y" is the same fact with a knife in it.

The posture: a well-prepared guest who clearly did the reading, is curious, and knows it is not their house yet.

## Step 3 — Everyone else named: the show-it-to-their-CEO test

For every third party the document mentions — competitors, customers, partners, former employers, named people — run one test: **could this sentence be shown to that company's CEO without embarrassment?** If not, rewrite it. This is about the writer's future, not about being nice.

- Winner/loser, "who beats whom," "who can stop whom," "X is doomed" → neutral structure: how the segments are positioned, what each player optimizes for, where the trade-offs lie. The analysis survives; the verdicts go.
- Judging adjectives (weak, struggling, failing, second-tier, also-ran) → observable facts (share, focus, recent moves) or nothing.
- Predictions about a specific company's decline → conditions under which the segment shifts, without naming who loses.
- Anything sourced from the writer's private knowledge (a contact's remark, a former employer's internal figure) → out, unless public.

Blunt analysis has a place: the writer's own eyes. If they asked for the honest read, give it clearly labeled as private, in a separate block, and keep the outward-facing document clean. Never let the private read leak into the version that ships.

## Step 4 — The frame places people too

Steps 2 and 3 test sentences. A document also places people through things that are not sentences: category names, tiers, section headings, axis and legend labels, and what is listed first or drawn largest. Each of those is a claim about everyone filed under it, and reading the prose will not find any of them.

Run one test over the list Step 1's travel question already produced — the reader, their company, customers, partners, competitors, former employers, anyone drawn into the document at all, whether or not they will ever read it:

**would anyone filed under this label read it as being placed below the others?**

- Yes → name the category after what it is. The distinction almost always survives in the layout — an indent, a separate panel, a border — and only the rank goes. A label that cannot be replaced by a plain name is there to order things, and ordering named parties is the Step 3 verdict moved into a different grammatical position.
- No → leave it. Upstream and downstream say where something sits in a flow; pilot and rollout say what stage it is at. Neither places anyone below anyone.

This check belongs to neither Step 2 nor Step 3, because a single label can demote the reader and a third party at the same time.

## Step 5 — Forward test before delivery

Read the draft once more in the shoes of each name in it — the reader, their boss, each third party — and ask: **if this were forwarded to them, what would the writer regret?** Fix those lines. Then, under the delivered draft, say in two or three plain sentences who you took the reader to be, who else could end up seeing it, and what that changed. Write it the way you would say it to a colleague — not as labelled fields, and not using the words in this file. It exists so a wrong assumption about the reader is visible immediately rather than discovered in the room; the writer can delete it.

## The prose itself — baseline standards

The seat checks remove liabilities; they add no quality on their own. Four baseline rules keep the surviving text worth reading:

- **Register.** Anything public-facing or professional is written in the written register of its language — no conversational filler, no chat idioms. This applies to every language in the draft; for Chinese, 书面语, not 口语.
- **A spine.** Converting verdicts to questions applies to the reader's territory — their product, their strategy. The writer's own observations and thesis are stated plainly. If every claim in the draft has become a question, the seat check has been over-applied: put the thesis back.
- **No template phrases.** The wordings in this skill ("I'd want to understand," "one thing I'd test") illustrate a posture, not sentences to copy. Vary the surface. Repeating them verbatim across a draft reads as boilerplate and defeats the sincerity they exist to protect.
- **Concrete over abstract.** Specific facts, numbers, named mechanisms. A sentence that could appear in any company's document about any product says nothing; cut it or sharpen it.
- **Self-contained.** Every term of art, numbered reference and pointer to another document has to be resolvable inside the piece. "Stage three," "the framework from the last review," "as the earlier note set out" — a reader who cannot resolve those is being asked to nod along at something they cannot see, and most will simply stop trusting the passage. Define it where it is used, or cut it. This bites hardest in a series: the day one part is renamed, moved or taken down, every reference to it from the others turns into noise, and nobody goes back to the others to notice. The check is to read the piece as someone holding only this piece — no series, no prior meeting, no author to ask.
- **Nothing the artifact already says.** The mirror of the rule above, and the one that keeps coming back. Cut every line that repeats what the reader can already see, or has just read one line earlier. It arrives in four shapes: a caption narrating what the drawing shows ("flows left to right", when the arrows are drawn); a legend entry for a mark that already carries its own label; a note that opens by restating its own heading; and a note defending against an objection nobody has raised — "this is not an omission," "this is deliberate," "to be clear." Same test each time: name what is genuinely invisible — an encoding, a rule, a pointer out of the piece — and write only that. And cut rather than shorten: a redundant line trimmed by half still teaches the reader to skim, and the two things they could not have known get skimmed along with it.

## Reporting back — the part the user reads

The checks above are your method. They are not vocabulary the user has agreed to learn. Every term in this file — seat, standing, travel, the step numbers, 分寸 itself — stays in your reasoning. "Step 3 flag: fails the show-it-to-their-CEO test" gives the user nothing to act on. "This line says a former employer decided the product wasn't worth fighting for — the person who made that call can recognise themselves in it" gives them everything, and it is the same finding.

Write the report in the user's language, for someone who has never read this skill and never will. If a sentence of yours would need this file to decode, rewrite it. A skill about writing legibly that reports illegibly has failed at its own subject.

**After drafting**, follow Step 5: the draft, then two or three plain sentences on the reader you assumed.

**When reviewing something already written**, sort findings by what the user has to decide, never by which check produced them:

1. **Broken** — factual errors, leftover import artifacts, dead links, things no author would keep on purpose. State them; they need no argument.
2. **Costly to the writer** — a line naming, or traceable to, a real person or company, where the cost lands on the writer if it travels. Quote the sentence, give its location, name who reads it and what it costs. One flag, one reason.
3. **Judgment calls** — voice, register, how much of the writer's own life sits on a public page. Give them the trade-off; do not resolve it for them.

Quote the line you are flagging and say where it is. A finding the writer cannot find in their own text is not a finding. Say plainly what passed, too — a review that only lists faults misrepresents the work.

## What this skill is not

- Not a flattery filter. Specific respect for what the reader built is the goal; generic praise is as naive as generic criticism.
- Not a ban on analysis. Keep the structure; change the seat it is spoken from.
- Not a ban on honesty toward the writer. If the honest read is that the company has a problem, tell them privately and help them decide what, if anything, to bring into the room.

## Reference cases

Read `references/cases.md` when the draft is an interview deck, a company-facing memo, or an industry overview. It holds the three canonical failures this skill exists to catch, with before/after rewrites.
