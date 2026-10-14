# Control: G-Star Writer 3, mock 2 (`Writer-B3-mock2.pdf`)

Hand proofread on 14 October 2026 of the second mock-up of G-Star Writer 3. This is the last check
before the answer keys are written and the book goes to print. Every page was read twice: from the
text layer and from a page image (130 dpi; the Overview at 200 dpi). Every Practice item was solved;
each lesson's C organizer was answered from its model text. The lessons were compared with the first
draft (`Writer B3.pdf`, 30 September; its proofread is
`docs/qc-control/results/create-content/gstar-writer-3-draft-2026-09-30.md`). Two independent review
agents then checked every finding against the page images, solved every Practice item again, and read
every line for misses (one took L1–4 and the Contents; the other took L5–8, the Overview and the back
page). Their corrections and additions are merged here. Nothing paid ran.

| File | Bytes | Pages | sha256 |
| --- | --- | --- | --- |
| `Writer-B3-mock2.pdf` | 8,716,691 | 21 | `2a2bc018507087cf53ec68ea16c9c5d3c108fc8e1eafaa159e617e725e3526e0` |

InDesign export of 13 October 2026. **Page map:** physical 1 = cover (A4); physical 2 = Contents spread; physical N
(3–18) = printed pages 2N−5 and 2N−4 (an A3 spread); physical 19 = Overview (printed 33–34); 20 = Note
pages; 21 = Certificate of Completion with the copyright notice (A4). That makes 40 printed pages, a
multiple of four.

