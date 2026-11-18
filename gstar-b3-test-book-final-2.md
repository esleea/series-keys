# Control: G-Star Test Book 3, final print file with answer key — second check

Hand proofread on 18 November 2026 of the revised G-Star Test Book 3, its answer key and its
audioscript, read cover to cover. Ids continue from the 9 November reports
(`control-2026-11-09/gstar-b3-test-book-final{,-texts,-grammar}.md`, TB3F-…). A first version of
this report, published earlier the same day, re-read only what had changed since 9 November. This
version replaces it.

**Verdict: nearly ready; two must-fixes remain.** The answer key is still right for every item. 28 of
the 9 November findings are fixed, including every 9 November must-fix but one: there are still no
scoring criteria for L3's listen-and-repeat speaking (TB3F-06). Reading cover to cover found one
item I missed on 9 November: L6 Listening Q6 has two defensible pictures (TB3F-35). Thirteen smaller
9 November items are still open, and this round adds twelve new small ones.

| File | Bytes | Pages | sha256 |
| --- | --- | --- | --- |
| `3 G-Star Test Book 3 (2).pdf` (Canva, 18 Nov 2026) | 29,417,101 | 88 | `e53f7bfaa6b270d000175a0c86042a7f3516d7018c131b1ce78531ae74054271` |
| `G-Star Test Book 3 ANSKEY (1).pdf` (Canva, 18 Nov 2026) | 7,981,610 | 22 | `4b4fa3a472e2811fc8f1da32bb39a0770200239abbefc0573781e394b7d2924b` |
| `3 G-Star Test Book 3 - Audioscript (2).docx` (`Last Updated 10 Nov 2026`) | 22,314 | — | `cac13d09ec70d4bec2ecf9235bf8167dfd70871692088e0bf190c7abead33194` |

The 9 November files are still in the same WeChat folder, and their sha256 match that report.

**How it was checked.**
- **Read cover to cover.** I read the whole book, key and audioscript myself: every lesson page
  from the text layer, and every page image wherever an item depends on a picture or a layout.
  Zooms where pictures are small: L3 Q6, L5 Q6, L6 Q5.
- **Solved every item.** All 168 scored items were solved again and compared with the key.
- **Key.** Every key page was read as an image. The multiple-choice bubbles were also read by
  script; they agree with the page images and with my 9 November key.
- **Regression.** For the 9 November table, I also diffed the text against the 9 November files
  and compared every page render pixel by pixel. That is how pictures that changed with no text
  change were caught: p34 L4 Q7 and p60 L6 Speaking.
- **Not done.** Nothing paid ran, and **I did not hear the recording**.

Page numbers are printed pages (physical = printed + 3).

## Must fix

| Id | Page | Item | Status | Correction | Fix in |
| --- | --- | --- | --- | --- | --- |
| TB3F-35 | 54 | L6 Listening Part 2 Q6 (key A, the leg cramp) | **New, missed on 9 November.** Picture C (the boy resting on the bench with a drink) also happened: `I sat on the bench for the rest of practice.` The question (`What happened to the boy at soccer practice?`) is heard only, so nothing on the page points to the cramp rather than the rest | Redraw C as a scene the audio rules out (the boy scoring a goal), or ask `What happened to the boy's leg?` | book (or script + recording) |
| TB3F-06 | 83–84 | Scoring criteria | **Still open.** L3 Speaking (p30) is listen-and-repeat. Neither set fits it (`Speaks independently`, `Completes the task within the time limit`), yet the L3 score box has five criteria | Add `Speaking – Repeating Sentences` criteria, or say which set L3 uses | book + key |

## Still open from 9 November (should fix)

| Id | Page | Item | As printed now | Correction | Fix in |
| --- | --- | --- | --- | --- | --- |
| TB3F-08 | 53–54 | L6 Listening Part 2 Q4–6 | Picture sets with no printed question; only the audio has `N: Question:` lines | Print the three stems | book |
| TB3F-09 | 43 | L5 Listening Part 2 Q6 (key T) | The case still holds pastries, cookies and cupcakes under `Sold Out`; the audio is about chicken sandwiches | Put sandwiches in the case | book |
| TB3F-11 | 49 | L5 Reading Part 3 Q10 | `She realized that she ___ her phone at home by the time she arrived at the airport.` (Q11 is fixed) | `When she arrived at the airport, she realized that she ___ her phone at home.` | book + key |
| TB3F-15 | 24 | L3 Listening Part 3 Q7 B | `The boy who wears red shoes is sitting in front of the teacher.` also picks out a boy (Q9 B is fixed) | `The boy who wears red shoes is my best friend.` | book |
| TB3F-22 | key 61 | L6 Listening Part 1 Q2 | `cold.` | `cold` | key |
| TB3F-23 | 23 | L3 Listening Part 1 card | `Have at least 1–2 years of teaching experience` | `at least one year` | book |
| TB3F-24 | 83 | Writing criterion 6 | `in logical chronological order` | `in a logical order` | book + key |
| TB3F-25 | answer sheets | Instruction boxes | Still the generic list on most sheets; L5 Reading now says `Write a one-word answer` for a part that only takes letters | Print only the lines each lesson needs | book |
| TB3F-26 | certificate | Copyright | `in any form or by any means electronic, mechanical` | `by any means, electronic,` | book + key |
| TB3F-27 | script | L1 Part 1 Q1, Q3; L8 Part 1 | Several turns on one line | One turn per line | script |
| TB3F-28 | script | L8 Part 3 (Robert) | `Neither he nor I like being separate from each other, so this is a win for the both of us!` | `… like being apart, so it's a win for both of us!` | script + recording |
| TB3F-T02 | script | L2 Listening Part 3 (Wendy) | `Feeling that bravery will be my greatest achievement.` | `Feeling brave on stage will be my greatest achievement.` | script + recording |
| TB3F-G09 | 58 | L6 Reading Part 3 Q11 | `"Don't eat any cake if your stomach still hurts," Paul's mom said to him.` needs a negative reported imperative, which SB3 L6 does not show | `"Drink some warm water," Paul's mom said to him.` | book + key |

