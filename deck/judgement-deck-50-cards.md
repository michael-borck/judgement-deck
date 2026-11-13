# The Judgement Deck — 50 cards

Fifty small moves for using and delivering AI with judgement, sorted the way the
masterclass runs: **Judge** (10), **Brief** (11), **Check** (10), **Deliver** (11),
**Practise** (8).

Two card types:

- **Habit cards** — why it goes wrong, the move, the line.
- **Brief cards** `[brief]` — use when, the brief (copy, adapt, then check), the check
  (the trust-tool corner its output usually lands in: **A** trust with light review ·
  **B** verify the load-bearing bits · **C** verify before you ship · **D** human in the loop).

Pull one when you've got a few minutes. Direct it. Don't delegate. Never surrender.

---

## JUDGE · How much should I trust this output?

### 01 · Place it before you act
**Why it goes wrong:** The time sink isn't drafting, it's checking everything as if everything matters. The same skim gets applied to a birthday message and a board figure.

**The move:** Ask two questions of any output: how exact must it be (average or precise), and what happens if it's wrong (small or large). Two answers place it in a corner, and the corner sets the check.

*"Ten seconds of placing saves an hour of wrong checking."*

### 02 · Corner A — trust with light review
**Why it goes wrong:** Low-stakes drafts get over-checked, which trains you to treat the tool as a toy or a threat instead of a calibrated instrument.

**The move:** Average precision, small consequences: use it, skim before it goes out. A first-pass draft, an internal summary.

*"Light review is a real answer. Not everything needs a committee."*

### 03 · Corner B — verify the load-bearing bits
**Why it goes wrong:** An output can be 95% right and still fail, if the 5% you skipped was the claim everything else rested on.

**The move:** Find the claims the piece rests on and check those from outside the tool. A strategy memo for the exec team lives here.

*"Check the claims it rests on, not the sentences you liked."*

### 04 · Corner C — verify before you ship
**Why it goes wrong:** A statistic in a newsletter looks identical to a statistic in a board paper. Only one of them gets found out.

**The move:** If it's going out the door, check every figure, name and date first. No exceptions for small audiences.

*"If it ships with your name on it, every number is yours."*

### 05 · Corner D — human in the loop
**Why it goes wrong:** When exactly-right meets high stakes, "review" is a fiction. You cannot review your way out of accountability.

**The move:** AI can help: draft options, summarise the file, run scenarios. The call and the signature stay human. Decisions about people live here, always.

*"AI can help. A person decides."*

### 06 · Check from outside the tool
**Why it goes wrong:** "Are you sure?" feels like verification, but models tend to agree with themselves. Asking the tool to check itself is not a check.

**The move:** Verify against something the tool can't charm: the data, the source document, a colleague who knows, your own arithmetic.

*"A source of truth that can't flatter you."*

### 07 · Gell-Mann amnesia
**Why it goes wrong:** You catch AI's errors in your own field, then believe it on the law, the market or the numbers, exactly where you can't check.

**The move:** Flip the instinct: be most sceptical where you know least. Inside your expertise, skim. Outside it, VET.

*"Your expertise finds errors at home. It doesn't travel."*

### 08 · The AI dismissal fallacy
**Why it goes wrong:** "That's just ChatGPT" feels like discernment. It's a refusal to engage, and it throws away real capability along with the bad drafts.

**The move:** Judge the reasoning, not where it came from. If an argument is wrong, say where. If it's right, use it, whoever drafted it.

*"'It's AI' isn't a critique. Wrong is a critique."*

### 09 · Sycophancy
**Why it goes wrong:** Models are tuned on human approval, and people prefer agreeable answers. Ask "what do you think?" and you get a mirror.

**The move:** Ask for weakness by name: "What are the three weakest points in this?" The push-back briefs in this deck do it for you.

*"Ask for the three weakest points, not the opinion."*

### 10 · Corners move; the check stays
**Why it goes wrong:** A model upgrade moves outputs between corners, and people carry old trust forward without noticing. Yesterday's green is today's amber.

**The move:** Revisit your placements every few months, especially for work you've automated.

*"Better models move the corners. They never remove the check."*

---

## BRIEF · How do I ask for what I need?

### 11 · Brief it like a new colleague
**Why it goes wrong:** People type a fragment and hope. The tool is a smart, fast colleague who is new to your job; a fragment briefs nobody well.

**The move:** RTCF. Role: who should it write as. Task: what exactly, and how much. Context: what only you know. Format: what it should look like.

