# The Judgement Deck — 30 essential cards

The small version: the 30 cards most people need first, sorted the same way —
**Judge** (6), **Brief** (7), **Check** (6), **Deliver** (7), **Practise** (4).
The full 50-card deck adds the rest of the prompt library and the edge cases.

Two card types:

- **Habit cards** — why it goes wrong, the move, the line.
- **Brief cards** `[brief]` — use when, the brief (copy, adapt, then check), the check
  (the trust-tool corner its output usually lands in: **A** trust with light review ·
  **B** verify the load-bearing bits · **C** verify before you ship · **D** human in the loop).

Direct it. Don't delegate. Never surrender.

---

## JUDGE · How much should I trust this output?

### 01 · Place it before you act
**Why it goes wrong:** The time sink isn't drafting, it's checking everything as if everything matters. The same skim gets applied to a birthday message and a board figure.

**The move:** Ask two questions of any output: how exact must it be (average or precise), and what happens if it's wrong (small or large). Two answers place it in a corner, and the corner sets the check.

*"Ten seconds of placing saves an hour of wrong checking."*

### 02 · Corner B — verify the load-bearing bits
**Why it goes wrong:** An output can be 95% right and still fail, if the 5% you skipped was the claim everything else rested on.

**The move:** Find the claims the piece rests on and check those from outside the tool. A strategy memo for the exec team lives here.

*"Check the claims it rests on, not the sentences you liked."*

### 03 · Corner C — verify before you ship
**Why it goes wrong:** A statistic in a newsletter looks identical to a statistic in a board paper. Only one of them gets found out.

**The move:** If it's going out the door, check every figure, name and date first. No exceptions for small audiences.

*"If it ships with your name on it, every number is yours."*

### 04 · Corner D — human in the loop
**Why it goes wrong:** When exactly-right meets high stakes, "review" is a fiction. You cannot review your way out of accountability.

**The move:** AI can help: draft options, summarise the file, run scenarios. The call and the signature stay human. Decisions about people live here, always.

*"AI can help. A person decides."*

### 05 · Check from outside the tool
**Why it goes wrong:** "Are you sure?" feels like verification, but models tend to agree with themselves. Asking the tool to check itself is not a check.

**The move:** Verify against something the tool can't charm: the data, the source document, a colleague who knows, your own arithmetic.

*"A source of truth that can't flatter you."*

### 06 · Gell-Mann amnesia
**Why it goes wrong:** You catch AI's errors in your own field, then believe it on the law, the market or the numbers, exactly where you can't check.

**The move:** Flip the instinct: be most sceptical where you know least. Inside your expertise, skim. Outside it, VET.

*"Your expertise finds errors at home. It doesn't travel."*

---

## BRIEF · How do I ask for what I need?

### 07 · Brief it like a new colleague
**Why it goes wrong:** People type a fragment and hope. The tool is a smart, fast colleague who is new to your job; a fragment briefs nobody well.

**The move:** RTCF. Role: who should it write as. Task: what exactly, and how much. Context: what only you know. Format: what it should look like.

*"Prompting is briefing, not spell-casting."*

### 08 · Context does most of the work
**Why it goes wrong:** The tool can guess at tone and structure. It cannot guess the client history, the board shift, or what good looks like this week. Missing context is why outputs feel generic.

**The move:** Spend your words on context: audience, situation, stakes, your standard for good. Paste your notes.

*"The only part it can't guess is the part only you know."*

### 09 · + Example `[brief]`
**Use when:** you've seen output you liked, and want that again.

**The brief:** `Here is an example I liked: [paste]. Match its length, tone and structure for [new task]. Don't copy its content.`

**The check:** A.

### 10 · + Done `[brief]`
**Use when:** the output keeps missing, or "good enough" keeps shifting.

**The brief:** `Done means: [length], [structure], using only facts I've given you. Mark anything you're unsure of with [CHECK] rather than guessing.`

**The check:** as the task.

### 11 · Guardrail `[brief]`
**Use when:** you want an honest assessment that holds across the conversation.

**The brief:** `Only change your assessment if I give you a new fact. If you do change it, name the fact that changed it.`

**The check:** B.

### 12 · Devil's advocate `[brief]`
**Use when:** you like the plan too much to trust your own review of it.

**The brief:** `Don't flatter me. Here is my [plan / proposal / idea]: [paste]. Give me the three strongest reasons it fails, and name the single assumption it all rests on.`

**The check:** B.

### 13 · Set it once
**Why it goes wrong:** Retyping the same standing context every chat is briefing tax, and the version you type at 4:55pm is thinner than the one you typed at 9.

**The move:** Save a standing brief in custom instructions, a project or a Gem: the role, the context that doesn't change, your format, your Done line. The task stays in the chat.

*"The standing brief holds what's true. The chat holds the task."*

---

## CHECK · How do I know it's right?

### 14 · Run the loop
**Why it goes wrong:** Analysis arrives fast and reads confident. Speed without a loop is how a wrong number reaches a decision document.

**The move:** Frame: the question and the decision it feeds, in a fresh chat. Explore: describe the data first. Verify: recount anything that would change a decision. Shape: write for the reader, then say what you checked.

*"AI makes analysis fast. It doesn't make it trustworthy."*

### 15 · Describe the data first `[brief]`
**Use when:** it's the first prompt on any dataset. Always.

**The brief:** `Describe this dataset before analysing it: number of rows, the columns and what each seems to contain, the date range, and anything missing, duplicated or inconsistent. Don't draw conclusions yet.`

