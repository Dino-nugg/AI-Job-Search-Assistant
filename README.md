# 🔍 Job Scout

An AI-powered job digest tool that scours the web for opportunities, scores them against your resume, and delivers a curated newsletter straight to your inbox.

Built with Claude (Anthropic) — no backend required. Runs entirely in the browser.

---

## What It Does

- **Search** job listings across Adzuna, VC firm career pages, and the a16z Build newsletter
- **Upload your resume** and describe the roles you're looking for in plain English
- **AI scoring** — Claude reads every listing and ranks them High Priority vs. Worth Watching based on your fit
- **Email digest** — sends a formatted newsletter to your inbox via Gmail

---

## How To Use

1. Open the app: **[https://dino-nugg.github.io/jobscraper](https://dino-nugg.github.io/AI-Job-Search-Assistant)**
2. Describe what you're looking for (role type, firm stage, location, sector)
3. Upload your resume (PDF or TXT)
4. Get a free Anthropic API key at **[console.anthropic.com](https://console.anthropic.com)** — just create an account, it takes 2 minutes. Your key is only used in your browser and never stored anywhere.
5. Hit **Run Scout** and get your ranked digest
6. Send it to your email with one click

---

## Stack

- Plain HTML/CSS/JS — no framework, no build step
- [Claude API](https://anthropic.com) for resume matching and digest formatting
- [Adzuna API](https://developer.adzuna.com) for live job listings
- Gmail MCP for email delivery

---

## Requirements

- A free **Anthropic API key** — sign up at [console.anthropic.com](https://console.anthropic.com) (no credit card required to start)
- A **Gmail account** for sending the digest

---

## Roadmap

- [ ] Scheduled delivery every N days (no manual trigger needed)
- [ ] LinkedIn integration via Proxycurl
- [ ] "Already seen" job deduplication across digests
- [ ] User accounts + saved search profiles

---

## License

MIT
