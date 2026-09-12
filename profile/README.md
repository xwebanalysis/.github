<h1 align="center">XWA — X Web Analysis</h1>

<div align="center">
<p><em>Modular web analysis ecosystem — cybersecurity, scraping, auditing and more</em></p>
</div>

## Tools

| Tool | Focus | Status |
|------|-------|--------|
| [samurai](https://github.com/xwebanalysis/samurai) | Web cybersecurity analysis | Released (v2.5.0) |
| [shinobi](https://github.com/xwebanalysis/shinobi) | Stealth web scraping with anti-blocking | Released (v0.1.0) |
| [tengu](https://github.com/xwebanalysis/tengu) | Web quality auditor | Released (v0.2.0) |
| [kensei](https://github.com/xwebanalysis/kensei) | Web technology stack profiler | In development (v0.3.0) |
| [kabuki](https://github.com/xwebanalysis/kabuki) | WAF and CDN analysis | In development (v0.1.0) |
| [yari](https://github.com/xwebanalysis/yari) | API security testing | In development (v0.1.0) |
| [musha](https://github.com/xwebanalysis/musha) | Web content and DOM analysis | In development (v0.2.0) |
| [azuma](https://github.com/xwebanalysis/azuma) | Web form and authentication flow analyzer | In development (v0.3.0) |

## Ecosystem

- [xwa-sdk](https://github.com/xwebanalysis/xwa-sdk) — shared data schemas and API contracts (v0.2.0)
- [meta](https://github.com/xwebanalysis/meta) — documentation, roadmap and orchestration

Every tool runs 100% locally with SQLite:

```bash
git clone https://github.com/xwebanalysis/<tool>.git
cd <tool>
./<tool>.sh local
```

With all repositories checked out side by side, `./xwa.sh up` starts the whole suite on distinct ports.
