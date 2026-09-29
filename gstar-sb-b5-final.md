# Control: G-Star Student Book 5, final print file (`G star-SB B5-final.pdf`)

Hand proofread, 29 September 2026, of the print file before it goes to the printer, done as the
quality pipeline would do it, with the model step done by hand. The audioscript came from the
manuscript `5 G-Star SB5 - audioscript.docx`, which is the whole book with the scripts inline.
The PDF is the authority: where the two disagree and the PDF is right, the docx is what changes.

| File | Size | sha256 |
| --- | --- | --- |
| `G star-SB B5-final.pdf` (InDesign export, 24 Sep 2026) | 1,141,441,382 B, 39 pages | `7f724932c4d6fcac…` |
| `G star-SB B5-final (reduced for QC).pdf` (what the run reads) | 44,357,379 B, 39 pages | `12334addc435d145…` |
| `5 G-Star SB5 - audioscript.docx` | 6,219,730 B | `6fe54f2315937600…` |

Nothing paid ran. Machine-readable: `reference-cases-sb5-final.json` (the scorer's reference set)
and `gstar-sb-b5-final-evaluation.json` (the manifest).

## Before you run it on prod: the file is too big

Quality checks refuse a PDF over **192 MiB** (`QUALITY_LIMITS.pdfBytes`). Unlike the core upload,
quality checks never reduce a file. The print file is 1.09 GB.
`G star-SB B5-final (reduced for QC).pdf` on the Desktop is the same book passed through the
app's own reducer settings (`core-pdf-reducer.ts`: Ghostscript pdfwrite, images at 200 dpi, JPEG,
fonts subset). It is 44 MB, has all 39 pages, and keeps its text layer. Upload that one. Don't
send the reduced copy to the printer.

## Page → lesson mapping for the web (Level 5 / Student Book)

The page numbering moved since the 0914 draft: page 1 is now the cover. Physical page N (3–38)
holds printed pages 2N−5 and 2N−4.

| Physical pages | Printed | Content | Map to |
| --- | --- | --- | --- |
| 1 | — | Cover | level |
| 2 | — | Contents | level |
| 3–6 | 1–8 | Lesson 1 | lesson 1 (first page 3) |
| 7–10 | 9–16 | Lesson 2 | lesson 2 (7) |
| 11–14 | 17–24 | Lesson 3 | lesson 3 (11) |
| 15–18 | 25–32 | Lesson 4 | lesson 4 (15) |
| 19 | 33–34 | Review 1 | level |
| 20–23 | 35–42 | Lesson 5 | lesson 5 (20) |
| 24–27 | 43–50 | Lesson 6 | lesson 6 (24) |
| 28–31 | 51–58 | Lesson 7 | lesson 7 (28) |
| 32–35 | 59–66 | Lesson 8 | lesson 8 (32) |
| 36 | 67–68 | Review 2 | level |
| 37–38 | 69–72 | Verb forms; Grammar and Vocabulary summary | level |
| 39 | — | Certificate | level |

Unkeyed book, so Q/A means soundness. The listening pages are the left halves of 5, 9, 13, 17, 22,
26, 30 and 34. Without the docx their answers are `cannot_verify`; with it, every item resolves
(see "Listening").

## How it was done, and what was real

| Step | What ran | Result |
| --- | --- | --- |
| Manifest | `gstar-sb-b5-final-evaluation.json`, preset `sonnet-5-medium` | 9 units: 8 lessons plus the level bucket |
| Free trace | `evaluate-quality.ts --trace` (real service path, fixture transport) | **18 requests** (unit + naturalness pass × 9), 39 of 39 pages reviewed, and the requests match the estimate's |
| Estimate | the service's own, from page and text sizes | **about $3.78, at most $7.16** at Sonnet medium, PDF only |
| Model step | by hand, spread by spread, at 130 dpi per half-spread, with 300 dpi zooms for every layout call | below |
| Reference | `reference-cases-sb5-final.json`, loaded by the trace through the shipped schema | parses; each positive's own correction satisfies its match rule |
| Manuscript diff | every docx sentence against the PDF text layer (exact, then 3-gram coverage), each difference judged by hand | see "Manuscript against print" |