*"Prompting is briefing, not spell-casting."*

### 12 · Context does most of the work
**Why it goes wrong:** The tool can guess at tone and structure. It cannot guess the client history, the board shift, or what good looks like this week. Missing context is why outputs feel generic.

**The move:** Spend your words on context: audience, situation, stakes, your standard for good. Paste your notes.

*"The only part it can't guess is the part only you know."*

### 13 · Role does the least
**Why it goes wrong:** People polish the role ("you are a world-leading expert…") and starve the context, then wonder why everything sounds the same.

**The move:** One clear role line is enough: "an experienced project manager who writes plainly." Move the effort to context.

*"A good role is one sentence. A good context is a paragraph."*

### 14 · + Example `[brief]`
**Use when:** you've seen output you liked, and want that again.

**The brief:** `Here is an example I liked: [paste]. Match its length, tone and structure for [new task]. Don't copy its content.`

**The check:** A.

### 15 · + Done `[brief]`
**Use when:** the output keeps missing, or "good enough" keeps shifting.

**The brief:** `Done means: [length], [structure], using only facts I've given you. Mark anything you're unsure of with [CHECK] rather than guessing.`

**The check:** as the task.

### 16 · + Questions `[brief]`
**Use when:** you're not sure what context it needs.

**The brief:** `Before you start on [task], ask me up to five questions about anything you'd need to know to do it well. Ask them one at a time and wait for my answer.`

**The check:** A.

### 17 · + Steps `[brief]`
**Use when:** the job is long, multi-part, or the model is small or old.

**The brief:** `We'll do [task] in steps. First, give me an outline only, as headings with one line each. Wait for my go-ahead, then draft one section at a time.`

**The check:** as the task.

### 18 · Guardrail `[brief]`
**Use when:** you want an honest assessment that holds across the conversation.

**The brief:** `Only change your assessment if I give you a new fact. If you do change it, name the fact that changed it.`

**The check:** B.

### 19 · Devil's advocate `[brief]`
**Use when:** you like the plan too much to trust your own review of it.

**The brief:** `Don't flatter me. Here is my [plan / proposal / idea]: [paste]. Give me the three strongest reasons it fails, and name the single assumption it all rests on.`

**The check:** B.

### 20 · Board of directors `[brief]`
**Use when:** one confident answer isn't enough.

**The brief:** `Respond to [proposal] as a board of three: a CFO, a sceptical customer and a frontline manager. One paragraph each from their point of view. Then list where they disagree with each other.`

**The check:** B.

### 21 · Set it once
**Why it goes wrong:** Retyping the same standing context every chat is briefing tax, and the version you type at 4:55pm is thinner than the one you typed at 9.

**The move:** Save a standing brief in custom instructions, a project or a Gem: the role, the context that doesn't change, your format, your Done line. The task stays in the chat.

*"The standing brief holds what's true. The chat holds the task."*

---

## CHECK · How do I know it's right?

### 22 · Run the loop
**Why it goes wrong:** Analysis arrives fast and reads confident. Speed without a loop is how a wrong number reaches a decision document.

**The move:** Frame: the question and the decision it feeds, in a fresh chat. Explore: describe the data first. Verify: recount anything that would change a decision. Shape: write for the reader, then say what you checked.

*"AI makes analysis fast. It doesn't make it trustworthy."*

### 23 · Describe the data first `[brief]`
**Use when:** it's the first prompt on any dataset. Always.

**The brief:** `Describe this dataset before analysing it: number of rows, the columns and what each seems to contain, the date range, and anything missing, duplicated or inconsistent. Don't draw conclusions yet.`

**The check:** C.

### 24 · Show your working `[brief]`
**Use when:** any figure will drive a decision.

**The brief:** `For each number in your answer, show how you calculated it: which rows or columns you used, any filters you applied, and the formula. List anything you excluded and why.`

**The check:** C, then recount it yourself.

### 25 · VET the claim `[brief]`
**Use when:** you can't check a claim against your own data.

**The brief:** `You told me: [paste the claim]. Help me VET it. VERIFY: What sources would support this, and how could I check them independently? EXPLAIN: Break it down step by step until I could explain it to a colleague. TEST: Under what conditions, or for whom, would it be wrong?`

**The check:** B or C.

### 26 · Five ways a smooth answer goes wrong
**Why it goes wrong:** Errors hide inside fluent prose. The reader feels the confidence and skips the arithmetic.

