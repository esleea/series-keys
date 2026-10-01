# Control: G-Star Power Book 5, final print files (`A-GS-PB-B5-*.pdf`)

Hand proofread on 1 October 2026 of the eight print files, the last check before they go to the
printer. The model step was done by hand. I read every page myself. Four independent reviewers
also read two files each, and I checked every finding below against the page image or the text
layer before listing it. Nothing paid ran.

The listening pages were checked against the audioscript `pb-5-audioscript.docx` (31,085 B,
"Last updated Sep 30, 2026", sha256
`1283bdb61a0b7c03ff11466a5e6316d77bbfe06cfa13ece32b6989c185fc6df1`), which arrived the same day.
Every printed listening item has been solved from it (see "Listening").

| File | Bytes | Pages | sha256 |
| --- | --- | --- | --- |
| `A-GS-PB-B5-L1.pdf` | 108,484,495 | 7 (single pages) | `956d6ed5ee759aad62bf5c57b7c514ab9bc2bde5c46e652fe1858a9b55a6291b` |
| `A-GS-PB-B5-L2.pdf` | 40,479,724 | 5 spreads | `d5151872f037043d4835fce5e1dc7fa99dfdc7d1efb4234d8c0373a475851799` |
| `A-GS-PB-B5-L3.pdf` | 39,253,897 | 5 spreads | `2ce08c8ea2ab2568ca78ffe4c6bc713051ec75d60148dea2d3161b389acfb927` |
| `A-GS-PB-B5-L4+R1.pdf` | 83,305,802 | 7 spreads | `79a851e4800de378770b5d43e87250569088d1e88fe1e310fcce5608c760769e` |
| `A-GS-PB-B5-L5.pdf` | 32,181,447 | 5 spreads | `a23894193f4243b2299d2fbb6733125e58ce923ddf7f04a9cb57a92067128993` |
| `A-GS-PB-B5-L6.pdf` | 51,590,257 | 5 spreads | `8bc118381db13d5ec06f8d744d45d271f70c65fd63d7b587fe96f54c5185d5d3` |
| `A-GS-PB-B5-L7.pdf` | 54,652,672 | 5 spreads | `eeeca6142d9a74a3fdee0192cb53c0645c3b494108af07c1226db2e6fbe9e470` |
| `A-GS-PB-B5-L8+R2.pdf` | 37,453,029 | 8 (7 spreads + certificate) | `2d8796f7300b66fdfa26d3aa2cec866c0e2ec4613668c49bda7c1dc15fe46bcc` |

InDesign 21.1 exports dated 30 Sep 2026. Every file has a text layer. Each is under the 192 MiB
quality-check limit, so a web run can take them as they are.

## Page map

| File | Physical → printed | Content |
| --- | --- | --- |
| L1 | 1 cover · 2 contents · 3–7 → pp 1–10 (one printed page per side, two per PDF page from 3) | Lesson 1 |
| L2 | 1–5 → pp 11–20 | Lesson 2 |
| L3 | 1–5 → pp 21–30 | Lesson 3 |
| L4+R1 | 1–5 → pp 31–40; 6–7 → pp 41–44 | Lesson 4, Review 1 |
| L5 | 1–5 → pp 45–54 | Lesson 5 |
| L6 | 1–5 → pp 55–64 | Lesson 6 |
| L7 | 1–5 → pp 65–74 | Lesson 7 |
| L8+R2 | 1–5 → pp 75–84; 6–7 → pp 85–88; 8 certificate | Lesson 8, Review 2 |

In spread files, physical page N holds printed pages `first + 2(N−1)` and `first + 2(N−1) + 1`.
The book is unkeyed, so Q/A here means soundness: whether a student can reach exactly one
defensible answer.

## Must fix before print

### Language and layout errors

