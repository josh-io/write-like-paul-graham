# write-like-paul-graham

A [Claude Code skill](https://docs.anthropic.com/en/docs/claude-code) that makes AI write simply.

## The story

I asked my AI to draft a LinkedIn post. The draft sounded like AI: little punchlines, fake emotion, em dashes everywhere. So I told it my favorite writing is [Paul Graham's essays](https://www.paulgraham.com/articles.html), and to write more like him.

The rewrite was better, so I had it write down what it changed as rules. This skill is those rules. Every time a draft drifts back, I add a rule. There are fifteen now.

## What it does

Drafts and edits prose the way Paul Graham writes it: ordinary words, short sentences, honest qualifiers, no em dashes, no punchlines, no fake emotion. The skill includes a checklist of AI tells to strip, a before and after example, and measured baselines from his essays (words per sentence, paragraph length, grade level) so the model can check a draft against his actual sentences.

It copies his style, not his opinions.

## Install

Copy the skill folder into your skills directory:

```bash
# available in every project
cp -r skills/write-like-paul-graham ~/.claude/skills/

# or per-project
cp -r skills/write-like-paul-graham your-repo/.claude/skills/
```

Then ask Claude to "de-AI this", "make this matter-of-fact", or "write like Paul Graham", or just invoke `/write-like-paul-graham`.

## Why bother

People can tell when AI wrote something. Paul Graham has spent twenty years explaining how to write plainly. This skill makes your AI follow his advice.

## License

MIT. Not affiliated with or endorsed by Paul Graham. His essays stay on his site: the skill fetches them to calibrate and never copies them.

Made by [Josh Merrill](https://www.linkedin.com/in/josh-io/) while building [Clair](https://getvoyance.com), a personal AI that catches the plans hiding in your messages.