**The move:** Watch for five: miscounts after filtering; correlation sold as cause; missing rows skipped silently; numbers that can't all be true; detail that isn't in the file.

*"The most dangerous output sounds completely right."*

### 27 · Say what you checked
**Why it goes wrong:** A checked analysis that doesn't announce its check reads the same as an unchecked one. The reader either re-does your work or trusts you blindly.

**The move:** End with one line: what you verified and how. "Totals recounted against the source file; two outliers excluded."

*"Your check is part of the deliverable."*

### 28 · Fresh-chat second opinion `[brief]`
**Use when:** a long conversation has gone on too long to be independent.

**The brief:** `I'm going to paste a conclusion reached in another conversation. Assess it independently. Where is it strongest, where is it weakest, and what would you need to see to be confident it's right? [paste]`

**The check:** B.

### 29 · Describe the shape, not the data `[brief]`
**Use when:** you can't share the real data. The tool never sees it.

**The brief:** `I can't share the data itself. Its structure is: [number] rows, columns [list them, with types and made-up example values]. Write the steps or spreadsheet formulas I'd use to answer [question], so I can run them myself. Or: write a single HTML page that runs entirely in my browser and shows [the result]. It must not send the data anywhere.`

**The check:** C. Run it on data where you know the answer first.

### 30 · If you can't read the code
**Why it goes wrong:** AI writes analysis code you can run without understanding. The run succeeding is not the same as the code being right.

**The move:** Run it on data where you know the answer, and see if it returns that answer. Can't read the code at all? Treat everything it produces as Corner D.

*"If you can't read it, you can't green-corner it."*

### 31 · Verify the channel
**Why it goes wrong:** A voice or video asking for money, a password or new bank details gets checked, if at all, in the channel it arrived in. That channel is what's compromised.

**The move:** Check outside the channel: hang up and call back on a number you already have. A familiar face on a call is no longer proof.

*"A familiar face on a call is no longer proof."*

---

## DELIVER · Where does AI fit, and will it work every week?

### 32 · Spot the four signals
**Why it goes wrong:** People hunt for "AI use cases" and find none, while their week fills the four real patterns unnoticed.

**The move:** Look for: work you do often the same way (automate); reading, gathering, comparing (assist); writing from a blank page (generate); hunting for meaning in numbers (analyse).

*"Your week is full of candidates. You just haven't counted them."*

### 33 · Assign who leads
**Why it goes wrong:** "Use AI for it" skips the only question that matters: which part of it.

**The move:** Per step: AI leads (minutes from your notes), AI assists (a client proposal), you lead (a strategy paper), human only (telling someone their role is going).

*"Empathy, ethics, accountability: never AI leads."*

### 34 · Count the checking as effort
**Why it goes wrong:** Time saved gets measured at the draft; checking gets measured never. Workflows that "save two hours" quietly cost five in review.

**The move:** Prioritise quick wins: high time saved, low setup effort. Setup includes the checking. Quick wins usually sit in green, because they're cheap to check.

*"Count the checking as effort."*

### 35 · Map my workflow `[brief]`
**Use when:** you're turning one repeated task into a delivery plan.

**The brief:** `Here's how I currently do [weekly task], in my own words: [describe it]. List it as numbered steps with a time estimate for each. For each step, suggest whether AI could lead, assist, or should stay with a person, and say why. Don't assume access to any system I haven't mentioned.`

**The check:** B.

### 36 · Pre-mortem `[brief]`
**Use when:** you're about to start a new workflow or project.

**The brief:** `Imagine it's 30 days from now and [the workflow / project] has failed. Write the five most likely reasons it failed, and for each, one early warning sign I could watch for and one thing I could put in place now.`

**The check:** B.

### 37 · Scope: one, one, one
**Why it goes wrong:** "We're rolling out AI" scopes nothing. Without a baseline, every outcome is debatable and every failure is invisible.

**The move:** One workflow, one owner, one success measure. Record today's time and quality before you start. That number is the whole argument.

*"If you can't name the baseline, you can't prove the win."*

### 38 · Checkpoints before checkpoints are needed
**Why it goes wrong:** Review steps get added after the first scare, by which time the wrong output has already gone out once.

**The move:** Every amber or red step gets a named person and a specific check before go-live. Pick someone who knows what right looks like.

*"'AI' is not the name of a checker."*

### 39 · Keep one human step on purpose
**Why it goes wrong:** Automating 80% of a junior's routine work looks like a win until you realise the work that trained their judgement has gone.

