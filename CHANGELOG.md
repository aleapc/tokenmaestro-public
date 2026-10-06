# Changelog

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
