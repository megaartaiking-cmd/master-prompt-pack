# Master Prompt Pack

Strong prompts that get the most out of any AI model — ChatGPT, Claude, Gemini, Copilot, or any other — for real work: coding, writing, planning, and research.

Every prompt is copy-paste ready. Copy the block, replace the parts in `[BRACKETS]` with your details, and paste it into the AI. Nothing else to set up.

## How to use this pack

1. Find the prompt that matches your task.
2. Copy the whole block, including the first and last line.
3. Replace every `[BRACKET]` with your own details. Delete any line you do not need.
4. Paste it in and send. If the first answer is weak, use one of the follow-up prompts at the end instead of starting over.

Three habits make every prompt work better:

- **Give an example.** One example of the style or format you want beats a paragraph describing it.
- **Say what "done" looks like.** Length, format, and audience — name them, or the AI guesses.
- **Ask it to think first.** Prompts below tell the AI to plan before answering. That one line improves almost every result.

---

## The universal master prompt

Use this when no specific prompt below fits. It works for almost any task.

```text
You are an expert in [TOPIC]. Help me with this task:

TASK: [Describe exactly what you want, in 1-3 sentences]

CONTEXT: [Who this is for, why it matters, and anything the AI must know]

REQUIREMENTS:
- [Requirement 1]
- [Requirement 2]
- [Requirement 3]

Before you answer, think step by step and make a short plan.
Then give me the final result in this format: [FORMAT — e.g. a table, a numbered list, code only, 200 words]

Rules:
- Be specific. No filler, no generic advice I could Google.
- If something is unclear, state your assumption instead of asking me.
- If you are unsure about a fact, say so — never invent details.
- End with: the single most important next step I should take.
```

---

## Coding prompts

### Build a feature or program

```text
You are a senior software developer. Build this for me:

WHAT: [What the program or feature should do]
LANGUAGE / STACK: [e.g. Python 3, JavaScript, HTML/CSS — or say "you choose the best fit"]
INPUT: [What the user provides or what data it works on]
OUTPUT: [What it should produce or show]

Requirements:
- Give me the complete, working code — no placeholders, no "add the rest yourself".
- Keep it as simple as possible while doing the job fully.
- Add short comments only where the code is not obvious.
- After the code, add: 1) how to run it, step by step, 2) one example of it working, 3) the most likely error a beginner will hit and how to fix it.
```

### Debug an error

```text
You are a senior developer helping me debug. Here is my problem:

WHAT I WANTED TO HAPPEN: [Expected behavior]
WHAT ACTUALLY HAPPENED: [Actual behavior]
ERROR MESSAGE: [Paste the full error, word for word]
MY CODE:
[Paste your code here]

Do this:
1. Explain the cause in plain English, in 2 sentences or less.
2. Give me the fixed code — the full corrected section, not just the changed line.
3. Tell me how to confirm the fix worked.
4. Tell me how to avoid this error next time, in one sentence.
Do not rewrite working parts of the code.
```

### Review my code

```text
You are a strict code reviewer. Review this code:

[Paste your code here]

GOAL OF THIS CODE: [What it is supposed to do]

Review it in this order and be honest, not polite:
1. BUGS — anything that will break or give wrong results. Quote the line.
2. SECURITY — anything unsafe: passwords, user input, file access, network calls.
3. PERFORMANCE — anything slow or wasteful, and the fix.
4. READABILITY — names, structure, or duplication that should change.

For every issue give: the problem, why it matters, and the corrected code.
End with a score out of 10 and the top 3 fixes to make first.
If the code is genuinely fine in a category, say "no issues" — do not invent problems.
```

### Refactor without breaking it

```text
Refactor this code to be cleaner and easier to maintain:

[Paste your code here]

Rules:
- Behavior must stay exactly the same — same inputs, same outputs, same edge cases.
- Do not change the language, libraries, or public function names.
- Improve: naming, duplication, long functions, and confusing logic.
- Show the full refactored code first, then a short list of what you changed and why.
- Flag anything you wanted to change but did not, because it would alter behavior.
```

### Explain code like a teacher

```text
Explain this code to me as a patient teacher:

[Paste your code here]

MY LEVEL: [Beginner / intermediate / advanced]

Do this:
1. One-sentence summary: what this code does overall.
2. Walk through it section by section in plain English — no jargon without explaining it.
3. Point out the 3 most important ideas a learner must understand here.
4. Give me one tiny practice exercise based on this code, and hide the answer until I ask.
```

