# Control: G-Star Student Book 6, Lesson 1 – Review 1 (print scan, Google Drive)

Hand proofread on 5 October 2026 of G-Star Student Book 6, Lessons 1–4 and Review 1. The model
step was done by hand. Every page was read as an image at 150 dpi. Nothing paid ran.

| File | Bytes | Pages | sha256 |
| --- | --- | --- | --- |
| `sb6.pdf` (Drive id `1YdIcGheLRAkLpbVkT40gpxzVw_Aap0_d`) | 60,129,327 | 19 | `b327173d7ec830ea3acdef9935aa1a252acc251ba455acc4db074f4aa0720541` |

The file is an Adobe Acrobat image conversion (one 300 dpi JPEG per page) with **no text layer**.
Physical page 1 is the cover and 2 the contents spread. Physical N (3–19) holds printed pages
2N−5 and 2N−4: L1 printed 1–8, L2 9–16, L3 17–24, L4 25–32, Review 1 33–34.

**Not supplied, so not checked:**
- The audioscript, so the eight listening exercises on printed pages 5, 13, 21 and 29 are proofread for wording only.
- The answer key.

**Review 1 is only two pages** (33–34), and the file ends there. SB5's Review 1 ran to four pages. Confirm whether Review 1 continues.

Conformance is judged against the committed G-Star syllabus:
- **Grammar:** the SB6 grammar headings in `data/transcriptions/gstar-sb-6/`, and the SB-ST to SB5 headings in `data/series/pages/` and `data/transcriptions/`.
- **Words:** `data/series/g-star-lexical-resolution.json`, read 30 Sep.

The live core was not reachable, because the Atlas CLI session has expired. For a reference
student book the conformance check is **forward reference**: a lesson may use only what earlier
books and its own earlier lessons have taught.

| SB6 lesson | Grammar | Words |
| --- | --- | --- |
| L1 You Ought to Be More Ambitious | past perfect continuous; ought to | distinguish, consistent, approve, neglect, promising, ambitious, underestimate, student exchange, application, requirement |
| L2 It Is Reasonable for Us to Take Precautions | infinitive phrases; it is + adj + of/for + sb + to-inf | essential, reasonable, keep one's side of the bargain, operate, assume, risky, precaution, doubt, intend, outcome |
| L3 Do You Know Why He Hesitated? | indirect questions; reporting verbs | get on one's nerves, confess, suffer, hesitate, fond of, forbidden, miserable, undertake, fault, favor |
| L4 It Is You That I Respect | it-cleft; wh-cleft | keep one's word, respect, appoint, envy, deserve, devote, reliable, demanding, circumstance, occupy |
| later: L5 | reporting verbs + passive; could/must/might + have | reveal, prove, attempt, … |
| later: L6 | double comparatives; present subjunctive | careless, influence, consequence, perspective, … |
| later: L7 | perfect participle phrases; inversion | |
| later: L8 | reduced relative clauses; wh-ever | particular, struggle, … |

## Must fix before print

### Wrong item, wrong reference, wrong key

