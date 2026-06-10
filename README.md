# write-like-paul-graham

A [Claude Code skill](https://docs.anthropic.com/en/docs/claude-code) that makes AI stop writing like AI.

## The story

I asked my AI to draft a LinkedIn post. It was good. It was also unmistakably AI: every paragraph landed on a little aphorism, the vulnerability was performed, and there were em dashes everywhere. I told it my favorite writing is [Paul Graham's essays](https://www.paulgraham.com/articles.html) and that my own register is matter-of-fact.

The rewrite was the post I actually published. Then we turned the difference into rules, and the rules into this skill.

## What it does

Drafts and edits prose in the PG register: short declarative sentences, ideas over rhetoric, honest qualifiers, no em dashes, no aphorism-stacking, no performed emotion. It includes the full editing checklist of AI tells and a before/after example.

It will not make your AI share Paul Graham's opinions. It transfers the register, not the man.

## Install

Copy the skill folder into your skills directory:

```bash
# available in every project
cp -r skills/write-like-paul-graham ~/.claude/skills/

# or per-project
cp -r skills/write-like-paul-graham your-repo/.claude/skills/
```

Then ask Claude to "de-AI this", "make this matter-of-fact", or "write like Paul Graham", or just invoke `/write-like-paul-graham`.

## Why plain prose, now

Models optimize sentences to sound good, so readers have learned that sounding good is what machines do. The register that reads as human in 2026 is the one that was always best anyway: plain, direct, specific. PG wrote the manual decades ago. This just makes your AI follow it.

## License

MIT. Not affiliated with or endorsed by Paul Graham.

Made by [Josh Merrill](https://www.linkedin.com/in/joshuamerrill) while building [Clair](https://getvoyance.com), a personal AI that catches the plans hiding in your messages.
