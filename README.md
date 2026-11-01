# Train Me on AI for GCC by ATeam

**Learn AI on your own work, and use it to solve your business's problems, in Arabic or English.**

Train Me on AI for GCC is a personal AI coach for founders, business owners, managers and non-technical teams in the UAE, Saudi Arabia, Qatar, Kuwait, Bahrain and Oman. It teaches by doing: each short session takes one of your real tasks, such as a WhatsApp reply to a customer, an Arabic contract summary, a sales spreadsheet, a tender or a weekly report, and shows you how to get a result you'd actually use. You write the requests yourself, the coach helps you improve them, and a plan records what you learnt and the time it saves you.

It also helps you solve business problems with AI: bring one problem, or map where AI could pay off across your business. It points you to the official GCC places for tax, e-invoicing, tenders and staffing rules, without giving legal or tax advice. And it checks AI vendors' proposals before you sign.

It works in Arabic or English, and it can draft for your staff and customers in the other languages they use, such as Hindi, Urdu, Malayalam or Tagalog.

It was built by [ATeam Soft Solutions](https://www.ateamsoftsolutions.com), a software and AI engineering firm that builds AI systems for businesses across the GCC. We share it as a contribution to the community.

## Install

### Claude (claude.ai, the desktop app and Claude Code)

Search for "Train Me on AI for GCC by ATeam" in Claude's plugin directory, or in Claude Code run:

```
/plugin install ateam-train-me-on-ai-gcc --marketplace ateamsoftsolutio/ateam-train-me-on-ai-gcc
```

On older versions of Claude Code, add the marketplace first:

```
/plugin marketplace add ateamsoftsolutio/ateam-train-me-on-ai-gcc
/plugin install ateam-train-me-on-ai-gcc@ateam-train-me-gcc
```

If you installed it with one of the commands above, update it later with these two commands, then restart Claude Code. The first fetches the new version; without it, the second reports that you're already up to date.

```
claude plugin marketplace update ateam-train-me-gcc
claude plugin update ateam-train-me-on-ai-gcc@ateam-train-me-gcc
```

### OpenAI Codex

```
codex plugin marketplace add ateamsoftsolutio/ateam-train-me-on-ai-gcc
codex plugin add ateam-train-me-on-ai-gcc@ateam-train-me-gcc
```

Start a new Codex session after installing. To update later, run `codex plugin marketplace upgrade ateam-train-me-gcc`.

### Other agents

The repository also has a root `plugin.json` in the open [Agent Plugins](https://agent-plugins.org) format, so other agents that support it may load it. We support Claude and Codex.

## The three skills

| Skill | Say | What it does |
|---|---|---|
| `train-me-on-ai` | "Train me on AI" | Gets to know you and your business in one round of questions, plans a short course on your own tasks, runs the sessions, and keeps your AI plan: what you learnt, your saved requests and your own estimates of the time saved |
| `ai-opportunity-map` | "Help me solve this problem with AI" or "Where can AI help my business?" | For one problem: practical options, from doing it yourself today to a build partner, with first steps, risks and costs. For the whole business: up to 12 uses ranked by the time at stake (from your own figures), the route and the risk, with first steps and build briefs |
| `ai-proposal-check` | "Check this AI proposal before I sign" | Reviews scope, success measures, one-off and running costs, data handling and where data is kept, ownership, lock-in and claims about accuracy, then gives a plain verdict and the questions to ask the vendor |

Asking in plain words works, in Arabic or English. You don't need to remember the skill names.

## How a course works

1. Say **"Train me on AI"** (or «علّمني الذكاء الاصطناعي»).
2. Answer one round of questions about your business, the tasks that eat your time, and how you use AI today.
3. You get a short plan: the core sessions for your level (up to six) plus up to two optional modules, each 15 to 25 minutes and built on one of your real tasks.
4. In each session the coach explains one idea, checks that what you share is safe, shows a weak and a strong request side by side, then you write your own and improve it. You check the result together and save your best request for next time.
5. Your AI plan records each session, the habit you agreed and your own estimate of the time saved. Bring it back next time and say **"next AI training session"** (or «الجلسة التالية من الدورة»).

| Session | You learn to |
|---|---|
| 1. Ask well | Get a result you'd actually use, with a simple request checklist |
| 2. Check its work | Spot mistakes, and check facts, numbers and names quickly |
| 3. Work with numbers | Get answers from a spreadsheet, with the working shown |
| 4. Research and decide | Research with real sources, including official GCC sites, and write a decision note |
| 5. Make it repeatable | Turn good requests into saved instructions and templates |
| 6. Delegate a whole job | Hand a recurring job to AI with the right checks |

Optional modules cover working in Arabic and English, government paperwork and tenders, your team's AI rules (a one-page policy for staff), sales and customer service, marketing (including Ramadan and Eid campaigns), meetings and management, and hiring.

## Your data

Data safety runs through every session: what never goes into an AI tool (passwords, Emirates ID, Iqama and other ID numbers, bank details, health information, staff and customer personal details), how to remove names and IDs before you paste anything, whether your AI account uses your chats for training, and how to connect email or files safely. Privacy-law notes cover the UAE (with the DIFC and ADGM), Saudi Arabia, Qatar (with the QFC), Kuwait, Bahrain and Oman.

## Important limits

- **Practical guidance, not legal, tax, investment or medical advice.** For tax, e-invoicing, labour rules and contracts, it points you to the official source and to your accountant, PRO or lawyer.
- **Your numbers.** Time and money saved are your own estimates, recorded as such. The coach is instructed never to invent savings figures.
- **Dates matter.** AI prices, laws and GCC rules in the library are dated 30 October 2026 and linked to their sources. The coach warns you when they may be out of date.
- **AI makes mistakes,** in Arabic as well as English. Every session teaches checking, and you stay responsible for what you send or sign.
- **Neutral.** It's instructed not to recommend any AI vendor or build partner, ATeam included, and to check ATeam's proposals the same way as anyone else's.
- **Instructions only.** It contains instructions for the AI and a reference library. It has no servers, hooks or scripts, and the plugin itself sends no data anywhere.

## Privacy

See the [Privacy policy](PRIVACY.md). In short: ATeam collects nothing, and the plugin has no servers of its own. What you share is processed by the AI tool you use, under that tool's terms.

## Files in this repository

| File | Used by |
|---|---|
| `.claude-plugin/plugin.json`, `.claude-plugin/marketplace.json` | Claude and Claude's plugin directory. Codex also reads the marketplace file. |
| `plugin.json` | Codex and other agents that support the Agent Plugins format |
| `skills/` | All of them |

## Licence

MIT. See [LICENSE](LICENSE).
