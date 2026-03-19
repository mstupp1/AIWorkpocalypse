# AGENTS.md — AI Workpocalypse Writing Project

## Project Overview

This repository contains the manuscript for **"Surviving the AI Workpocalypse: A Cynic's Guide"** — a satirical nonfiction book about how corporate work actually functions in the AI era (circa 2026), and how individuals can navigate it without overcommitting, overworking, or misunderstanding how organizations actually operate.

**Author:** Myles Stupp

### Target Audience
White-collar knowledge workers — primarily remote — who see their jobs as a means to an end, not a calling. Cynics who don't really give a shit about fake corporate culture and just want to maximize their actual lives. If you love posting on LinkedIn, this book isn't for you.

### The Real Thesis
This is NOT a book about getting ahead, winning, getting promoted, or climbing the ladder. It's about:
- Appearing competent enough to keep getting paid
- Getting good enough reviews that nobody bothers you
- Your manager liking you (or at least not disliking you)
- People not actively wanting you gone
- **Enjoying your actual life** — gym, lunch, TV, side projects, errands, family, pets, multiple jobs, whatever

AI is both the enemy (it's coming for your job) and the tool for surviving until it does. Your duty is to hold the line, automate the bullshit, and reclaim your time.

### Scope & Perspective
- Focused on the **2026 landscape** with an eye toward where things are headed
- Primarily white-collar, remote/hybrid knowledge work — the author's lived experience
- Draws from personal examples throughout a relatively short but dense career
- References *Out of Office* by Charlie Warzel and Anne Helen Petersen as prior art on pre-AI workplace brokenness — this book picks up where that left off, especially the AI shit
- The pipeline: **corporate cracks → COVID/remote shattered it → AI piled on and made it a dumpster fire**

---

## Voice & Tone

### The voice is:
- **Cynical but grounded** — not bitter, just honest (okay, a little bitter)
- **Aggressive and funny** — humor that hits hard, not polite chuckles
- **Blunt and direct** — say the real thing, not the polished corporate version
- **Profane when it lands** — strategic swearing for emphasis and comedy, not gratuitous but not shy about it either. If a "fuck" makes the sentence funnier or more honest, use it.
- **Satirical without becoming purely comedic** — this is still a *useful* book
- **Practical beneath the satire** — every observation should imply or state actionable insight
- **Anti-hustle, anti-grind** — this is not a book about working harder or smarter. It's about working less and living more.

### The voice is NOT:
- Academic, formal, or textbook-like
- A corporate whitepaper or consulting deck
- Preachy, self-righteous, or motivational-speaker-y
- Pure comedy with no substance
- Overly abstract or philosophical
- LinkedIn-brained ("I'm so grateful for this journey" energy is banned)
- Sanitized or corporate-safe — if it reads like HR approved it, rewrite it

### Write like:
Someone describing reality as they've experienced it, not as theory. Like a sharp coworker explaining how things *really* work over drinks — someone who's been in the rooms, seen the patterns, and can articulate them with precision and dark humor. Someone who will absolutely say "this is bullshit" when it's bullshit.

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
9. **AI as both enemy and salvation** — it's coming for your job, but it's also the tool that lets you survive until it does
10. **Work is not your life** — the goal is to minimize corporate time and maximize living
11. **The AI religion** — deniers, evangelists, and everything in between; everyone has a stupid opinion about which model/company/framework is the best
12. **The dumpster fire pipeline** — corporate cracks → COVID/remote → AI → current state of chaos
13. **Type bullshit in, get bullshit out** — the blessing and curse of AI as a black box that converts garbage input into polished garbage output
14. **Every company is an "AI company"** — yet most don't do anything useful with it, usually reinventing worse versions of existing tools
15. **AI coding and the software layer** — a shitload of these jobs are fundamentally about generating code that makes something that makes money, and AI is rewriting that equation

### AI Ecosystem References (Use When Relevant):
- OpenAI, Anthropic, Google — the big players and their competitive acceleration
- The rapid evolution from early ChatGPT-style tools to widespread enterprise adoption
- The arms race dynamic and what it means for workers on the ground
- The nostalgia for older models that produced more hilariously bad artifacts vs. newer models that are "pretentious assholes who are always right and wrong at the same time"
- The ecosystem of opinions, frameworks, interfaces, and hot takes that nobody asked for

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