The trace itself needed one fix: since the main-component rule (18 Sep) it refused every manifest,
because the trace's series had no main component. `evaluation-trace.ts` now gives it one.

**Text-layer blind spots.** Rotated or outlined text comes out of `pdftotext` scrambled or not at
all: the casting call (p17), the handwritten letter (p37), the Performance Club poster (p43) and
the El Niño spread (pp48–49). The model reads the image, so this doesn't hide those pages from it.
But five quotes in the reference can't be checked against the text layer (SB5F-08, E20, E22, E23,
N03); I checked them against the page images.

## Since the 0914 draft

All 23 positives of the 16 September proofread (`control-2026-09-16/gstar-sb-b5.md`) are fixed in
this file, as are most of its reword candidates. The Q/A candidates Q02, Q04 and Q05 are resolved
too: the CRISPR passage now supports four problems, and the exit-sign options now differ.

## Positives (errors to fix before print)

| Id | Physical / printed | Check | As printed | Defect | Correction |
| --- | --- | --- | --- | --- | --- |
| SB5F-01 | 3 / 2 | layout | Vocabulary 7 `I love taking public transportation.` | The highlight covers `public transport` and stops before `ation`. The docx still reads `public transport,`, so the highlight was set on the old wording | Extend the highlight over the whole headword |
| SB5F-02 | 4 / 3 | language | Usage 1 `I'm researching a rare plant that only grows near Dew Village.` | The next turns say it also grows in the city, only smaller | `…a rare plant that grows especially large near Dew Village.` |
| SB5F-03 | 5 / 5 | language | Listening Ex1 item 3 `…expensive rent and ____` | No full stop; items 1 and 2 have one | add `.` |
| SB5F-04 | 5 / 5 | language | Listening Ex1 item 4 `…because they can be ____` | No full stop | add `.` |
| SB5F-05 | 9 / 13 | language | Listening Ex2 last box `A police spokesperson asked citizens to ____` | No full stop | add `.` |
| SB5F-06 | 9 / 14 | layout | Reading header | The `Reading` label is printed over the web page's tab row and covers `Home` | Move the label or the tab row |
| SB5F-07 | 22 / 39 | language | Listening Ex1 item 2 `…shipping services for ____` | No full stop; items 1, 3 and 4 have one | add `.` |
| SB5F-08 | 24 / 43 | language | `I would either be a singer or an actor.` | `either … or` pairs a verb phrase with a noun phrase | `I would be either a singer or an actor.` |
| SB5F-09 | 24 / 44 | language | Vocabulary 7 `If it weren't for him, I wouldn't have gotten on the roller coaster.` | A past result with the present form; the page's own Grammar Note gives `If it hadn't been for` for the past | `If it hadn't been for him, …` (an editorial finding counts) |
| SB5F-10 | 32 / 59 | language | `Install window coverings to prevent them from breaking.` | `them` can only mean the coverings | `…to prevent your windows from breaking.` (editorial or naturalness counts) |
| SB5F-11 | 33 / 61 | language | `By 2035, we will have been using the Richter scale … for 100 years.` | The same paragraph says `Nowadays, scientists use the moment magnitude scale` | `By 2035, the Richter scale will have been around for 100 years.` |
| SB5F-12 | 5 / 5 | language | Listening Ex2 item 3 `…take the bus to Spring Hill?` | The audio says `Spring Hills` | `Spring Hills` (or re-record) |
| SB5F-13 | 17 / 29 | qa | Listening Ex2 items 2 and 3 | **The audio plays the high-school item second and the robot item third; the page prints them the other way round.** A student answering in order gets both wrong | Swap items 2 and 3 on p29, or re-cut the audio |

SB5F-12 and SB5F-13 can only be found with the audioscript supplied. Scoring: a finding counts
when it names the page and quotes the item. For 01, 06 and 13 an instruction is the expected
correction.

## Candidates: rewords, consistency, soundness

Naturalness findings are classification `error` under the current prompts; the others are
editorial.

