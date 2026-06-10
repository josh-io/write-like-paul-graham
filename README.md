# write-like-paul-graham

A [Claude Code skill](https://docs.anthropic.com/en/docs/claude-code) that makes AI stop writing like AI.

## The story

I asked my AI to draft a LinkedIn post. Every sentence was fine and I couldn't publish it. Each paragraph ended on a little punchline, the emotion was fake, and there were em dashes everywhere. So I told it my favorite writing is [Paul Graham's essays](https://www.paulgraham.com/articles.html), and that my own register is matter of fact.

The rewrite was the post I published. Then I had it write down what it changed and why, as rules, and the rules became this skill. Since then, every time a draft has drifted back toward AI, the correction has become another rule. There are fifteen now.

## What it does

Drafts and edits prose in Paul Graham's register: ordinary words, short declarative sentences, honest qualifiers, no em dashes, no punchlines, no fake emotion. The skill includes a checklist of AI tells to strip, a before and after example, and measured baselines from his essays (words per sentence, paragraph length, grade level) so the model can check a draft against the real thing instead of its memory of the real thing.

It transfers his register, not his opinions.

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

Models learned to write from people, and a lot of people decorate. So models decorate. Readers have spent three years learning to spot it, and now plain writing is the writing that reads as human. Paul Graham has been explaining how to do it for twenty years. This skill makes your AI take the advice.

## License

MIT. Not affiliated with or endorsed by Paul Graham. His essays stay on his site: the skill fetches them to calibrate and never copies them.

Made by [Josh Merrill](https://www.linkedin.com/in/josh-io/) while building [Clair](https://getvoyance.com), a personal AI that catches the plans hiding in your messages.
