```text
╔══════════════════════════════════════════════════════════════════════════════╗
║  ██╗   ██╗ ██████╗ ██╗██████╗ ██████╗  █████╗ ██╗   ██╗██╗                   ║
║  ██║   ██║██╔═████╗██║██╔══██╗██╔══██╗██╔══██╗██║   ██║██║                   ║
║  ██║   ██║██║██╔██║██║██║  ██║██████╔╝███████║██║   ██║██║                   ║
║  ╚██╗ ██╔╝████╔╝██║██║██║  ██║██╔══██╗██╔══██║╚██╗ ██╔╝██║                   ║
║   ╚████╔╝ ╚██████╔╝██║██████╔╝██║  ██║██║  ██║ ╚████╔╝ ███████╗              ║
║    ╚═══╝   ╚═════╝ ╚═╝╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝  ╚═══╝  ╚══════╝              ║
╚══════════════════════════════════════════════════════════════════════════════╝

───[ whoami ]──────────────────────────────────────────────────────────────//──

I find what doesn't belong, I prove it, and I make it hold up — with
people, with systems, and with code.

~6 years of security fieldwork — overt/covert, CCTV, plainclothes,
armored — a year of rural 911 EMS, 70+ offensive lab engagements, and
a behavioral host-defense tool with a handwritten eBPF probe. I've
been on every side of an incident: responded to one as an EMT, watched
one through a camera wall, tailed one in plainclothes, documented one
for court, replayed one in a lab.

Low-resource, high-capability — the read path never needs a network,
and neither do I.

───[ ps ]───────────────────────────────────────────────────────────────────//──

[-] Terminal software — Python (stdlib-first), bash, some C. Single-file
    tools with offline test suites and documentation meant to be read.
[-] Systems — Linux internals, x86 assembly, eBPF, bubblewrap sandboxing,
    kernel hardening. Below the API layer, on purpose.
[-] Offensive security — 70+ documented lab engagements (HTB / Proving
    Grounds / THM). Active Directory end to end: AS-REP roasting,
    Kerberoasting, DCSync, ADCS and ACL abuse, BloodHound path reasoning,
    spraying under lockout constraints. Web exploitation, Linux and
    Windows privesc, exploit dev and reversing fundamentals. The
    methodology ships as tooling: an MCP stack (recon, C2) that lets an
    AI agent drive the kill chain under explicit safety gates.
    Authorized labs only.
[-] Host defense & opsec — behavioral detection: no signatures, no
    network calls. Opsec as daily practice, not posture.
[-] Investigations, OSINT & surveillance — open-source research on a
    two-source corroboration standard; nothing single-source goes in a
    report. Surveillance tradecraft: overt/covert, CCTV, plainclothes.
    Rapid behavior-based assessment, never appearance-based. Evidence
    tooling, chain of custody, Wicklander-Zulawski interview
    methodology.
[-] Field readiness — austere-capable and unrestricted: any state, any
    road, short notice, minimal footprint. Code 3, armored, off-highway,
    snow, winch recovery; chainsaw and land tools; de-escalation first.

───[ ls ]───────────────────────────────────────────────────────────────────//──

terminal tools

- [shinbun](https://github.com/v0idravl/shinbun) — the daily newspaper as
  one dated 80-col file, pulled over tor, read offline; hand-rolled
  SOCKS5 + HTTP, fail-closed mode
- [sdwx](https://github.com/v0idravl/sdwx) — weather, surf, tides,
  sun/moon, and space weather in one 80-col report; no API keys,
  stale-cache fallback offline
- [yomu](https://github.com/v0idravl/yomu) — terminal EPUB reader; one
  file, no network, the comments teach the format
- [sokudoku](https://github.com/v0idravl/sokudoku) — flashing-word (RSVP)
  speed reader; pacing follows the reading research
- [tidepool](https://github.com/v0idravl/tidepool) — binaural beat player;
  named modes, vim keys, phase-continuous synthesis, one file
- [dotfiles-public](https://github.com/v0idravl/dotfiles-public) — minimal,
  plaintext-forward Debian/Wayland desktop; sudo-free, nothing outside
  $HOME

host defense

- [traxerax-lite](https://github.com/v0idravl/traxerax-lite) — behavioral
  Linux host defense and audit; anomaly-based, no signatures, no network
  calls, handwritten eBPF probe

offensive tooling — the ai-offsec stack

- [p0rtix](https://github.com/v0idravl/p0rtix) — scope-aware recon:
  interactive TUI, headless CLI, or over MCP; every action logged
- [sliver-mcp](https://github.com/v0idravl/sliver-mcp) — the Sliver C2
  operator surface as MCP tools an AI agent can drive; safety-gated

casework

- [chr0nix](https://github.com/v0idravl/chr0nix) — the investigative-
  documentation suite: SHA-256 manifests + custody logs, UTC exhibit
  timelines, identifier research, image metadata, case management. One
  repo, one security model, one console orchestrating every module
  behind risk-tiered attestation

field notes

- [hakiki](https://v0idravl.github.io/hakiki) — command-first offensive
  quick reference: full AD kill chains, web, privesc, exploit dev
- [lab-writeups](https://v0idravl.github.io/lab-writeups) — 70+ redacted
  HTB / PG / THM engagements; every claim traceable to a command, a log,
  or a screenshot

───[ env ]──────────────────────────────────────────────────────────────────//──

- Offline-first. The read path never needs a network.
- Stdlib-first. Zero dependencies is a feature, not a constraint.
- Small and auditable. Read any tool end-to-end in ten minutes —
  that is the flex.
- Lawful and authorized, always.
- Behavior-based, never appearance-based — in the field and in the logs.
- The written record is the product.

───[ man ]──────────────────────────────────────────────────────────────────//──

Opinions and projects here are my own and unrelated to my employer's
systems, data, or casework. Public content is sanitized and limited to
lab or authorized environments.

───[ ping ]─────────────────────────────────────────────────────────────────//──

email     v0id.ravl@mailbox.org — pgp preferred; signed mail read first
pgp       36C1 E0A6 63E8 1484 ED32 562B 8117 C621 0E02 2019
web       v0idravl.github.io/whoami (pubkey + monthly warrant canary)
location  san diego, ca — unrestricted mobility, short notice
```

[![whoami](https://img.shields.io/badge/whoami-v0idravl.github.io%2Fwhoami-3DA639)](https://v0idravl.github.io/whoami)
[![lab-writeups](https://img.shields.io/badge/lab--writeups-70%2B%20engagements-222222)](https://v0idravl.github.io/lab-writeups)
[![hakiki](https://img.shields.io/badge/hakiki-field%20reference-CC0000)](https://v0idravl.github.io/hakiki)
[![chr0nix](https://img.shields.io/badge/chr0nix-investigative--doc%20suite-222222)](https://github.com/v0idravl/chr0nix)
[![email](https://img.shields.io/badge/email-pgp%20preferred-3DA639)](mailto:v0id.ravl@mailbox.org)