**Scope and rules** (the owner's G-Star rules of 30 September and 5 October):
- **Level:** Writer level 3, lesson k, may use everything in Student Book (SB) Starter–2, Writer
  Starter–2 and Power Book Starter–2, plus SB3 **up to lesson k** (printed numbering). Words were
  checked against `data/series/g-star-lexical-resolution.json`, grammar against
  `data/transcriptions/gstar-sb-3`.
- **Lesson contract:** B is the model text. C analyzes it with a graphic organizer. D teaches words for
  the student's own G writing. E practises D. F brainstorms on the same organizer as C. G is the
  writing task, and H is a rubric that matches the goals and the plan.
- US spelling and punctuation throughout.

Ids are `W3M2-nn`. **Must fix** means wrong as printed: a wrong or double answer, an error in the
English, a contradiction, or a breach of a rule the owner has already decided. **Should fix** means a
recommendation.

## Must fix before print

### Practice items: double answers and wrong definitions (these would become wrong keys)

| Id | Where | Item | Problem | Fix |
| --- | --- | --- | --- | --- |
| W3M2-01 | p19 L5 E-A3 | `People who break the rules have to pay the authorities / fines.` | **Both options are right.** "Pay the authorities" is grammatical and natural, so the item has two answers | `People who break the rules have to pay a fine / crime.`, or `… get a fine / patrol.` |
| W3M2-02 | p31 L8 E-B3 | `to be thinking of other people` (two bank words are left: *personality* and *mindful*) | **No right answer as printed.** *Personality* does not fit, and *mindful* has the wrong meaning. *Mindful* means aware of or careful about something, which is how D3 (`mindful of the slippery floor`) and E-A3 (water and electricity) use it. "Thinking of other people" is *thoughtful* or *considerate* | `careful about or aware of something` |
| W3M2-04 | p23 L6 E-B2 | `to not be somewhere you should be at` → *absence* | *Absence* is a noun (D2), and the definition is a verb phrase. `be at` also repeats the preposition | `a time when you are not where you should be` |
| W3M2-05 | p27 L7 E-B3 | `The frosting is not smooth because I measured / overmixed it.` (key *overmixed*) | The cause is wrong. Overmixing a batter makes a cake tough, as D3 says (`My cupcakes came out hard because I overmixed the batter`). Lumpy cream-cheese frosting comes from *under*-mixing or cold cheese. The key teaches a false cause | `The cake is hard because I measured / overmixed the batter.` |

### Contradictions and wrong pre-filled answers

| Id | Where | As printed | Problem | Fix |
| --- | --- | --- | --- | --- |
| W3M2-06 | p23 L6 E-A1 | `Lena will take over my work during my ___.` | In B, **Lena Diaz is the writer** who is away; Alex and Jane take over her work. The item says the opposite | `Alex will take over my work during my ___.` |
| W3M2-07 | p7 L2 F-B | The Timeline's first box prints **`2010`** | 2010 is Ellie's year in C, copied into the student's own plan. A student born around 2015 would date their inspiration before their own birth | Leave the box empty, as Important Events 1 and 2 are |
| W3M2-08 | p18 L5 C ① | `What: nighttime activities are banned` | The headline and the first sentence ban **camping** and nighttime outdoor activities. The pre-filled answer leaves out the headline's subject | `What: camping and nighttime outdoor activities are banned` |
| W3M2-09 | p18 L5 C ③ | `The announcement made campers and families feel disappointed.` | In B, "the announcements" are the ten warnings *before* the ban. What disappointed campers and families was **the news of the ban** (`The news disappointed both campers and families`). The pre-filled line mixes the two up | `The ban disappointed campers and families.` |

### Errors in the English

| Id | Where | As printed | Fix |
| --- | --- | --- | --- |
| W3M2-10 | p17 L5 B | `as the park had been a popular spot for camping, picnics, and barbecue parties for the fifteen years.` | `… for fifteen years.` (or `for the past fifteen years`) |
| W3M2-11 | p17 L5 B | `"The ban is introduced to protect our beautiful park.` | `"The ban has been introduced to protect …` (or `We introduced the ban to protect …`) |
| W3M2-12 | p21 L6 B | `If the doctor needs to do more tests, I need to extend my leave until March 20th.` | `… I will need to extend …` (a first conditional with a future result) |
| W3M2-13 | p25 L7 B step 6 | `Leave the cake to cool for 30 minutes. Then, remove them from the pans to fully cool.` | `Leave the cakes to cool … Then, remove them from the pans …` (two pans, two cakes; step 8 says `the cakes`) |
| W3M2-14 | p26 L7 C Steps ① (pre-filled) | `1. Preheat an oven at 180°C. Prepare baking pans.` | `1. Preheat the oven to 180°C. Prepare the baking pans.` B says it correctly. "Preheat an oven" was also a 30 Sep finding |
| W3M2-15 | p29 L8 B | `She said that the dog's name was Marty. He was left on the side of the street.` | `He had been left by the side of the street.` (earlier than the past of the story; 30 Sep finding, still open). SB3 teaches the past perfect in L5 and L7, so it is allowed here |
| W3M2-16 | p13 L4 B | `Have a picnic or take a walk in this scenic, pet-friendly hill.` (also on the Overview) | `… on this scenic, pet-friendly hill.` |
| W3M2-17 | p13 L4 B Tips | `Because of occasional rain, please prepare an umbrella.` | `… please bring an umbrella.` ("prepare an umbrella" is a transfer of 準備). In the same paragraph, `Remember to bring your sunscreen and put on comfortable clothes` → `Remember to bring sunscreen and wear comfortable clothes` |
| W3M2-18 | p14 L4 D5 | `The cheap cost of staying at Rudolph hotel makes it a great budget-friendly choice for travelers.` | A cost is *low*, not *cheap*, and the hotel's name needs a capital and an article: `The low cost of staying at the Rudolph Hotel makes it a great budget-friendly choice for travelers.` |
| W3M2-19 | p26 L7 D4 | `He stored the old photos in a disk.` | `He stored the old photos in a box.` (photos are stored *on* a disk, and a disk is a dated example for children) |
| W3M2-20 | p23 L6 F-A Ideas | `going to a get a health check-up` | `going to get a health check-up` |
| W3M2-21 | p9 L3 B tip 3 | `instead of "study every day", set "learn 10 new words this week" as a goal.` | US punctuation puts the comma inside the quotation marks: `instead of "study every day," set …` |

### Missing full stops

| Id | Where | As printed | Fix |
| --- | --- | --- | --- |
| W3M2-22 | p7 L2 E-A1 | `There will be a costume ______ The person with the best costume will win a $100 prize.` | `There will be a costume ______. The person …` |
| W3M2-23 | p19 L5 E-B3 | `I reported the holes on the road to the ______` | `I reported the holes in the road to the ______.` (also *in*, not *on*) |

### Overview (pp. 33–34) and back page

| Id | Where | As printed | Fix |
| --- | --- | --- | --- |
| W3M2-24 | p33 Overview, Lesson 4 heading | `Lesson 4 Narrative Writing` | **`Lesson 4 Persuasive Writing`**, as on p13 and the Contents |
| W3M2-25 | p33 Overview, Lesson 3 | `Guess who just got her language certificatein Japanese? Me!` | `certificate in` (a missing space; it shows on the page image too) |
| W3M2-26 | p33 Overview, Lesson 2 | `An autobiography is a story of your life that you yourself wrote.` | Use the lesson's fixed callout: `An autobiography is a story of your life, written by you.` (the 30 Sep tense finding was fixed on p5 but not here) |
| W3M2-27 | p33 Overview, Lesson 2 | `Use time words in your biography when you're telling your story in a chronological order.` | `Use time words in your autobiography when you tell your story in chronological order.` |
| W3M2-77 | p34 Overview, Lesson 5 Vocabulary | `authority` | `authorities` (D2 and E teach `authorities (n)`; the singular means power, a different sense) |
| W3M2-28 | back page, copyright | `or transmitted, in any form or by means electronic, mechanical, photocopying, or otherwise` | `in any form or by any means, electronic, mechanical, photocopying, or otherwise` |

### Level and syllabus (rules already decided)

| Id | Where | As printed | Rule | Fix |
| --- | --- | --- | --- | --- |
| W3M2-29 | p17 L5 B | `Neither the announcements nor the posters stopped the damage.` | *Neither … nor* is **SB3 L8**, so Writer L5 cannot use it (a forward reference; 30 Sep finding, still open) | `The announcements and the posters did not stop the damage.` |
| W3M2-30 | p17 L5 B (and Overview, and C ③) | `The news disappointed both campers and families` | *Both … and* is **SB3 L8** (Writer L8 teaches it as a similarity word) | `The news disappointed campers and families` |
| W3M2-31 | p13 L4 callout and B; Overview | `Use transition words to express causes: due to, given, because of, or since.`; `Given the large number of guests, please reserve a table in advance.`; Overview `Given … ,` | On 30 Sep the owner accepted *because of, due to, since* and dropped *given* as above the level | Callout `due to, because of, or since`; B `Because of the large number of guests, please reserve a table in advance.` (or use *since*, which the callout teaches but B never models); Overview `Since …` |
| W3M2-32 | p29 L8 callout | `Use time markers: after, before, throughout, until, when, or while.` | On 30 Sep the owner dropped *throughout*. B does not use it either | `after, before, until, when, or while` |
| W3M2-33 | p5 L2 B (twice) | `Inspired by the magician's performance`; `Not everyone in the audience liked my performance` | *Performance* is an **SB3 L5** word, so Writer L2 is too early for it (30 Sep finding, still open) | `Inspired by the magician's show`; `… liked my show` |
| W3M2-34 | p21 L6 B | `I need to extend my leave until March 20th.` | *Extend* is an **SB4 L6** word, above the level | `I will need to stay away until March 20th.` (combine with W3M2-12) |

## Should fix (recommendations)

### Language and naturalness

| Id | Where | As printed | Suggestion |
| --- | --- | --- | --- |
| W3M2-35 | p9 L3 B tip 2 (and Overview) | `For me, I only use two textbooks.` | `I only use two textbooks myself.` ("For me, I …" is a Chinese transfer; 30 Sep finding). The Overview also says `finish the one I'm using`, but B says `the ones` |
| W3M2-36 | p9 L3 B tip 1; p10 C ① (pre-filled) | `find out the difficulty level of the language, which textbooks are useful, and how long …`; C `like how difficult it is, which textbooks to use, and the time learning the language takes` | Make the list parallel: `find out how difficult the language is, which textbooks are useful, and how long …`. In C: `… and how long it takes to learn` |
| W3M2-37 | p21 L6 B | `The doctor said he thought there was a possible problem from my symptoms and asked me to stay longer at the hospital.` | `The doctor was worried about my symptoms and asked me to stay in the hospital for a few more days.` (the same line is on the Overview) |
| W3M2-38 | p17 L5 B | `Rift City Mayor Peter Chavez said that littering and wildlife protection were the main reasons for the ban.` | `… said that the ban was meant to stop littering and protect wildlife.` (littering is not a reason; stopping it is). C's `Why:` changes to match |
| W3M2-39 | p5 L2 B | `Standing on stage, I was sweating out of nervousness.` | `Standing on stage, I was so nervous that I was sweating.` (30 Sep finding) |
| W3M2-03 | p31 L8 E-B2 | `to be lost and away from home` (*stray*) | `lost, or having no home` ("away from home" implies the animal has a home) |
| W3M2-40 | p7 L2 E-B1; E-B2 | `… to make sure guests feel welcomed and comfortable.`; `They will ___ her for her latest movie.` (*award*) | `feel welcome`; `They will ___ her a prize for her latest movie.` (*award* takes an object: award someone a prize) |
| W3M2-41 | p31 L8 E-A3 | `I'm ___ about how much water and electricity I use every day.` (*mindful*) | `I'm ___ of how much …` (*mindful of* is the collocation, as D3 has it) |
| W3M2-42 | p3 L1 E-A1 | `Sorry, I need to ___ you to grab something from the supermarket.` (*trouble*) | `Could I ___ you to grab something from the supermarket?` (the D4 frame; "I need to trouble you to" is not natural) |
| W3M2-43 | p3 L1 F-A Ideas | `ask for changes to your food`; `change the dates for your hotel` | `ask for a special meal`; `change the dates of your hotel booking` |
| W3M2-44 | p1 L1 callout | `Write a short request and thank you in the closing.` | `Write a short request and a thank-you in the closing.` (also on the Overview) |
| W3M2-45 | p15 L4 F-A | `Imagine a city or country and the five places to visit there.`; Ideas `a museum in a massive boat` | `… and five places to visit there.`; `a museum on a huge ship` |
| W3M2-46 | p19 L5 F-A Ideas | `The authorities banned a book title.`; `A new local library was opened.` | `The authorities banned a book.`; `A new library opened in town.` |
| W3M2-47 | p7 L2 F-A | `What do you work as? What are your motivation and inspiration?` | `What is your job? What inspired you?` (H asks for `what inspired you`) |
| W3M2-48 | p6 L2 D5 | `We were awarded first prize at the spelling bee competition.` | `… at the spelling bee.` (a spelling bee is a competition) |
| W3M2-49 | p10 L3 D3 | `I got the third prize in my first singing contest.` | `I won third prize in my first singing contest.` |
| W3M2-50 | p30 L8 D2 | `More people are choosing to adopt pets over buying them.` | `… to adopt pets instead of buying them.` |
| W3M2-51 | p11 L3 E-B1 | `success that came early and as a surprise` (*beginner's luck*) | `good luck when you try something for the first time` |
| W3M2-52 | p14 L4 D3 | `The inn's restaurant serves delicious meals.` | The example does not show what an inn is: `We stayed at a small inn in the mountains. It had only six rooms.` |
| W3M2-53 | p27 L7 E-A2 | `completely closed, no air can get in or out` | `closed so that no air can get in or out` |
| W3M2-54 | p25 L7 B | `Put baking paper at the bottom of the baking pans.` | `Put baking paper in the bottom of the baking pans.` |

### Callouts and terms

| Id | Where | Concern | Suggestion |
| --- | --- | --- | --- |
| W3M2-55 | Taught but not modelled | L2 callout lists `on` and `ago`, but B uses neither (it does use `at` in `At first` and `in` in `in 2018`), and B uses `since`, which is not listed. L3 teaches `such as, or like`, but B uses only `for example` and `for instance`. L4 teaches `since` but B never uses it. L6 teaches `even if, only if` but B uses neither (the Overview gives `… even if ….`). L8 teaches `just as, until, while` but B uses none (the Overview gives `Just as … ,`) | Model each word the callout teaches, or teach only the ones B models |
| W3M2-56 | p21 L6 callout | `Use transition words for conditionals or how something can happen if another event happens: if, in case, even if, as long as, or only if.` | `Use these words to show that one thing depends on another: if, in case, as long as.` (the gloss is circular, and *conditionals* is undefined; 30 Sep finding) |
| W3M2-57 | p9 L3 callout | `Use imperative language to push the reader to take action.` | `Use commands (imperatives) to tell the reader what to do.` (the Overview has the same line, with `the readers`) |
| W3M2-58 | p33 Overview L8 | `A recount has an orientation, middle, and reorientation.` | The lesson calls the middle "events": `… an orientation, events, and a reorientation.` |
| W3M2-59 | L1 terms | C and G say "graphic organizer"; F-B says `Complete the table to plan your email.` L5 says "newspaper article" (A), "news article" (G, H) and "news report" (F-A) | One term per lesson |
| W3M2-60 | p2–3 L1 C vs F-B | C labels the greeting `Opening Address`; F's plan labels the same box `To Whom` | Use the same label in both. `To Whom` reads as the To: field |
| W3M2-61 | Overview L5 | `Ex. Authorities had released announcements and put up posters, but neither worked to stop the damage.` | This is a paraphrase that is not in B. Quote B instead (after W3M2-29) |

### Content and design

| Id | Where | Concern | Suggestion |
| --- | --- | --- | --- |
| W3M2-62 | p29 L8 B photo | The photo shows a large, healthy golden retriever (and a second one at the right edge). The text says Marty is `a small, thin dog` | Use a picture of a small, thin dog |
| W3M2-63 | p14 L4 C Closing | The `Tips` and `Why?` columns have two rows. Tip 1 is pre-filled (September to March / weather). B has two more tips: *bring sunscreen and comfortable clothes* (no reason given) and *bring an umbrella* (occasional rain). A student who writes the sunscreen tip has no Why to give | Tell students which tips to use (`Write the tips that have a reason.`), or give the sunscreen tip a reason in B |
| W3M2-64 | Pre-filled C cells | L5 C ③ is filled in completely (both bullets and the Ending), and L8 C event 2 is filled in completely. The students have nothing left to do in those boxes. Also pre-filled: L1 Subject, Purpose and Q1; L2 Inspiration; L3 Main Idea and No. 1; L4 row 1 and tip 1; L5 What, Who, Why and detail 1; L6 Letter to; L7 the first ingredient and steps 1–2; L8 event 1 | Keep one model cell per box and leave the rest for students to find (30 Sep design finding) |
| W3M2-65 | H rows with no slot in C/F, and goals with no H row | L5 H `includes at least one quote` (2 points), but F has no quote line. L8 H `uses transition words to compare two similar things`, but F has no box for it. L1 goal 1 is *formal*, but no H row checks formal language (no contractions). L6 B ends by thanking (callout), but H does not check it | Add a `Quote:` line to L5 F, and a `Similar things:` line to L8 F. Add `uses formal language (no contractions)` to L1 H |
| W3M2-66 | L6 hospital context | B: a hospital stay with `a possible problem` and more tests. D1: `My illness is very rare and doctors don't know how to cure it.` D3: a cold leads to a hospital stay. That is heavy for young learners (the owner flagged hospital contexts on 30 Sep). The B photo also shows a woman at home on a sofa, not in a hospital | B: a sprained ankle and rest at home. D1 `The medicine cured my cough in three days.` D3 `My cough worsened, so I stayed home.` |
| W3M2-67 | p31 L8 F-A | `Imagine … you adopt an animal that was left behind by its owner.` Two of the four Ideas (`adopting a friend's hamster`, `taking in a friend's old dog`) were not left behind | `taking in a lost rabbit`, `adopting a dog from a shelter` |
| W3M2-68 | p26–27 L7 D vs F | D teaches *batter* and *overmix* (baking words). F's ideas are stir-fry and rice dishes (sweet and sour chicken, omelette fried rice, baked rice, stir-fried tomato and egg), where students cannot use them | Use cooking words for F's dishes (e.g. *ingredient*, *fry*, *serve*; the owner's 30 Sep list), or give F a baking idea |
| W3M2-69 | p1 L1 B | The email names `www.cheaphotels.com`, which may be a real site | Use a clearly fictional name (e.g. `www.bookmyroom-example.com`) |
| W3M2-70 | p11 L3 E-A1 distractors | `aroma` is taught nowhere in the series. `problem` fails on grammar (`a lot of problem`), not on meaning | `a courage b patience c luck d energy`, or similar at-level distractors |
| W3M2-71 | p26–27 L7 C vs F Ingredients | C has two ingredient rows (`Cake` and an unlabelled one that is *Frosting*) plus Equipment; F has only one unlabelled row plus Equipment, so F does not repeat C's boxes | Print `Frosting` in C, and give F two open rows (Part 1 / Part 2) |

### Typography

| Id | Where | Concern | Suggestion |
| --- | --- | --- | --- |
| W3M2-72 | p22 L6 D5 | `back on one's feet` has a straight apostrophe; E and the Overview have a curly one (`one’s`) | Curly apostrophe (30 Sep finding, still open). The grey colour of `one's` is the book's placeholder style, as `someone` in L1 D4, so it is not a fault |
| W3M2-73 | p32 L8 H | `Check and tick if your recount text…` (no space before the ellipsis); every other H has `… your email …` | `your recount text …` |
| W3M2-74 | Contents | Page ranges use hyphens (`1-4`, `33-34`) | En dashes (`1–4`) |
| W3M2-75 | Note pages (physical 20) | The bottom three rules on each page are grey and the rest purple; some rules are heavier than others | One colour and one weight |
| W3M2-76 | p21 L6, p9 L3 dates | `March 16th, 2025`; `posted on October 15th` | US style prints dates without the ordinal: `March 16, 2025`; `October 15` (consistent within the book, so low) |

### Added by the second review

| Id | Where | As printed | Suggestion |
| --- | --- | --- | --- |
| W3M2-78 | p3 L1 E-B1 | `something that causes worry or problems` (*matter*) | D2 uses *matter* to mean a situation to deal with (`a small matter that I need help with`); the definition describes *trouble*: `a situation or subject you need to deal with` |
| W3M2-79 | p15 L4 E-B1; p31 L8 E-A | `There is an inn / unwind` fails on part of speech alone. L8 E-A distractors `equipped`, `estimated`, `capable` are taught nowhere in the book (*estimate*, *capable* are words the owner dropped on 30 Sep), and `mindful`, `stay` fail item 1 on part of speech | Use taught words of the same part of speech: `inn / circus show`; for L8, e.g. `personality / commitment / absence / courage` |
| W3M2-80 | Contents | `Remember to put periods . , commas , , and / or question marks ?` | `periods, commas, and question marks` (or US `and/or` with no spaces) |
| W3M2-81 | p2 L1 C Q1 (pre-filled) | `Could they confirm the booking?` | B asks `Could you please check my booking?`: `Could they check the booking?` |
| W3M2-82 | p1 L1 B | `But I still have not received the booking confirmation.` | `However, I have still not received the booking confirmation.` (a formal model) |
| W3M2-83 | p2 L1 D5 | `I missed my reservation at the restaurant because I overslept.` | `… because I was stuck in traffic.` |
| W3M2-84 | p6 L2 C Inspiration (pre-filled); p7 F-A Ideas | `saw a magic show for the first time at 10 years old`; `your journey to be a journalist` | `… for the first time at age ten` (B spells *ten*); `your journey to become a journalist` |
| W3M2-85 | p9 L3 B | `I hope this blog post can be useful.` | `I hope this blog post will be useful.` |
| W3M2-86 | p11 L3 F-A Ideas | `How I Got the Highest Score in Science Class` | Not a skill or an ability, which F-A and G ask for: `How I Learned to Ride a Bike` |
| W3M2-87 | p13 L4 B | `All tea is made from high-quality tea leaves.` | `All our tea is made from high-quality leaves.` |
| W3M2-88 | p14 L4 C (pre-filled row) | `have a picnic, walk, see sunset and sunrise, see fireworks` | `have a picnic, take a walk, see the sunrise or sunset, see the fireworks` (B's order and articles) |
| W3M2-89 | p15 L4 E-A3; E-B3 | `some ___ party decorations for today's party since we already spent …`; `perform at the circus show` | `some ___ decorations for today's party since we had already spent …`; `perform in the circus show` |
| W3M2-90 | p16 L4 H; p14 D2 | `begins with a title and short description.`; `The hotel's breakfast menu is diverse.` | `a title and a short description`; give *diverse* a wildlife or people example, as B does (`diverse wildlife`); a menu is *varied* |
| W3M2-91 | p17 L5 B photo; p18 C ① | The photo shows a grey-haired woman at press microphones; the only official is Mayor Peter Chavez (`He talked about …`). C box ① has no label, though boxes ② and ③ do | Use a photo that fits the mayor, or a park photo. Label box ① `Important Information (5Ws):` in C and F, as the callout names it |
| W3M2-92 | p21 L6 B dates | `March 16th, 2025`; leave from March 16th | 16 March 2025 is a **Sunday**, so the school or work leave starts on a Sunday. Use 2026 (a Monday), or other dates |
| W3M2-93 | p21 L6 B; p22 D3; Overview | `stay longer at the hospital`; `told me to stay at the hospital` | US English: `in the hospital` (see also W3M2-37, -66) |
| W3M2-94 | p23 L6 E-B1; p21 goal 2; p24 H | `to hurt the place where two bones are connected` (*sprain*); `transition words to express conditionals` | `to hurt a joint, such as an ankle or wrist, by twisting it`; the goal and H follow W3M2-56 (`to show that one thing depends on another`) |
| W3M2-95 | p22 L6 C; p23 F | `What Lena Plans to Do With Her Tasks` | Title case: `What Lena Plans to Do with Her Tasks` |
| W3M2-96 | p25 L7 B | Equipment lists a knife but no grater, though the carrots are `grated`; `100 grams sugar` next to `200 grams brown sugar`; callout `If the ingredient needs …`; callout `(e.g. large bowl, small pan), cooking times (e.g. until brown, 25 minutes)` | Add `grater`; `100 grams white sugar` (and step 3); `If an ingredient needs …`; `e.g.,` with B's own examples (`large mixing bowl`, `23 cm pans`, `35 minutes`) |
| W3M2-97 | p26 L7 C step 2 (pre-filled); p28 G | `2. Mix dry ingredients in a mixing bowl.`; G headings `What You Need:` / `What to Do:` against B `You will need:` / `What to do:`; G has no storage heading, though H gives storage 2 points | `2. Mix the dry ingredients in a large mixing bowl.`; one wording for the headings; add `Storage:` to G |
| W3M2-98 | p29 L8 B; p30 C event 2 (pre-filled) | `He ate quickly, like he was scared someone would take away his food.`; `He was left on the side of the street.`; `Marty was nervous and scared for the first three days.` | `… as if he was scared …`; `by the side of the road` (with W3M2-15); `Marty was scared and sat in the corner for the first three days.` |
| W3M2-99 | p32 L8 G | Pink circles sit behind the ✦ and 2 markers and look like extra plan markers that match nothing in F | Remove them, or make them clearly decorative (punched holes) |
| W3M2-100 | Overview, against the lessons | L1 `"dear" or "To Whom It May Concern."` (the callout is lower case); L1 example skips `I would like to solve this problem before my arrival.`; L1 and L6 `who you're writing to`; L3 `in your passage`; L4 `Hike through Lotus Hill Forest for amazing views` (B: `and enjoy amazing views`); L5 headline in title case (B: capitals); L8 `For the first three days, ….` as a time marker (not in the callout's list) | `"Dear" or "To Whom It May Concern"` in both places; mark the gap with `…`; `the person you're writing to`; `in your blog post`; quote B exactly; match the case; use `Before we took him home, ….` |
| W3M2-101 | back page | `Melody Publishing Co., Ltd. Copyright 2026. All rights reserved.`; the certificate does not name the book | `Copyright © 2026 Melody Publishing Co., Ltd. All rights reserved.`; `… for doing a wonderful job in G-Star Writer 3.` |

## Status of the 30 September first-draft findings

The mock rewrote most lessons. L7 has a new model text (a carrot cake instead of tacos). The checks
below cover the earlier findings that still apply.

**Fixed:** L1 contractions and `I've already booked … yesterday`; informal sign-offs (`best`,
`thank you`). L1 `as soon as possible as` is fixed, and `Address` is now `Opening Address`. L2's
autobiography callout (on p5) and `Many people came` are fixed. L3 `namely`, the fragment `For
instance, difficulty level …`, `reader's attention`, and the "challenging goals" contradiction are
fixed. L3 now defines transition words (`Transition words link ideas`). L4 `in the event of` is
gone, and *due to* is now modelled. L5 has `inverted pyramid`, `hiking, strolling, and dog-walking`,
and a quote slot in C. L6 `in the event that`, `so long as`, the misused `In case … I might`,
`attached with`, and the inflected word-bank form `detected` are all fixed. The L7 recipe quantities
are plausible now. L8's timeline contradiction, `Likewise … too` and `Throughout the first three days
… never` are fixed. The Contents' `Overview 33–34` now exists. The L4 E-B two-answer item is gone.

**Still open:** listed above as W3M2-15, -29, -31, -32, -33, -35, -39, -56, -64, -65 (partly) and -72.
Above-level words that remain unglossed: `refund`, `arrival` (L1); `stationery` (L3); `admiring`,
`stunning`, `footwear` (L4); `strolling`, `lift the ban` (L5); `notified` (L6); `responding` (L8). In
the lexical list, `in advance` and `souvenir` are SB1 words and `notify` is an SB2 word. So
`in advance` was wrongly called above the level on 30 Sep. `Notified` is in the syllabus but formal.

### Word Corner against the 30 September decisions (question for the owner)

On 30 Sep the owner accepted these replacements. The mock keeps some of the words the owner meant to
drop, and adds new words the owner did not list:

| Lesson | 30 Sep: replace → with (keep) | Mock 2 Word Corner | Differs |
| --- | --- | --- | --- |
| L1 | amenity→reservation, inquiry→refund, communicate→request (keep confirm, deposit) | confirm, matter, deposit, trouble someone to, miss (a) reservation | *refund*, *request* not added; *matter*, *trouble someone to* new |
| L2 | go the extra mile→career, recognition→award, remarkable→journey (keep contest, improve) | go the extra mile, contest, improve, skillful, award | *go the extra mile* kept; *career*, *journey* not added; *skillful* new |
| L3 | forgetful→progress, beginner's luck→tip (keep courage, course, tutor) | courage, forgetful, beginner's luck, course, tutor | *forgetful*, *beginner's luck* kept |
| L4 | capable→local, seek→attraction, bear in mind→unique (keep diverse, unwind) | circus show, diverse, inn, unwind, budget-friendly | *local*, *attraction*, *unique* not added; *circus show*, *inn*, *budget-friendly* new |
| L5 | patrol→report, penalty→fine (keep ban, authorities, crime) | ban, authorities, patrol, crime, fine | *patrol* kept; *report* not added |
| L6 | detect→leave (n), mourn→absence, inpatient→arrange, back on one's feet→recover (keep treatment) | cure, absence, worsen, sprain, back on one's feet | *back on one's feet* kept; *leave*, *arrange*, *recover*, *treatment* not used; *cure*, *worsen*, *sprain* new (note: *recover* is an SB4 word) |
| L7 | excess→ingredient, method→fry, estimate→serve (keep measurement, store) | measurement, batter, overmix, store, airtight | *ingredient*, *fry*, *serve* not added; *batter*, *overmix*, *airtight* new (see W3M2-68) |
| L8 | hardship→stray, mindful→shy, characteristic→personality (keep adopt, commitment) | stray, adopt, mindful, commitment, personality | *mindful* kept; *shy* not added |

None of the new words is in an earlier G-Star list, so the mock does not re-teach any word. If the
new lists were a deliberate editorial choice, this table needs no action. The E items were checked
against the lists as printed.

## Derived answer key (for the key writers)

Solved from the page. Items marked † depend on the fixes above.

| Lesson | E-A | E-B |
| --- | --- | --- |
| L1 | 1 b (trouble) · 2 a (deposit) · 3 c (missed the reservation) | 1 matter · 2 deposit · 3 confirm |
| L2 | 1 contest · 2 skillful · 3 improve | 1 c (goes the extra mile) · 2 a (award) · 3 b (improve) |
| L3 | 1 a courage · 2 c courses · 3 c forgetful | 1 beginner's luck · 2 tutor · 3 course |
| L4 | 1 diverse · 2 unwind · 3 budget-friendly | 1 inn · 2 budget-friendly · 3 circus show |
| L5 | 1 patrolled · 2 crime · 3 fines † (W3M2-01: *authorities* is also right as printed) | 1 crime · 2 banned · 3 authorities |
| L6 | 1 b absence † (W3M2-06) · 2 c worsening · 3 d cured | 1 sprain · 2 absence † (W3M2-04) · 3 back on one's feet |
| L7 | 1 measurement · 2 airtight · 3 store | 1 measurements · 2 batter · 3 overmixed † (W3M2-05) |
| L8 | 1 b personality · 2 c commitment · 3 a mindful | 1 adopt · 2 stray † (W3M2-03) · 3 mindful † (W3M2-02) |

Each item has one answer except where marked. In the word-bank items, exactly one bank word is left over, except L8 E-B (W3M2-02). L3 E-A, L4 E-B, L5 E-A, L7 E-B and L8 E-A are option items with no bank.

**C organizers** (the cells that students fill in):
- **L1:** Opening Address `To Whom It May Concern`. Problem: booked two rooms online and was charged,
  but has not received the booking confirmation. Q2 `If the booking is not confirmed, should she
  request a refund from the website or the hotel?` Q3 `How long will that take?` (detail: the
  booking is for next week). Closing: `Please let me know … Thank you for your help.` Sign-Off:
  `Sincerely, Natasha Cobbler`.
- **L2:** Ellie · 2000 · Tusk City · magician. 2018: first performance in front of an audience, at a
  school talent show; not everyone liked it, but she did not give up. 2020 (`Two years later`): began
  her own shows at the city park; at first only a few people came. Closing: still working hard to
  improve; wants to stand out in the world of magic and share its joy. Students must work out 2020
  from `Two years later`, which is a good reasoning step.
- **L3:** Headline `How I Learned Japanese Without Stress`. Opening `Guess who just got her language
  certificate in Japanese? Me!` No. 2 `Only buy what you need.`: don't rush to buy textbooks,
  courses and stationery; she uses two textbooks. No. 3 `Set goals that you can reach.`:
  challenging but not too difficult, and clear (`learn 10 new words this week`). No. 4 `Have the
  courage to speak and write in the language.`: record yourself, keep a diary, find pen pals, join
  language exchange groups.
- **L4:** Title `Experience the Wonderful City of Greybridge`. Description `Enjoy nature, creativity,
  and comfortable city life on your vacation.` Peak Tea House: beautiful, historic; drink fresh tea,
  reserve a table. Greybridge Museum: modern; look at artwork, make chalk drawings at the Art Wall.
  Fern Safari Park: diverse, special; see wildlife, meet animals at the petting zoo, buy souvenirs.
  Scale Shopping Square: massive; shop for jewelry, relax at a spa. Tip 2: bring an umbrella, because
  of occasional rain (see W3M2-63).
- **L5:** Headline `MAYOR BANS CAMPING IN BIRCH FOREST PARK`. Where: Birch Forest Park (Rift City).
  When: starting today. Details: more than ten announcements warned people not to leave equipment and
  garbage; posters went up where people fed squirrels and other animals; neither stopped the damage.
- **L6:** Date `March 16th, 2025`. Absent: March 16th–18th, perhaps until the 20th. Reason: sick for
  two days, so the doctor asked her to stay at the hospital. Tasks: Alex and Jane will take over her
  work. Contact: `lenadiaz@email.com`; she will answer emails as long as she feels well enough.
  Ending: `Thank you for your understanding. I hope I can return soon.`
- **L7:** Title `How to Make a Carrot Cake`. Question `Are you looking for ways to make carrots less
  boring?` Description `Try this delicious carrot cake … perfect for beginner bakers.` Cake: the 11
  ingredients. Frosting: cream cheese, butter, powdered sugar. Equipment: the 7 items. Steps 3–8.
  Storage: an airtight container, up to 3 days, in the fridge.
- **L8:** What happened: met Marty, a small, thin dog Mrs. Jenkins was looking after. When and where:
  a sunny Sunday afternoon, walking around the neighborhood (Mrs. Jenkins' yard). Who: Mom, Dad, the
  narrator, Mrs. Jenkins, Marty. Event 3: after two weeks, Marty asked to play by bringing his toys,
  began responding to his name, and Mrs. Jenkins visited with treats and toys. Reorientation: three
  weeks on, Marty and the family are comfortable with each other; he is smart; the narrator is glad.

## Checked and correct (negative controls)

- **Page numbers** 1–34 run in order, and the Contents ranges match the lessons. Each lesson is four
  pages, and the lesson tabs are right.
- **Every H rubric totals 10:** L1 1+1+2+2+1+1+2, L2 1+2+2+2+1+2, L3 1+1+1+1+2+2+2, L4 1+3+1+2+1+2,
  L5 1+2+2+1+2+2, L6 1+3+2+2+2, L7 2+2+2+2+2, L8 2+2+2+1+1+2.
- **Every F organizer repeats C's boxes** except L7 (W3M2-71), and the G frames' markers (✳ ★ in L1, ● ■ in L6, ✦ 1 2 3 ⬟
  in L8, 1 2 3 in L5) match F's.
- **Callout leader lines** point at the right text on every model page.
- **Grammar allowed by the SB3-up-to-lesson-k rule:** participle phrases in L2 (`Born in Tusk City`,
  `Watching the magician`; SB3 L2); relative clauses in L3 (SB3 L3); reported statements in L5, L6
  and L8 (SB3 L4); `asked me to stay` in L6 (SB3 L6); the past perfect in L5 (SB3 L5); `had him
  checked` and `Both Mom and Dad` in L8 (SB3 L8). `Symptoms` in L6 is an SB3 L6 word.
- **Story facts agree:** born 2000, aged ten in 2010, first show in 2018, two years later 2020 (L2).
  The festival is in November, inside September–March (L4). Leave from 16 to 18 March in a letter
  dated 16 March (L6). Met Marty, asked, the vet, then three weeks (L8).
- **Text-layer artefacts** that are correct on the page and are not findings: `agree d`, `barke d`,
  `calle d`, `some one`, `takin g` (L8), `tothrequest` (Overview L6).
- **American spelling** is consistent (neighborhood, jewelry, practicing, color). `omelette` (L7
  Ideas) is an accepted US variant.

## Summary

- **4 Practice items would give wrong or double keys:** L5 E-A3 has two right answers (01); L8 E-B3
  has no right answer, because *mindful* is defined wrongly and *personality* does not fit (02); L6
  E-B2 defines a noun as a verb (04); L7 E-B3 teaches a false cause (05).
- **4 contradictions or wrong pre-filled answers:** `Lena will take over my work` (06), `2010` printed
  in the student's L2 plan (07), and two L5 C cells that misreport the article (08, 09).
- **12 errors in the English, 2 missing full stops, and 6 Overview or back-page errors.** The Overview
  calls Lesson 4 *Narrative Writing* (24) and lists `authority` for `authorities` (77).
- **6 syllabus breaches of rules already decided:** *neither … nor* and *both … and* in L5 (29, 30);
  *given* (31); *throughout* (32); *performance* in L2 (33); *extend* in L6 (34).
- That makes **34 must-fix items**. There are also **67 recommendations** (03, 35–76, 78–101),
  including the L8 photo of a big golden retriever for "a small, thin dog" (62), a letter dated on a
  Sunday (92), and a recipe that grates carrots with no grater (96).
- **Question for the owner:** the Word Corner lists differ from the replacements agreed on 30 Sep, in
  every lesson (see the table above).