**The check:** C.

### 16 · Show your working `[brief]`
**Use when:** any figure will drive a decision.

**The brief:** `For each number in your answer, show how you calculated it: which rows or columns you used, any filters you applied, and the formula. List anything you excluded and why.`

**The check:** C, then recount it yourself.

### 17 · VET the claim `[brief]`
**Use when:** you can't check a claim against your own data.

**The brief:** `You told me: [paste the claim]. Help me VET it. VERIFY: What sources would support this, and how could I check them independently? EXPLAIN: Break it down step by step until I could explain it to a colleague. TEST: Under what conditions, or for whom, would it be wrong?`

**The check:** B or C.

### 18 · Five ways a smooth answer goes wrong
**Why it goes wrong:** Errors hide inside fluent prose. The reader feels the confidence and skips the arithmetic.

**The move:** Watch for five: miscounts after filtering; correlation sold as cause; missing rows skipped silently; numbers that can't all be true; detail that isn't in the file.

*"The most dangerous output sounds completely right."*

### 19 · Say what you checked
**Why it goes wrong:** A checked analysis that doesn't announce its check reads the same as an unchecked one. The reader either re-does your work or trusts you blindly.

**The move:** End with one line: what you verified and how. "Totals recounted against the source file; two outliers excluded."

*"Your check is part of the deliverable."*

---

## DELIVER · Where does AI fit, and will it work every week?

### 20 · Spot the four signals
**Why it goes wrong:** People hunt for "AI use cases" and find none, while their week fills the four real patterns unnoticed.

**The move:** Look for: work you do often the same way (automate); reading, gathering, comparing (assist); writing from a blank page (generate); hunting for meaning in numbers (analyse).

*"Your week is full of candidates. You just haven't counted them."*

### 21 · Assign who leads
**Why it goes wrong:** "Use AI for it" skips the only question that matters: which part of it.

**The move:** Per step: AI leads (minutes from your notes), AI assists (a client proposal), you lead (a strategy paper), human only (telling someone their role is going).

*"Empathy, ethics, accountability: never AI leads."*

### 22 · Count the checking as effort
**Why it goes wrong:** Time saved gets measured at the draft; checking gets measured never. Workflows that "save two hours" quietly cost five in review.

**The move:** Prioritise quick wins: high time saved, low setup effort. Setup includes the checking. Quick wins usually sit in green, because they're cheap to check.

*"Count the checking as effort."*

### 23 · Scope: one, one, one
**Why it goes wrong:** "We're rolling out AI" scopes nothing. Without a baseline, every outcome is debatable and every failure is invisible.

**The move:** One workflow, one owner, one success measure. Record today's time and quality before you start. That number is the whole argument.

*"If you can't name the baseline, you can't prove the win."*

### 24 · Checkpoints before checkpoints are needed
**Why it goes wrong:** Review steps get added after the first scare, by which time the wrong output has already gone out once.

**The move:** Every amber or red step gets a named person and a specific check before go-live. Pick someone who knows what right looks like.

*"'AI' is not the name of a checker."*

### 25 · The 30-day gate
**Why it goes wrong:** Pilots drift into permanent fixtures because nobody set the date or the criteria, and the demo already convinced everyone.

**The move:** Before you start: a date about 30 days out, and the criteria for each call. Scale if it met the measure with a light review. Pivot if close but checking costs too much. Kill if it missed.

*"Set the gate before the demo convinces you."*

### 26 · Three gate mistakes
**Why it goes wrong:** The gate moment is where sunk cost, selective memory and perfectionism all show up wearing sensible clothes.

**The move:** Watch for: sunk cost ("we've come too far"), cherry-picking the measures that passed, and treating "not perfect" as "broken". Killing cheaply is a win.

*"Killing is a good outcome: you found where the line is, cheaply."*

---

## PRACTISE · Keep the learning

### 27 · The two-pass habit
**Why it goes wrong:** Routine work used to teach you while you did it. When AI does it, the reps stop, and your judgement quietly rusts.

**The move:** Once a week, on a task that matters: your own rough pass first, then give AI the same brief and compare.

*"Where it beat you is your blind spot. Where you beat it is its limit."*

### 28 · Interview me for my rules `[brief]`
**Use when:** your answer to "why did you decide that?" is "it depends".

**The brief:** `Help me write down the rules I use for one decision: [the decision]. Question me one at a time, choosing each question from my last answer. Each time I say "it depends" or stay vague, dig until you can state it as an if-then rule. Stop after fifteen to twenty questions and list the rules you've heard, every branch included, for me to check.`

**The check:** B. Read every rule and ask whether you'd have said it.

### 29 · The two-chat workflow
**Why it goes wrong:** One chat that thinks and builds does both badly: the mess stays in the output, and the output drifts towards whatever you last agreed with.

**The move:** Thinking chat: explore, argue, follow tangents. Then you curate: keep what matters, write a short focused brief. Building chat: a fresh chat that produces the output from your brief.

*"Curation is where your judgement lives."*

### 30 · The un-promptable part
**Why it goes wrong:** Some of what makes a good decision can't go in a brief: the situation is changing in real time, the right call is against the data, and the variables that matter haven't all been thought of yet.

**The move:** Keep the cases that didn't fit any rule. They show where your judgement is doing work a page of rules cannot.

*"The rules draft the call. You still make it."*

---

**Direct it. Don't delegate. Never surrender.**
