# G-Star Writer 3 — Answer Key Proofreading Report

**Date:** 29 October 2026  
**File:** `GSTAR-WB3 ANS KEY.pdf`  
**SHA-256:** `ad4799b6b2144c3c9fccfd64af62d45d6328a16cc38e64bad8b1dbc26286325a`  
**Coverage:** 21 physical PDF pages, 34 numbered textbook pages, 8 lessons.

## Method and scope

The review covered:

- **Correctness Q/A:** Independently solved the Practice exercises and compared Analyze organizers with their source passages.
- **Spelling and grammar:** Checked red keys, blue sample answers, instructions, examples, headings, and surrounding prose.
- **Natural English:** Checked collocations, idiomatic expression, coherence, and appropriateness for learners.
- **Core conformance:** Compared against the G-Star level structure and existing Writer 3 curriculum decisions. Writer lesson *k* is evaluated against previously taught material and Student Book 3 through lesson *k*.
- **Internal consistency:** Compared Brainstorm organizers with Write examples, model texts with Analyze answers, and writing samples with Check rubrics.

The repository references used were the [G-Star core snapshot](https://github.com/esleea/rdbeast/blob/main/data/series/pages/g-star-level-3.json), [grammar mapping](https://github.com/esleea/rdbeast/blob/main/data/series/authored/g-star-level-3.json), [lexical resolution](https://github.com/esleea/rdbeast/blob/main/data/series/g-star-lexical-resolution.json), and [Writer 3 mock-up 2 review](https://github.com/esleea/rdbeast/blob/main/docs/qc-control/results/control-2026-10-14/gstar-b3-writer-mock-2.md).

**Limitation:** These are repository-backed references; I did not independently open the live `/rd/series/g-star?tab=core` interface. The review is therefore strongest for page-level correctness and previously documented curriculum decisions. Open-ended writing is treated as illustrative, not as having one required answer.

## Summary

| Category | Findings |
|---|---:|
| Wrong Practice answer keys | 3 |
| Answer-key transcription, wording, and source-fidelity defects | 7 |
| Exercise/sample/rubric contradictions | 3 |
| Other language, copyright, or confirmed curriculum defects | 4 |
| **Confirmed defects to fix** | **17** |
| Additional editorial recommendations | 9 |

The 3 wrong Practice answers are concentrated in one exercise. Other Practice answers appear correct, although one question stem contradicts the book's own example.

## 1. Confirmed defects — must fix

### 1.1 Incorrect Practice answer keys

| ID | Printed page / item | Current answer | Correct answer | Explanation |
|---|---|---|---|---|
| W3AK-01 | p27, L7 E-A1 | `scenic` | **measurement** | The definition is “length, height, width, amount, etc. of something.” *Scenic* is unrelated. |
| W3AK-02 | p27, L7 E-A2 | `precious` | **airtight** | The definition is “completely closed, no air can get in or out.” |
| W3AK-03 | p27, L7 E-A3 | `culture.` | **store** | The definition is “to keep things for future use.” |

**Important:** All three current answers are absent from the exercise's word bank, which contains `store`, `airtight`, `measurement`, and `overmix`. The current answers are also all G-Star Student Book 2 Lesson 7 vocabulary, suggesting answer-copy contamination from another exercise.

### 1.2 Incorrect, misleading, or malformed Analyze answers

| ID | Printed page / item | As printed | Problem | Correction |
|---|---|---|---|---|
| W3AK-04 | p26, L7 C, cake ingredients | `100 grams sugar` | The Observe recipe distinguishes **200 grams white sugar** from **100 grams brown sugar**. Omitting *brown* loses an important distinction. | `100 grams brown sugar` |
| W3AK-05 | p26, L7 C, step 6 | `remove them from the pan` | The recipe uses two baking pans and two cakes. The source says *pans*. | `remove them from the pans` |
| W3AK-06 | p26, L7 C, step 8 | `Cut the tops of the cake flat` | Two cakes are being prepared, as specified in the source. | `Cut the tops of the cakes flat` |
| W3AK-07 | p14, L4 C, Places to Visit | `Grebridge Museum` | The Observe text calls it **Greybridge Museum**. | `Greybridge Museum` |
| W3AK-08 | p30, L8 C, Orientation | `Mrs. Jenkin’s yard` | The character's surname in Observe is **Jenkins**. | `Mrs. Jenkins’ yard` |
| W3AK-09 | p10, L3 C, tip 3 | `You also need to make clear instructions on how to reach the goal.` | The Observe passage says goals should be clear and achievable. It does not say learners must make instructions, and *make clear instructions* is unnatural. | `Set clear, achievable goals. For example, try learning ten new words this week.` |
| W3AK-10 | p18, L5 C, Important Details | `Authorities have released more than ten announcements and posters...` | The source specifically counts **more than ten announcements**, then separately mentions posters. The key blurs that distinction and changes the past-time account to present perfect. | `Before the ban, authorities had released more than ten announcements. They also put up posters warning visitors about harmful behavior.` |

### 1.3 Contradictions and failures of the writing contract

| ID | Printed page / item | Problem | Correction |
|---|---|---|---|
| W3AK-11 | p23, L6 E-A1 | `Lena will take over my work during my ____.` The answer `absence` is grammatically correct, but in Lesson 6's model, **Lena is the person taking leave**. Alex and Jane take over her work. | `Alex will take over my work during my ____.` |
| W3AK-12 | p4, L1 G, sample email | The book explicitly teaches that formal emails should not contain contractions. The blue model answer nevertheless uses `I’m` and `it’s` several times. | Replace contractions with `I am`, `it is`, etc. throughout the sample. |
| W3AK-13 | p24, L6 G, sample letter | The organizer specifies `alexchen@greenfield.edu.com`, and H checks for contact information. The sample letter merely says readers can contact Alex through his school email, without giving the actual address. | Include `You can contact me at alexchen@greenfield.edu.com.` |

### 1.4 Language and curriculum

| ID | Printed page / item | As printed | Problem | Correction |
|---|---|---|---|---|
| W3AK-14 | p7, L2 F, Closing | `releasing a new song album` | Unnatural collocation; the corresponding G sample correctly says *a new album*. | `releasing a new album` |
| W3AK-15 | p7, L2 F, Event 1 | `awarded as the most talented newcomer` | Unidiomatic award construction. | `received the Most Talented Newcomer award` |
| W3AK-16 | p13, L4 B and callout; p33 Overview | Causal `given`, including `Given the large number of guests...` | The 30 September owner decision, carried into the previous QC report, explicitly excluded this construction at this level. It remains in this version. This is a **policy-based core violation**, not a claim that *given* is ungrammatical English. | Use `Because of the large number of guests...` and remove `given` from the teaching list and Overview. |
| W3AK-17 | Physical PDF p21, copyright notice | `in any form or by means electronic, mechanical...` | Missing *any* and a connector before the list of means. | `in any form or by any means, including electronic, mechanical, or photocopying methods...` |

## 2. Key verification

Every Practice A and B item was checked against its options, word bank, or sentence.

| Lesson | Practice A | Practice B | Result |
|---|---|---|---|
| L1 | b, a, c | matter; deposit; confirm | Correct |
| L2 | contest; skillful; improve | c, a, b | Correct |
| L3 | a, c, c | beginner's luck; tutor; course | Correct |
| L4 | diverse; unwind; budget-friendly | inn; budget-friendly; circus show | Correct |
| L5 | patrolled; crime; fines | crime; banned; authorities | Correct |
| L6 | b, c, d | sprain; absence; back on one's feet | Keys correct; A1's scenario is inconsistent |
| L7 | **Wrong, wrong, wrong** | measurements; batter; overmixed | Three wrong A keys |
| L8 | b, c, a | adopt; stray; mindful | Correct |

**Result:** 45 of 48 Practice answer entries are correct as keyed. All three incorrect entries are L7 E-A1–3. The L6 E-A1 stem requires repair independently of its answer.

## 3. Editorial candidates — should fix

These are recommendations rather than additional confirmed wrong keys.

| ID | Page | As printed / concern | Suggested improvement |
|---|---|---|---|
| W3AK-E01 | p10 L3 C, tip 2 | `Start slow with the purchase.` The wording is unnatural, and the source instead explains that Jessica buys a new textbook only after finishing the ones she is using. | `Start with a few books and buy more only when you need them.` |
| W3AK-E02 | p10 L3 C, tip 4 | The key advises readers to “improve and train your practical skills” but omits the specific techniques in Observe: recording yourself, keeping a diary, finding pen pals, and joining language exchange groups. | Summarize at least one or two concrete techniques from Observe. |
| W3AK-E03 | p14 L4 C, Tips/Why | `there are chances of occasional rain` | `Occasional rain is possible.` |
| W3AK-E04 | p4 L1 G | `Will there be a lot of price changes from the date I asked about earlier?` The writer has not previously asked a question about price. The sentence also sounds unnatural. | `Could you tell me whether the ticket price is likely to change before I book?` |
| W3AK-E05 | p16 L4 G | `there are many fruits to collect` | `there is plenty of fruit to pick` |
| W3AK-E06 | p28 L7 G | The chocolate lava cake recipe says to heat the chocolate and butter carefully until melted, but does not explain how. It also uses butter to grease the cups without specifying extra butter. | Specify a microwave or double-boiler method, and list a little extra butter for greasing. |
| W3AK-E07 | p29 L8 B | The photograph shows a large, healthy-looking dog, while the text describes Marty as a “small, thin dog.” | Use a visual closer to the story's description, or change the text. |
| W3AK-E08 | p21 L6 B and p34 Overview | The callout lists `even if` and `only if`, but the model letter does not demonstrate either. The list may encourage students to use forms they have not seen modeled. | Restrict the callout to constructions demonstrated in the lesson, or supply suitable examples. |
| W3AK-E09 | Physical PDF p2, Contents footer | `periods . , commas , , and / or question marks ?` is visually cluttered and awkward. | `Remember to put periods, commas, and question marks in the right places.` |

## 4. Core conformance and earlier-report regression check

The existing Writer 3 mock-up report establishes the intended progression: earlier Student Books, Writer books, and Power Books may be used, plus Student Book 3 through the matching lesson.

The current key shows several corrections from that report:

| Previously flagged issue | Current status |
|---|---|
| L5 `neither ... nor` and premature `both ... and` | Fixed in the current Observe passage |
| L2 above-level use of `performance` | Replaced by *show* |
| L6 above-level `extend my leave` | Replaced by *be away until* |
| L8 use of `throughout` in the time-marker callout | Removed |
| L7 Practice B3 using overmixing to explain lumpy frosting | Reworked to a cake/batter sentence; now sound |
| L8 wrong definition of `mindful` | Revised to `to be careful and aware` |
| L4 causal `given` | **Still open** |
| L6 misleading `Lena will take over my work` | **Still open** |

The lexical-resolution data also places `aroma`, a distractor in L3 E-A1, in Student Book 2. It should **not** be flagged as an untaught word merely because it is not a Writer 3 target.

A separate, lower-confidence lexical review is warranted for words appearing without explicit teaching support, including `refund`, `stationery`, `stunning`, and `responding`. Absence from a headword list alone does not prove a curriculum violation, so these are **not counted as confirmed defects** here.

The current Word Corner choices also differ from replacements documented as accepted or proposed on 30 September. Whether those changes are still binding should be established before treating the entire vocabulary selection as a new failure.

## 5. Negative controls — correct as printed

| Location | Item | Why it is acceptable |
|---|---|---|
| p3 L1 E-A2 | `deposit` for the lost hotel key card | The hotel can retain the deposit when the key card is lost. |
| p7 L2 E-B2 | `They will award her a prize...` | Correct use of *award someone something*. |
| p11 L3 E-A2 | `courses` | `a few art courses` is grammatical and matches the reference to performing arts. |
| p15 L4 E-B1 | `inn` | Fits the overnight accommodation context. |
| p19 L5 E-A3 | `fines` | `People who break the rules have to pay fines` is a valid completion; *crime* is not. |
| p27 L7 E-B3 | `overmixed` | Overmixing cake batter can lead to a tougher cake, and the sentence fits the vocabulary example. |
| p31 L8 E-A3 | `mindful` | `mindful of how much water and electricity I use` is the correct construction. |
| p31 L8 E-B2 | `stray` | Fits an animal that is lost and without a home. |

Other checks passed: the contents' lesson ranges match the printed pagination, the Ellie timeline is internally consistent (2000, 2010, 2018, 2020), the Lesson 6 leave dates match the letter, and all eight H rubrics add up to 10 points.

## 6. Priority and recommendations

**First priority:** Correct the three wrong answers on printed page 27. These would directly cause students or teachers to mark correct answers as wrong.

**Second priority:** Repair the source-fidelity defects in the Analyze keys, particularly Lesson 7's brown sugar, the misspelled names, and the misleading Lesson 5 summary.

**Third priority:** Repair the Lesson 6 contradictory question, ensure the Lesson 1 formal email models its stated rule, and complete the Lesson 6 sample's contact details.

**Fourth priority:** Reconcile the remaining curriculum-policy violation involving `given` and apply the language corrections and editorial suggestions.

### Overall assessment

This is not an answer key with widespread incorrect Practice answers. The large majority of the keyed vocabulary exercise answers are correct. However, the three consecutive wrong answers in Lesson 7 are a serious production defect.

The wider proofreading also reveals a different class of problem: some answer-key organizer entries do not faithfully reflect the passage they are meant to analyze, and some writing samples fail rules or rubrics printed on the same lesson pages.

**Publishing recommendation:** Correct the confirmed issues before release, then run a targeted verification pass on every red and blue answer, with special attention to copy/paste contamination, source-to-organizer accuracy, and the agreement between G writing samples and H rubrics.