| Id | File / printed | Item | As printed | Correction |
| --- | --- | --- | --- | --- |
| PB5F-01 | L1 / 3 | Grammar Ex2 blank 6 | `6 ___ Leo carefully checks the bus and Mia sometimes forgets important details.` The intended answer is `While`, which leaves the sentence with no main clause (the `and` has to go), and `the bus` needs a noun | `While Leo carefully checks the bus schedule, Mia sometimes forgets important details.` |
| PB5F-02 | L1 / 5 | Reading Ex1, Tamara Brown | `Now, is clearer.` (no subject) | `Now, the schedule is clearer.` |
| PB5F-03 | L1 / 5 | Reading Ex1, "Whereas many…" | `…inaccessibility issue in the city's outer neighborhoods, where.` (the sentence stops at `where`) | e.g. `…outer neighborhoods, where there are very few bus routes.` |
| PB5F-04 | L1 / 9 | Listening Ex1 item 5 | `Mia was often late because she was stuck in ___` (no full stop; items 1–4 and 6 have one) | add `.` |
| PB5F-05 | L3 / 24 | Reading Ex1, after blank 3 | `”Maybe he only said it to seem generous,”` (opens with a closing quote, U+201D). **Unfixed since the mock (GB5-09)** | `“Maybe` |
| PB5F-06 | L3 / 26 | Reading Ex2 para 3 | `Finally, on the final day of the program each, student will receive…` | `On the final day of the program, each student will receive…` |
| PB5F-07 | L4 / 31 | Vocabulary blank 7 | `Noah made 7 ___ He learned to move…` (no full stop). **Unfixed since the mock (GB5-11)** | `…made ___. He learned…` |
| PB5F-08 | L4 / 39 | Listening Ex2 item 3 | `Sally thinks that the course is a ___` (no full stop, unlike 1, 2 and 5) | add `.` |
| PB5F-09 | L5 / 46 | Grammar Ex1 items 4 and 6 | `…summer vacation ___ (begin)` and `…charity event ___ (arrive)` (no full stop; the other six items have one) | add `.` after each cue |
| PB5F-10 | L5 / 51 | Reading Ex2 (Teen Power) | `By the time the day wrapped up, they raised over $2,000` (this lesson teaches perfect tenses) | `they had raised` |
| PB5F-11 | L5 / 54 | Listening Ex2 note 5 | `The cafe will be used as the 5 ___` (no full stop; the other two notes have one) | add `.` |
| PB5F-12 | L6 / 56 | Grammar Ex2 item 4 | `But for ___the injured man ___ help in time.` (no comma after the `But for` phrase; items 1 and 5 print one) | `But for ___, the injured man ___ help in time.` |
| PB5F-13 | L6 / 61 | Reading Ex2 | `fossil fuels are cheaper, and people in the past did not fully understand the damage it caused` | `the damage they caused` |
| PB5F-14 | L7 / 68 | Reading Ex1, March 17th | `small glowing organisms1 on their scales` (the footnote marker is set full size; `fatal¹`, `vibrations¹` and `aftershocks¹` are superscript) | `organisms¹` |
| PB5F-15 | L7 / 71 | Reading Ex2 | `couldn't get tired, distracted2, or angry` (same fault) | `distracted²` |
| PB5F-16 | L8 / 75 | Vocabulary email, blank 2 | `The mayor has declared it an 2 ___ She is also leading…` (no full stop) | `…an ___. She is also…` |
| PB5F-17 | L8 / 83 | Listening Ex1 Q1 a | `meet and talk to the filmmakers.` (the only option with a full stop) | drop the `.` |
| PB5F-18 | R2 / 86 | Grammar Ex1 item 5 | The part letter `D` above `after the race.` sits higher than A–C on the same line | align `D` with the other letters |
| PB5F-19 | R2 / 88 | Listening Ex2, last bullet | `The system is tested so that it doesn't make 7 ___` (no full stop) | add `.` |
| PB5F-20 | L8+R2 / certificate | Copyright notice | `in any form or by means electronic, mechanical, photocopying, or otherwise` | `in any form or by any means, electronic, mechanical, photocopying, or otherwise` |
| PB5F-21 | all files | Typography | **28 straight apostrophes and 2 straight double quotes** in a book that otherwise sets curly ones. Counted from the text layer and seen in the page images: L2 pp14–16 `Let's`, `Alvarez's` ×2 · L4+R1 pp34, 36, 43 `didn't`, `don't` ×3, `I've`, `it's`, `Woodcutter's`, `you're` · L5 p50 `"Many of the chairs … lifeless,"` · L6 pp59–61 `isn't`, `She's`, `doesn't`, `world's` · L7 pp65, 68–69 `Jane's`, `it's`, `won't` · L8 pp78–82 `earthquake's` ×3, `Earth's`, `isn't`, `I've` ×2, `it's`, `don't`, `can't` | Find and replace `'` → `’` and `"` → `“ ”` in those stories |

