# Ben Thompson

**@benthompsondev** · Cambridge, Ontario · [benthompsondev.github.io](https://benthompsondev.github.io/) · [LinkedIn](https://www.linkedin.com/in/benjaminthompson1993/)

Healthcare IT systems, PowerShell and Python automation, DevOps growth, and practical software projects.

I work in healthcare information systems and systems support. The part of the job I enjoy most is taking disorganized operational work and turning it into something safer, repeatable, and easier for another person to trust.

Most of my strongest work is PowerShell automation around Microsoft 365, Active Directory / Entra ID, Exchange, SCCM, Intune, endpoint support, onboarding, migrations, reporting, and code review. I am building this GitHub as a public-safe version of that story: real workflow patterns, fake data, readable docs, validation checks, and projects that are useful enough to explain plainly.

I am aiming toward automation-heavy DevOps, cloud automation, platform/support automation, and practical software engineering work. Titles matter less to me than useful systems, good habits, accurate testing, and work that solves real problems.

> ⬇ **[Download SignalSpace Finance for Windows](https://github.com/benthompsondev/ledger-local-finance/releases/latest/download/SignalSpaceFinance-setup.exe)**: private, local-first personal finance. Install one .exe, import a bank statement, and see where your money went. No account, no subscription, and your finances never leave your computer. **[See it first](https://benthompsondev.github.io/ledger-local-finance/)**

> ▶ **[Try CloakScan in your browser](https://benthompsondev.github.io/cloakscan/)** — a local-first text redactor that cleans secrets and personal data out of text before you share it. Nothing to install, nothing leaves your machine.

## Start Here

| If you only open one thing | Link | Why it matters |
| --- | --- | --- |
| Shipped Windows app anyone can use | [SignalSpace Finance](https://benthompsondev.github.io/ledger-local-finance/) | Private, local-first personal finance. One installer, no account, no subscription, database stays on your machine. Tauri/Rust shell, React and TypeScript interface, packaged Python finance engine, SQLite, close to 1,400 tests |
| Personal site | [benthompsondev.github.io](https://benthompsondev.github.io/) | Short version of who I am and what I have built |
| Full portfolio map | [docs/portfolio-map.md](docs/portfolio-map.md) | The best index for everything public on this GitHub |
| Flagship automation repo | [enterprise-powershell-systems](https://github.com/benthompsondev/enterprise-powershell-systems) | Sanitized PowerShell systems based on real IT automation work |
| Shipped app (Windows, Linux, web demo) | [CloakScan](https://github.com/benthompsondev/cloakscan) | Local-first text redactor with a live browser demo, Windows and Linux installers, React/TypeScript UI, Rust/Tauri shell, tests, and CI |
| Deployed event web app | [Wedding 50/50 Draw Platform](https://github.com/benthompsondev/wedding-50-50) | React and TypeScript site connected to a private Google Workspace workflow, with live totals, tests, and GitHub Pages deployment |
| Script-by-script map | [PowerShell Script Index](https://github.com/benthompsondev/enterprise-powershell-systems/blob/main/docs/script-index.md) | Direct links to each script and what problem it solves |
| Python teaching archive | [comp10001-python-teaching-exercises](https://github.com/benthompsondev/comp10001-python-teaching-exercises) | Earlier Python teaching support and beginner examples |
| AI coding & course labs | [ai-coding-labs](https://github.com/benthompsondev/ai-coding-labs) | Course projects, agent experiments, and bug fixes in relation to AI automation and learning  |

## The Short Version

I like building practical tools for the parts of IT work that are too messy to ignore and too repetitive to keep doing by hand:

- Disorganized CSVs that need validation before anyone trusts them
- repeated account, mailbox, access, and endpoint tasks
- migration projects where the same checks happen again and again
- reports and logs that project teams can actually use
- scripts that need guardrails before they should be run by someone else
- private text that needs a careful local review before it is shared
- documentation that makes a process repeatable instead of guarded knowledge

The pattern I keep coming back to is simple:

```text
input -> validate -> plan -> review -> act or simulate -> log -> verify
```

That is the thread through most of my public work.

## What I Have Built And Worked On

These are public-safe summaries of the kind of work behind the repos. Private workplace details, raw exports, internal names, and real data are intentionally not published.

| Area | What I worked on | Public artifact |
| --- | --- | --- |
| Account and access automation | Built PowerShell workflows for structured onboarding input, account planning, access planning, mailbox planning, handoff files, and logs | [Learner Onboarding Automation](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-healthcare-systems/learner-onboarding-automation) |
| Security follow-up automation | Turned weak-password follow-up into a staged process with reminder planning, state tracking, directory re-checks, and audit output | [Password Remediation Workflow](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-healthcare-systems/password-remediation-workflow) |
| Endpoint migration | Wrote automation around a Windows 11 hardware refresh project so old-device state could be captured, restored, tracked, and reviewed across many replacements | [Workstation Migration State Toolkit](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-endpoint-systems/workstation-migration-state-toolkit) |
| Browser standardization | Built a Chrome-to-Edge bookmark migration flow with backups, merge behavior, reporting, and a recovery path so users did not lose bookmarks during a browser move | [Browser Bookmark Migration Utility](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-endpoint-systems/browser-bookmark-migration) |
| O365 / Exchange migration support | Helped support a staged move from on-prem mail systems to O365, including user waves, shared mailbox readiness, license checks, public folder planning, and mailbox repair work | [O365 Migration Support Toolkit](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-messaging-systems/o365-migration-readiness-toolkit) |
| Workforce identity migration | Built planning/reporting scripts around messy project data, existing accounts, re-enable paths, project OU tracking, mailbox/license planning, and status exports | [Workforce Platform Identity Migration](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-identity-systems/workforce-platform-identity-migration) |
| Code review and team support | Reviewed scripts from other technical teams, tightened risky pieces, added validation/run notes, and explained changes in plain language before they were used | [Support And Code Review Utilities](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-support-systems/enterprise-support-and-code-review-utilities) |
| Local-first privacy tooling | Built and packaged a text redactor for Windows and Linux (plus a live browser demo) that finds sensitive details in text, supports reusable custom detection profiles, and keeps scan content local | [CloakScan](https://github.com/benthompsondev/cloakscan) |
| Local-first personal finance | Built and shipped a native Windows app that imports bank statements, preserves transaction signs, compares spending fairly, plans the month, isolates each household member's finances in its own database, and keeps everything on the machine | [SignalSpace Finance](https://benthompsondev.github.io/ledger-local-finance/) |
| Event workflow automation | Built a real wedding draw app that connects a mobile-friendly participant site to private Google Sheets operations, payment reconciliation, confirmation emails, and printable physical draw slips | [Wedding 50/50 Draw Platform](https://github.com/benthompsondev/wedding-50-50) |

## Featured Repositories

### [Enterprise PowerShell Systems](https://github.com/benthompsondev/enterprise-powershell-systems)

This is my main portfolio repo.

It is built from sanitized versions of real workflow solutions I built in a large healthcare enterprise environment: onboarding, password remediation, Windows 11 device replacement, Chrome-to-Edge bookmark migration, workforce identity migration, O365 migration support, smaller troubleshooting utilities, and code review examples.

What I want this repo to prove:

- I can turn a manual process into a repeatable system.
- I care about validation, logs, state, rollback paths, and reviewable output.
- I can protect private data while still preserving the useful architecture.
- I can write docs and demo checks so another person can understand and run the work.
- I can review other people’s scripts and help make them safer before they hit production.

Good places to start:

- [Script Index](https://github.com/benthompsondev/enterprise-powershell-systems/blob/main/docs/script-index.md)
- [Reviewer Guide](https://github.com/benthompsondev/enterprise-powershell-systems/blob/main/docs/reviewer-guide.md)
- [Public Release Checklist](https://github.com/benthompsondev/enterprise-powershell-systems/blob/main/docs/public-release-checklist.md)
- [PowerShell demo checks](https://github.com/benthompsondev/enterprise-powershell-systems/actions/workflows/powershell-demo-check.yml)

### [CloakScan](https://github.com/benthompsondev/cloakscan)

CloakScan is a local-first desktop app (Windows and Linux) for cleaning secrets, infrastructure details, and personal information out of code, logs, prompts, and support text before sharing them. There is also a live browser demo, so people can try it with nothing to install.

I built it because manually checking every script and log for hostnames, usernames, paths, tokens, and organization-specific details is slow and easy to get wrong. It runs without a backend or account and keeps scan content in memory only. The part I use most is the PowerShell-aware **Portfolio-code** mode: instead of turning a script into placeholder-filled soup, it swaps organization-specific terms for readable generic identifiers, so sanitized code is still worth reading — and v1.5 exports a small review kit (sanitized script, counts-only summary, manual checklist) to go with it.

This is currently my clearest end-to-end software project: React and TypeScript in the interface, a deliberately small Rust/Tauri desktop shell, a signed cross-platform updater, privacy-focused storage rules, detector and browser tests, GitHub Actions, release packaging, and an honest warning that automated detection still needs human review.

Good places to start:

- [Try the live demo](https://benthompsondev.github.io/cloakscan/) — runs in your browser, nothing is uploaded
- [Download for Windows or Linux](https://github.com/benthompsondev/cloakscan/releases/latest)
- [Screenshots](https://github.com/benthompsondev/cloakscan/tree/main/docs/screenshots)
- [Security and privacy model](https://github.com/benthompsondev/cloakscan/blob/main/SECURITY.md)
- [GitHub Actions](https://github.com/benthompsondev/cloakscan/actions)

### [Wedding 50/50 Draw Platform](https://github.com/benthompsondev/wedding-50-50)

I built this for a real event, not as a sample storefront. It turns a wedding fundraiser into one complete flow for participants and the people running the draw.

Friends and family can choose entries, get the correct flexible price, submit a validated form, receive payment instructions, and see live aggregate totals. Payments happen separately by e-transfer and are checked manually. Behind the site, Google Apps Script records the submission in a private Google Sheet, sends confirmation emails, updates the public totals, and prepares one printable name slip for every included entry.

The final winner is drawn from the physical jar on video. The application handles the participant experience and the repetitive administration around the draw; it does not process payments or choose the winner.

**Stack:** React · TypeScript · Google Apps Script · Google Sheets · GitHub Actions · GitHub Pages

Good places to start:

- [Live site](https://benthompsondev.github.io/wedding-50-50/)
- [Source code](https://github.com/benthompsondev/wedding-50-50)
- [GitHub Actions](https://github.com/benthompsondev/wedding-50-50/actions)

### [SignalSpace Finance](https://github.com/benthompsondev/ledger-local-finance)

**Private, local-first personal finance.** A Windows app that turns your own
bank and credit-card statements into a straight answer about where the money
went, without handing your transaction history to anyone.

![SignalSpace Finance Home screen, shown with synthetic demo data](https://github.com/benthompsondev/ledger-local-finance/raw/main/site/assets/home.png)

I built it because every budgeting tool I tried wanted an account, a
subscription, and a copy of my finances on someone else's server. This one
wants none of those. It is the project I use myself, most weeks.

**Why you might want it**

- No account and no sign-in. There is nothing to register for.
- No subscription and no service charge from me.
- Your finance database is a file on your computer, and the calculations run
  there too.
- Separate profiles keep two people in a household completely apart. Each
  profile is its own database, not a filter over a shared one.
- Backups, restore, and a full CSV export are built in, so your data is never
  trapped in the app.

**Getting it running**

1. **[Download SignalSpace Finance for Windows](https://github.com/benthompsondev/ledger-local-finance/releases/latest/download/SignalSpaceFinance-setup.exe)** and run the installer.
2. If Windows shows a blue **"Windows protected your PC"** box, click
   **More info**, then **Run anyway**. (See below for why.)
3. Open SignalSpace. There is no sign-up, so it opens straight into the app
   and tells you what to do next:

![The Getting started checklist a new SignalSpace profile opens on](https://github.com/benthompsondev/ledger-local-finance/raw/main/site/assets/getting-started.png)

4. Import a **CSV** your bank or credit card exports. Home and Insights fill
   in from there.

**About that warning.** SignalSpace has no Authenticode publisher certificate,
which is the paid signing that stops SmartScreen appearing. Every release
publishes a SHA-256 checksum you can verify the download against. Updates are
a separate matter: in-app update downloads *are* cryptographically signed, and
SignalSpace refuses to install one whose signature does not match its own key.

Bank formats vary a lot. SignalSpace reads common CSV exports and detects the
date and amount conventions per file, but it deliberately refuses a file it
cannot read confidently rather than guessing at your numbers. Some exports will
need a manual column mapping, and some will not work at all.

**What it does once your data is in**

| Screen | What it answers |
| --- | --- |
| Home | Where am I right now, and roughly what is safe to spend |
| Insights | What changed, and which patterns are worth knowing about |
| Plan | What this month looks like once bills and savings come out |
| Transactions | The underlying rows, so you can check and correct anything |

**About the optional AI**

AI is **off by default and entirely optional**. Every figure on every screen
is calculated locally whether it is on or not. Turn it on and it explains
findings SignalSpace already worked out. If you enable it, only the data you
select for that question goes to the provider *you* configure, using *your* API
key, and that provider may bill you for it. You can also point it at a model
running on your own machine, in which case nothing leaves at all.

The only other network activity in the whole app is an update check that runs
when you press the button in Settings. There is no telemetry and nothing about
your finances is synced anywhere.

<details>
<summary><b>The technical layer</b>: architecture, testing, and packaging</summary>

**Stack:** React · TypeScript · Rust/Tauri 2 · Python · SQLite · GitHub Actions

- **Tauri 2 desktop shell (Rust)** wrapping a React and TypeScript interface,
  talking to a **packaged Python finance engine** over stdin/stdout. One
  short-lived engine process per request, so a crash cannot corrupt a session.
- **Deterministic finance semantics.** The signed amount, direction and
  transaction type are decided in one module, and cash-flow rules live there
  rather than in the charts. There is exactly one Safe to Spend calculation and
  every screen reads it.
- **Imports fail closed.** A statement file has one date format, one decimal
  convention and one column layout; they are detected once per file and a
  contradictory file is refused. Silently importing hundredfold amounts is the
  worst thing a finance app can do.
- **Multi-profile isolation by directory, not by filter.** Each profile owns its
  data directory and therefore its own SQLite database, backups and exports. A
  profile that is not open is not opened, so there is no `WHERE` clause to
  forget. Covered by a dedicated isolation suite including path-escape and
  cross-profile leakage tests.
- **Privacy boundary is explicit.** Finance math makes no network calls at all.
  The optional AI path is the only outbound request besides a user-triggered
  update check, and what it may send is a stored, previewable setting.
- **Close to 1,400 tests**, mostly engine-level integration tests asserting real
  financial outcomes rather than units, plus frontend and Rust command-registry
  tests, all run in CI.
- **Native packaging and a signed updater.** NSIS installer, per-user install,
  upgrade-in-place that preserves the database, and an updater that verifies a
  signature before it will install anything.

| Area | Link |
| --- | --- |
| Source and setup | [ledger-local-finance](https://github.com/benthompsondev/ledger-local-finance) |
| Privacy model | [SECURITY.md](https://github.com/benthompsondev/ledger-local-finance/blob/main/SECURITY.md) |
| Release validation | [GitHub Actions](https://github.com/benthompsondev/ledger-local-finance/actions/workflows/ci.yml) |
| Changelog | [CHANGELOG.md](https://github.com/benthompsondev/ledger-local-finance/blob/main/CHANGELOG.md) |

</details>

### [COMP10001 Python Teaching Exercises](https://github.com/benthompsondev/comp10001-python-teaching-exercises)

This is older and simpler, but it belongs here.

It comes from my Python PASS Leader / teaching support work. It shows where the coding side started: breaking down programming concepts for newer learners, writing beginner examples, and explaining code in a way people can follow.

## Skills And Tools

| Area | Tools and experience |
| --- | --- |
| Automation | PowerShell, Python, CSV workflows, validation, reporting, logging, repeatable scripts |
| Microsoft / identity | Microsoft 365, Exchange Online, Teams, SharePoint, OneDrive, Entra ID / Azure AD, Active Directory |
| Endpoint / systems | SCCM, Intune, Windows deployment, Windows Server, Group Policy, endpoint troubleshooting |
| Operations support | migrations, onboarding, mailbox work, access reviews, documentation, vendor/team coordination |
| Growing into | GitHub Actions, Docker, Linux, Azure/cloud, testing, packaging, cleaner software architecture |
| Project habits | fake demo data, privacy reviews, readable READMEs, local checks, small reversible changes |

## Background

My current work is in a large healthcare IT / information systems environment, mostly around Microsoft 365, hybrid identity, endpoint deployment, automation, documentation, and enterprise troubleshooting.

Before that, I worked across desktop support, networking, security software deployment, imaging, print services, licensing, and end-user support. I also worked as a Python PASS Leader at Mohawk College, where I created beginner programming material and helped students get comfortable with code.

Education and certification:

- Computer Systems Technician - Network Systems, Mohawk College
- Network Engineering and Security Analyst, Mohawk College
- Bachelor of Sports Business Management, Honours, Brock University
- CompTIA A+

I keep a Linux/networking homelab to learn by building real systems, breaking them safely, and improving the setup each time.

## What I Am Building Toward

I want this GitHub to become a clean public trail of the kind of work I want more of:

- practical IT and systems automation
- cloud and DevOps-adjacent workflows
- useful PowerShell and Python projects
- local-first apps and tools
- CI checks, testing, docs, and privacy-safe examples
- projects that are easy for a teammate, recruiter, or anyone interested in tech to understand

The goal is not to collect the most repos. The goal is to show useful work that is organized, tested, and real enough to explain clearly.
