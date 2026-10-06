# Changelog

## 1.0.3 (6 October 2026)

- New `tokenmaestro uninstall` (add `--purge-data` to delete the local data too): removes the session guard's hooks from Claude Code and frees this computer's license seat in one step. If the license service cannot be reached, the release is retried on the next run.
- Session guard: `guard install --statusline` sets TokenMaestro as Claude Code's status line; the "ask" setting for pause warnings is gone (any setting other than off warns; old settings still load).
- Hook: tells a closed input from an open, silent one; an open pipe with no input ends quietly instead of waiting.
- X-ray: skips network shares and removable drives, with a 2-second budget for the folders it checks.
- License service: rate limits per address; the founders' link falls back to the plain price when the offer is closed.
- Site and installers: refund policy (7 days; 14 in the EU, EEA and UK), uninstall instructions, PATH hint per shell.

## 1.0.2 (3 October 2026)

- Measurement: declined attempts with no output are no longer priced; cache rewrites after a pause subtract what was still read from cache; PDF page ranges, replayed transcripts and compactions are counted correctly.
- Session guard: no network waits inside Claude Code; safer writes to Claude Code's settings and to the guard's state.
- License: errors that are not a verdict of the store (proxy pages, rate limits) no longer end a license; proxies from the environment and the system's certificate store are honoured.
- Installers: updates replace the program safely while Claude Code is open; checksum and cache handling after a release.
- Dashboard: adaptive decimals; original path case; clearer labels.

## 1.0.1 (2 October 2026)

- The hook never waits for its input pipe to close and is never mistaken for the X-ray.

## 1.0.0 (2 October 2026)

- First public release: the free X-ray for Claude Code on Windows, macOS and Linux; Pro session guard and status line.