### Questions a student cannot answer cleanly

| Id | File / printed | Item | Problem | Correction |
| --- | --- | --- | --- | --- |
| PB5F-Q01 | L2 / 18 | Reading Ex2, Officer Ruiz | `the higher number of reported crimes might be because more residents felt comfortable coming forward`, but p17 says `reported crimes have only dropped slightly`, and the chart shows them falling | e.g. `…that reported crimes may have dropped only slightly because more residents felt comfortable coming forward…` |
| PB5F-Q02 | L2 / 16 | Reading Ex1 Q3 | Intended b `They locked him in Mr. Alvarez's storage shack until police arrived.` is only implied (the passage says `took him to` the shack and later `opened the door`). d `They called an officer to arrest him.` is close to `Connie called the police` | Say he was locked in (p15), or make d plainly false |
| PB5F-Q03 | L3 / 21 | Vocabulary 7 | `It is very efficient.` with `limited edition` as the replacement gives `It is very limited edition`. **Unfixed since the mock (GB5-19)** | `It is a limited edition.` |
| PB5F-Q04 | L4 / 31 | Vocabulary blank 8 | `move slowly and patiently since 8 ___ movements could frighten the animals`: the word that fits is `sudden`, which is not in the box, and the only candidate, `subtle`, inverts the meaning. **Unfixed since the mock (GB5-18)** | Put `sudden` in the box in place of `subtle` |
| PB5F-Q05 | L4 / 32 | Grammar Ex1 item 3 | `My brother keeps leaving his wet towel on the bed. I wish he ___ it in the bathroom instead.`: a `left` is as grammatical as the intended d `would leave` | Replace a with a form that fails (e.g. `has left`) |
| PB5F-Q06 | L5 / 46 | Grammar Ex1 item 3 | `When the train ___ (leave) the station, the passengers ___ (take) their seats.`: with "simple present or future perfect", both `leaves / take` and `leaves / will have taken` work | `By the time the train leaves the station, …` |
| PB5F-Q07 | L5 / 46 | Grammar Ex1 item 6 | The only answer the instruction allows is `will have been ready`, which no native speaker would say | Use an action verb, e.g. `The chefs ___ (prepare) all the dishes before the guests ___ (arrive).` |
| PB5F-Q08 | L8 / 77 | Grammar Ex2 item 5 | `began learning French in 2006. Her course finishes in 2010. → When the course ends, ___` asks for a future form about a course that ended 16 years ago (the example is 2025–2028; the book is © 2026) | e.g. `began … in 2024. Her course finishes in 2028.` |
| PB5F-Q09 | L8 / 77 | Grammar Ex3 example | Cues `weather / be cold / children / yesterday morning` → model `Despite the cold weather, the children played outside.` drops `yesterday morning` and invents the verb | Add the cue: `… / children / play outside / yesterday morning`, and end the model with `…played outside yesterday morning.` |

### Print against audio (found only with the audioscript)