| Id | Printed page | Item | Problem | Correction |
| --- | --- | --- | --- | --- |
| SB6-Q01 | 7 | L1 Reading CQ 4 `In the sixth paragraph, why did Regina talk about being sick at home?` | The posts hold six paragraphs: two per post. "At home, being sick meant …" is in the **fifth** paragraph, the first of post 3/3. The sixth paragraph is the phone call | `In the fifth paragraph, …` |
| SB6-Q02 | 24 | L3 Speaking Ex2 `Fill the empty boxes below with Reporting Verbs from page 10.` | The reporting-verb tables are on **page 18**. Page 10 is the L2 vocabulary and grammar | `… from page 18.` |
| SB6-Q03 | 18 | L3 Grammar | The table `Some Reporting Verbs Followed by Object + To-Infinitive` (advise, convince, … warn) is **printed twice**, identically. The second copy is almost certainly meant to be another pattern, such as verb + that-clause (explain, confirm, insist that…). `confirm` appears in the bingo grid on p24 but in no table | Replace the second table with the intended pattern, or delete it |
| SB6-Q04 | 33 | Review 1 Ex2 example | The prompt is `James said, "Let's go to the cafe. It'll be fun!"`, but the model answer is `Jonas convinced me to go to the cafe.` The name changes (Jonas comes from Ex1's example) | `James convinced me to go to the cafe.` |
| SB6-Q05 | 34 | Review 1 Ex4 item 3 | `What did he do to keep his side of your bargain?` | `… to keep his side of the bargain?` |
| SB6-Q06 | 31 | L4 Reading CQ 4 `What does hazardous mean …?` a `dangerous` / c `risky` | Two options are right: *risky* is as good a gloss as *dangerous* | Replace c with a clearly wrong option (e.g. `expensive`) |
| SB6-Q07 | 33 | Review 1 Ex1 example | `Jonas is too busy to give us a lift.` → `It is troublesome for Jonas to give us a lift.` This changes the meaning (busy ≠ troublesome) and models a sentence students would not produce. The other five items work: 1 ambitious (of), 2 risky (for), 3 unusual (for), 4 kind (of), 5 cruel (of) | `Jonas has a lot of work, so giving us a lift is hard for him.` → `It is troublesome for Jonas to give us a lift.` |

### Language errors

| Id | Printed page | As printed | Fix |
| --- | --- | --- | --- |
| SB6-01 | 12 | L2 Usage 3 go-bag: `a first-aid kid` | `a first-aid kit` |
| SB6-02 | 18 | L3 Vocabulary 5 `fond of (v)` | `fond of (phr)` (or `adj`); *fond* is not a verb |
| SB6-03 | 2 | L1 Grammar Note `We also use ought to express probability` | `We also use ought to to express probability` (or `We also use "ought to" to …`) |
| SB6-04 | 3 | L1 Usage 2 `We should be informed … earlier` (about something that already happened) | `We should have been informed … earlier` (see SB6-C02: the perfect modal is L5) |
| SB6-05 | 3 | L1 Usage 2 `can't afford waiting` | `can't afford to wait` |
| SB6-06 | 3 | L1 Usage 1 `I had been watering it for you since you were away` | `… while you were away` |
| SB6-07 | 4 | L1 Usage 3 letter `starting from September 5th to January 29th` | `from September 5th to January 29th` |
| SB6-08 | 4 | L1 Usage 3 `You ought to have some questions about …, please feel free to …` (comma splice; the wrong modal) | `If you have any questions about …, please feel free to …` |
| SB6-09 | 4 | L1 Usage 3 `You had been waiting for this confirmation for a while, and we are happy …` | `You have been waiting …` (the wait runs up to now) |
| SB6-10 | 4 | L1 Usage 3 `Ph.D` | `Ph.D.` |
| SB6-11 | 7 | L1 Reading `She promised to visit me over winter break, and that she and dad would cook …` | `She promised to visit me over winter break and said that she and Dad would cook …` |
| SB6-12 | 7 | L1 Reading `She had just been closing up her clinic when I called.` | `She was just closing up her clinic when I called.` |
| SB6-13 | 7 | L1 Reading `I knew I ought not worry my parents`; L1 Grammar Note `He ought not behave so rudely.` | `ought not to worry`, `ought not to behave`. Standard and taught form: the L1 heading gives `ought not to` |
| SB6-14 | 8, 10 | `behaviour` (L1 Speaking, L2 Grammar Note), in a book that spells `behavior` elsewhere (p13, p17) | `behavior` |
| SB6-15 | 10 | L2 Grammar 1 `to add an infinitive phrase as a noun, adjective, or an ad-verb` (and hyphenated across the line break) | `… as a noun, an adjective, or an adverb` (unbroken) |
| SB6-16 | 11 | L2 Usage 1 `Peter, who usually manages all the lighting, just graduated this year.` | `Peter, who used to manage all the lighting, graduated this year.` |
| SB6-17 | 11 | L2 Usage 2 `will enter an agreement` | `will enter into an agreement` |
| SB6-18 | 12 | L2 Usage 3 `important for high-rise buildings residents` | `important for residents of high-rise buildings` |
| SB6-19 | 12 | L2 Usage 3 `damage to others' properties` | `damage to other people's property` |
| SB6-20 | 14 | L2 Reading `Hence, to sound off a false alarm costs much less than missing a real threat.` (a to-infinitive paired with a gerund) | `Hence, sounding a false alarm costs much less than missing a real threat.` |
| SB6-21 | 14 | L2 Reading `Imagine that you are living thousands of years in the Stone Age.` | `Imagine that you are living thousands of years ago, in the Stone Age.` |
| SB6-22 | 14 | L2 Reading table heading `Not flee` | `Don't flee` |
| SB6-23 | 15 | L2 Reading `Not only emotional responses, but our bodies also overreact` (the paired construction pairs a noun phrase with a clause) | `Not only our emotions but also our bodies overreact to keep us safe.` |
| SB6-24 | 15 | L2 Reading `the cost of running away … is less than not running away` | `… is less than the cost of not running away` |
| SB6-25 | 15 | L2 Reading `Our brains would rather sound off false alarms for our safety, than not at all.` | `Our brains would rather sound false alarms for our safety than not sound them at all.` |
| SB6-26 | 16 | L2 Speaking Ex `Being hardworking and organized are also important qualities` (the subject is one gerund phrase) | `Being hardworking and organized is also important.` |
| SB6-27 | 17 | L3 opener `This is supposed to be a happy day, I don't want anything to go wrong.` (comma splice) | `… a happy day. I don't want …` |
| SB6-28 | 18 | L3 Vocabulary 4 `We hesitated between having a picnic or a barbecue.` | `… between having a picnic and a barbecue.` |
| SB6-29 | 18 | L3 Grammar Note `"Why don't you go …? It will be fun!" She said.` / `"Don't go there!" He said.` | `… fun!" she said.` / `… there!" he said.` |
| SB6-30 | 19 | L3 Usage 1 `taking part of the decorations are forbidden` | `taking pieces of the decorations are forbidden` |
| SB6-31 | 20 | L3 Usage 3 Linda: `He or she was around my height and he had long, straight hair.` | `… and had long, straight hair.` |
| SB6-32 | 20 | L3 Usage 3 Game Instructions `… and look for clues` (no full stop) | `… and look for clues.` |
| SB6-33 | 22 | L3 Reading `Look at these examples to illustrate the benefits and cost of relationships.` | `Look at these examples that illustrate the benefits and costs of relationships.` |
| SB6-34 | 22 | L3 Reading `Our relationship with other people is, in nature, transactional.` | `… is, by nature, transactional.` |
| SB6-35 | 22 | L3 Reading `many relationships suffer failure` | `many relationships fail` |
| SB6-36 | 23 | L3 Reading diagram: `Lina had a bad day at school.` / `Wendy has a fine day at school.` | `Wendy had a good day at school.` |
| SB6-37 | 26 | L4 Grammar Note `to add new context to an information that we already know`; `A wh-clause in wh-cleft sentence usually introduces an old information.` | `… to information that we already know`; `A wh-clause in a wh-cleft sentence usually introduces old information.` |
| SB6-38 | 27 | L4 Usage 1 `Since she was elected … six months ago, Mayor Martinez had kept her word. She'd rebuilt bus stops, approved plans of renovating …` | `… Mayor Martinez has kept her word. She has rebuilt bus stops, approved plans to renovate …` |
| SB6-39 | 27 | L4 Usage 1 `What I set out to do as a mayor`; `the Mayor Office`; `It is the voice of the residents that make Redstone City great.` | `as mayor`; `the Mayor's Office`; `… that makes Redstone City great.` |
| SB6-40 | 28 | L4 Usage 3 `a new chef working at a professional kitchen` | `in a professional kitchen` |
| SB6-41 | 30 | L4 Reading `this amount of money still isn't worth the extreme danger` (no full stop at the end of the passage) | add `.` |
| SB6-42 | 30 | L4 Reading `including damage to the brain, lungs, bones, and safety risks that can come from faulty equipment` (the list mixes organs with a second risk) | `including damage to the brain, lungs, and bones, as well as safety risks from faulty equipment` |
| SB6-43 | 30 | L4 Reading `devote their time to help others` | `devote their time to helping others` (*devote … to* + -ing; *devote* is this lesson's word) |
| SB6-44 | 30 | L4 Reading `constantly being under risk of injury`; `falling or jumping from height`; `the dark and cold depth of the sea` | `constantly at risk of injury`; `from heights`; `the dark, cold depths of the sea` |
| SB6-45 | 31 | L4 Reading `including a hazmat suit2` (the footnote 2 is set as body text) | superscript ² |
| SB6-46 | 31 | L4 Reading `a threat produced by a living organism, like viruses, bacteria, … parasites, etc.` | `such as viruses, bacteria, … and parasites` (*like* … *etc.* is redundant) |
| SB6-47 | 5 | L1 Listening Ex1 1 `Emily prepares for the scholarship exam by ___ for more than a year.` (a simple present with a duration) | `Emily has been preparing …` (check against the audio) |
| SB6-48 | 32 | L4 Speaking Ex2 model `Who works a demanding job is my aunt.` and L4 Grammar table `Who called just now was Lulu.` *Who*-headed wh-clefts are marginal; *work a job* is not standard | `The person who has a demanding job is my aunt.` / `The person who called just now was Lulu.` (or teach *what*-clefts only) |

### Glosses (Note boxes) that are wrong for the text

| Id | Printed page | Note | Problem | Fix |
| --- | --- | --- | --- | --- |
| SB6-G01 | 1 | `Prestigious means exclusive.` | Prestigious means respected and admired; exclusive is a different word | `Prestigious means respected and admired by many people.` |
| SB6-G02 | 9 | `Furnished means containing furniture.` for `a furnished kitchen or a stovetop` | A kitchen "with furniture" is not the sense; the text means an equipped kitchen | `Furnished means having furniture and equipment.` |
| SB6-G03 | 15 | `Extensively means in large size or amount.` for `has written extensively about` | Here it means at length, in detail | `Extensively means a lot and in great detail.` |
| SB6-G04 | 19 | `To commission means to assign someone for a task.` | A commission is paid, formal work | `To commission means to officially ask and pay someone to make something.` |

## Conformance and forward reference

| Id | Rule | Printed page | Finding | Class | Action |
| --- | --- | --- | --- | --- | --- |
| SB6-C01 | 3 | 2 | The L1 Grammar table pairs `ought to` with `carelessly`. *Careless* is taught in **SB6 L6**, and the combination `ought to … carelessly` makes no sense either | error (in a grammar box) | Replace it with an adverb that fits the obligation, such as `carefully` |
| SB6-C02 | 2 | 3 | L1 Usage 2 needs the perfect modal *should have been informed* (SB6-04). *Could / must / might + have* is **SB6 L5**, and *should have* is not in any earlier heading | editorial (read only) | Rewrite with a structure taught by L1: `They ought to inform students earlier.` |
| SB6-C03 | 2 | 4 | L1 Usage 3 `You ought to have some questions` reads as *ought to have* (+ object). Students meet the L5 perfect-modal pattern in L1 with a different meaning | editorial | Fixed by SB6-08 |
| SB6-C04 | 3b | 14–15 | The L2 reading (`psychiatrist`, `cortisol`, `fight-or-flight`, `false positive/negative`, `dehydration`, `malnutrition`, `seizures`) is the densest passage in the unit. It is a science text, and four terms are glossed or tabled, so the unglossed `cortisol`, `dehydration`, `malnutrition` and `seizures` are borderline domain words | editorial | Gloss `dehydration` and `seizures` |
| SB6-C05 | 3b | 22–23 | The L3 reading uses `transactional`, `cynical`, `resentment`, `Maslow`, `self-actualization`, `surpasses`. Three are glossed; `transactional` is defined inline. `surpasses` is not glossed | editorial | Gloss `surpass` or use `is greater than` |
| SB6-C06 | 3b | 30–31 | The L4 reading (`saturation diver`, `decompress`, `biohazard`, `sewage backup`, `infestations`, `hazmat`) is content-based and mostly glossed. `infestations` and `pressurized` are not glossed | editorial | Gloss `infestation` |
| SB6-C07 | 2 | 6–7, 15, 31 | Reduced relative clauses (`a young woman named Regina`, `soup made by my mom`, `a hormone called cortisol`, `a threat produced by a living organism`) are the **SB6 L8** heading. The past-participle forms are already covered by SB3 L2 (past participle phrases), so this is not a forward reference | none (recorded so it is not flagged) | — |

Things checked and found clean for forward reference:
- **No L5–L8 structure appears in L1–L4:** no passive reporting verbs (*is said to*), no double comparatives, no present subjunctive, no perfect participle (*Having …*), no inversion and no *-ever* words.
- **Later SB6 words don't appear in L1–L4,** apart from `careless(ly)` (C01). Checked: reveal, prove, attempt, rumor, guilty, temporary, permanent, influence, consequence, perspective, negotiate, ordinary, knowledge, documentary, particular, struggle, outstanding.
- **Every L1–L4 grammar heading is practised:** in Grammar in Context, in Speaking and in Review 1. Review 1 covers L2 (it is + adj + of/for), L3 (reporting verbs, indirect questions) and L1/L4 in Ex3 (past perfect continuous, *ought to*, *what*-cleft, infinitive of purpose).
- **Review 1 vocabulary:** Ex1's adjectives come from earlier levels (troublesome, cruel and unusual from B4; kind from Starter) or from SB6 L1–L2 (ambitious, risky). All the Ex3 options are L1–L4 words.

## Reword or editorial candidates

| Id | Printed page | Concern | Possible action |
| --- | --- | --- | --- |
| SB6-E01 | contents | L5 title `The Man Is Revealed To Be Guilty` capitalizes *To*; every other title has a lower-case *to* | `Revealed to Be` |
| SB6-E02 | 1 | `had consistently been writing for all her life`; `best authors in this generation`; `grateful for everyone who believed in me` | `all her life`; `of her generation`; `grateful to everyone` |
| SB6-E03 | 4 | `pay the full tuition of your home university`; `details of your admittance`; `ought to still register` | `full tuition at your home university`; `admission`; `still ought to register` |
| SB6-E04 | 5 | L1 Listening Ex2 `apply for a leave`; `By what time` asked for a date | `apply for leave`; `By what date` |
| SB6-E05 | 6 | `Our family has a small boat and a ship.` `studying in university`; `accepted for` / `accepted to` (CQ2) | `a small boat`; `at university`; `accepted into` |
| SB6-E06 | 9 | `The Quick Cook Pro is essential to cook easy … meals`; `anti-stick coating`; `plug it to an electricity source` | `essential for cooking`; `non-stick`; `plug it into an outlet` |
| SB6-E07 | 12 | `(like passport or ID card)` | `(like your passport or ID card)` |
| SB6-E08 | 14 | `Usually, a household smoke detector is installed in the kitchen as a precaution.` Detectors are kept out of kitchens because of toast false alarms, which is this passage's own point | `… is installed near the kitchen` |
| SB6-E09 | 14 | `In the one time that there is a fire`; `as if you haven't heard anything` | `The one time there is a fire`; `as if you heard nothing` |
| SB6-E10 | 15 | `People who aren't anxious get injured or fail more easily.` (an absolute claim); CQ3 `getting vaccinated for a disease` | `People who never feel anxious may …`; `vaccinated against` |
| SB6-E11 | 16 | Speaking Q3 `Give an example of one time you have done so.` / Q4 `we first must know` | `a time when you did so`; `we must first know` |
| SB6-E12 | 17 | `Steven is acting weird today` (informal) | `acting strangely` |
| SB6-E13 | 18 | Vocabulary 8 `He undertook the leader role` | `the role of leader` |
| SB6-E14 | 20 | The August Reed card art is an **unfinished orange line sketch**; the other three cards are finished color illustrations | Replace it with the finished art |
| SB6-E15 | 20 | `True Suspects: the Board Game` | `The Board Game` |
| SB6-E16 | 21 | L3 Listening Ex1 2c `She's having allergies from the hospital food`; 3c `Michelle's headache is because she sleeps too long` | `She is allergic to the hospital food`; `… is caused by sleeping too long` |
| SB6-E17 | 22 | `Some evolution theories`; `after a 10-hour isolation`; E `predators like birds or lions`; `share a candy` | `evolutionary theories`; `after 10 hours alone`; `like wolves or lions`; `a piece of candy` |
| SB6-E18 | 24 | L3 bingo grid mixes `asked` and `said` with base forms (`remind`, `confirm`, `decide`) | One form throughout |
| SB6-E19 | 29 | L4 Listening Ex2 prints options with no question stems; L1–L3 print the stems | Confirm that the audio carries the questions |
| SB6-E20 | 30 | `Nurses spend most of each shift being on their feet`; `long shift hours that can last up to 12 hours a day`; `To be a nurse, someone requires a degree` | `on their feet`; `long shifts that can last 12 hours`; `a nurse needs a degree` |
| SB6-E21 | 31 | `waste water`; `$150,000-$300,000`, `$35,000-$50,000`, `No. 1-2` (p13) | `wastewater`; en dashes |
| SB6-E22 | 33 | Review Ex2 item 1 `"I've never doubted you from the start," said Tom.` | `"I've never doubted you, right from the start," …` |

## Not verifiable here

- **Listening, pages 5, 13, 21 and 29:** no audioscript was supplied. The stems are proofread above, but the keys and the item order against the audio are not checked.
- **Answer key:** not supplied.
- **Review 1 beyond page 34:** not in the file.

## Summary

- 7 item or reference faults. The worst are SB6-Q01 (the CQ points at the wrong paragraph), Q02 (the bingo sends students to page 10 instead of 18) and Q03 (a duplicated reporting-verb table, so one pattern is missing).
- 48 language errors, including `first-aid kid`, `fond of (v)`, `ought to express`, and the tense slips in the L1 letter and the L4 news post.
- 4 wrong glosses.
- Conformance: 1 forward-reference error (C01, `carelessly` in the L1 grammar box) and 5 editorial. Every lesson practises its own headings.
- 22 editorial candidates, including the unfinished August Reed illustration (E14).