**The move:** Keep at least one human checkpoint that exists to build capability, not to catch errors. Say so, so nobody "efficiency-improves" it away later.

*"Routine work used to teach. Now practice is a choice."*

### 40 · The 30-day gate
**Why it goes wrong:** Pilots drift into permanent fixtures because nobody set the date or the criteria, and the demo already convinced everyone.

**The move:** Before you start: a date about 30 days out, and the criteria for each call. Scale if it met the measure with a light review. Pivot if close but checking costs too much. Kill if it missed.

*"Set the gate before the demo convinces you."*

### 41 · Gate review `[brief]`
**Use when:** you're at the gate. You make the call.

**The brief:** `At the start I set these criteria. Scale if: [criteria]. Pivot if: [criteria]. Kill if: [criteria]. Here's what happened over 30 days: [log, numbers, issues]. Assess the evidence against each criterion and tell me what's missing. Don't make the decision for me.`

**The check:** D.

### 42 · Three gate mistakes
**Why it goes wrong:** The gate moment is where sunk cost, selective memory and perfectionism all show up wearing sensible clothes.

**The move:** Watch for: sunk cost ("we've come too far"), cherry-picking the measures that passed, and treating "not perfect" as "broken". Killing cheaply is a win.

*"Killing is a good outcome: you found where the line is, cheaply."*

---

## PRACTISE · Keep the learning

### 43 · The two-pass habit
**Why it goes wrong:** Routine work used to teach you while you did it. When AI does it, the reps stop, and your judgement quietly rusts.

**The move:** Once a week, on a task that matters: your own rough pass first, then give AI the same brief and compare.

*"Where it beat you is your blind spot. Where you beat it is its limit."*

### 44 · Interview me for my rules `[brief]`
**Use when:** your answer to "why did you decide that?" is "it depends".

**The brief:** `Help me write down the rules I use for one decision: [the decision]. Question me one at a time, choosing each question from my last answer. Each time I say "it depends" or stay vague, dig until you can state it as an if-then rule. Stop after fifteen to twenty questions and list the rules you've heard, every branch included, for me to check.`

**The check:** B. Read every rule and ask whether you'd have said it.

### 45 · Blind test my rules `[brief]`
**Use when:** you've drafted decision rules and are about to rely on them. Run in a new chat.

**The brief:** `Using the decision rules below, make the call on each of these [three to five] cases. I've left out what I decided. For each case, give your call, the rule you used, and your reasoning in two or three short steps. Then stop, and I'll compare your calls with mine. [Paste the rules, then the cases.]`

**The check:** D. You make the final call.

### 46 · Write like me `[brief]`
**Use when:** every draft sounds like everyone. Teach the tool your voice once.

**The brief:** `Here are [three or four] things I've written: [paste, with anything confidential removed]. Describe my writing style as a brief another writer could follow: tone, sentence length and structure, vocabulary, how I open and close, and anything I never do. Quote a short example from my samples for each point.`

**The check:** B. It will be slightly a parody. Edit it until it's you.

### 47 · Voice pass `[brief]`
**Use when:** one draft needs to sound like you, today.

**The brief:** `Here's about 100 words I wrote: [paste, with anything confidential removed]. Rewrite your last output in my voice, leading with the one thing only I would say.`

**The check:** A. Read it aloud. Would you have said it?

### 48 · The two-chat workflow
**Why it goes wrong:** One chat that thinks and builds does both badly: the mess stays in the output, and the output drifts towards whatever you last agreed with.

**The move:** Thinking chat: explore, argue, follow tangents. Then you curate: keep what matters, write a short focused brief. Building chat: a fresh chat that produces the output from your brief.

*"Curation is where your judgement lives."*

### 49 · Handover prompt `[brief]`
**Use when:** a long chat has drifted. Before you close it.

**The brief:** `Write a handover prompt that captures everything important from this conversation: the context, the decisions made, open questions, and where we left off. I'll paste it into a new chat to continue.`

**The check:** A. You keep the thinking and lose the noise.

### 50 · The un-promptable part
**Why it goes wrong:** Some of what makes a good decision can't go in a brief: the situation is changing in real time, the right call is against the data, and the variables that matter haven't all been thought of yet.

**The move:** Keep the cases that didn't fit any rule. They show where your judgement is doing work a page of rules cannot.

*"The rules draft the call. You still make it."*

---

**Direct it. Don't delegate. Never surrender.**