| Id | File / printed | Item | Problem | Correction |
| --- | --- | --- | --- | --- |
| PB5F-A01 | L1 / 9 | Listening Ex2 Q2 `Which sentence correctly describes Josh's preference?` | b `He would rather have a video call…` is his view at the start; the audio ends `Josh changed this opinion. He now thinks that meeting face-to-face is better`, which makes d `He preferred meeting Amir in person to speaking online` true as well | Anchor the time: `…Josh's preference before the interview?`, or replace d |
| PB5F-A02 | L3 / 30 | Listening Ex3 item 2 `Maya hopes to introduce a more competitive way to organize classroom duties.` | The audio says `reorganize the student council, so that it can run more efficiently`. That is two mistakes (`competitive`, `classroom duties`) where every other item has one, so a student who fixes only `competitive` still has a false sentence | Keep one mistake: `Maya hopes to reorganize the student council so that it can run more competitively.` (answer `efficiently`) |
| PB5F-A03 | L4 / 40 | Listening Ex2 item 4 `Zoe said, "If only I'd ___ last year."` | The audio says `I never applied … If only I had been more confident back then.` Both `applied` and `been more confident` fill the blank, and the quote prints `last year` where she says `back then` | `Zoe said, "If only I'd ___ back then."` (and accept only `been more confident`), or drop the quotation marks |
| PB5F-A04 | L5 / 53 | Listening Ex1 Q4 `What will the family have finished by Friday evening? Circle all the correct answers.` | The audio says only `By this Friday, we will have completed all of the preparations.` It never lists them, never says `evening`, and never mentions choosing pizzas. So a, b and c are all inference, and d (food for opening day) is the only clear no | Make the audio list the jobs, or ask a question it answers (`What will the family have completed by Friday?` with one option `all the preparations`) |

### Grammar not yet taught (curriculum conformance, both unchanged since the mock)

| Id | File / printed | Item | Structure |
| --- | --- | --- | --- |
| PB5F-G01 | L2 / 13 | Grammar Ex2 item 9 `It ___ should / would (deliver) by now.` | Perfect modal passive (`should have been delivered`). SB5 L2 teaches modal + be + past participle only. Was GB5-G01 |
| PB5F-G02 | L3 / 22 | Grammar Ex1 item 4, d `I might have added too much orange juice.` | Past modal of deduction. SB5 L3 teaches `might` for present and future only. Was GB5-G02 |

These two need a decision rather than a correction: either accept a stretch beyond the core, or
rewrite the items.

## Editorial: worth fixing if the files are reopened

