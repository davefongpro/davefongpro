# Dave Fong

Product leader in NYC. 15 years building product experiences at the critical moments of the user's journey where the stakes are highest: your first time investing, choosing someone to renovate your home, the moments when your child is having a moment.

🔗 [**LinkedIn**](https://linkedin.com/in/davefong/) · Open to Principal Product, Head of Product, and Director of Product roles on teams that want traditional product craftsmanship with a little AI daring.

⚖️ **[Ballast](https://ballast.nwtnlabs.com)** — *not every tradeoff has a winner.* A free tool that plots ideas against measures with no better end, and reads out which way your portfolio leans. [Source](https://github.com/davefongpro/ballast)

🌿 **[Parent Coach](https://nwtnlabs.com/r/github)** — *a logbook for the hard moments.* Parents log a moment with their child in about thirty seconds; the app finds what those moments have in common, then coaches the parent's own response instead of diagnosing the child. Private preview — the link is a full tour of the product.

<details> 
<summary><b>🤖 AI has made it cheaper to build things </b></summary>

<br>
  
Yes, AI has made building cheap. Its why this product manager has a repo. But it didn't make deciding any cheaper. Rowing harder doesn't help if the boat is pointed at the wrong shore. I still gotta point that boat. 


I use AI to disappear the mundane. Coding tickets from my backlog get automated overnight, so they cost me almost nothing during the day. Ideas get plotted onto an interactive chart my stakeholders can actually use, so they understand the landscape of bets before we commit to one. I'm still steering. There's just a lot less pushing.

This code is how I earn the right to say what good looks like. I've shipped AI-native and AI-enabled experiences, so I own the lessons learned. 

<details>
<summary><b>🚀 Shipped and running</b> — five products live, from an AI parenting coach to an automated housing finder</summary>

<br>

Ballast is public — link above. Parent Coach keeps its source closed but has a public tour you can read end to end. The rest are private because they are systems that run my life: searching for housing, accelerating my own product development loop, tools that help me be more present with my family. The contribution graph below is the public trace of it.

| What | Does | Stack |
|---|---|---|
| **[Parent Coach](https://nwtnlabs.com/r/github)** | AI coaching app for parents. Logs structured observations of parent-child interactions, surfaces behavioral patterns, and coaches the parent's behavior instead of diagnosing the child. Knows when to stop and hand off to a human professional. | Next.js, Supabase, Claude |
| **[Ballast](https://ballast.nwtnlabs.com)** | Prioritization tool for product managers. Turns a table of ideas and measures into interactive scatter, bubble, and radar charts, including bipolar tradeoffs where no direction is the winner. Drag a dot to change the underlying value. | React 19, TypeScript, Recharts, Vite |
| **career-os** | An operating system for a job search. 62 skills, 7 scheduled agent routines, a CRM web app, and feedback loops that learn which resume and mock-interview changes actually produce callbacks. | Node, Next.js, Supabase, Claude Code |
| **Housing Finder** | Automated listings aggregator. Daily scan routines across a dozen sources that block scrapers, cross-source dedup into one row per property, alerting only on genuinely new inventory. | Python, Next.js, GitHub Actions |
| **diary-learner** | Longitudinal reflection system, and the one I would hand to another PM first. Agents read my recorded meetings, my calendar, and my commits across six repos, then hand the day back to me as evidence at 5:15pm. Ten minutes of my own interpretation goes in. Next morning it returns as what I actually did, the thread across recent weeks, and what to focus on. Decisions logged in it come back at 7, 30, 90, 180, and 365 days. | Python, Next.js, Claude Code, Gmail and Calendar APIs |

</details>

<details>
<summary><b>⚙️ The system that builds them</b> — how my backlog ships itself overnight</summary>

<br>

The products above are the output. This is the machine that produces them, and it is the part I would want a team to have.

An idea enters as one line in a backlog. Triage either approves it as a small fix or promotes it to a plan with a sequenced task list and a roadmap row. Overnight, a build routine picks up every approved fix first, then advances the highest-priority plan, and opens a pull request. CI blocks that PR if behavior changed and the docs did not. When the checks go green the routine merges its own work. A reconciler then updates the roadmap, and marks an initiative done only when no unchecked tasks remain and no other open PR still references it. Anything a machine genuinely cannot do lands in a single durable ledger of human action items. A morning brief reports what shipped, what needs me, and which routines have gone quiet.

Six repos, one shared source of truth. A skill or workflow written once syncs into all of them, so a fix lands everywhere instead of only in the repo that happened to hit the bug. A dashboard reads every roadmap and flags when two initiatives have open work touching the same files.

That is a delivery function with intake, planning, quality gates, and release management, run by one person. Building it is the same instinct as standing up product operations for a team, which is the job I actually want.

</details>

<details>
<summary><b>🔁 A day in the loop</b> — what the agents carry, and what stays mine</summary>

<br>

The clearest answer I have to *what does an AI-native operator actually look like all day*. It is one loop, and the split down the middle of it is the entire point.

**Overnight, the machine does the remembering.** A routine reads every call I recorded that it has not seen before. Real interviews get scored against a rubric and written up. Everything else gets read for the commitments **I** made out loud, which then land wherever that thing already lives: the CRM, the tracker, or a single ledger of things only a human can do. It never invents an item that was not said, never files someone else's promise as mine, and never contacts anyone.

**At 4:50am it looks at the day ahead.** My calendar, the live pipeline, the prepped work, the networking queue. It composes at most three focus blocks and two habits, never more than three planned hours. Everything that did not make the cut stays in the system rather than in front of me. An attention budget is a product decision, and most personal-productivity tools quietly refuse to make it.

**At 5:15pm it hands the day back to me as evidence.** Applications sent, pipeline movement, pull requests merged across every repo, themes recurring in recent entries. Then two questions. I am reacting to a record, not reconstructing a day from memory, which is why ten minutes is enough. If a source failed to load, the email says so in amber rather than rendering a quiet day and a broken pipeline identically.

**Ten minutes of judgment goes in.** That is the only part no system can do for me: what the day meant, what I would do differently, what I decided and why. Skipping is free. No streaks, no nagging, and a slow day still has a true answer, because the question asks what moved rather than what I achieved.

**Next morning it comes back to me interpreted.** Yesterday reflected back, the thread running across recent entries, one forward move. And, on its own schedule, a decision I made months ago, quoting what I said I expected at the time and asking how it actually went.

**That last one is the reason the whole thing exists.** A judgment that worked out is not automatically a judgment that was correct. Storing my expectation *before* I know the answer is what stops hindsight from quietly rewriting it, and it is the difference between a system that makes me faster and one that makes me better.

I am not looking to have my thinking done for me. I am looking to stop spending it on recall.

</details>

<details>
<summary><b>🎯 What I am demonstrating</b> — evals, agent orchestration, guardrails, and honest measurement</summary>

<br>

**Evals are a product decision.** Defining what "good" means for an AI feature is not something to hand to QA. Every scoring rule I ship has a test suite beside it. When a lift calculation started ranking single-instance coincidences above findings with a sample of thirteen, the regression test that already existed passed against the bug. I rewrote the test with the data shape that actually occurs, watched it fail, then fixed the code.

**Agents with a job, not a chat window.** Scheduled routines wake on cron, do one scoped piece of work, write their reasoning to a run journal, and version-check themselves against a manifest. Drift gets reported. A routine that stops running is caught by a health check rather than by me noticing months later.

**Knowing where the machine has to stop.** Parent Coach hands off to a human professional at the boundary of what software should judge. No routine sends email outside four named workflows. Nothing submits a job application without a human click. Agents act only inside a closed allowlist, so a hostile job listing cannot talk one into something it was never meant to do. Autonomy is safe in exact proportion to how precisely the edges are written down.

**Outcomes, including the null result.** Extract structured features from an artifact, wait for the real-world result, then join the two. Which resume edits precede a screen. Which cover-letter openers precede silence. The honest version of this reports "no finding at this sample size" more often than it reports a win, and holding that line is what makes the wins worth acting on.

**Decision quality is not outcome quality.** When I log a decision, the system stores what I expected to happen, in my own words, before I know the answer. It comes back at 7, 30, 90, 180, and 365 days and asks whether the call was sound given only what I knew at the time. A judgment that worked out is not automatically a judgment that was correct, and separating those two is most of what senior product judgment is. I built the review schedule because I could not be trusted to run it myself, which is the honest reason to automate anything.

</details>

<details>
<summary><b>🧭 Before this</b> — Capital One, Stash, Vital Card, Zappos, Sweeten</summary>

<br>

Group Product Manager at Capital One, product leadership at Stash and Vital Card, earlier work at Zappos and Sweeten. Two acquisitions. Led OKR and data-driven development training for 20+ PMs. At Stash I evolved a shared AI product-operations model that cut speed to market roughly in half.

The through-line: I build the environment that lets a product team do its best work, then I build in it alongside them.

</details>



</details>

