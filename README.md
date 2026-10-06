# TokenMaestro

Make your AI coding plan go further. TokenMaestro is a small local program that reads the session logs your AI coding agent already keeps on your computer and shows where the tokens went: value at API prices by day, model, effort and project; leaks with evidence labels; a weight map; and a cross-check against the agent's own counters.

Works with Claude Code today; Codex and Gemini next. Windows, macOS and Linux.

Website: https://thetokenmaestro.com

## Install

Windows (PowerShell):

```powershell
irm https://thetokenmaestro.com/install.ps1 | iex
```

macOS and Linux (Terminal):

```sh
curl -fsSL https://thetokenmaestro.com/install.sh | sh
```

Then run:

```sh
tokenmaestro xray
```

The dashboard opens in your browser from a file on your computer. The installers check the download against the published SHA-256 (https://thetokenmaestro.com/download/SHA256SUMS) and need no administrator rights.

## What leaves your computer

The X-ray sends nothing anywhere: no account, no upload, no tracking. Pro (the session guard and the terminal status line) checks its license through a small relay, sending only the license key and a device name (at activation) or the activation id (on checks). Details: https://thetokenmaestro.com/privacy.html

## Numbers

Token counts come from the usage block the API returns with each message, recorded on your machine. Dollar figures are API-equivalent values, not an invoice. We publish no savings percentage until it is measured on real work.

## Uninstall

Run `tokenmaestro uninstall` first (it removes the session guard's hooks from Claude Code and frees the license seat), then delete the program. On versions before 1.0.3: `tokenmaestro guard uninstall`, then `tokenmaestro deactivate`, then delete the program.

## Support

Open an issue in this repository or write to hello@thetokenmaestro.com.

This repository holds documentation, release notes and the issue tracker; the source code is not public.

TokenMaestro is an independent product, not affiliated with Anthropic, OpenAI, Google or any other AI provider. Claude Code, Codex and Gemini are trademarks of their owners.
