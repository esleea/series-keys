# Control: G-Star Book 3, Mock Test 1, final — grammar and words

Hand proofread on 23 November 2026. This report checks the test against **SB3 Lessons 1–4**, the
first half of the book:
- that it uses the lessons' grammar correctly;
- that it tests that grammar;
- that nothing from a later lesson or book has to be produced.

Keys and sentences are in `gstar-b3-mock-test-1-final.md`; texts in
`gstar-b3-mock-test-1-final-texts.md`. The files are the same as there.

**How it was checked.**
- **Grammar** was read by hand against the SB3 L1–4 grammar points. These are taken from the
  5 October report, which read them from `data/series/pages/g-star-sb-3-sections.json`. I did not
  re-read that file this round.
- **Words:** a `grep` over the book's text layer and the audioscript searched for each of the 40
  L1–4 words, allowing inflections. Hits were checked by hand for false matches (for example,
  *learn* for *earn*).
- **Forward reference** was judged by hand against the later SB3 and SB4–6 lesson headings in the
  October report.
- Nothing paid ran.

★ marks a misuse of the lesson's own target grammar.

## The lessons' grammar

| SB3 lesson | Grammar | Used correctly? | Tested? |
| --- | --- | --- | --- |
| L1 We've Already Paid the Bill | present perfect with *already / yet / still* | `All my friends have already eaten there` ✓. ★ `we still haven't found a designer yet` (audio Part 4; A02) | No |
| L2 Feeling Confident, She Gave a Speech | participle phrases | `Seeing my passion, …`, `Feeling a strong sense of achievement, …`, option B `Feeling refreshed and inspired …` ✓ | No (Part 10 B is chosen by meaning) |
| L3 The Girl Who Speaks English Is Self-Taught | relative pronouns | `Jane Miller, who is one of my favorite artists`, `The people who live in the village`, `which I really enjoyed`, `the bracelet that I made` ✓ | No |
| L4 She Said That the Street Market Was Lively | reported speech | `She said that being a news anchor was part of journalism`, `They said that they were very proud of me`, `I asked if I could bring it home` ✓. Present tense for things still true (`Mom said that the parade starts at 4 PM`) is allowed | Only as comprehension (Q5) |

## Must fix

| Id | Where | Finding | Suggested change |
| --- | --- | --- | --- |
| B3M1F-G01 | Whole test | **Still no item tests the L1–4 grammar** (October C01). Part 8 used to be the obvious place, and it is now a vocabulary cloze (`inspired`, `Internet`, `confident`, `useful`, `proud of`). Part 10 is chosen by meaning. A Book 3 mock never asks the student to choose or produce *already/yet*, a participle phrase, a relative pronoun or a reported form | Turn two or three Part 8 gaps into grammar items. For example: a participle gap `___ my passion, my teacher said …` (`Seeing / Saw / Seen / Sees`, L2); a relative gap `The news anchor, ___ name was Giselle Whitaker, …` (`whose / who / which / that`, L3); a reported-speech gap `She said that being a news anchor ___ part of journalism` (`was / were / be / been`, L4; leave out `is`, which is also right for a fact that is still true) |
| B3M1F-G02 | Audio Part 4 ★ | `we still haven't found a designer yet` (see A02 in the overall report) | `we haven't found a designer yet` |

## Should fix (forward reference, all read or heard only)

| Id | Where | Finding | Suggested change |
| --- | --- | --- | --- |
| B3M1F-G03 | p13 Part 7 (Finn) | `I wish I could visit the countryside again`: *wish* + past is Book 5 L4 (October C02, still open) | `I hope I can visit the countryside again.` |
| B3M1F-G04 | p18 Part 10 | `a student from our school had won a place`: the past perfect is SB3 **L5**. In October there were seven of these; this is the only one left (October C03) | `that a student from our school won a place in the top three` |
| B3M1F-G05 | p15 Part 8 | `asked them to be part of the video`: reported requests are the heading of SB3 L6. It is borderline, because *ask someone to* is also an ordinary verb pattern (October C04) | Keep, or `invited them to be in the video` |
| B3M1F-G06 | pp9–10 Part 6; p14 Part 8 | Reading level: `invoice`, `tenant`, `insurance`, `utilities`, `rent period`, `news anchor`, `broadcasting company`, `journalism`, `scripts` are in no G-Star list up to SB3, and none is glossed (October C05–C06). `worthwhile` is gone | Gloss `invoice` and `news anchor` in the series' Note-box style |

## Words

**39 of the 40 SB3 L1–4 words appear.** The missing one is **`fill out`** (L1). In October it was
in Part 8 (`asked me to fill out a form`), and that passage was replaced.

- *pay the bill* appears only as `pay the rent and utilities bill` (Q31 B, itself a fault) and
  `pay … the utility bills` (Q35).
- *check out* appears only as option A `checking out of a hotel` (Q1).

| Lesson | Words |
| --- | --- |
| L1 | check in, check out, tour guide, excellent, pay the bill, ~~fill out~~, reserve a table, modern, resort, book a room |
| L2 | confident, presentation, creative, stand out, inspire, brave, motivation, designer, achievement, speech |
| L3 | textbook, useful, professional, beginner, proud of, certificate, language, earn, self-taught, internet |
| L4 | food stand, festival, explore, facility, lively, popular, parade, go sightseeing, memorable, street market |

Suggested: put `fill out` back, e.g. Part 10 `she happily handed me the sign-up form to fill out`.
