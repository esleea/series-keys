# Control: G-Star Book 4, Mock Test 1, final — grammar and words

Hand proofread on 27 November 2026, against **SB4 Lessons 1–4**, the first half of the book. Keys
and sentences are in `gstar-b4-mock-test-1-final.md`; texts in `gstar-b4-mock-test-1-final-texts.md`.

**How it was checked.**
- **Grammar** was checked by hand against the SB4 L1–4 grammar points. I took these from the
  2 November report, which read them from `data/transcriptions/gstar-sb-4/lesson-{1,2,3,4}.json`;
  I did not re-read those files this round.
- **Words:** a `grep` over the book's text layer and the audioscript for each of the 40 L1–4
  words, allowing inflections.
- **Forward reference:** a `grep` for the present perfect continuous, *should / could / would
  have*, *wish*, the past perfect passive and later SB4 words, plus a hand read.
- Nothing paid ran.

★ marks a misuse of the lesson's own target grammar.

## The lessons' grammar

| SB4 lesson | Grammar | Used correctly? | Tested? |
| --- | --- | --- | --- |
| L1 | linking verbs; *remember / forget / stop* + infinitive or gerund | `face turned pale`, `they looked annoyed`, `he grew uneasy`, `stopped working`, Q38 `forget purchasing` ✓ | Q29, Q47 (an adjective after a linking verb) |
| L2 | *so / such … that* | `so magical that I was curious`, `so loud that everyone … could hear`, `such a long life that she outlived …` ✓ | No item |
| L3 | future continuous; *be supposed to* | `I'll be hosting a party`, `we'll be looking for some`, `Everyone else will be wearing …`, `I'm supposed to attend`, `he was supposed to retire`, `Kate was supposed to keep an eye on the queue` ✓ | Q17 (comprehension) |
| L4 | second conditional; *If I were you*; *either … or* | `If he held a meet-and-greet event here, would you come …?`, `If I won that much money, I'd be on a plane too!`, `If I were you, I'd be proud …`, `either Brown University or Green University` ✓. ★ `You can either purchase a ticket online or at the ticket booth` | No item |

## Must fix

| Id | Where | Finding | Suggested change |
| --- | --- | --- | --- |
| B4M1F-G01 | p8 Part 6 Q31 ★ | `You can either purchase a ticket online or at the ticket booth.` *Either* sits before the verb, but *or* joins two places (B4M1F-11) | `You can purchase a ticket either online or at the ticket booth.` |
| B4M1F-G02 | p18 Part 10 | `they were so concentrated on their projects`. *Concentrate* (an L4 word) is used as an adjective (B4M1F-12) | `they were concentrating so hard on their projects that …` |
| B4M1F-G03 | Audio Part 4 Q18 | `Why do you call it a day?` (L1 phrase; reversed meaning; B4M1F-A02) | `Why don't you call it a day?` |

## Should fix (forward reference, all read or heard only)

| Id | Where | Finding | Suggested change |
| --- | --- | --- | --- |
| B4M1F-G04 | Audio Part 4 Q18 | `You've been working all day`: the present perfect continuous is SB4 L8 (2 November C01, half fixed) | `You worked all day` |
| B4M1F-G05 | p19 Part 10 | `I should have made sure they heard my warning`: *should have* + past participle is SB6 L5 (2 November C04) | `Next time, I will make sure they hear my warning.` |
| B4M1F-G06 | p18 Part 10 | `equipment had not been replaced`: the past perfect passive is in no heading (2 November C05) | `The school had not replaced our science lab equipment since …` |
| B4M1F-G07 | p8 Q32; p18 | `can be easily damaged`; `the school would be criticized`. The modal passive is SB5 L2 | `it is valuable and people can easily damage it`; `people would criticize the school` |
| B4M1F-G08 | p6 Part 5; p8 Q33 | `disturbing other guests / visitors`: *disturb* is an SB4 **L5** word (2 November C06) | `bothering other guests` |

## Words

**All 40 SB4 L1–4 words appear.** `playful`, the one missing on 2 November, is now in the Part 3
audio (`My siblings are so playful`). The least-used words are `compromise` and `playful` (once
each, both in the audio).

| Lesson | Words |
| --- | --- |
| L1 | attend, annoy, check on, in pain, pale, strange, uneasy, awful, call it a day, playful |
| L2 | participate, wear out, panic, rowdy, well-dressed, valuable, urgent, exhausted, incredible, unforgettable |
| L3 | root for, dedicate, wait in line, queue, flea market, purchase, concert, fan, well-liked, amaze |
| L4 | exercise, concentrate, retire, take up, diet, travel around the world, lottery, wealthy, compromise, cruel |

As in Book 3 Mock Test 1, **few items make the student choose a structure.** Only Q29 and Q47 need
a linking-verb adjective. Parts 5, 9 and 10 test words. A gap such as `I was ___ tired that I fell
asleep` (`so / such / very / too`) or `If I ___ rich, I would travel` (`were / am / will be /
have been`) would test L2 and L4.

## Fixed since 2 November

- C02: the subjunctive in Q19 is gone.
- C03: *I wish … would* in Part 9 is gone.
- C05: two of the three past perfect passives (*had been murdered*, *had been taken*) are gone.
- C07: *faint* is gone.
