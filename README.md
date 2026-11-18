<!--
  GitHub profile README — goes in the repository dmokariya/dmokariya (name must match the
  username exactly), file README.md, repo public.
  Add repo links next to project names once those repos are public.
  Everything in this comment is invisible on GitHub.
-->

# Dinesh Mokariya

**I build businesses, and increasingly the software that runs them.** Vadodara, India.

I started as an entrepreneur and ended up shipping code, which is not the order most people do it in.

I founded **Ishto**, a B2B wholesale networking platform — a LinkedIn for wholesalers, an idea people
politely nodded at right up until it worked — and sold it to **Searchinmena.com**. In between and since:
wholesale trading, a pharmacy business, Pizzeria 21, lead generation, and a long stretch in Indian and
US markets watching money do things that fundamentals did not explain.

I studied Information Systems in Dubai and International Business in Brisbane. Neither degree covers
what happens when a broker API returns a 401 at 09:16 with a live position open. That part I learned
the way most people learn it: by paying tuition directly to the market.

---

## What I'm building

| Project | What it is | Status |
|---|---|---|
| **GreatWall** | 24×7 crypto perpetuals terminal for Delta Exchange India. Built the evidence machinery before the strategy, ran 10,000 verified outcomes, and shut it down when the gross numbers said the signal was wrong. | Closed |
| **GoldenGate** | NSE/BSE options terminal with shadow-first execution and a pre-registered adoption bar. 434 verified trades, then failed its own gate on day concentration. | Closed |
| **MarineDrive** | US equities and options on Alpaca. 21,284 verified shadow outcomes, an archived postmortem, and zero live orders — which turned out to be the correct number. | Closed |
| **Bidzilla** | Commercial intelligence for Indian procurement: live tenders, HS-code trade data, buyer discovery and evidence-backed scoring. | Active |
| **Hunter / SwingBro / SwingMan** | Market scanners that grade their own picks. One of them disproved its own edge; the backtest is still in the repo because the result is the deliverable. | Mixed |
| **WorthyAccounting** | P&L, tax-claimability and net-worth tracking for two businesses and a household. Offline-capable, rule-enforced, no spreadsheet. | Active |
| **Swarnim Capital** | [swarnimcapital.com](https://swarnimcapital.com) — the investment identity, plus the journal and disclosure tooling behind it. | Live |
| **Intelflow** | [intelflow.in](https://intelflow.in) — a daily briefing from thirty public feeds that clusters, tags and cites instead of summarising. | Live |
| **PowerStation** | One page for the eight apps running on this Mac: what is up, on which port, and why the last start failed. launchd owns the processes; nothing polls in the background. | Active |

Most repos are private — some are still commercially live, some are still being measured. Code and
postmortems available on request.

---

## The part portfolios usually leave out

I have closed more trading systems than most people have started.

GreatWall lost **$7,116 after costs** across 10,000 verified shadow outcomes. The number that settled
it was the gross one: with fees, slippage and funding all set to zero, expectancy was still
**−$0.44 per trade**. The signal was wrong, not the execution. So I wrote the postmortem, kept the data
corpus, and stopped.

Gatekeeping myself is the cheapest discipline I know. A terminal that can prove its own result can also
prove its own failure — and finding that out in week six instead of year two is the entire return on the
exercise.

---

## How I build

- **Money first, code second.** If I cannot name whose problem this solves and what it is worth, the
  build does not start.
- **Paper, then shadow, then live.** Kill switches before features. An order path that has never been
  armed is a design decision, not an accident.
- **Every number on a screen is traceable to a stored row.** If I cannot reproduce it from the database,
  it does not get displayed.
- **Boring infrastructure, disciplined scope.** SQLite before a data warehouse. One subsystem per
  change, a hard budget on files touched, no "while I'm here" edits.
- **Failures get documented, not deleted.** Half the value in these repos is the postmortem folder.

---

## On AI-assisted development

I am not a traditionally trained engineer, and I am not going to pretend otherwise in a README.

What I am is the person who decides what gets built, reviews what comes back, and signs off on the
numbers. I write with AI agents the way I would run a sharp, fast junior team: they type faster than me,
I set the architecture, the constraints and the standard, and the mistakes are mine.

The interesting part is that the discipline shows up in the repos — written engineering rules with
change budgets, test gates, and a convention I keep everywhere: **nothing is "verified" until the named
evidence passes.** It stays marked `FIXED_UNVERIFIED` until then. That single habit is why a business
person could build three trading terminals and kill all three without lighting money on fire.

---

## Stack I actually use

TypeScript · React · Node · Python · FastAPI · SQLite · Postgres · Firebase · Cloudflare Workers + D1 ·
Zerodha Kite · Alpaca · Delta Exchange · launchd · pytest · Playwright

---

## Open to

Product engineering, founding-engineer and technical co-founder conversations where the business problem
is concrete — market data, trading infrastructure, procurement, or small-business finance. Remote from
Vadodara, or on site when the problem is worth the flight.

I will not out-architect a staff engineer with twenty years of C++. I will out-ship most people, and I
will tell you the idea is weak before you spend a quarter building it.

**dmokariya@hotmail.com** · [swarnimcapital.com](https://swarnimcapital.com)

<sub>Built with AI-assisted development under my direction.</sub>