| Id | Physical / printed | As printed | Suggestion |
| --- | --- | --- | --- |
| E01 | 2 / contents | `Remember to put periods . , commas , , and / or question marks ? in the right places.` | `…periods, commas, and question marks…` |
| E02 | 3 / 1 | `During rush hours, the train is crowded.` | `During rush hour` |
| E03 | 4 / 3 | `It will still be pretty safe.` | `So it should be pretty safe.` |
| E04 | 4 / 4 | `a balcony on the second floor and the third floor` | `balconies on the second and third floors` |
| E05 | 5, 9, 13, 22 | `fill in each blank with one to two words` | `one or two words` |
| E06 | 5 / 6 | `avoid unneeded stress` | `unnecessary stress` |
| E07 | 8 / 11 | `and that the people can enjoy the streets safely again` | drop `the` |
| E08 | 9 / 14 | `should be talked about between parents and children openly` | `should be discussed openly between parents and children` |
| E09 | 12 / 20 | `who was working night shifts every day as a cleaner` | `who worked night shifts as a cleaner` |
| E10 | 14 / 23 | `useless without giving clear steps for improvement` | `useless unless they give clear steps…` |
| E11 | 16 / 27 | `I wish she wouldn't give feedback in such a rude way.` (one event, today) | `I wish she hadn't given me feedback…`, unless a habit is meant |
| E12 | 16 / 28 | `Good afternoon, Miss Rita Jones.` | `Good afternoon, Ms. Jones.` |
| E14 | 19 / 33 | `take a bus during the rush hour` | `during rush hour` |
| E15 | 19 / 34 | R1 Ex4 distractors `limited edition` (taught hyphenated) and `complicatedly` | `limited-edition`; replace `complicatedly` |
| E16 | 20 / 35 | `make sure all our efforts are not wasted` | `make sure none of our efforts are wasted` |
| E17 | 21 / 37 | `Turbo will have helped customers for thirty years` | `will have been helping` |
| E18 | 22 / 40 | `When I used to play with the kids…, I was the leader.` | `When I played with the kids…, I was always the leader.` |
| E19 | 24 / 44 | Grammar 3 `I expect that I can handle this problem easily.` | `…that I will handle…` |
| E20 | 24 / 43 | `The art group` is for would-be singers and actors | a performing-arts or drama group |
| E21 | 25 / 46 | `The first food bank in Maroon City` against the mayor's `our food banks stock` | `our food bank stocks` |
| E22 | 26 / 48 | `winds blow across the centerline of the Earth from east to west` | `winds blow from east to west along the equator` |
| E23 | 27 / 49 | Note 1: `"Hurricane" is used for a storm that forms over the eastern Pacific` | Atlantic too; read with this note, p48's `El Niño suppresses hurricane activity` is wrong for the eastern Pacific |
| E24 | 27 / 50 | model `If it hadn't been for using my phone` | `If it hadn't been for my phone` |
| E25 | 28 / 51 | `discover new fun and exciting games` | `fun and exciting new games` |
| E26 | 28 / 51 | VIP 1-day $450 / 2-day $500 against $100 / $175 | a $325–350 bag of souvenirs? check the prices |
| E27 | 31 / 57 | `a virus' DNA` | `a virus's DNA` |
| E28 | 31 / 58 | `Suppose you lived two thousand years in the future.` | `two thousand years from now` |
| E29 | 32 / 59 | `despite not getting an evacuation order` | `even if you have not received an evacuation order` |
| E30 | 33 / 61 | `Green City Police and Fire Department` | `Departments` |
| E31 | 33 / 61 | `Despite the Richter scale being a modern invention, the first device…` | `Although the Richter scale is a modern invention, …` |
| E32 | 34 / 64 | the comma in `prevent theft, and` is set smaller and lighter than the body text | reset it in the body style |
| E33 | 35 / 65 | Q1 `What is not true`: c `They mark the nearest exit` (the passage never says nearest) competes with intended d | `They show people where to go in an emergency.` |
| E34 | 35 / 65 | photo labels `North America`, `European`, `China` | `Europe` |
| E35 | 35 / 66 | model `They will have been leading the chess club…` (no referent) | `I will have been leading…` |
| E36 | 36 / 68 | R2 Ex4 `the robots can clean up … We don't need to send people…` inside a hypothetical | `could clean up … wouldn't need to send` |
| E37 | 2 / 1 | contents `Prefer + to`, lesson `Prefer … To` | one form |

E13 is withdrawn: Lesson 4 Ex2 prints no question stems, but the audio speaks each question.