### Write tests for my code

```text
Write tests for this code:

[Paste your code here]
TEST FRAMEWORK: [e.g. pytest, Jest — or "you choose the standard one for this language"]

Cover:
- The normal case (valid input, expected output)
- Edge cases: empty input, zero, very large values, wrong types
- Failure cases: what should happen when input is invalid

Give me the complete test file, ready to run, plus the exact command to run it.
Each test gets a clear name that says what it checks. Aim for quality over quantity: 6-10 strong tests.
```

---

## Writing prompts

### Write anything from scratch

```text
You are an expert writer. Write this for me:

TYPE: [Email / blog post / product description / cover letter / social post / other]
TOPIC: [What it is about]
AUDIENCE: [Who will read it — their level, what they care about]
GOAL: [What the reader should think, feel, or do after reading]
TONE: [Professional / friendly / bold / simple and direct]
LENGTH: [e.g. 150 words, 5 short paragraphs, one page]
MUST INCLUDE: [Key points, facts, or phrases that must appear]
MUST AVOID: [Words, claims, or topics to leave out]

Write 2 versions: Version A safe and clear, Version B bolder and more memorable.
Use short paragraphs and plain words. No clichés, no filler openings like "In today's world".
```

### Rewrite and polish my draft

```text
Rewrite my draft below. Keep my meaning and all my facts — change only the writing.

MY DRAFT:
[Paste your text here]

FIX THESE:
- Make it clearer and shorter — cut every word that adds nothing.
- Fix grammar, spelling, and awkward sentences.
- Tone should be: [Professional / friendly / confident / simple]
- Keep the reading level at: [e.g. understandable by a 14-year-old / expert level]

Give me:
1. The rewritten text, ready to use.
2. A short list of the 5 biggest changes you made and why.
Do not add new claims, numbers, or promises that are not in my draft.
```

### Summarize anything

```text
Summarize the text below for me.

TEXT:
[Paste the article, document, or notes here]

FORMAT:
1. TL;DR — one sentence.
2. Key points — maximum 5 bullets, each one line.
3. Decisions or action items — who needs to do what, if any are mentioned.
4. One thing that is unclear, missing, or questionable in the text.

Rules: Use only what is in the text. Do not add outside facts or your own opinions.
Write for someone who has 60 seconds, not 10 minutes.
```

---

## Planning prompts

### Turn a goal into a step-by-step plan

```text
You are an expert project planner. Turn my goal into a plan I can actually follow.

GOAL: [What I want to achieve]
DEADLINE: [Date, or "no fixed deadline"]
MY SITUATION: [Time I can give per day/week, budget, skills I already have, tools I have]
CONSTRAINTS: [Anything that limits me]

Give me:
1. The goal restated as one measurable outcome.
2. The plan in phases, each phase broken into small concrete steps — each step doable in one sitting.
3. For each step: what to do, how long it should take, and how I know it is done.
4. The top 3 risks or obstacles, and how to handle each.
5. What to do in the first 24 hours — maximum 3 actions.

Be realistic, not motivational. If my deadline is impossible, say so and give me the closest achievable version.
```

### Make a hard decision

```text
Help me decide. Do not just list pros and cons — analyze and recommend.

DECISION: [The choice I face]
MY OPTIONS: [Option A, Option B, Option C]
WHAT I CARE ABOUT MOST: [e.g. cost, time, risk, long-term growth — in order]
MY SITUATION: [Facts that matter: budget, deadline, experience, obligations]

Do this:
1. Build a comparison table: each option scored 1-5 on cost, time, risk, and long-term value.
2. For each option, name the worst realistic outcome and how likely it is.
3. Tell me what information would change the decision, if I could get it.
4. Give your recommendation and the strongest argument for it.
5. Give the strongest argument AGAINST your own recommendation — steelman the other side.
```

### Plan my week or day

```text
Plan my schedule. Here is everything on my plate:

TASKS: [List them, with any deadlines]
FIXED COMMITMENTS: [Meetings, work hours, family time — with times]
AVAILABLE TIME: [e.g. weekdays 6-9pm, weekends free]
ENERGY: [When I think best — morning / evening]

Give me:
1. A day-by-day schedule with time blocks, hardest work in my best hours.
2. Tasks grouped together where it saves effort.
3. Anything that does not fit — say so honestly instead of cramming it in, and suggest what to drop, delay, or delegate.
4. One buffer block per day for the unexpected.
```

