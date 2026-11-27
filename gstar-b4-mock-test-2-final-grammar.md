# Control: G-Star Book 4, Mock Test 2, final — grammar and words

Hand proofread on 27 November 2026, against **SB4 Lessons 5–8**, the second half of the book. Keys
and sentences are in `gstar-b4-mock-test-2-final.md`; texts in `gstar-b4-mock-test-2-final-texts.md`.

**How it was checked.**
- **Grammar:** by hand, against the SB4 L5–8 grammar points. These are taken from the 2 November
  report, which read them from `data/transcriptions/gstar-sb-4/lesson-6.json` to `lesson-9.json`
  (the files are offset by Review 1). I did not re-read those files this round.
- **Words:** a `grep` over the book's text layer and the audioscript for each of the 40 words,
  allowing inflections.
- **Forward reference:** a `grep` for *should / could / would have*, *wish*, modal passives,
  *which* clauses and the past perfect continuous, plus a hand read.
- Nothing paid ran.

★ marks a misuse of the lesson's own target grammar.

## The lessons' grammar

| SB4 lesson | Grammar | Used correctly? | Tested? |
| --- | --- | --- | --- |
| L5 | passive continuous; *be able to* | `It's being prepared for delivery`, `Will you be able to carry it inside`, `The solder was able to stick properly` ✓ | No item |
| L6 | tag questions | `That's you, isn't it?`, `You paid by card, didn't you?`, `You're taking this pretty seriously, aren't you?`, `It is unusually hot today, isn't it?`, `That's a lot of training, isn't it?`, `You didn't check …, did you?` ✓. ★ `your boss had offered you a promotion, didn't he?` | No item |
| L7 | third conditional; sense verb + object + *-ing* / base form | `If I'd accepted the offer, I would've had even more responsibilities`, `If Scott hadn't given me such helpful advice, I would not have succeeded`, `If you had started earlier, you would have had more time`, `I heard my brother knocking on the door` ✓ | Q19, Q23 (comprehension of a third conditional) |
| L8 | present perfect continuous; indirect objects | `I've been baking a lot lately`, `I've been training all week`, `I have been practicing simple recipes`, `I can lend you some money`, `promise me free coffee`, `sent me a step-by-step guide`, `gave us some water` ✓ | Q6 and Q22 (comprehension) |

## Must fix

| Id | Where | Finding | Suggested change |
| --- | --- | --- | --- |
| B4M2F-G01 | Audio Part 4 Q21–25 ★ | `your boss had offered you a promotion, didn't he?` The past perfect takes a *hadn't* tag, and the simple past is what is meant (B4M2F-A01) | `your boss offered you a promotion, didn't he?` |

## Should fix (forward reference, all read or heard only)

| Id | Where | Finding | Suggested change |
| --- | --- | --- | --- |
| B4M2F-G02 | Audio Part 4 Q18–20 | `I shouldn't have yelled at you`, `You should have told me about it`: *should have* + past participle is SB6 L5 | `I'm sorry I yelled at you.`; `If you had told me, I would have helped you.` (L7) |
| B4M2F-G03 | Audio Part 4 Q18–20 | `I just wish you had been more honest with me`: *wish* + past perfect is SB5 L4 | `You should be more honest with me.` |
| B4M2F-G04 | p9 Part 6; p13 Part 7; audio Part 3 | The modal passive (SB5 L2): `should be checked by a healthcare professional`, `habits can be changed`, heard `will be divided`, `will be posted` (2 November C02, fewer now) | `a doctor should check them`; `you can change habits`; `We will divide you into three groups` |
| B4M2F-G05 | p12 Part 7 | `which can lead to mistakes and stress`: a sentence-final *which* clause is SB5 L3 (2 November C03) | `This can lead to mistakes and stress.` |
| B4M2F-G06 | Audio Part 4 Q21–25 | `I thought you'd been hoping for that promotion`: the past perfect continuous is in no G-Star heading | `I thought you wanted that promotion!` |

## Words

**All 40 SB4 L5–8 words appear.** The least-used are `make fun of`, `lose one's temper` and
`peaceful`, twice each.

| Lesson | Words |
| --- | --- |
| L5 | deliver, disturb, extend, make fun of, carry out, responsible, book club, membership, package, preparation |
| L6 | allergic reaction, food poisoning, unusual, severe, concerned, diagnose, infection, nauseous, faint, recover |
| L7 | lose one's temper, depend on, succeed, insist, take notice (of), carry on, sensible, diligent, advise, assistance |
| L8 | train, keep up with, put off, apart, complaint, ecstatic, troublesome, issue, peaceful, offer |

**The grammar is used throughout, but no item makes the student choose a form.** Parts 5 and 9
test words only. In 2 November's version, too, the grammar was only modeled. These are possible
gap items:
- a tag: `It's hot today, ___?` (`isn't it / is it / doesn't it / wasn't it`);
- a third conditional: `If I ___ earlier, I would have finished` (`had started / started / have started / would start`);
- a passive continuous: `The package ___ prepared now` (`is being / is been / being / was be`).

## Fixed since 2 November

- C01: *You could've sent me a message* is gone.
- C03: the *which* clause in Q33 D (the key) is gone.
