# 🗺️ Phage — Public Roadmap

This is the **single source of truth** for what gets built next in [Phage](https://slonto.com/happytodev/digitaux/phage).

Phage is [sponsorware](https://github.com/sponsors/happytodev): free binaries for everyone, source code sponsor-only until **50 sponsors**, then 100% open source (MIT).

**Progress: X / 50 sponsors** — see [Become a sponsor →](https://github.com/sponsors/happytodev)

## How voting works

> Everyone votes with 👍. Each verified sponsor adds +3, no cap. Highest score wins. Maintainer keeps a public veto on feasibility / scope / security only.

- **Everyone**: react with 👍 on the issue you want. No `+1` comments — they are ignored in the count.
- **Sponsors ($10/mo+)**: comment `sponsor-vote` on the issue (or DM to stay anonymous). After verification against the sponsors list, a maintainer adds the `sponsor-voted xN` label and pins a scoring comment.
- **Score**: `score = 👍 + 3 × verified sponsors`. Example: 19 👍 + 2 sponsors = 19 + 6 = 25.
- **Decision**: highest score wins within the top requests. Ties go to sponsors.
- **Veto**: the maintainer can only refuse or reshape on public grounds (too big, out of scope, security risk) — with a written reason on the issue. A `sponsor-voted` issue always gets a maintainer decision, never silence.

Monthly, the top 10 by score is published in a pinned Discussion and promoted to `planned`.

## 🚧 In progress

- Wails v2.16 upgrade
- HTTPS certificate UX improvements

See linked issues with the `in-progress` label.

## 📋 Planned (ordered by score)

_Sorted at each monthly review. Each entry links its issue with the pinned score._

| Feature | Score | Issue |
|---|---|---|
| _Empty — be the first to propose_ | — | — |

## 💡 Under consideration

Everything labeled `enhancement` + `needs-triage` or `accepted`, sorted by 👍. Vote there.

👉 [Browse feature requests →](../../issues?q=is%3Aissue+is%3Aopen+label%3Aenhancement+sort%3Areactions-%2B1-desc)

## ✅ Shipped

Shipped features keep their `shipped` label for history. Recent highlights:

- FrankenPHP + hybrid PHP-FPM backend (8.5 → 7.4 side by side)
- One-click templates (Laravel, Symfony, Filament, WordPress, CakePHP, Drupal, Vanilla)
- Custom `.test` domains, reverse proxy, auto-detection
- MySQL, PostgreSQL, SQLite + Adminer + Redis browser
- Real-time debugger, Xdebug, SPX profiler, Mailpit, logs, docs
- Public tunnels (Cloudflare + Pinggy)
- Native desktop GUI (Go + React), light/dark/auto theme
- macOS, Linux, Windows support

## Propose something

- 💡 [Open a feature request →](../../issues/new?template=feature_request.yml) — describe your **use case**, not just the solution.
- 🐛 [Report a bug →](../../issues/new?template=bug_report.yml) — bugs are fixed by severity, not by vote.
- 💬 [Join the discussion →](../../discussions) — half-baked ideas welcome in `Ideas`; actionable ones get promoted to issues by a maintainer.