## New this round (should fix)

| Id | Page | Item | As printed | Note | Correction | Fix in |
| --- | --- | --- | --- | --- | --- | --- |
| TB3F-30 | 59–60 | L6 Speaking (reworded instead of redrawn, TB3F-18) | `Here are some pictures that show different situations about health.` | The new framing works with the flu-shot and check-up pictures; the phrase is awkward | `different health situations` | book |
| TB3F-31 | script | L6 Listening Part 3 (Joy, rewritten) | `promised to give it to her when she goes back to school` | Tense inside a past report; L6 is reported speech | `when she went back to school` | script + recording |
| TB3F-32 | 8 | L1 Writing prompt | `You are on a vacation with your family.` | The key model was fixed to `on vacation`; the prompt was not | `You are on vacation with your family.` | book |
| TB3F-33 ★ | script | L4 Listening Part 3 Q9 (Ashley) | `She said that she wants to visit the market again.` | L4 teaches the backshift after a past reporting verb; Lena's and Evan's turns use it | `She said that she wanted to visit the market again.` | script + recording |
| TB3F-34 | 38, 58 | L4 and L6 Writing | `Write the story shown in the pictures.` with no grammar requirement | Reported speech is the target in both lessons; L2, L3, L5, L7 and L8 name their grammar | Add `Use at least two sentences with reported speech.` (owner's call) | book |
| TB3F-36 | script | L8 Listening Part 3 (Sadie) | `I was worried that I couldn't go to work that day` | | `I was worried that I wouldn't be able to go to work that day` | script + recording |
| TB3F-37 | 80 | L8 Speaking passage | `I kept the same hairstyle as part of my daily routine.` | A hairstyle is not a routine; the easy-to-maintain point is | `It was easy to style, so it became part of my daily routine.` | book |
| TB3F-38 | 20 | L2 Speaking passage | `But, she still finished her story` | No comma after a sentence-opening *But* | `But she still finished her story` | book |
| TB3F-39 | 75 | L8 Reading Part 1 (Flora's email) | `the kitchen faucet  started leaking again last night` … `so he ordered a new one … The new faucet has already arrived` | Double space. The faucet is ordered after last night's leak and has already arrived | Single space; `The new faucet will arrive on Thursday.` | book |
| TB3F-40 | 36 | L4 Reading Part 2 | `3,000 visitors participated in the survey that our reporter did.` | A sentence should not open with a numeral | `A total of 3,000 visitors took part in our reporter's survey.` | book |
| TB3F-41 | 57 | L6 Reading Part 2 | `But in cases of emergency such as an accident, you should see a doctor right away.` | | `But in an emergency, such as an accident, you should see a doctor right away.` | book |
| TB3F-42 | contents | Footer | `Remember to put periods . , commas , , and / or question marks ?` | Cluttered (as in Test Book 4) | `Remember to put periods, commas, and question marks in the right places.` | book |

## Fixed since 9 November

| Group | Fixed |
| --- | --- |
| Must fix (TB3F-01 to -05, G01) | 01 L4 Q7 picture (the girl now watches the parade); 02 `If you are feeling anxious`; 03 L6 model (`was back on her feet`, `had a bad cold`); 04 `use at least one sentence`; 05 `Is an amusement park fun?`; G01 `perform together: she would play` |
| Should fix | 07 gap spacing; 10 Q5 stem; 12 `Because of this, the show ended late`; 13 `a poor way to learn`; 14 the cousin is now named Daisy, so `She said` has a referent; 16 `He ate all of his vegetables`; 17 `Have you ever lost touch with a friend?`; 18 by rewording (see 30); 19 `eat out`; 20 `on vacation in Greece`; 21 `bad for my brother`, `Part 1`; 29 `festivalgoers` |
| Texts | T01 `Making the bag was a big ___`; T03 Luke inside the haunted house, `screamed loudly. Other people …`; T04 `said he could install it` |
| Grammar | G02 `things that were old and broken`; G03 `Inspired by my mother, I …`; G04 key now `he and Jim`; G05 Q9 C replaced; G06 `the most creative project at the fair`; G07 `next time he would ask for help earlier`; G08 `Did anything happen to her?` |

## Answer key

All 168 scored items were solved again. The key gives the right answer for every one; TB3F-35 is a second defensible answer, not a wrong key. Lesson by lesson, the key equals
the table in the 9 November report, with one change: L4 Reading Part 3 Q12 now reads `Tom said
that he and Jim …` (G04).

## Open questions for the owner

1. Which speaking criteria should L3's listen-and-repeat use (TB3F-06)?
2. Redraw L6 Q6 picture C, or change the question (TB3F-35)?
3. Has the audio been recorded from the 10 November script? If so, TB3F-28, T02, 31, 33 and 36 need
   re-recording, and the G01 and G02 fixes need checking in the recording.
