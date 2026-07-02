# AI, your way

**A Claude skill that adapts AI to how your brain actually works.** ADHD-first, and friendly to neurodivergent people generally.

Most AI tools default to walls of text, long menus of options, and no clear next step. For a lot of people — especially with ADHD — that's the exact opposite of helpful. This skill flips it: calm, scannable, one thing at a time, with a clear next action every time.

It does two things:

1. **Reconfigures how Claude talks to you** — a low-friction interaction mode you set up in about a minute, which Claude Code can save and reuse in future sessions.
2. **Gives you portable tools** — a "My AI Working Style" profile you can paste into **Gemini, ChatGPT, or Claude Projects**, plus standalone technique cards that work in any tool (or on paper).

## Principles

- **Strengths-based, not broken** — different wiring, not a defect.
- **No diagnosis required** — you never have to label yourself to switch on support.
- **Personalised** — you choose the tone, detail, and helpers; what suits one person doesn't suit another.
- **Plain and scannable** — the skill practises what it preaches.

> **ADHD-first, extensible.** Defaults are tuned for ADHD today. Autism- and dyslexia-specific modes are a welcome next step — contributions appreciated.

## Install

This is a [Claude Code](https://claude.com/claude-code) skill. Clone it straight into your skills folder:

```bash
git clone https://github.com/mf-cdr-jameson/ai-your-way ~/.claude/skills/ai-your-way
```

Then in Claude Code just say something like *"AI feels overwhelming, I have ADHD — help"* or *"set up my AI working style"*, and the skill will run.

## What's inside

```
ai-your-way/
├── SKILL.md                              # the skill itself
└── references/
    ├── tone-examples.md                  # warm vs neutral samples for setup
    ├── technique-cards.md                # standalone, paste-anywhere techniques
    ├── portable-profile-template.md      # the "My AI Working Style" profile
    └── tool-tips.md                      # where to paste the profile per tool
```

You can also read `references/technique-cards.md` and `references/tool-tips.md` on their own — they're useful even without Claude.

## Using it in other tools

The technique cards and the "My AI Working Style" profile are tool-agnostic on purpose. `references/tool-tips.md` shows exactly where the profile goes in Claude Code, Cowork, Chat/Projects, Gemini Gems, and ChatGPT custom instructions.

## Contributing

Best informed by people with lived experience. Issues and PRs welcome — especially autism- and dyslexia-friendly modes, and better wording. Keep it strengths-based and diagnosis-optional.

## License

MIT — see [LICENSE](LICENSE).
