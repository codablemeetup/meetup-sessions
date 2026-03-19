# Contributing Session Materials

Thanks for speaking at Codable Meetup! Here's how to add your slides, code, and demos to this repo.

## Quick Start

1. **Fork** this repository
2. **Find your event folder** (e.g. `2026-03-15-ai-assisted-software-engineering/`)
3. **Add your session subfolder** using the format: `##-short-session-title`
4. **Open a Pull Request** — one of the organisers will review and merge it

No need to be a member of the GitHub org. Anyone can contribute via a fork and PR.

## Repo Structure

Each meetup event gets a top-level folder. Individual sessions live inside it:

```
meetup-sessions/
├── README.md
├── CONTRIBUTING.md
└── 2026-03-15-ai-assisted-software-engineering/
    ├── README.md                                    ← event overview (maintained by organisers)
    ├── 01-prompt-engineering-for-developers/
    │   ├── README.md                                ← your session README
    │   ├── slides.pdf
    │   └── examples/
    ├── 02-ai-powered-code-review-workflows/
    │   ├── README.md
    │   └── slides.pdf
    └── ...
```

The event-level folder and its README are created by the organisers. You just need to add your numbered session folder inside it.

## Session README Template

Please include a `README.md` inside your session folder with at least the following:

```markdown
# Session Title

**Speaker:** Your Name — [GitHub](https://github.com/you) · [LinkedIn](https://linkedin.com/in/you)
**Event:** [Event Name](../)
**Date:** DD Month YYYY
**Slides:** [slides.pdf](./slides.pdf)

## Description

A short summary of what the talk covered (2–3 sentences is fine).

## Resources

- Links to tools, libraries, or articles mentioned in the talk
- Any setup instructions if the demo code needs them
```

See [a full example here](./2026-03-14-ai-assisted-software-engineering/01-introduction-to-agents-and-agentic-coding/).

## Guidelines

- **Keep files reasonable in size.** If your slides are over 25 MB, consider hosting them externally (Google Slides, Speaker Deck, etc.) and linking in the README instead.
- **Don't commit secrets or API keys.** Use environment variables or `.env.example` files for any configuration. Double-check before pushing.
- **Include a brief setup guide** if your demo code has dependencies, so people can actually run it.
- **License:** By contributing, you agree that your materials are shared under this repo's license. If your content has a different license, note it in your session's README.

## Need Help?

Never used Git/GitHub before? No worries — reach out to one of the organisers and we'll help you get your materials added. You can also email them to us and we'll upload on your behalf.
