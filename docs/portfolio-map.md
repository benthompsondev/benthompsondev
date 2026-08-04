# Portfolio Map

This is the starting point for my public GitHub.

If someone only has a few minutes, this page should make it clear what to open first, what each repo is meant to show, and where the useful docs, scripts, screenshots, and run checks live.

My strongest skill right now is practical IT automation: taking disorganized operational work, adding validation and guardrails, and turning it into something repeatable. I also want this page to show the personal projects I am building, my earlier Python teaching work, and the path I am building toward with DevOps, cloud, and cleaner software habits.

## Quick Path

| If you want to see... | Open this first | Why |
| --- | --- | --- |
| My best automation work | [Enterprise PowerShell Systems](https://github.com/benthompsondev/enterprise-powershell-systems) | The flagship repo: sanitized PowerShell systems, fake data, run checks, reviewer docs, and GitHub Actions |
| A complete desktop app I can ship | [CloakScan](https://github.com/benthompsondev/cloakscan) | Local-first privacy tool with React, TypeScript, Rust/Tauri packaging, a one-file Windows installer, tests, and CI |
| A real event workflow built end to end | [Wedding 50/50 Draw Platform](https://github.com/benthompsondev/wedding-50-50) | Responsive React app connected to Google Apps Script and a private Google Sheets workflow, with live totals and automated deployment |
| The fastest script-by-script map | [PowerShell Script Index](https://github.com/benthompsondev/enterprise-powershell-systems/blob/main/docs/script-index.md) | Direct links to each demo script and the problem it solves |
| My local-first finance app | [Northstar Ledger](https://benthompsondev.github.io/ledger-local-finance/) | Native Windows app with a product tour, installer, statement imports, planning, net worth, tests, and local SQLite storage |
| My early Python / teaching background | [COMP10001 Python Teaching Exercises](https://github.com/benthompsondev/comp10001-python-teaching-exercises) | Beginner Python exercises from my PASS Leader / teaching support work |
| The public profile landing page | [benthompsondev](https://github.com/benthompsondev) | Short version of who I am, what I build, and what to open first |

## Public Repo Index

| Repo | Type | Best links | What it shows |
| --- | --- | --- | --- |
| [enterprise-powershell-systems](https://github.com/benthompsondev/enterprise-powershell-systems) | Flagship automation portfolio | [Script Index](https://github.com/benthompsondev/enterprise-powershell-systems/blob/main/docs/script-index.md), [Reviewer Guide](https://github.com/benthompsondev/enterprise-powershell-systems/blob/main/docs/reviewer-guide.md), [Actions](https://github.com/benthompsondev/enterprise-powershell-systems/actions) | PowerShell automation for account workflows, security follow-up, endpoint migrations, O365 migration support, reporting, validation, and code review |
| [cloakscan](https://github.com/benthompsondev/cloakscan) | Local-first privacy tool | [Windows release](https://github.com/benthompsondev/cloakscan/releases/latest), [Screenshots](https://github.com/benthompsondev/cloakscan/tree/main/docs/screenshots), [Security](https://github.com/benthompsondev/cloakscan/blob/main/SECURITY.md), [Actions](https://github.com/benthompsondev/cloakscan/actions) | React and TypeScript app structure, privacy-focused design, Rust/Tauri desktop packaging, automated tests, and a one-file Windows installer |
| [wedding-50-50](https://github.com/benthompsondev/wedding-50-50) | Deployed event web app | [Live site](https://benthompsondev.github.io/wedding-50-50/), [Source](https://github.com/benthompsondev/wedding-50-50), [Actions](https://github.com/benthompsondev/wedding-50-50/actions) | React and TypeScript frontend, Google Workspace automation, private operational data, aggregate-only public totals, tests, and GitHub Pages deployment |
| [ledger-local-finance](https://github.com/benthompsondev/ledger-local-finance) | Local-first Windows finance app | [Product tour](https://benthompsondev.github.io/ledger-local-finance/), [Windows release](https://github.com/benthompsondev/ledger-local-finance/releases/latest), [Security Notes](https://github.com/benthompsondev/ledger-local-finance/blob/main/SECURITY.md), [Actions](https://github.com/benthompsondev/ledger-local-finance/actions) | React and TypeScript interface, Rust/Tauri packaging, packaged Python finance engine, SQLite, statement-import safeguards, tests, and release validation |
| [comp10001-python-teaching-exercises](https://github.com/benthompsondev/comp10001-python-teaching-exercises) | Learning / teaching archive | [README](https://github.com/benthompsondev/comp10001-python-teaching-exercises/blob/main/README.md) | Earlier Python fundamentals, teaching support, and breaking code down for newer learners |
| [ai-coding-labs](https://github.com/benthompsondev/ai-coding-labs) | AI / coding-course work | [README index](https://github.com/benthompsondev/ai-coding-labs/blob/main/README.md), [ragchatbot-course-fix](https://github.com/benthompsondev/ragchatbot-course-fix) | Coding I do while working through AI courses — debugging code I didn't write, fixing what's broken, and writing up what I learned |
| [benthompsondev](https://github.com/benthompsondev/benthompsondev) | Profile repo | [Profile README](https://github.com/benthompsondev), [This Map](https://github.com/benthompsondev/benthompsondev/blob/main/docs/portfolio-map.md) | The front door for the portfolio |

## Work-Inspired Automation

The PowerShell repo is probably the best place to start. It’s where I’m turning the systems, scripts, fixes, and automations I’ve built from real enterprise IT work into public-safe projects with fake data, clear run steps, and no private details.

These are not raw workplace scripts. They are cleaned public demos based on real types of IT work: messy CSVs, account planning, security follow-up, endpoint replacement, messaging migration, project reporting, and code review. Private details are removed and replaced with fake users, fake domains, local files, and simulated actions.

What I want this repo to show:

- I can take a disorganized operational problem and turn it into a repeatable workflow.
- I care about validation before action.
- I write outputs and systems that another admin or project team can review.
- I think about logs, handoff files, state tracking, and rollback paths.
- I can sanitize work-inspired automation without flattening it too much.
- I can use GitHub Actions and demo checks so the repo is not just a pile of scripts.

### PowerShell Systems

| System | Link | What it handles | What to notice |
| --- | --- | --- | --- |
| Learner Onboarding Automation | [folder](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-healthcare-systems/learner-onboarding-automation) | Intake CSV validation, directory action planning, group/access planning, mailbox planning, handoff files, notification drafts, logs, and sample output | The full workflow shape: input, validation, planning, output, and review |
| Password Remediation Workflow | [folder](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-healthcare-systems/password-remediation-workflow) | Security export conversion, staged reminders, mock directory checks, cycle state, final reset planning, archive output, and audit logs | Stateful automation instead of a one-time script |
| Workforce Platform Identity Migration | [folder](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-identity-systems/workforce-platform-identity-migration) | Source data validation, account create/re-enable planning, project OU review, mailbox/license planning, and reporting | Project tracking and identity cleanup around a large platform migration |
| Browser Bookmark Migration Utility | [folder](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-endpoint-systems/browser-bookmark-migration) | Chrome bookmark backup, Edge favorite merge, multi-profile handling, reporting, and manual recovery | A small endpoint script built around avoiding user pain during a browser standardization move |
| Workstation Migration State Toolkit | [folder](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-endpoint-systems/workstation-migration-state-toolkit) | Old-device state capture, new-device restore planning, app/printer/local group inventory, master tracking, and directory prep | Automation that helped make a large device replacement project easier to run and track |
| O365 Migration Support Toolkit | [folder](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-messaging-systems/o365-migration-readiness-toolkit) | User migration waves, shared mailbox readiness, license group review, public folder planning, mailbox repair, and summary reports | Multiple scripts solving different problems in a staged on-prem to O365 migration |
| Enterprise Support And Code Review Utilities | [folder](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-support-systems/enterprise-support-and-code-review-utilities) | Smaller support utilities plus sanitized reviewer notes and templates | Code review, troubleshooting, and helping other teams make scripts safer to run |

### Best Entry Points In The PowerShell Repo

| Page | Link | Why it exists |
| --- | --- | --- |
| Script Index | [docs/script-index.md](https://github.com/benthompsondev/enterprise-powershell-systems/blob/main/docs/script-index.md) | Clickable map of every script |
| Reviewer Guide | [docs/reviewer-guide.md](https://github.com/benthompsondev/enterprise-powershell-systems/blob/main/docs/reviewer-guide.md) | Best route through the repo if someone is reviewing it quickly |
| Public Release Checklist | [docs/public-release-checklist.md](https://github.com/benthompsondev/enterprise-powershell-systems/blob/main/docs/public-release-checklist.md) | Privacy and quality checklist before I add more work-inspired material |
| GitHub Actions | [Actions](https://github.com/benthompsondev/enterprise-powershell-systems/actions) | Proof that the demo checks and PowerShell quality checks run after changes |

## Open Source And Personal Projects

This section is for projects that are not just sanitized work automation. These are personal or open-source projects that someone could download, run, learn from, or build on.

### CloakScan

[CloakScan](https://github.com/benthompsondev/cloakscan) is a local-first tool for removing sensitive details from text before it is pasted into an AI prompt, support ticket, GitHub issue, or public post. You can [try it in your browser](https://benthompsondev.github.io/cloakscan/) or install it on Windows or Linux.

It combines the practical problem with software work I wanted to learn properly: React and TypeScript structure, detector tests, Playwright browser checks, a very small Rust/Tauri desktop shell, Windows and Linux installers with a signed updater, privacy documentation, and GitHub Actions.

| Area | Link | What it shows |
| --- | --- | --- |
| Live demo | [Try it in your browser](https://benthompsondev.github.io/cloakscan/) | The full scanner, running client-side with nothing uploaded |
| Main repo | [cloakscan](https://github.com/benthompsondev/cloakscan) | Project overview, source, and run commands |
| Download | [Latest release](https://github.com/benthompsondev/cloakscan/releases/latest) | Windows and Linux installers for everyday users |
| Screenshots | [docs/screenshots](https://github.com/benthompsondev/cloakscan/tree/main/docs/screenshots) | Scan, settings, country packs, rules, and privacy screens |
| Security notes | [SECURITY.md](https://github.com/benthompsondev/cloakscan/blob/main/SECURITY.md) | What stays in memory, what can be saved, and the limits of pattern detection |
| Validation | [Actions](https://github.com/benthompsondev/cloakscan/actions) | Web, Windows, and Linux desktop checks |

### Wedding 50/50 Draw Platform

[Wedding 50/50 Draw Platform](https://github.com/benthompsondev/wedding-50-50) is a responsive event website connected to a private operational workflow. I built it for our real wedding fundraiser, then tested and deployed the full flow instead of stopping at a static event page.

#### The problem

A traditional stag and doe would have taken considerably more planning and administration. Tori and I wanted a simpler way for friends and family to participate without creating another event to organize.

#### The solution

The public site calculates flexible entry pricing, validates submissions, provides payment instructions, and displays live aggregate totals. Google Apps Script handles the server-side workflow, while a private Google Sheet keeps participant details, payment checks, draw entries, and printable slips away from the public site.

Payments are sent separately by e-transfer and reconciled manually. The application does not process money.

#### Workflow

1. A participant chooses how many entries they want.
2. The site calculates the correct price and validates the form.
3. The participant submits their name and e-transfer sender information.
4. Google Apps Script records the included submission in a private Google Sheet and sends the payment instructions.
5. Aggregate entry and winner-share totals update without exposing individual orders.
6. The e-transfer is checked manually and marked as received in the private workflow.
7. One private draw-list row and printable slip is prepared for every included entry. Cancelled or refunded entries are removed automatically.
8. The final winner is selected from the physical jar on video.

#### How it works

- React and TypeScript frontend designed for phones and desktop browsers
- Google Apps Script as a lightweight serverless backend
- Google Sheets as the private operational data store
- automatic email and print-preparation workflow
- aggregate-only public status response with no participant details
- live countdown, flexible pricing, form validation, status refreshes, and an accessible gallery lightbox
- automated tests and production validation in GitHub Actions
- GitHub Pages hosting with path-safe assets and repeatable deployment

#### Result

This is a real deployed system that reduces manual record keeping and connects the public participant experience to the private administration needed for a physical draw.

| Area | Link | What it shows |
| --- | --- | --- |
| Live application | [Open the wedding draw](https://benthompsondev.github.io/wedding-50-50/) | Responsive participant flow, live totals, entry form, countdown, and draw information |
| Source code | [wedding-50-50](https://github.com/benthompsondev/wedding-50-50) | React, TypeScript, Apps Script, tests, deployment workflow, and project documentation |
| Validation | [GitHub Actions](https://github.com/benthompsondev/wedding-50-50/actions) | Automated tests, production build, and GitHub Pages deployment |

**Stack:** React · TypeScript · Google Apps Script · Google Sheets · GitHub Actions · GitHub Pages

### Northstar Ledger

[Northstar Ledger](https://github.com/benthompsondev/ledger-local-finance) is a
local-first personal finance app for Windows.

It turns bank and credit-card exports into a monthly check-in without sending
the database to a finance service. The desktop app uses React and TypeScript in
the interface, Rust/Tauri for packaging, a Python engine for the finance math,
and SQLite for local storage. It preserves statement signs, separates transfers
and card payments from real cash flow, refuses ambiguous imports, and keeps one
canonical Safe to Spend result across the app.

| Area | Link | What it shows |
| --- | --- | --- |
| Product tour | [Open the tour](https://benthompsondev.github.io/ledger-local-finance/) | Current native screens using generated transactions |
| Download | [Latest Windows release](https://github.com/benthompsondev/ledger-local-finance/releases/latest) | Installer, release notes, and SHA-256 checksum |
| Main repo | [ledger-local-finance](https://github.com/benthompsondev/ledger-local-finance) | Project overview, architecture, source, and run commands |
| Security notes | [SECURITY.md](https://github.com/benthompsondev/ledger-local-finance/blob/main/SECURITY.md) | Privacy boundaries and what should stay local |
| Validation | [Actions](https://github.com/benthompsondev/ledger-local-finance/actions) | Checks that run against the app |

What Ledger is meant to show:

- a multi-language desktop app with clear boundaries between UI and finance math
- bank-neutral CSV detection that fails closed instead of guessing
- SQLite-backed local data, backups, and migrations
- React charts and native Windows packaging
- synthetic demo data, public screenshots, and release validation
- privacy-first design with optional read-only AI kept separate
- a project I can keep improving without turning it into a cloud service

## Learning And Teaching

This section is for older learning and teaching material. It is not the main portfolio lane, but it helps explain where the coding side started.

### COMP10001 Python Teaching Exercises

[COMP10001 Python Teaching Exercises](https://github.com/benthompsondev/comp10001-python-teaching-exercises) contains beginner Python examples from my PASS Leader / teaching support work.

This repo matters because it shows a different skill: explaining code to people who are still getting comfortable with it. That connects directly to the kind of work I enjoy now: making technical systems easier to understand, easier to test, and easier for someone else to pick up.

What it shows:

- Python fundamentals
- simple examples for newer learners
- teaching and explanation
- early coding background before the heavier automation work

## AI Coding And Course Work

This is the coding I do while working through AI courses and figuring out how these
tools actually work. It usually starts with something in the course material that
doesn't run — I dig into why, fix it, and write down what I learned. It's a learning
lane, not a flagship, but it shows I can debug code I didn't write and leave it
better than I found it.

[ai-coding-labs](https://github.com/benthompsondev/ai-coding-labs) is the index.
Standalone projects stay in their own repos and are linked from there.

| Project | Link | What it shows |
| --- | --- | --- |
| AI coding labs index | [ai-coding-labs](https://github.com/benthompsondev/ai-coding-labs) | The index for course and AI-assisted coding work |
| RAG Chatbot course fix | [ragchatbot-course-fix](https://github.com/benthompsondev/ragchatbot-course-fix) | Fixed fork of the DeepLearning.AI "Claude Code" course starter — diagnosed and fixed the query endpoint failing on current Claude models (retired model id + a broken tool-use loop), with a README that explains the bugs and the fix |

What this lane is meant to show:

- I can debug an unfamiliar codebase and find the real cause, not just the symptom
- I understand how agent tool-use loops work and why they break
- I leave the fix behind, documented, for the next person hitting the same wall

## What I Am Building Toward

The direction is pretty simple:

- keep expanding the PowerShell repo with useful sanitized systems
- keep improving CloakScan and Ledger as practical local-first app projects
- add future projects only when they solve real problems and are practically useful to others
- keep docs, checks, screenshots, and examples strong enough that someone else can follow them
- keep GitHub focused on work I can actually explain in an interview or to another technical person

The goal is not to have the most repos. The goal is to have a clear public trail of the useful work I've done.