## Negative controls (correct as printed; a finding here is a false positive)

N01 `I wish the assignment was less complicated.` (26) · N02 `…and so can you.` (37) · N03
`neither have you` (37, the taught form) · N04 Virgo `August 23rd and September 22nd` (22) · N05
`By 2030, it will have been working … for more than a century` (64; founded 1911) · N06 `and
later, so did I` (40) · N07 `lie lay lain` / `lay laid laid` (69) · N08 `planted fewer trees` (44).

## Listening: every printed item solved from the audioscript

| Lesson / page | Ex1 | Ex2 |
| --- | --- | --- |
| 1 / p5 | `metropolitan area`, `Public transportation`, `traffic jams`, `disorganized`, first | d, b, d, c (SB5F-12) |
| 2 / p13 | d, a, c, d | `surrounded`, `been arrested`, `remain cautious` |
| 3 / p21 | b Julie, d Jason, c Z-4, a red comic book | `competitive`, `brand-new`, `trustworthy`, `suspicious people` |
| 4 / p29 | b, a, c, d | in audio order: D, A (high school), D (robot), C; see SB5F-13 |
| 5 / p39 | `provides`, `ten years`, `Teamwork`, `effort` | F T F F T T T |
| 6 / p47 | a, c, a, d | `make a difference`, `charities`, `the environment`, `public transportation`, `kindness`, `Fearlessly` |
| 7 / p55 | T F T F T T | b, a, d, c |
| 8 / p63 | c, c, d, b | `two years`, `make a difference`, `book events`, `four hours`, `miss your email` |

Soundness notes, all editorial:

- L2 Ex1 item 3: option d `call the authorities as soon as possible` competes, since the script says `report it to the security desk as soon as possible`.
- L6 Ex1 1a: `No one knows if it's safe to eat` uses "it" for the chips.
- L8 Ex2 last blank: the answer has to be paraphrased from `in order to prevent your email being missed`.

## Manuscript (docx) against print (PDF)

The docx is an **older manuscript** than the PDF, not a copy with scattered typos. I found no
case where the docx has a fix the PDF lacks. Two disagreements are settled by the audio, which
was recorded from the docx: SB5F-12 and SB5F-13 above. Everything else below is the PDF right and
the docx stale, so the docx needs updating.

