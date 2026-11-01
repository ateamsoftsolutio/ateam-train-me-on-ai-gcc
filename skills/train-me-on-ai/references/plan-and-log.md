# The AI plan

One document holds the person's progress across all three skills. Keep it short: the person should be able to read it in a few minutes. Longer material, such as build briefs and proposal reviews, goes in separate documents that the plan links to.

## Where it's kept

- **As files** (project folder, desktop app with folder access, coding tool; if the folder is a software project, ask first): `ai-plan/AI-PLAN.md`, with build briefs as `ai-plan/brief-<short-name>.md` and proposal reviews as `ai-plan/proposal-<vendor>-<date>.md`.
- **Otherwise:** documents the person keeps (a canvas, artifact or document in their tool, or text copied from the chat). They bring the plan back by uploading or pasting it. Give the whole updated plan at the end of every session.

`train-me-on-ai` and `ai-opportunity-map` create the AI plan if there isn't one; `ai-proposal-check` adds to it only if they keep one. Everything is kept in one place.

## What never goes in it

Nothing from the red list in `data-safety.md`: no passwords, ID numbers, bank or card details, health information, or customers' and staff's personal details. Use roles ("Customer A", "the sales manager"), not names.

## Layout

```markdown
# AI plan: <business name or "My business">

Owner: <first name or role> · Started: <date> · Last updated: <date>
AI tools and account types: <tool used for this course: free / paid personal / business or team>; <other tools used at work>
Training setting checked: <on / off, date> for each tool
Language for the course: <language> · Library dated: 30 October 2026

## 1. Profile
- Business: <one line>
- Team size: <number or range>
- Countries: <countries>; personal data handled: <none / customers / health / payments>
- Systems: <email, accounting, customer database, WhatsApp Business…>
- AI use today: <never / less than weekly / most weeks / daily>, for <what>
- Level: <Starter / Regular / Confident>
- Budget for AI tools: <if given> · Cost per hour: <if given, by role>
- Gaps: <questions they skipped>

## 2. Tasks that eat time (your estimates)
| # | Task | Minutes each | How often | Who does it |
|---|---|---|---|---|

## 3. Training plan
| Session | Topic | Your real task | Status | Date |
|---|---|---|---|---|
Status: Planned / In progress (stopped at <step>) / Done / Skipped

## 4. Session log
### Session <n>: <topic> (<date>)
- Task: <task>
- Usual time: <minutes> · Expected with AI, including checking, once you're used to it: <minutes> (your estimates)
- How often you do it yourself: <times a week> (your estimate; others in the team count once they're trained)
- Result compared with usual: <better / same / worse>; would you use it: <as it is / with small edits / no>
- Confidence now: <1–5>
- Habit for this week: <when and what>
- Saved request: see section 6

## 5. Results so far (your estimates, after using it)
| Task | Minutes saved each time | Times a week (yours) | Minutes saved a week |
|---|---|---|---|
Total: about <hours> a week, from your own estimates after using it.

## 6. Saved requests
### <name of the request>
<the request, with [blanks] to fill>

## 7. Opportunity map (from ai-opportunity-map)
<the short ranking table, any "Required, with its date" items with their official links, and the "Start now" uses, with links to any build briefs; for a single problem: the problem, any "Required, with its date" item, the options in a line each, the recommended option's first step, measure and cost, and any "Rules and dates to confirm with your adviser"; or "Not done yet">

## 8. Proposal checks (from ai-proposal-check)
| Date | Vendor | What for | Verdict | Review |
|---|---|---|---|---|

## 9. Decisions and next steps
- <date>: <decision> (keep / fix / stop / next)

## 10. Questions for later
- <question parked during a session>
```

## In Arabic, or kept on a phone

Keep the same section numbers, so the next session can find section 3, with these Arabic headings: 1 «الملف التعريفي», 2 «المهام التي تستهلك الوقت», 3 «جدول الجلسات», 4 «سجل الجلسات», 5 «النتائج حتى الآن», 6 «الطلبات المحفوظة», 7 «فرص الذكاء الاصطناعي», 8 «مراجعة العروض», 9 «القرارات والخطوات التالية», 10 «أسئلة لاحقة». Use short lists instead of tables, since tables break in notes apps and WhatsApp. Write each sum with words on its own line (for example «3 دقائق × 20 مرة = 60 دقيقة»), and start each line with an Arabic word so it reads right to left. Product names stay in Latin script.

## How to record time saved

- **Ask, don't assume.** In the session: "How long does this usually take you?", "Once you're used to it, how long do you expect it to take with AI, including checking?" and "How many times a week do you do it yourself?" Record each answer as "your estimate", and the time with AI as "expected".
- **Confirm before counting.** At the next recap, ask how long it actually took with AI, including checking. Only then add the task to "Results so far".
- **Minutes saved a week** = (usual minutes − minutes with AI) × the times a week they do it themselves. The team's volume stays as time at stake until others are trained. Show the arithmetic. Don't round up.
- **If the result was worse than usual,** or they wouldn't use it, record it and count no saving for that task until it's fixed.
- **If an answer is missing,** leave that row's saving as "not worked out yet". Never fill it in yourself.
- **Money:** only if they gave a cost per hour. Multiply by their figure and show the working. Give a range only if they gave a range (for example "AED 45 to 60 an hour").
