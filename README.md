# Ben Thompson

Healthcare IT systems specialist in Cambridge, Ontario. I turn messy operational
work into repeatable PowerShell and Python automation, and I build local-first
utilities that keep private data on the machine they run on.

[Website](https://benthompsondev.github.io/) ·
[LinkedIn](https://www.linkedin.com/in/benjaminthompson1993/) ·
[Full portfolio index](docs/portfolio-map.md)

## Things worth your time

### [UsageLoop for Codex](https://github.com/benthompsondev/usageloop)

[Download for Windows](https://github.com/benthompsondev/usageloop/releases/latest/download/UsageLoop-Setup.exe)
· [View project](https://benthompsondev.github.io/usageloop/)
· [Report a problem](https://github.com/benthompsondev/usageloop/issues/new?template=bug_report.yml)

**Plan when your Codex day starts.**

Your 5-hour window only begins when you actually use Codex, so a window that
ends overnight leaves the next reset sitting idle until you come back.
UsageLoop starts it on a schedule you set: one time, separate weekday and
weekend times, or a different time for every day. It keeps windows rolling
through the day and pauses overnight. Local-first: no API key, telemetry, or
cloud account. It does not add quota or bypass limits. Windows, with a Linux
beta in testing.

### [CloakScan](https://github.com/benthompsondev/cloakscan)

[Try it in your browser](https://benthompsondev.github.io/cloakscan/)
· [Windows and Linux downloads](https://github.com/benthompsondev/cloakscan/releases/latest)

Cleans secrets, hostnames, and personal details out of scripts, logs, and
prompts before you share them. No backend and no account. The part I use most is
the PowerShell-aware Portfolio-code mode: it swaps organization-specific terms
for readable generic ones, so sanitized code is still worth reading.

### [SignalSpace Finance](https://github.com/benthompsondev/ledger-local-finance)

[Download for Windows](https://github.com/benthompsondev/ledger-local-finance/releases/latest/download/SignalSpaceFinance-setup.exe)
· [See it first](https://benthompsondev.github.io/ledger-local-finance/)

Private personal finance. Import your own bank statements and get a straight
answer about where the money went. No account, no subscription, and the database
is a file on your computer. Tauri and Rust shell, React and TypeScript
interface, packaged Python finance engine, SQLite, close to 1,400 tests.

### [Enterprise PowerShell Systems](https://github.com/benthompsondev/enterprise-powershell-systems)

[Script index](https://github.com/benthompsondev/enterprise-powershell-systems/blob/main/docs/script-index.md)
· [Reviewer guide](https://github.com/benthompsondev/enterprise-powershell-systems/blob/main/docs/reviewer-guide.md)

Sanitized versions of real healthcare IT automation: onboarding, password
remediation, Windows 11 device replacement, O365 migration support, workforce
identity migration, and code review utilities. The private data is stripped and
the workflow patterns are intact.

## Web projects

[Wedding 50/50 Draw](https://github.com/benthompsondev/wedding-50-50)
· [live site](https://benthompsondev.github.io/wedding-50-50/).
React and TypeScript on a Google Apps Script and Sheets backend, built for a real event.
Live totals, confirmation emails, printable draw slips, tests, and Pages
deployment.

[benthompsondev.github.io](https://github.com/benthompsondev/benthompsondev.github.io)
· [live site](https://benthompsondev.github.io/). My personal site.

## How I work

The shape is the same in almost everything here:

```text
input -> validate -> plan -> review -> act or simulate -> log -> verify
```

I care about validation, logs, rollback paths, and output another person can
actually review. I am heading toward automation-heavy DevOps, cloud automation,
and practical software engineering.

The [full portfolio index](docs/portfolio-map.md) has everything else, including
older teaching and course work.

Questions about any of it, or want to talk shop?
**[Find me on LinkedIn](https://www.linkedin.com/in/benjaminthompson1993/).**
