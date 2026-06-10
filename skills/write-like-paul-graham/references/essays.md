# Calibration essays

Paul Graham's FAQ (paulgraham.com/gfaq.html) asks people to link to his essays rather than mirror them, so this repo contains none of his text. When you need to calibrate against the source, fetch one or two of these live and study the sentences before writing. Pick by which rule needs reinforcing.

| Essay | URL | What it demonstrates |
|---|---|---|
| Write Simply | paulgraham.com/simply.html | The whole register, stated as an argument. Read first. |
| Write Like You Talk | paulgraham.com/talk.html | The read-aloud test (rule 3). Notice how few words per sentence. |
| Writing, Briefly | paulgraham.com/writing44.html | His process in one paragraph-sized essay. Cutting (process step 3). |
| How to Write Usefully | paulgraham.com/useful.html | Honest qualifiers (rule 6): watch how he hedges precisely, never decoratively. |
| Putting Ideas into Words | paulgraham.com/words.html | Ideas carrying the interest (the core idea). |
| The Age of the Essay | paulgraham.com/essay.html | Starting mid-thought (rule 10) and ending when done (rule 11). |
| Maker's Schedule, Manager's Schedule | paulgraham.com/makersschedule.html | One explanatory analogy doing real work (rule 9). |
| Do Things that Don't Scale | paulgraham.com/ds.html | Specifics over abstractions (rule 12): count the proper nouns and numbers. |

## How to calibrate

1. Fetch one essay matched to the weakness in the current draft.
2. Read ten sentences. For each, note: word count, clause count, whether you'd say it aloud.
3. Rewrite the draft's worst paragraph to those measurements.
4. Do not copy his sentences or imitate his opinions. Calibrate rhythm and plainness only.

## Measured baselines

Computed over five essays fetched live (Write Simply, Write Like You Talk, How to Write Usefully, Putting Ideas into Words, Do Things That Don't Scale; 8,700 words). Heuristic sentence splitting and syllable counts, so treat as targets, not gospel.

| Metric | PG |
|---|---|
| Words per sentence | mean 15.6, median 14 (13-15 in the writing essays, 18 when explaining startups) |
| Sentence-length spread | 22% under 9 words, 13% over 25, longest 45 |
| Sentences per paragraph | 4 (median), ~63 words |
| One-syllable words | ~69% |
| 3+ syllable words | 8-12% |
| Flesch-Kincaid grade | 6-9 depending on topic, ~7.7 overall |

The non-obvious finding: his plainness is not uniform shortness. One sentence in eight runs past 25 words, usually a chain of plain clauses joined with "and" or commas, sitting next to a 4-word sentence. A draft where every sentence lands between 8 and 20 words has the drumbeat of a model imitating him, not the rhythm of him. Vary the lengths; keep the words short.
