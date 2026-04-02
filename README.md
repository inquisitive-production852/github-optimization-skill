<div align="center">

# GitHub Optimization Skill for Claude Code

**Turn any GitHub repo into a star-magnet landing page -- in one command.**

<br />

[![Star this repo](https://img.shields.io/github/stars/199-biotechnologies/github-optimization-skill?style=for-the-badge&logo=github&label=%E2%AD%90%20Star%20this%20repo&color=yellow)](https://github.com/199-biotechnologies/github-optimization-skill/stargazers)
&nbsp;&nbsp;
[![Follow @longevityboris](https://img.shields.io/badge/Follow_%40longevityboris-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/longevityboris)

<br />

[![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)
&nbsp;
[![Claude Code](https://img.shields.io/badge/Claude_Code-Skill-blueviolet?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48cGF0aCBkPSJNMTIgMkM2LjQ4IDIgMiA2LjQ4IDIgMTJzNC40OCAxMCAxMCAxMCAxMC00LjQ4IDEwLTEwUzE3LjUyIDIgMTIgMnoiIGZpbGw9IndoaXRlIi8+PC9zdmc+)](https://github.com/199-biotechnologies/github-optimization-skill)
&nbsp;
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=for-the-badge)](https://github.com/199-biotechnologies/github-optimization-skill/pulls)

---

Most GitHub repos look like abandoned wikis. Walls of text, no badges, no CTAs, buried install instructions. Visitors bounce in seconds and never star. This skill rewrites your README as a high-converting landing page, tunes your metadata for search engines and LLMs, adds the social proof signals that drive stars -- and includes a built-in knowledge base on how to promote your repo across every channel that matters.

[Install](#install) | [How It Works](#how-it-works) | [Before vs After](#before-vs-after) | [Features](#features) | [Star Growth Knowledge Base](#star-growth-knowledge-base) | [Contributing](#contributing)

</div>

## The Problem

Your code might be great, but nobody finds it. GitHub search ranks repos by metadata quality. Google indexes your README. LLMs cite repos with clear structure. If your README reads like a technical spec, you're invisible to all three.

Stars compound -- a repo with 50 stars gets recommended more than one with 5, which gets recommended more than one with 0. The gap widens every day you wait.

## Before vs After

| | Before | After |
|---|---|---|
| **README** | Wall of text, no structure | Landing page with CTAs, badges, visual flow |
| **Description** | Empty or "A tool for..." | Keyword-rich, action-oriented, under 120 chars |
| **Topics** | 0-3 generic tags | 10-20 targeted tags across purpose/tech/domain |
| **Badges** | None or mismatched sizes | Consistent `for-the-badge` with star + follow CTAs |
| **SEO** | H1 says "README" | H1/H2 contain target keywords naturally |
| **Footer** | Nothing | Repeated CTAs + your own author attribution |
| **Voice** | Robotic / AI-sounding | Human, direct, no slop phrases |

## Install

One step. Drop the skill into your Claude Code skills directory:

```bash
# Clone into your Claude Code skills folder
git clone https://github.com/199-biotechnologies/github-optimization-skill.git \
  ~/.claude/skills/github-optimization
```

Then tell Claude Code: "optimize this repo" or "use the github-optimization skill" on any repository.

On first run, the skill asks for your name, X handle, company, and website -- then saves a config file so it never asks again. Every repo you optimize gets your branding, not ours.

## How It Works

The skill runs an 8-step pipeline on your repo:

```
┌──────────────────────────────────────────────────────────┐
│                                                          │
│  0. CONFIG     Load or create your user config (once)    │
│       ↓                                                  │
│  1. AUDIT      Read current README, metadata, tags       │
│       ↓                                                  │
│  2. KEYWORDS   Find target search terms                  │
│       ↓                                                  │
│  3. METADATA   Optimize description + 10-20 topics       │
│       ↓                                                  │
│  4. README     Rewrite as a landing page                 │
│       ↓                                                  │
│  5. HUMANISE   Strip AI patterns from all prose          │
│       ↓                                                  │
│  6. EXTRAS     Add LICENSE, CONTRIBUTING if missing       │
│       ↓                                                  │
│  7. PUBLISH    Commit, push, apply gh repo edit           │
│                                                          │
└──────────────────────────────────────────────────────────┘
```

Step 5 chains into the [`humanise-text`](https://github.com/199-biotechnologies/humanise-text-skill) skill automatically -- every README passes through de-slopping before it ships.

## Features

| Feature | What It Does |
|---|---|
| **Self-configuring** | Asks for your details once, saves to config, uses your branding on every repo |
| **Landing page README** | Rewrites your README with CTAs, badges, pitch, visual workflow, and structured sections |
| **SEO-optimized headers** | Places target keywords in H1/H2 for GitHub search, Google, and LLM discoverability |
| **Metadata optimization** | Writes a punchy description under 120 chars + 10-20 topic tags |
| **Badge system** | Adds consistent `for-the-badge` shields with star count, optional follow CTA, license, and more |
| **AI de-slopping** | Chains into [`humanise-text`](https://github.com/199-biotechnologies/humanise-text-skill) to strip words like "leverage", "seamlessly", "robust" |
| **Star growth advisor** | Built-in knowledge base with launch strategies, channel playbooks, and ROI rankings |
| **Author attribution** | Consistent footer with your name, company, and social links -- not ours |
| **Extras** | Adds MIT LICENSE and CONTRIBUTING.md if missing |

## Star Growth Knowledge Base

The skill includes a comprehensive knowledge base on how to grow GitHub stars. Ask "how do I get more stars?" or "launch strategy" and it draws from research across 50+ tactics:

| Channel | Expected Stars | Key Insight |
|---|---|---|
| **Hacker News** | 121 avg in 24h, up to 1,500 | Post Tue-Thu 8-10 AM PT. Write like a peer, not a marketer. |
| **Reddit** | 50-300 per post | r/SideProject allows self-promo. Tailor per subreddit. Build karma first. |
| **Product Hunt** | 200-1,000 for top 5 POTD | Launch 12:01 AM PST. Reply to everything. 600-800 upvotes for #1 weekday. |
| **Twitter/X** | 50-500+ if viral | Demo videos outperform text. Supporters' tweets > your own. |
| **Awesome lists** | Slow burn, compounds | Submit PRs. Also: create your own list in your niche. |
| **Newsletters** | 50-500 per feature | Console.dev, Changelog, PyCoder's Weekly accept submissions. |
| **GitHub Trending** | 200-2,000+ | Triggered by velocity, not absolute numbers. Stack launches to hit it. |
| **Stacked launch** | 200-2,000+ in a week | HN + Reddit + X + PH on the same day. The meta-strategy. |

The full knowledge base covers: HN/Reddit/PH detailed playbooks, the stacked launch strategy, GitHub SEO, awesome lists, newsletter directory with submission links, 17 growth hacks, cold start strategy (first 100 stars), and GitHub Trending algorithm mechanics.

## What's Inside

```
github-optimization-skill/
├── SKILL.md           # Skill definition + star growth knowledge base
├── README.md          # You're reading it
├── LICENSE            # MIT
└── CONTRIBUTING.md    # How to contribute
```

## Dependencies

This skill chains into one other skill during execution:

| Skill | Purpose | Repo |
|---|---|---|
| **humanise-text** | Strips AI writing patterns from all README prose before publishing | [`199-biotechnologies/humanise-text-skill`](https://github.com/199-biotechnologies/humanise-text-skill) |

Install both for the full pipeline:

```bash
git clone https://github.com/199-biotechnologies/humanise-text-skill.git \
  ~/.claude/skills/humanise-text
```

## User Config

On first run, the skill creates `~/.claude/skills/github-optimization/.config.yml` with your details:

```yaml
# GitHub Optimization Skill -- User Config
author_name: "Your Name"
author_github: "yourusername"
x_handle: "yourhandle"          # leave "" to skip Follow badge
company_name: "Your Company"    # leave "" to skip
company_url: "https://yourcompany.com"
website_url: "https://yoursite.dev"
```

Edit this file anytime, or tell Claude Code "update my github-optimization config" to change it.

## Writing Rules the Skill Enforces

The skill bans common AI writing patterns and enforces a direct, human voice:

**Banned words:** leverage, streamline, empower, seamlessly, robust, cutting-edge, revolutionize, harness, elevate, supercharge

**Required style:** Active voice, short sentences, "you/your" address, concrete examples, no filler words, no fake enthusiasm (no exclamation marks)

## Contributing

Contributions welcome. If you've found a pattern that drives more stars, a README structure that converts better, or a growth tactic worth adding to the knowledge base, open a PR.

See [CONTRIBUTING.md](CONTRIBUTING.md) for the 3-step process.

## License

[MIT](LICENSE) -- use it however you want.

---

<div align="center">

Built by [Boris Djordjevic](https://github.com/longevityboris) at [199 Biotechnologies](https://github.com/199-biotechnologies) | [Paperfoot AI](https://paperfoot.ai)

<br />

**If this is useful to you:**

[![Star this repo](https://img.shields.io/github/stars/199-biotechnologies/github-optimization-skill?style=for-the-badge&logo=github&label=%E2%AD%90%20Star%20this%20repo&color=yellow)](https://github.com/199-biotechnologies/github-optimization-skill/stargazers)
&nbsp;&nbsp;
[![Follow @longevityboris](https://img.shields.io/badge/Follow_%40longevityboris-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/longevityboris)

</div>