---

## Research prompts

### Research a topic deeply

```text
Research this topic for me and give me a briefing I can trust.

TOPIC: [The topic or question]
WHY I NEED IT: [Decision I will make, thing I will build, or argument I must understand]
MY LEVEL: [Beginner / intermediate / expert]

Structure your answer:
1. THE SHORT ANSWER — 3 sentences maximum.
2. KEY FACTS — the 7 most important facts, each with a number or date where one exists.
3. HOW IT WORKS — the mechanism, explained simply.
4. DIFFERENT VIEWS — where experts disagree, present both sides fairly.
5. COMMON MYTHS — claims people repeat that are wrong or unproven.
6. WHAT I SHOULD VERIFY — facts you are less certain about, flagged honestly.

Rules: Never invent statistics, dates, names, or quotes. If you do not know, write "not certain" next to it. Separate facts from opinions clearly.
```

### Compare options before buying or choosing

```text
Compare these options for me and tell me which one fits me best.

OPTIONS: [Product / tool / service A, B, C — names or links]
I WILL USE IT FOR: [Main use cases]
MY BUDGET: [Amount or range]
MUST-HAVES: [Features I cannot live without]
DEAL-BREAKERS: [Anything that rules an option out]

Give me:
1. A comparison table: price, key strengths, key weaknesses, best for whom.
2. Hidden costs or downsides most reviews skip — subscriptions, limits, lock-in, support quality.
3. Your pick for my situation, and why, in 3 sentences.
4. The option to pick if my budget were half — and if it were double.
Only use facts you are confident about. Flag any price or spec you are unsure of instead of guessing.
```

### Learn any topic fast

```text
Teach me [TOPIC] from zero. I am a [beginner / your level] and I can give [e.g. 30 minutes a day].

Teach like this:
1. Start with the big picture: why this topic matters, in 3 sentences.
2. Give me the 5 core ideas that explain 80% of the topic, each with one real-world example.
3. Explain idea 1 fully, then quiz me with 2 questions before moving on. Wait for my answers.
4. Correct my answers kindly and fill the gaps.
5. After all 5 ideas, give me a one-page cheat sheet summary and a 7-day practice plan.

Use simple words first, technical terms second — and define every term when you first use it.
```

---

## Follow-up prompts that fix a weak answer

Paste one of these right after any disappointing answer. They work in the same chat, on any model.

### Make it better

```text
That answer was too generic. Do it again, but:
- Use my specific details, not general advice.
- Cut the length in half and double the usefulness.
- Replace every vague claim with a concrete example, number, or step.
```

### Check your own work

```text
Now review your last answer like a critic:
1. List anything that is wrong, invented, outdated, or unverifiable.
2. List anything important you left out.
3. Give me the corrected, improved version.
Be honest — finding your own mistakes is the point of this step.
```

### Go deeper

```text
Go one level deeper on your last answer:
- Explain WHY each point is true, not just that it is true.
- Add the trade-offs and downsides you skipped.
- Add what an expert would know that a beginner would miss.
```

### Give me options

```text
Give me 3 different approaches to this instead of one:
- Approach 1: fastest
- Approach 2: cheapest or simplest
- Approach 3: highest quality, no shortcuts
For each: the steps, the cost in time or money, and who it suits best. Then recommend one for my situation.
```

### Explain it simpler

```text
Explain your last answer again for a smart 14-year-old:
- Plain words, short sentences.
- One everyday example or comparison for each main idea.
- Keep every important fact — simplify the language, not the truth.
```

---

## Quick reference — which prompt for which job

| I want to | Use this prompt |
| --- | --- |
| Do almost anything | The universal master prompt |
| Build software | Build a feature or program |
| Fix an error | Debug an error |
| Check code quality | Review my code |
| Clean up messy code | Refactor without breaking it |
| Understand code | Explain code like a teacher |
| Test my code | Write tests for my code |
| Write something new | Write anything from scratch |
| Fix my own writing | Rewrite and polish my draft |
| Shorten a long text | Summarize anything |
| Reach a big goal | Turn a goal into a step-by-step plan |
| Choose between options | Make a hard decision |
| Organize my time | Plan my week or day |
| Understand a topic | Research a topic deeply |
| Pick a product or tool | Compare options before buying or choosing |
| Learn a new skill | Learn any topic fast |
| Fix a weak answer | Any follow-up prompt above |
