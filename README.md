# Dave Fong

Product leader in NYC. 15 years building product experiences at the critical moments of the user's journey where the stakes are highest: your first time investing, choosing someone to renovate your home, the moments when your child is having a moment.

🔗 [**LinkedIn**](https://linkedin.com/in/davefong/) · Open to Principal Product, Head of Product, and Director of Product roles on teams that want traditional product craftsmanship with a little AI daring.

<details> 
<summary><b>🤖 AI has made it cheaper to build things </b></summary>

<br>
  
Yes, AI has made building cheap. Its why this product manager has a repo. But it didn't make deciding any cheaper. Rowing harder doesn't help if the boat is pointed at the wrong shore. I still gotta point that boat. 


I use AI to disappear the mundane. Coding tickets from my backlog get automated overnight, so they cost me almost nothing during the day. Ideas get plotted onto an interactive chart my stakeholders can actually use, so they understand the landscape of bets before we commit to one. I'm still steering. There's just a lot less pushing.

This code is how I earn the right to say what good looks like. I've shipped AI-native and AI-enabled experiences, so I own the lessons learned. 

<details>
<summary><b>🚀 Shipped and running</b> — five products live, from an AI parenting coach to an automated housing finder</summary>

<br>

These repos are private because they are systems that run my life: searching for housing, accelerating my own product development loop, tools that help me be more present with my family. The contribution graph below is the public trace of it.

| What | Does | Stack |
|---|---|---|
| **Parent Coach** | AI coaching app for parents. Logs structured observations of parent-child interactions, surfaces behavioral patterns, and coaches the parent's behavior instead of diagnosing the child. Knows when to stop and hand off to a human professional. | Next.js, Supabase, Claude |
| **Framework Visualizer** | Prioritization tool for product managers. Turns a table of ideas and measures into interactive scatter, bubble, and radar charts, including bipolar tradeoffs where no direction is the winner. Drag a dot to change the underlying value. | React 19, TypeScript, Recharts, Vite |
| **career-os** | An operating system for a job search. 62 skills, 7 scheduled agent routines, a CRM web app, and feedback loops that learn which resume and mock-interview changes actually produce callbacks. | Node, Next.js, Supabase, Claude Code |
| **Housing Finder** | Automated listings aggregator. Daily scan routines across a dozen sources that block scrapers, cross-source dedup into one row per property, alerting only on genuinely new inventory. | Python, Next.js, GitHub Actions |
| **diary-learner** | Longitudinal reflection system. An evening prompt collects the day, a morning routine reflects it back and threads it against recent entries. Decisions logged here return at 7, 30, 90, 180, and 365 days. | Python, Claude Code, Gmail API |

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
<summary><b>🎯 What I am demonstrating</b> — evals, agent orchestration, guardrails, and honest measurement</summary>

<br>

**Evals are a product decision.** Defining what "good" means for an AI feature is not something to hand to QA. Every scoring rule I ship has a test suite beside it. When a lift calculation started ranking single-instance coincidences above findings with a sample of thirteen, the regression test that already existed passed against the bug. I rewrote the test with the data shape that actually occurs, watched it fail, then fixed the code.

**Agents with a job, not a chat window.** Scheduled routines wake on cron, do one scoped piece of work, write their reasoning to a run journal, and version-check themselves against a manifest. Drift gets reported. A routine that stops running is caught by a health check rather than by me noticing months later.

**Knowing where the machine has to stop.** Parent Coach hands off to a human professional at the boundary of what software should judge. No routine sends email outside four named workflows. Nothing submits a job application without a human click. Agents act only inside a closed allowlist, so a hostile job listing cannot talk one into something it was never meant to do. Autonomy is safe in exact proportion to how precisely the edges are written down.

**Outcomes, including the null result.** Extract structured features from an artifact, wait for the real-world result, then join the two. Which resume edits precede a screen. Which cover-letter openers precede silence. The honest version of this reports "no finding at this sample size" more often than it reports a win, and holding that line is what makes the wins worth acting on.

**Decision quality is not outcome quality.** When I log a decision, the system stores what I expected to happen, in my own words, before I know the answer. Reviews come back months later and ask whether the call was sound given only what I knew at the time. A judgment that worked out is not automatically a judgment that was correct, and separating those two is most of what senior product judgment is.

</details>

<details>
<summary><b>🧭 Before this</b> — Capital One, Stash, Vital Card, Zappos, Sweeten</summary>

<br>

Group Product Manager at Capital One, product leadership at Stash and Vital Card, earlier work at Zappos and Sweeten. Two acquisitions. Led OKR and data-driven development training for 20+ PMs. At Stash I evolved a shared AI product-operations model that cut speed to market roughly in half.

The through-line: I build the environment that lets a product team do its best work, then I build in it alongside them.

</details>



</details>

