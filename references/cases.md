# Reference cases

Three fictional cases. The companies, products, and people are invented to illustrate the three failure modes; any resemblance to a real company is coincidence. Each shows the seat that was ignored, why the draft failed (the reader in the room, or the document traveling), and what the corrected version does instead.

---

## Case 1 — The proposal that graded the customer's own system

**Situation.** A solutions consultant at a software vendor writing a proposal for a prospective customer — a regional grocery chain evaluating its online ordering. The readers are the chain's e-commerce team, who built and run the current system. Seat: vendor → prospective customer.

**What the draft did.** Analyst voice. It opened with a current-state assessment that called the chain's ordering site outdated and clunky, then listed what the chain "should do" — replatform now, consolidate on a modern stack.

**Why it failed.**
- *Reader in the room:* the people evaluating the proposal built the system it grades. "Outdated" is a verdict on their work, delivered by someone asking for their budget. "You should" puts the vendor above a customer that hasn't bought anything yet.
- *Standing:* a vendor has standing to show they understand the customer's operation and to propose things to test. They have none to grade the customer's past decisions or dictate its roadmap.
- *Travel:* proposals get forwarded — to the CIO who approved the current system, and to the champions of competing vendors. Every "outdated" is on record with the person who signed off on it.

**Before (invented):**

> Section 2 — Current-state assessment
> - The existing ordering site is outdated and slow; cart abandonment reflects it
> - In-store and online inventory are disconnected — a problem competitors solved years ago
> - Recommendation: the chain should replatform now and consolidate on a modern stack

**After:**

> Section 2 — What we'd build on
> - The pickup program has real repeat usage — that habit is the asset any online improvement compounds.
> - What we'd want to understand first: where the team sees the ordering flow lose customers, and what they've already tried.
> - What we'd propose testing: a four-week pilot syncing inventory for one store, measured on order accuracy — before any platform conversation.

**What changed.** Same analysis (an aging flow, disconnected inventory, a replatforming decision on the horizon). The seat changed: the customer's asset is named first; the gap becomes a question the team answers; the recommendation becomes a small test with a measurement attached. "Outdated" → gone. "Should" → "we'd want to understand / propose testing."

---

## Case 2 — The field guide framed as "who can stop whom"

**Situation.** A field guide written to learn the project-management software market before starting a role in it. Written for the author's own use, but such documents get kept, shared, and reused publicly. Seat: author of a durable, shareable reference → the industry.

**What the draft did.** Framed the market as a contest: "who can stop whom," which players are boxed in or bleeding users. Named real companies on the losing side of each framing.

**Why it failed.**
- *Travel:* the author may interview with, sell to, or sit in a customer meeting with any company described as stoppable or losing. A document in the author's own files saying so is a self-authored liability.
- *Show-it-to-their-CEO test:* "Vendor B is bleeding teams to cheaper tools" cannot be shown to Vendor B's CEO. The analysis behind it (where each vendor's depth or onboarding advantage lies) can.
- *Nothing about the reader in the room here* — the failure is purely about travel. That is why the skill runs both checks every time: this case passes Step 2 and fails Step 3.

**Before (invented):**

> Vendor A owns the enterprise tier and can lock out challengers through its integration ecosystem. Vendor B is stuck between enterprise and prosumer and has been bleeding teams to cheaper tools. The lightweight vendors compete on simplicity and cannot move upmarket without rebuilding for administration and compliance.

**After:**

> The market splits along two axes: how deep a vendor's administration and compliance layer goes, and how fast a new team reaches its first useful board. Vendor A has invested most heavily in integrations and admin controls, which is what shows up in its enterprise deals. Vendor B spans single-team and company-wide use with an emphasis on flexible views. Vendors built for instant onboarding win where one team makes the decision; moving into deployments where IT makes the decision means investing in the admin layer, which several are doing.

**What changed.** Same map. "Lock out," "stuck," "bleeding," "cannot" are gone; each player is described by what it optimizes for. If the author wants the blunt read — who is actually under pressure — it goes in a clearly labeled private note, not in the guide.

---

---

## Case 3 — The partner map whose legend did the ranking

**Situation.** A software company building the ecosystem map for its own partner conference — every company that has shipped an integration, on one slide. The readers are those partners, sitting in the room. Seat: host → guests.

**What the draft did.** Nothing wrong in any sentence. Every partner was described accurately, several warmly. The map sorted them into two bands: **Strategic partners** across the top, **long-tail integrations** in a narrower band below.

**Why it failed.**
- *Reader in the room:* most of the audience found their own company in the band labelled long-tail, at an event they had paid to attend. No sentence said they mattered less. The legend said it, and the legend is what a room of two hundred people reads first.
- *Steps 2 and 3 both pass.* Read sentence by sentence there is nothing to flag: no pejorative characterization, no "should," no winner/loser claim, nothing that fails the show-it-to-their-CEO test. The verdict is not in the prose.
- *Travel:* the ecosystem slide is the one partners screenshot and forward to their own teams. The band a company was put in outlives the conference.

**Before (invented):**

> Legend — **Strategic partners** (upper band) · **Long-tail integrations** (lower band)

**After:**

> Legend — **Co-engineered integrations** (built with our solutions team) · **Self-serve integrations** (built on the public API)

**What changed.** The map is identical: same companies, same two bands, same layout. The names now say what actually differs — how the integration was built — instead of how much each partner is judged to be worth. Nobody is placed below anyone, and the distinction the map exists to draw is still perfectly visible.

## Pattern across the three

| | Case 1 (proposal) | Case 2 (field guide) | Case 3 (partner map) |
|---|---|---|---|
| Failed check | Step 2 — reader's own company | Step 3 — third parties / travel | Step 4 — the frame |
| Where the verdict sat | In the assessment | In the adjectives | In the legend |
| Voice problem | Outside analyst grading the host | Outside analyst ranking the field | Host ranking its own guests |
| Fix | Asset first, gap as question, recommendation as hypothesis | Structure and trade-offs, verdicts removed | Bands named for what differs, not for worth |
| What was kept | All of the analysis | All of the map | All of the map |

The analysis was never the problem. The seat was — and in Case 3 the seat spoke through the legend, where no amount of careful sentence-writing would have found it.