| File / printed | As printed | Suggestion |
| --- | --- | --- |
| L1 / 2 | `Combine the sentences using the words in ( ).` The cues are pills, not brackets | `…using the words given.` |
| L1 / 3 | Blank 5 `take public transport rather than drive` (Mia is a schoolchild) | `rather than go by car` |
| L1 / 8 | Q4 `According to Oliver, what disadvantages did city life have?` The narrator lists them; Oliver only says `constant fear` | `What disadvantages did city life have?` |
| L1 / 8 | Q5 `Why did Oliver think he would rather live…` | `Why would Oliver rather live…` |
| L1 / 10 | `Exercise 3:  Listen…` (double space) | one space |
| L2 / 11 | Vocab 5 `An elderly man was ___ outside the bank`: `robbed`, `threatened` and `harmed` all fit | add a clue (`…and his bag was taken`) |
| L2 / 11 | Vocab 8 `saying that she would break the window if she did not receive a refund` (two women, two `she`s) | make the customer `he`, or recast |
| L2 / 15 | `we should be careful and think carefully before we act` | `we should stop and think before we act` |
| L2 / 16 | Q5 c `Take some time to think carefully…` is the only imperative among statements | recast as a statement |
| L2 / 17 | `continue to be 2 ___ , and` (space before comma) | close it up |
| L2 / 18 | `The cause of the problem 6 ___ into to solve it for good.` | `…looked into if we want to solve it for good.` |
| L2 / 19 | Listening Ex2 Q3 `What caused the fire?` a `a fire in an apartment building` (circular) | a real cause |
| L3 / 22 | Item 4 `I probably used more orange juice than I'm supposed to.` | `than I was supposed to` |
| L3 / 23 | `I found a beginner glassmaking class at Ember Studio this Saturday.` | `…for this Saturday.` |
| L3 / 23 | Ex3 blank 3: distractor e `visitors may watch from a safe viewing area` also answers `Can I come with you?` | make e plainly irrelevant |
| L3 / 26 | `a limited-edition welcome kit` given `on the final day`; `extra credit` and `extra gifts` for the same sessions | `farewell kit`; one reward |
| L3 / 26 | `Registrations will be open on January 15th` | `Registration opens on January 15th` |
| L3 / 26 | **Preflight:** a hidden text frame reading `Fans` sits under the `Exercise 2` heading (in the text layer, not visible) | make sure it is not on a printing layer |
| L3 / 28 | `the woman` for a message signed `Mom`; `text` and `passage` both used | `Mom`; one term |
| L4 / 31 | `but Lena 4 ___ that an experienced photographer…` (`clarified` with `but`) | `so Lena clarified…` |
| L4 / 33 | `Complete the conversations with the sentences… Not all the letters will be used.` | `Not all the sentences will be used.` |
| L4 / 35–36 | Q4 `a second, once-in-a-lifetime chance`; `after he had gotten his wish`; `the spirit and gold had disappeared` | `one more chance`; `after he got`; `the gold` |
| L4 / 36 | Q5 `what did Tomas realize was more valuable than gold?` (`wisdom` p34 and `this peaceful life` p35 both fit) | `…what did Tomas say was worth more than any gold?` |
| L4 / 36 | `They would shame me if they knew…` | `They would be ashamed of me…` |
| L4 / 38 | T/F/N 5 `Grandma regrets not telling her parents…` is only implied: T and N are both arguable | state the regret in the 1993 entry |
| R1 / 43–44 | `On Board with Battling Burnout`; `make you become easily irritated`; app bullets `helps students track…` / `remember…` / `create…` | `Beating Burnout`; `make you easily irritated`; parallel bullets |
| L5 / 45 | `all the ingredients and dessert … count their sales` | `desserts`; `the day's sales` |
| L5 / 47 | Ex3 item 2 is one sentence under "Combine the sentences" | split it |
| L5 / 48 | `(April-June 2012)` | en dash |
| L5 / 48 | A second `AHEAD` logo shows on the back sheet behind the report card | confirm the stacked-paper look is intended |
| L5 / 49 | `We provided these units to our clients who urgently needed them first.`; `reduce our delivery time by two more days` | `We sent these units first to the clients who needed them most.`; `by two days` |
| L5 / 50–51 | `brought up the problem to her three closest friends`; `give up and postpone`; `my team aims for a better learning environment …, and so do I` | `brought the problem up with`; `give up or postpone`; recast |
| L5 / 51 | A row of dots above the left column | remove, or confirm it is intended |
| L5 / 52 | Ex2 item 1 a `teamworked` (not a word); d `discussed` also fits `Freya ___ the budget` | real, clearly wrong verbs |
| L5 / 53–54 | `designing the shops` (one restaurant); Ex3 `for each person` over rows labelled `Message`; `Message 1 :` | `the restaurant`; `for each message`; `Message 1:` |
| L5, L8, R2 | `one to two words` | `one or two words` |
| L6 / 55–56 | `rules that were recently put up`; `rewrite the sentence` (plural mistakes); item 2 `believes he can` → `expects to` (not the same meaning); item 5 `showed the report` | `introduced`; `each sentence`; `thinks he will handle`; `showed the principal her report` |
| L6 / 58–59 | One letter of A–F goes unused with no warning; `City Marathon Challenge` for a 10-km run; `extra chefs` with `No experience is necessary`; `Evening Street Outreach … at 4 PM` | `One letter will not be used.`; `10K Challenge`; `extra volunteers`; `6 PM` |
| L6 / 59 | Note `(e.g. because of injury, etc.)` | `(e.g. because of an injury)` |
| L6 / 60 | An oil-refinery photo beside the definition of renewable energy; `What is renewable energy?` repeats para 1 | a solar or wind photo; `What are some types of renewable energy?` |
| L6 / 61–62 | `By the 1990s and 2000s, the world became`; `the use of fossil fuel`; Q3 `help solve climate change` (text: `slow down`), b `carbon gas emissions`; Note 2 not parallel | `In the 1990s…`; `fossil fuels`; `slow down`; `carbon emissions`; recast |
| L7 / 65 | Vocab 5 `used to work two part-time jobs and lived` | `and live` |
| L7 / 67 | `He recorded himself 3 ___ listen back and hear if…`; `sleep early` | `check whether`; `go to bed early` |
| L7 / 68–69 | Tense shifts (`Suppose these organisms are causing … Are they …? It seemed possible`); `would need to be studied more`; `won't repeat the same mistakes` (one mistake) | keep one tense; `needs further study`; `make the same mistake again` |
| L7 / 70 | Q4 event 2 `on the fish's skin` (text: `scales`); event 1 calls the fish `samples` | `scales`; `The filter was left off and the fish died.` |
| L7 / 71 | `that trust drops sharply … the gap becomes` in a past-tense paragraph; `too sick or tired, but you don't have anyone`; `That will be an incredible advancement` after `Suppose`; `In reality, the idea was becoming real` | past tense; `too sick or tired to drive and`; `would be`; `In fact, the idea is becoming real` |
| L7 / 71 | Chart bars ≈ 11.6 / 21.6 / 26.3 and 20 / 12.8 / 5 (totals ≈ 59.5 and 37.8 against the text's 60 and 38); axis `18~30` | redraw at whole numbers summing to 60 / 38; `18–30` |
| L8 / 76–77 | `hopeless at solving` (means "bad at"); `moved to Melbourne and she`; `Ava volunteered … in 2018 and will continue`; item 4 `It is now 2023`; cue `finds time` | `hopeless about`; comma; `started volunteering`; `2026`; `find time` |
| L8 / 78–80 | `6.0 is ten times stronger than the one measuring 5.0`; `but they are too unpredictable` (scientists or earthquakes?); Q5 c `pause trains` (text: `slow down`) | `about ten times … than one`; `earthquakes are`; `slow down trains` |
| L8 / 82 | `like a landslide, hurricane, or an earthquake` | `a landslide, a hurricane, or an earthquake` |
| R2 / 85 | `encourage her to not give up`; `high expectations for you to be able to properly manage`; `the booking numbers to check into the hotel room` | `not to give up`; recast; `your booking number to check into the hotel` |
| R2 / 87 | `a person or organization who gives`; `It will also decide the type of venue` | `that gives`; `determine` |
| R2 / 88 | `Because 2 ___ is affecting the weather.` (a fragment among sentences); Ex1 `four statements about the picture` (there are four pictures) | `It was created because…`; `about each picture` |

## Since the mock drafts

**L1–R1 mock** (`control-2026-09-15/gstar-pb-b5.md`, 19 positives): 15 are fixed, and 4 are
still in the print file: GB5-09 (→ PB5F-05), GB5-11 (→ PB5F-07), GB5-18 (→ PB5F-Q04) and
GB5-19 (→ PB5F-Q03). The fix to GB5-04 (`she's stuck` → `she was stuck`) dropped the full stop
(PB5F-04). Of the receptive grammar candidates, `it is time I think` (GB5-G07) is now well formed.
The others are unchanged and remain editorial.

**L5–R2 mock** (`control-2026-09-16/gstar-pb-b5-l5-r2.md`, 15 positives): all fixed. PB5B-11
(the chart totals) is fixed only approximately: the bars now sum to about 59.5 and 37.8 against
the text's 60 and 38. That is listed above as editorial.

## Curriculum conformance

Each Power Book lesson practises the grammar of its Student Book 5 lesson
(`data/series/authored/g-star-level-5.json`):

| PB lesson | SB5 grammar | Practised in |
| --- | --- | --- |
| 1 | Prefer … To; Prefer to / Would Rather; While / Whereas | Grammar Ex1–3; Reading Ex1–2 |
| 2 | Passive (present perfect); Passive (modal + be + pp) | Grammar Ex1–2; Reading Ex1–2 |
| 3 | Nonrestrictive relative clauses; May; Might | Grammar Ex1–3; Reading Ex1 |
| 4 | Wish / If Only; I Wish You Would | Grammar Ex1–3; Reading Ex1–2 |
| 5 | Future perfect; So / Neither | Grammar Ex1–3; Reading Ex2 |
| 6 | But For / If It Weren't For; Expect | Grammar Ex1–3; Reading Ex2 Q2 |
| 7 | Suppose / What If (three tenses); So That / In Order To | Grammar Ex1–3; Reading Ex1–2 |
| 8 | Future perfect continuous; despite / in spite of | Grammar Ex1–3; Reading Ex1–2 |
| R1 / R2 | Lessons 1–4 / 5–8 | Grammar Ex1–2 each |

Beyond the syllabus, the only productive cases are PB5F-G01 and PB5F-G02. L1–R1 uses no grammar
from lessons 5–8 productively: `expects me to` appears in the L4 diary only receptively.

## Listening: every printed item solved from the audioscript

The script follows the printed order exercise by exercise, and the names, numbers and places match
the pages. I found no order swap like the Student Book's SB5F-13. The four print-against-audio
findings are PB5F-A01 to A04 above.

| Lesson / pages | Ex1 | Ex2 | Ex3 |
| --- | --- | --- | --- |
| 1 / 9–10 | `foreign students`, `venue`, `accessible`, `the train` (or `public transportation`), `traffic jams`, `disadvantage` | d, b (d also true: A01), b, d, a | b baking, d aquarium, a cafe at the station, b laundry, c (Anna library, brother band) |
| 2 / 19–20 | Rebecca e, Mark d, Nora f, Kevin b, Duke a (c unused) | d, b, c, a, a | F F T F T T |
| 3 / 29–30 | b, c, b, d, a | Rosa trustworthy, Max competitive, Wade generous, Chelsea determined, Brenda outgoing | `suspicious`→`outgoing`; `competitive`→`efficient` (A02); `Maya`→`Leo`; `charming`→`competitive`; `before`→`after` |
| 4 / 39–40 | c (talk it out), c (practise in the daytime), d camera, a art room | `good progress`, `aiming for`, `great opportunity`, `been more confident` (A03), `would take` | Gina f, Stanley e, Chuck d, Rachel b, Jamie c (a unused) |
| R1 / 44 | gym d, store a, holiday b, watch e (c unused) | `Westfield Middle`, `1,200`, `efficient`, `trustworthy`, `disorganized`, `September`, `independent`, `opportunity` | — |
| 5 / 53–54 | b, b, d, a/b/c by inference (A04) | `6`, `manage`, `translate`, `provide`, `solution`, `have filmed` | 1 d, 2 e, 3 b, 4 c (a unused) |
| 6 / 63–64 | c, b, d, c | d run, c group, b chase the cat, a `For our Earth!` | T F T F T F |
| 7 / 73–74 | 1: c b d a · 2: a c d b | Lisa c, Chris f, Ethan a, Ashley b, Kyle e (d unused) | b, a, d, a |
| 8 / 83–84 | a + c, d, c, c, b | `follow`→`lead`; `park managers`→`rescue team`; `Because of`→`Despite`; `cause`→`prevent`; `uninterested`→`eager` | T F F T F |
| R2 / 88 | 1 b, 2 a, 3 c, 4 d | `advancement`, `climate change`, `emergency`, `evacuate`, `backup solutions`, `been testing`, `any errors` | — |

Soundness notes, all editorial:

- L1 Ex1 item 6: `disadvantage` is never spoken (`Too bad that the community center is much smaller`). Accept `problem` or `drawback`.
- L1 Ex3 Q1 `Which Saturday class will Lucy join?`: neither `Lucy` nor `Saturday` is in the audio.
- L5 Ex2 note 5: `The cafe will be used as the ___` keys to `solution`, from `use the cafe near the school as a solution`. `backup location` would read better on both sides.
- L6 Ex1 Q4: distractor d `declared the train unsafe` is nearly what the audio says (`declared the track unsafe`).
- R1 Ex2 item 8: `given them an ___` takes only `opportunity`. A student who writes the audio's `great opportunity` produces `an great`.

### The audioscript's own language

These lines are in the recording, so a fix means a re-record. They are listed for the publisher
to decide. Lines marked *script only* are typing slips that don't affect the audio.

| Lesson / exercise | Script line | Fault |
| --- | --- | --- |
| 1 Ex1 | `during the rush hour` | `during rush hour` |
| 1 Ex2 | `And in the end, Josh changed this opinion.` | `his opinion` |
| 1 Ex2 | `Public transportation is accessible there, but it is not as convenient as the city.` | `as in the city` |
| 1 Ex3 | `I can't choose between the computer class or the baking class.` | `and` |
| 1 Ex3 | `a busy afternoon for the both of you` | `for both of you` |
| 2 Ex1 | `threatened to share her private information to the public` | `with the public` |
| 2 Ex3 | `Recently, many tourists have had their phones and wallets stolen over the past two weeks.` | `Recently` and `over the past two weeks` say the same thing |
| 3 Ex1 | `She, who is the most competitive person I've known, was determined…` | A nonrestrictive clause on a bare pronoun, in the lesson that teaches them: `Maya, who is…` |
| 3 Ex1 | `I also did.` | `So did I.` |
| 3 Ex1 | `You'll have to pay to replace the items if you break it` | `an item … it` |
| 3 Ex3 | `Students at Class 6A` | `in Class 6A` |
| 3 Ex3 | `reorganize the student council, so that it can run more efficiently` | No comma before a purpose `so that` |
| 4 Ex1 | `I wish he wouldn't just jump into conclusions` | `jump to conclusions` |
| 4 Ex2 | `Participants can work with professional designers and get feedback for our own games.` | `their own games` |
| R1 Ex1 | `you may be able to workout on your own` | `work out` (*script only*) |
| R1 Ex1 | `such a big amount of money` | `such a large amount` |
| 5 Ex1 | `We end up borrowing my uncle's pizza oven … He agrees to let us use the oven until ours arrive.` | Present tense inside a past narrative; `ours arrives` |
| 5 Ex3 | `I don't have the record file` | `the recording` |
| 8 Ex1 | `she volunteers as a staff at the film club` | `as a staff member` |
| R2 Ex2 | `climate change is unusually affecting the weather` | `is affecting the weather in unusual ways` |

The script heads L4 Ex2 `Write no more than three words`, where the page prints `one to three words`. The
two agree in practice.

## Checked and correct (a finding here is a false positive)

- L1 Grammar Ex2 blanks 3 and 5: `rather stay` and `prefers to … rather than` are the only grammatical options; the others are deliberate distractors.
- L2 Grammar Ex1 item 6 `have being announce` has two errors, which the plural rubric covers.
- L3 Grammar Ex1 5a `The coin, who comes from…` is a deliberate distractor.
- L4 Grammar Ex1 `could have charge`, `has accept`, and R1 Grammar Ex1's wrong forms are the errors students are asked to find.
- L5 sales chart: the twelve weeks sum to 845, as the text says.
- L6 pie chart: the renewables sum to 32.4 %, which supports `over 30%`.
- L6 Grammar Ex1 item 1 now contains an error (`won't be able`), so PB5B-05 is resolved.
- L7 journal dates are consistent (March 3 → `past ten days` → March 17; March 13 + `four more days`).
- R2 Grammar Ex1 has exactly one wrong part per sentence (B, B, C, D, A).
- `Thomas' assistance` and `James' effort` are an accepted possessive style; US spelling is consistent throughout.

## Counts

Must fix: 21 language and layout errors (PB5F-01 to 21; PB5F-21 covers 30 marks), 9 soundness
errors (Q01 to Q09), 4 print-against-audio errors (A01 to A04) and 2 conformance decisions (G01,
G02). Editorial: about 65 rows, plus 20 audioscript language faults for the publisher to decide
on (re-record or accept).
