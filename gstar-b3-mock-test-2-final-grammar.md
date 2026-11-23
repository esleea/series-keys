# Control: G-Star Book 3, Mock Test 2, final — grammar and words

Hand proofread on 23 November 2026. This report checks the test against **SB3 Lessons 5–8**, the
second half of the book. It checks three things:
- that the test uses the lessons' grammar correctly;
- that it tests that grammar;
- that nothing from a later lesson or book has to be produced.

Keys and sentences are in `gstar-b3-mock-test-2-final.md`; texts in
`gstar-b3-mock-test-2-final-texts.md`. The files are the same as there.

**How it was checked.**
- **Grammar:** by hand, against the SB3 L5–8 grammar points. These are taken from the 5 October
  report, which read them from `data/series/pages/g-star-sb-3-sections.json`. I did not re-read
  that file this round.
- **Words:** a `grep` over the book's text layer and the audioscript for each of the 40 L5–8
  words, allowing inflections. The hits were checked by hand.
- **Forward reference:** judged by hand against the later lesson headings in the October report,
  with a `grep` for modal passives, the present perfect continuous and *wish* / *should have* /
  *would have*.
- Nothing paid ran.

★ marks a misuse of the lesson's own target grammar.

## The lessons' grammar

| SB3 lesson | Grammar | Used correctly? | Tested? |
| --- | --- | --- | --- |
| L5 I Had Shown Up Early | past perfect | `the train had already left`, `we realized that the bell had already rung`, `I had told him to be careful` ✓ | Yes: Q16 (`had already ___`), Q43 (`realized` against `had realized`) |
| L6 The Doctor Told Me to Rest | reported commands and requests (*tell / ask / order* + object + *to*) | `Mom told us to apologize`, `ordered Darren to go`, Part 11 `You were asked to put up a picture frame` ✓ | Yes: Q42 `told … to` |
| L7 She Said That Everyone Had Gathered | reported speech with backshift to the past perfect | `He told me that he had dropped it`, `I told her that my brother had damaged my toy` ✓. ★ `she has caught a cold` (diary). ★ `I asked … when the next train will be coming` (audio) | Yes: Q44 `had damaged` |
| L8 I Had My Car Repaired | causative *have / get* + object + past participle | `I had my hair cut`, `My parents also had some new lights installed`, Q35 C `had her symptoms seen by a doctor` ✓ | Yes: Q4 (listening) |

The test makes students produce or choose the grammar of all four lessons. That is still the
main difference from Mock Test 1.

## Must fix

| Id | Where | Finding | Suggested change |
| --- | --- | --- | --- |
| B3M2F-G01 | p16 Part 9 diary ★ | `Mr. Robert said that Ms. Jane couldn't come in because she has caught a cold.` This is the L7 point the test itself scores in Q44 (B3M2F-05) | `because she had caught a cold` |
| B3M2F-G02 | Audio Part 4 ★ | `I asked an officer when the next train will be coming` has no backshift in a reported question (B3M2F-A02) | `when the next train would come` |

## Should fix (forward reference; all read or heard only)

| Id | Where | Finding | Suggested change |
| --- | --- | --- | --- |
| B3M2F-G03 | p10 Q35, Dad's message | `The weather has been changing a lot`: the present perfect continuous is SB4 L8 | `The weather is changing a lot these days` |
| B3M2F-G04 | Audio Part 3 Q13; p15 diary | `Any drink without coffee can be made, sir.`; `Seeds can be spread by animals or nature.` The modal passive is SB5 L2 | `We can make any drink without coffee.`; `Animals and the wind can spread seeds.` |
| B3M2F-G05 | p11 Part 7 | Reading level: `pregnant women`, `overweight`, `balanced diet`, `minerals`, `calf`, `thigh` are in no list up to SB3 and are not glossed (October C06, still open) | Gloss `calf` and `thigh` with a small picture, or cut the list of who gets cramps |
| B3M2F-G06 | p17 Q47 D | `to gather other flowers`. *Gather* (L7) is used in a sense the lesson does not teach (flowers do not gather things), and it is the only place the word appears | `gather` in a text: `Everyone gathered around the screen to watch the video.` |

## Words

**39 of the 40 SB3 L5–8 words appear.** The missing one is **`polite`** (L7). *Gather* appears
only in the Q47 distractor (G06).

| Lesson | Words |
| --- | --- |
| L5 | attract, performance, worthwhile, damage, run out of, face-to-face, fulfill one's promise, accommodation, realize, show up |
| L6 | cramp, catch a cold, see a doctor, fever, symptom, flu shot, weak, examine, sneeze, prescribe |
| L7 | entertainment, ~~polite~~, have a barbecue, prank, gather (distractor only), hang out, amusement park, behave, keen on, selfish |
| L8 | order, mow the lawn, attentive, take time off, maintain, install, repair, routine, satisfied, haircut |

Suggested: put `polite` back. For example, in Part 5 write `Jessie was fun, bubbly and very
polite`, or in Part 8 write `My mom told him to be polite and ask first.`

## No longer an issue (fixed since October)

October listed five forward references. All of them have been removed:
- C01: the third conditional in Q1;
- C02: *should have seen*;
- C03: *wish I had*;
- C04: *is being repaired*;
- C05: *may be caused*, *can be found*.
