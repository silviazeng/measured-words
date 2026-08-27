---
name: measured-words
description: "分寸 (fencun) — knowing what your position lets you say, and who else will read it. Run before drafting anything another person will read on the user's behalf: interview slides or talking points, a deck or memo for a company, a message to a hiring manager or an executive, a LinkedIn profile, post, or article, an industry write-up or field guide, a competitive comparison, a cover letter, an outreach DM. Use it whenever a draft names a real company, product, or person, or will be seen by a manager, colleague, customer, or the public, even if the user only asks for slides, a summary, an analysis, or a post and says nothing about tone. 适用于任何将由他人阅读的文字：面试材料、提交给公司的方案、致上级的邮件、LinkedIn、行业分析。It checks the piece has a thesis, then establishes the seat the user writes from and what happens when the document travels. It prevents the default failure of writing as a detached analyst who grades the reader's own products, tells their company what to do, and ranks third parties as winners and losers the user may later face."
license: MIT
metadata:
  version: "1.0.0"
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

Answer four questions briefly, at the top of your thinking:

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

## Step 4 — Forward test before delivery

Read the draft once more in the shoes of each name in it — the reader, their boss, each third party — and ask: **if this were forwarded to them, what would the writer regret?** Fix those lines. Then put a short block at the top of the delivered draft so the writer can check the seat you assumed:

```
Seat check
Reader: [role / person] · Seat: [what the writer is to them]
Also likely to see it: [names]
Adjusted: [one line on what the check changed, or "nothing flagged"]
```

Four lines. The writer can delete it; it exists so a wrong assumption is visible immediately rather than discovered in the room.

## The prose itself — baseline standards

The seat checks remove liabilities; they add no quality on their own. Four baseline rules keep the surviving text worth reading:

- **Register.** Anything public-facing or professional is written in the written register of its language — no conversational filler, no chat idioms. This applies to every language in the draft; for Chinese, 书面语, not 口语.
- **A spine.** Converting verdicts to questions applies to the reader's territory — their product, their strategy. The writer's own observations and thesis are stated plainly. If every claim in the draft has become a question, the seat check has been over-applied: put the thesis back.
- **No template phrases.** The wordings in this skill ("I'd want to understand," "one thing I'd test") illustrate a posture, not sentences to copy. Vary the surface. Repeating them verbatim across a draft reads as boilerplate and defeats the sincerity they exist to protect.
- **Concrete over abstract.** Specific facts, numbers, named mechanisms. A sentence that could appear in any company's document about any product says nothing; cut it or sharpen it.

## What this skill is not

- Not a flattery filter. Specific respect for what the reader built is the goal; generic praise is as naive as generic criticism.
- Not a ban on analysis. Keep the structure; change the seat it is spoken from.
- Not a ban on honesty toward the writer. If the honest read is that the company has a problem, tell them privately and help them decide what, if anything, to bring into the room.

## Reference cases

Read `references/cases.md` when the draft is an interview deck, a company-facing memo, or an industry overview. It holds the two canonical failures this skill exists to catch, with before/after rewrites.
