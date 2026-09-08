```text
╔══════════════════════════════════════════════════════════════════════════════╗
║  ██╗   ██╗ ██████╗ ██╗██████╗ ██████╗  █████╗ ██╗   ██╗██╗                   ║
║  ██║   ██║██╔═████╗██║██╔══██╗██╔══██╗██╔══██╗██║   ██║██║                   ║
║  ██║   ██║██║██╔██║██║██║  ██║██████╔╝███████║██║   ██║██║                   ║
║  ╚██╗ ██╔╝████╔╝██║██║██║  ██║██╔══██╗██╔══██║╚██╗ ██╔╝██║                   ║
║   ╚████╔╝ ╚██████╔╝██║██████╔╝██║  ██║██║  ██║ ╚████╔╝ ███████╗              ║
║    ╚═══╝   ╚═════╝ ╚═╝╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝  ╚═══╝  ╚══════╝              ║
╚══════════════════════════════════════════════════════════════════════════════╝

───[ whoami ]───────────────────────────────────────────────────────────────//──

I find what doesn't belong, I prove it, and I make it hold up — with
people, with systems, and with code.

The skill is behavioral and it transfers: rapid, behavior-based
assessment honed over ~6 years of security fieldwork (overt/covert,
CCTV, plainclothes, armored), a year of rural 911 EMS, 70+ offensive
lab engagements, and a behavioral host-defense tool with a handwritten
eBPF probe. I've been on every side of an incident — responded to one
as an EMT, watched one through a camera wall, tailed one in
plainclothes, documented one for court, and replayed one in a lab.

The way I work is the other half of the offer: offline-first,
stdlib-only tools a single person can audit in an evening, and
documentation that makes evidence hold. Low-resource, high-capability —
the read path never needs a network, and neither do I.

───[ ps ]───────────────────────────────────────────────────────────────────//──

[-] Terminal software — Python (stdlib-first), bash, some C. Single-file
    tools with offline test suites and documentation meant to be read,
    not just rendered.
[-] Systems — Linux internals, x86 assembly, eBPF, bubblewrap sandboxing,
    kernel hardening. I like understanding systems below the API layer.
[-] Offensive security — 70+ documented lab engagements (HTB / Proving
    Grounds / THM). Active Directory end to end: AS-REP roasting,
    Kerberoasting, DCSync, ADCS and ACL abuse, BloodHound path reasoning,
    spraying under lockout constraints. Web exploitation, Linux and
    Windows privesc, exploit dev and reversing fundamentals. Authorized
    labs only — the writeups are the discipline. The methodology also
    ships as tooling: an MCP stack (recon, C2, PoC runner) that lets an
    AI agent drive the kill chain under explicit safety gates.
[-] Host defense & opsec — behavioral detection (no signatures, no
    network calls), personal opsec as daily practice rather than posture.
[-] Investigations, OSINT & surveillance — open-source research on a
    two-source corroboration standard (nothing single-source goes in a
    report); surveillance tradecraft from ~6 years in the field —
    overt/covert, CCTV, plainclothes; rapid, behavior-based assessment
    (never appearance-based); hands-on and de-escalation skills from
    armed and unarmed posts; evidence tooling, chain of custody,
    interview methodology (Wicklander-Zulawski, self-study). One year
    911-response EMS before the keyboards.

[-] Field readiness — austere-capable and unrestricted: any state, any
    road, short notice, minimal footprint. Code 3, armored, off-highway,
    snow, winch recovery; chainsaw and land tools; hands-on,
    de-escalation first. Self-sufficient by practice, not by slogan.

───[ ls ]───────────────────────────────────────────────────────────────────//──

terminal tools

- [shinbun](https://github.com/v0idravl/shinbun) — the daily newspaper as
  one dated 80-col file, pulled over tor each morning and read offline;
  hand-rolled SOCKS5 + HTTP, blend-in UA, fail-closed mode
- [sdwx](https://github.com/v0idravl/sdwx) — weather, surf, tides,
  sun/moon, and space weather in one 80-col report; stdlib only, no API
  keys, stale-cache fallback when offline
- [yomu](https://github.com/v0idravl/yomu) — terminal EPUB reader; one
  file, no network ever, the comments teach the format
- [sokudoku](https://github.com/v0idravl/sokudoku) — flashing-word (RSVP)
  speed reader for EPUB and text; pacing follows the reading research,
  not the app marketing
- [tidepool](https://github.com/v0idravl/tidepool) — binaural beat player;
  named modes, vim keys, phase-continuous synthesis, one file
- [dotfiles-public](https://github.com/v0idravl/dotfiles-public) — minimal,
  plaintext-forward Debian/Wayland desktop starter (sway, waybar, fuzzel);
  curated, sudo-free, nothing touches the system outside $HOME

host defense

- [traxerax-lite](https://github.com/v0idravl/traxerax-lite) — behavioral
  Linux host defense and audit; anomaly-based, no signatures, no network
  calls, handwritten eBPF probe

offensive tooling — the ai-offsec stack

- [p0rtix](https://github.com/v0idravl/p0rtix) — scope-aware recon:
  interactive TUI, headless CLI, or over MCP; every action logged
- [sliver-mcp](https://github.com/v0idravl/sliver-mcp) — the Sliver C2
  operator surface as MCP tools an AI agent can drive; safety-gated
- [p0cs](https://github.com/v0idravl/p0cs) — one uniform runner for PoC
  exploits and offensive helpers; stdlib only, authorized use only

casework

- [chr0nix](https://github.com/v0idravl/chr0nix) — UTC-ordered,
  hash-manifested exhibit timelines
- [cust0dia](https://github.com/v0idravl/cust0dia) — recursive SHA-256
  exhibit manifests + chain-of-custody logs
- [h4ndl3](https://github.com/v0idravl/h4ndl3) — offline-first identifier
  research worksheets
- [m3talex](https://github.com/v0idravl/m3talex) — image metadata
  extraction and synthetic-media indicator flagging

field notes

- [hakiki](https://v0idravl.github.io/hakiki) — command-first offensive
  quick reference: full AD kill chains, web, privesc, exploit dev;
  authorized use only
- [lab-writeups](https://v0idravl.github.io/lab-writeups) — 70+ redacted
  HTB / PG / THM engagements: AD, Linux, Windows; every claim traceable
  to a command, a log, or a screenshot

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
