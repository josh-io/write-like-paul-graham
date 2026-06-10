---
name: write-like-paul-graham
description: 'Use when writing or editing prose that should read plain, direct, and human - essays, founder posts, launch logs, emails, READMEs, landing copy. Triggers on "this sounds like AI", "de-AI this", "write like Paul Graham", "make it matter-of-fact", "plain prose", or any draft the user says reads as written-by-a-model. Produces the PG register: short declarative sentences, ideas over rhetoric, no em dashes, no aphorism-stacking.'
license: MIT
---

# Write Like Paul Graham

This skill copies the way Paul Graham writes, not what he thinks: ordinary words, simple sentences, ideas over rhetoric.

It exists because language models write the opposite way by default. They make each sentence sound good, so every paragraph ends on a little punchline, every list comes in threes, and em dashes hold together sentences that should be two. Readers have learned to spot all this. Plain writing now reads as human.

## The core idea

Good writing shows the reader your thinking. If the thinking is good, plain sentences are enough. If it's bad, fancy sentences hide that, mostly from you.

So the skill is mostly subtraction: remove everything that isn't the idea.

## The rules

1. **Plain sentences.** Subject, verb, object. If a sentence needs a second read, rewrite it. Two short sentences are better than one clever one.

2. **Short common words.** "Use" not "utilize." "Helps" not "facilitates." "Now" not "in today's landscape." If a simpler word means the same thing, use it. The same goes for judgments: if you mean bad, say bad. Models avoid plain judgments ("you can tell when AI wrote it" instead of "AI writing is bad"), which is a way of hedging.

3. **Write like you talk.** Read the draft aloud and rewrite every sentence you wouldn't say to a friend. Two signs you're talking: you say "you", and you repeat the important words. PG uses "conceal" three times in three sentences. Swapping in synonyms (hides, masks, obscures) is something writers do and talkers don't.

4. **No em dashes.** The most reliable AI tell, and PG rarely uses them. Replace each one with a colon, a comma, parentheses, or two sentences. (A signature like "— Josh" is fine.)

5. **Kill the quotable sentences.** The most important rule. If a sentence sounds like it wants to be shared ("A log where the numbers only appear once they're impressive isn't a log, it's a press release"), rewrite it flat ("A log where the numbers only show up once they're good isn't a log"). One quotable line per piece at most.

6. **Honest qualifiers.** "Which is small." "I don't know if this will work." Saying what you're unsure of builds trust. Faked feeling does the opposite: "typing that number made me wince" is acting, while "I considered not publishing it" is a fact.

7. **State motives simply.** Not "radical transparency is core to who we are." Just "mostly because I always wished other founders would publish this stuff."

8. **Don't use formatting for emotion.** No bold for emphasis, no italics to tell the reader how to read a word, no dramatic one-line paragraphs. If a sentence needs typography to work, fix the sentence.

9. **One comparison at most, and only if it explains.** Cut comparisons that add scenery ("like a lighthouse in the fog of productivity"). Keep one if it explains something new through something the reader already knows ("building an AI with AI still feels strange, though I suspect in a year it won't, the way electricity stopped feeling strange").

10. **Start with the thing itself.** No warming up, no "In a world where," no opening question. PG's first sentences already say something.

11. **End when you're done.** No summary paragraph. No "the journey continues." When the information runs out, stop.

12. **Use numbers and specifics.** "13 people," not "a small but growing community." "Four minutes," not "remarkably fast." Specifics show you're telling the truth.

13. **One idea per piece, stated first.** Each PG essay makes one claim, often a surprising one, and the first sentence usually states it. If nothing in your draft could be disagreed with, you have a summary, not an essay. Find the claim and move it to the top.

14. **Explain, don't dramatize.** An anecdote is evidence. Tell it in one flat sentence and spend the space on what it proves. Don't set scenes or stage feelings; readers know when a feeling is staged. If a paragraph performs instead of explains, cut it.