**Passages rewritten for print** (replace the docx text with the PDF's): the Lesson 2 statue
report (p11) · the Lesson 7 CRISPR reading and its questions (pp56–57) · the Lesson 8 exit-sign
reading (pp64–65) · the Lesson 3 casting call (`TV Show` → `TV show`, p17) · the Lesson 1 Josie
blog `I prefer having a nice view to living in a big space` (p4).

**Sentences corrected in the PDF, still wrong in the docx:**

| Printed | docx | PDF |
| --- | --- | --- |
| 2 | `I love taking public transport,` | `…public transportation.` |
| 3 | `W2: … I prefer working in the village rather than working in the city.` | `I prefer to work in the village rather than work in the city.` (and no `W2:` labels) |
| 4 | `three-storey`; `a balcony on the second and third floor` | `three-story`; `…second floor and the third floor` |
| 5 | `rules and laws that apply in your destination country` | `rules and laws in your destination country` |
| 12 | `unsolved to this day and the suspects` | `…to this day, and the suspects` |
| 12 | `1A suspect is the person that…` | `A suspect is a person that…` |
| 13 | Ex1 4c `it makes the place look ugly.` | `it makes those places look ugly.` |
| 14 | `reported so they can be removed` | `reported so it can be removed` |
| 14 | `…get angry when I interrupt their time online.` | `…when I interrupt them while they're online.` |
| 15 | `Bad manners means…`; `made my children angrier and behave more rudely.` | `Having bad manners means…`; `…and caused them to behave more rudely.` |
| 19 | `twice more efficient`; `any Super Appliance stores` | `twice as efficient`; `any Super Appliance store` |
| 20 | `the 700-page long story` | `the 700-page-long story` |
| 21 | Lock-IT `Feature:` with a dangling fourth blank | `Features:` with three numbered blanks |
| 22 | `Horoscopes also make predictions` | `Horoscopes make predictions` |
| 24 | `You have to use a codename.` | `You have to use a code name.` (corrected 29 Sep by a free audit; first written as `You must use code names.`) |
| 30 | `people blow all the fuzzy white seeds` | `a person blows…` |
| 35 | `all our efforts are not wasted tomorrow`; `neither can you all` | `…not wasted`; `neither can you` |
| 40 | `I have always been active ever since I was a kid.` | `I have been active since I was a kid.` |
| 40–41 | `quiet and sometimes`; `with my family or I go out` | commas added |
| 42 | `reading the question and answering` | `reading the questions and answering` |
| 43 | `I would either be a singer or act in a play` | `either be a singer or an actor` (still wrong: SB5F-08) |
| 46 | `Money donations can be made at their website` | `…on its website at` |
| 52 | `We can do many things on our smartphones` | `almost everything` |
| 54 | `interest in space and what I do`; `I would love being a science teacher` | `your interest in what I do`; `I would love to be` |
| 58 | `Engineers find a new problem.` | `Engineers study a new problem.` |
| 62 | `complete the form and do training again` | `complete the form and the training again` |
| 64 | `locked to prevent workers from leaving early`; `buildings were required`; `falls`; `the American Society … was founded in 1911` | `locked to prevent theft`; `have been required`; `falling from a height`; `An organization that is now called the American Society…` |
| 65 | `declared as a global standard by the International Organization of Standardization` | `declared a global standard by the International Organization for Standardization` |
| 39 | T/F item 6 ends `money..` | one full stop |

The docx also carries production notes (`(design as …)`, `(pic: …)`, `content done by grace
(除了listening)`). They're expected in a manuscript and aren't findings.

**The audioscript's own language.** These lines are in the recorded audio, so a fix means a
re-record. Listed for the publisher to decide:

| Lesson | Script line | Fault |
| --- | --- | --- |
| 1 Ex1 | `I also prefer to live alone than share with roommates.` | `prefer to … than`: the lesson teaches `prefer to … rather than` |
| 1 Ex1 | `stand in a bus for 40 minutes` | `on a bus` |
| 1 Ex1 | `Hmm ..` | stray spacing and mark |
| 2 Ex1 | `Visitors should especially be cautious when you're in the middle of a crowd.` | person shift: visitors / you |
| 2 Ex2 | `reports … have been filed to the police` | `with the police` |
| 3 Ex1 | `G1: … B: … G: I agree.` | missing speaker number (`G1`/`G2` elsewhere) |
| 3 Ex1 | `He doesn't give up, I think he'll push himself hard` | comma splice |
| 3 Ex2 | `records strangers or suspicious people, who ring your doorbell` | non-restrictive comma on a restrictive clause, in the lesson that teaches them |
| 4 Ex1 | `continue working and developing with our ideas` | `developing our ideas` |
| 5 Ex1 | `put a lot of effort in making sure` | `into` |
| 6 Ex1 | `Open Hearts is an amazing and trustworthy charity` | no full stop |

## What the pipeline cannot do yet

1. **No manuscript role.** A source is `exercise`, `answer_key`, `supporting_material`,
   `audioscript` or `prose`. Nothing says "this docx is the whole manuscript of this PDF, with the
   scripts inline". So a run can't pull the scripts out of it, and can't treat the rest as the
   same book in another state.
2. **No comparison between two sources of the same material.** A finding has one location and a
   `repairTarget` of key, question, supporting_material or prose. None of those says which file to
   change. The two cases the publisher needs both have no home: "the PDF is right, update the
   docx" and "the docx has the fix, the PDF doesn't". Neither do the order and name mismatches
   between print and audio (SB5F-12, SB5F-13).
3. **The upload limit.** A 1.09 GB print file is refused at 192 MiB, with no reduction step.

## Scoring the prod run against this

`score-web-run.ts --manifest docs/qc-control/results/control-2026-09-29/gstar-sb-b5-final-evaluation.json`
with the run's export and publication, `--naturalness-policy error`.

- **PDF only:** the ceiling is 11 of 13 positives (SB5F-12 and 13 need the script), and the
  listening items should come back `cannot_verify`.
- **With the docx attached as audioscript:** all 13 are in reach. Because the docx is the whole
  manuscript, expect level-wide evidence in every request and findings on the stale docx text.
  Those are the "docx is out of date" rows above, not print errors.
