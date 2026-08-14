# GitHub Profile - agent instructions

Applies to Claude Code and Codex. The shared global core arrives separately.
Do not assume the parent workspace guide is present in a session started here.

## Purpose and boundaries

This public repo is Ben's GitHub profile and portfolio navigation. Keep claims
accurate, links current, and wording concise and in Ben's voice. Do not add
private paths, personal agent configuration, credentials, workplace details,
or claims that the linked repositories do not support.

This is documentation-only. There is no application build or test suite.

## Verification

Run `git diff --check`, inspect every changed link, and compare factual claims
with the linked repo or release. Before any public push, use the
`ben-voice-polish` and `git-push` skills and run:

```powershell
powershell -ExecutionPolicy Bypass -File ..\codex-home\scripts\Invoke-PrivacyScan.ps1 -Path .
```

## Repo-specific push authority

For this repo only, when Ben clearly asks for setup, GitHub, or portfolio work,
default to committing and pushing completed safe changes after the checks above.
Summarize the files changed and confirm there are no secrets, private data, or
workplace details. Otherwise, follow the global ask-before-push rule.
