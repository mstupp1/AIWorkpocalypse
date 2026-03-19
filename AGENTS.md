# AGENTS.md — AI Workpocalypse Writing Project

## Project Overview

This repository contains the manuscript for **"Surviving the AI Workpocalypse: A Cynic's Guide"** — a satirical nonfiction book about how corporate work actually functions in the AI era (circa 2026), and how individuals can navigate it without overcommitting, overworking, or misunderstanding how organizations actually operate.

**Author:** Myles Stupp

---

## Voice & Tone

### The voice is:
- **Cynical but grounded** — not bitter, just honest
- **Funny and observational** — humor emerges from recognizing truth, not from jokes
- **Blunt and direct** — say the real thing, not the polished corporate version
- **Satirical without becoming purely comedic** — this is still a *useful* book
- **Practical beneath the satire** — every observation should imply or state actionable insight

### The voice is NOT:
- Academic, formal, or textbook-like
- A corporate whitepaper or consulting deck
- Preachy or self-righteous
- Pure comedy with no substance
- Overly abstract or philosophical

### Write like:
Someone describing reality as they've experienced it, not as theory. Like a sharp coworker explaining how things *really* work over drinks — someone who's been in the rooms, seen the patterns, and can articulate them with precision and dark humor.

### Voice Sample (Reference Paragraph):
> Nobody tells you when you start a corporate job that the actual job is about 30% of what you'll spend your time on. The rest is a magnificent tapestry of meetings about meetings, Slack threads that could have been emails, emails that could have been nothing, and documentation that exists solely so someone can point to it later and say "we had a process." AI didn't create this problem. AI just made it possible to produce the documentation faster, which means now there's more of it, which means now you need more meetings to discuss it. Progress.

---

## Core Themes

When writing or expanding any section, keep these themes in mind. They are the connective tissue of the book:

1. **AI as a normalization layer** — producing "good enough" work at scale
2. **The shift from actual output → perceived output** — what matters is what *looks* like work
3. **Corporate optimization for signals** — documentation, coordination, and signaling over real impact
4. **Meetings, processes, and artifacts as performance** — theater with KPIs
5. **Asymmetry of proof** — burden placed unevenly (you must prove value; the org does not)
6. **Layoffs, instability, and constant change** — the permanent impermanence of modern employment
7. **AI-enabled individual velocity** — tools that let one person generate what used to take teams
8. **The gap between appearance and reality** — what work appears to be vs. what it actually is

### AI Ecosystem References (Use When Relevant):
- OpenAI, Anthropic, Google — the big players and their competitive acceleration
- The rapid evolution from early ChatGPT-style tools to widespread enterprise adoption
- The arms race dynamic and what it means for workers on the ground

---

## Book Structure

The manuscript lives in `manuscript/` and follows this structure:

```
manuscript/
├── 00-front-matter/
│   ├── title-page.md
│   ├── dedication.md
│   └── epigraph.md
├── 01-introduction/
│   └── introduction.md
├── 02-part-1-the-ai-work-layer/
│   ├── ch01-the-great-normalization.md
│   ├── ch02-good-enough-is-the-new-great.md
│   ├── ch03-the-translation-layer.md
│   ├── ch04-the-arms-race.md
│   └── ch05-the-collapse-of-effort-visibility.md
├── 03-part-2-the-reality-of-corporate-work/
│   ├── ch06-the-illusion-of-work.md
│   ├── ch07-meetings-as-theater.md
│   ├── ch08-process-over-purpose.md
│   ├── ch09-metrics-as-narrative.md
│   ├── ch10-ownership-without-authority.md
│   ├── ch11-the-vague-request.md
│   └── ch12-the-burden-of-proof.md
├── 04-part-3-operating-inside-the-system/
│   ├── ch13-decoding-vague-requests.md
│   ├── ch14-ai-as-your-production-layer.md
│   ├── ch15-the-meeting-survival-guide.md
│   ├── ch16-information-flooding.md
│   ├── ch17-corporate-communication.md
│   └── ch18-the-art-of-satisficing.md
├── 05-part-4-stability-survival-positioning/
│   ├── ch19-layoffs-and-volatility.md
│   ├── ch20-the-restructuring-cycle.md
│   ├── ch21-avoiding-overcommitment.md
│   ├── ch22-leverage-and-visibility.md
│   ├── ch23-effort-vs-impact.md
│   └── ch24-navigating-instability.md
├── 06-conclusion/
│   └── conclusion.md
└── 07-back-matter/
    ├── acknowledgments.md
    └── about-the-author.md
```

---

## Writing Guidelines for AI Agents

### Content Rules
1. **Use clear, engaging prose with a satirical edge** — every paragraph should be interesting to read
2. **Include concrete examples** — vague observations are boring; specific ones are funny and relatable
3. **Avoid jargon unless satirizing it** — if you use corporate-speak, make it clear you're doing it on purpose
4. **Keep paragraphs readable** — no walls of text; break things up
5. **Prioritize clarity and relatability** — if a reader can't see themselves in it, it's not working
6. **Do NOT sound like a textbook** — ever
7. **Maintain consistency** — each chapter builds on the thesis, not repeating generic advice
8. **Use section headers within chapters** — break chapters into digestible, scannable sections

### Structural Rules
1. Each chapter is a single `.md` file in its respective part directory
2. Chapter files use `# Chapter Title` as the H1, followed by content with `## Section` headers
3. Front matter and back matter files are kept minimal and clean
4. All writing happens in the `manuscript/` directory
5. Notes, outlines, and research go in `notes/`
6. Export-ready versions go in `exports/` (when applicable)

### Chapter Format
```markdown
# Chapter Title

> *Optional opening quote or pithy one-liner*

## Section One

Content here...

## Section Two

Content here...
```

### When Continuing or Expanding the Manuscript
- Read the existing content in nearby chapters before writing new material
- Ensure new content doesn't repeat points already made elsewhere
- Maintain the same voice and tone throughout
- Each chapter should have a clear thesis and build toward it
- End chapters with either a sharp observation or a practical takeaway (or both)

---

## Project Conventions

### File Naming
- Use lowercase with hyphens: `ch01-the-great-normalization.md`
- Chapter files are prefixed with `chXX-` for ordering
- Part directories are prefixed with `XX-` for ordering

### Git Workflow
- Commit messages should reference what was written/edited: `"Draft ch01: The Great Normalization"`
- Use branches for major drafting sessions if desired
- Keep commits granular — one chapter or section per commit when possible

### Word Count Targets (Approximate)
- **Chapters:** 2,500 – 4,000 words each
- **Introduction:** 2,000 – 3,000 words
- **Conclusion:** 2,000 – 3,000 words
- **Full book target:** ~60,000 – 80,000 words

---

## Directory Overview

| Directory | Purpose |
|-----------|---------|
| `manuscript/` | The actual book content — chapters, front/back matter |
| `notes/` | Outlines, research, brainstorming, reference material |
| `exports/` | Compiled/exported versions (PDF, EPUB, etc.) |
| `.agents/` | Agent workflows and configuration |

---

## Quick Reference for Agents

When asked to write or edit book content:
1. **Check AGENTS.md** (this file) for voice, tone, and structural guidelines
2. **Read adjacent chapters** to maintain continuity
3. **Follow the chapter format** specified above
4. **Stay in character** — cynical, grounded, funny, practical
5. **Never produce generic self-help content** — this book is anti-generic