15. **Observations, not laws.** "Writers with small ideas decorate" is a law. "That's why some people write that way" is an observation. The observation is truer and easier to believe. Include yourself and the reader in it, the way PG does. A piece that is only about other people's faults sounds smug.

## AI tells to strip (the editing checklist)

Run this pass on any draft, yours or a model's:

- Em dashes (rule 4)
- "It's not just X. It's Y." constructions
- Parallel triads ("the texts, the bills, the birthdays" is fine once; three triads in a piece is a pattern)
- Every paragraph ending on a punchline (let most paragraphs just stop)
- The vocabulary: delve, crucial, robust, comprehensive, nuanced, multifaceted, landscape, tapestry, testament, journey, elevate, seamless, supercharge
- Rhetorical questions as transitions ("So what does this mean for founders?")
- Faked emotion ("I'll be honest, this one stings") and staged scenes
- Adjective inflation (if every noun has a modifier, none of them matter)
- Summary endings, and calls to action where there is no real ask
- Italics on the word the reader was already going to stress
- Synonym rotation: new words for the key word instead of repeating it (rule 3)
- Words with private meaning: a term that means something to you but that the piece never explains ("decorate", "the spine")
- Laws where observations would do (rule 15)
- No "you" anywhere in the piece

## The process

1. **Draft fast and plain.** Don't write fancy and then simplify. Write the way you'd explain it out loud.
2. **Read it aloud.** Mark every sentence you wouldn't say. Rewrite those.
3. **Cut 30%.** Almost any draft survives this. The cuts are usually the rhetoric.
4. **The quotable pass.** Find sentences that sound like writing instead of talking. Flatten them.
5. **The dash pass.** Search for "—" and "–". Replace each one.
6. **The tells pass.** Run the checklist above.

## Before and after

Here is how a language model tends to write the idea behind this skill:

> In today's content-saturated landscape, the most powerful writing isn't the most elaborate — it's the most accessible. When you write with ordinary words and simple sentences, something almost magical happens: friction melts away, and your reader's energy flows directly into your ideas rather than your prose. Because here's the truth: writing isn't about sounding smart. It's about being understood.

Every tell is there: the warm-up opener, the em dashes, "isn't X, it's Y" twice, "almost magical," a paragraph built to end on a punchline.

Here is how Paul Graham actually wrote that idea, in the first three sentences of [Write Simply](http://paulgraham.com/simply.html):

> "I try to write using ordinary words and simple sentences. That kind of writing is easier to read, and the easier something is to read, the more deeply readers will engage with it. The less energy they expend on your prose, the more they'll have left for your ideas."

Same idea. The first version performs it. The second says it, and you read his three sentences without noticing them. That's the goal.

## What this skill is not

- Not for legal or academic writing that has to follow its own conventions.
- Not a Paul Graham impersonation. Don't take his opinions, his topics, or his "I" unless you share them.
- Not an excuse for lazy thinking. Plain prose exposes weak ideas. That's the point.

## Calibrating against the source

When the rules aren't enough, fetch one or two of Graham's essays and study the sentences before you write. `references/essays.md` maps each essay to the rule it shows best, lists measured baselines (sentence length, paragraph length, grade level), and gives a four-step calibration process.

Fetch, don't bundle: Graham's FAQ asks for links rather than copies, so this skill includes none of his text. Quote him only in short attributed snippets, and never copy his sentences into your output.

## Sources

Paul Graham's essays on writing, which say all of this better:

- [Write Simply](http://paulgraham.com/simply.html)
- [Write Like You Talk](http://paulgraham.com/talk.html)
- [Writing, Briefly](http://paulgraham.com/writing44.html)
- [How to Write Usefully](http://paulgraham.com/useful.html)
- [Putting Ideas into Words](http://paulgraham.com/words.html)

This project is not affiliated with or endorsed by Paul Graham.
