# Design review \u2014 after the teaching went in

The Climb, KS2 maths. 7 September 2026. Second review, on the build where every stop teaches.

## The fix worked, and it created a new problem

All 47 stops now teach before they ask. That was right and it was the whole job. But look at what it costs to reach a question:

| | screens before the first question |
|---|---|
| Long division | **14** |
| Median stop | **8** |
| Adding in columns | **8** |
| Mean | 8.6 |

**A child who opens *Adding in columns* to practise column addition sits through eight screens first** \u2014 two of story, three of worked example, three of guided \u2014 before answering anything. They may already be able to do it. They may have been sent there by the check five minutes ago and want to get on with it.

I said in the last review that not every stop needs a story, that *Adding in columns* does not need one, and then I gave it one anyway. Applying the same four phases to all 47 stops is the same mistake as giving every stop the same number of questions.

**Two fixes, and they are cheap:**

**A door past the teaching.** On the story screen, a quiet second button: *I know this \u2014 let me practise*. Not hidden, not shameful, and it lands them in the drill. A child who is wrong about knowing it will find out in two questions and can walk back.

**And let the drill send them back.** Get three wrong in a stop and offer *Show me how* rather than only flashing the reason. At the moment the teaching is a gate at the front rather than something you can return to.

## The frequency labels flattened

The last review said the shelf rows all looked the same weight, so I put a label on each. Now:

| | |
|---|---|
| The ground you stand on | comes up sometimes |
| Arithmetic you can trust | **comes up a lot** |
| The two long methods | comes up often |
| Fractions, decimals, percentages | **comes up a lot** |
| Shapes, measuring and sharing | **comes up a lot** |

**Three of five camps say exactly the same thing.** Three phrases across five rows, and *a lot* / *often* / *sometimes* are not distinguishable to a ten-year-old anyway \u2014 they are the same word wearing different hats.

Either drop the labels and let the description do the work, or give the row something a child can actually read at a glance: a row of three, two or one filled dots. Dots are honest about being approximate, which words pretending to be precise are not.

## The visual design held

Nothing drifted while the file grew from 76 KB to 126 KB:

| | before | now |
|---|---|---|
| Literal px font sizes | 1 | **1** |
| Border radii | 7 | **7** |
| Hex colours | 16 | **16** |
| `!important` | 2 | **2** |

That is worth noting because it is the exact opposite of what happened to the Fulfulde course, which reached 218 colours and 344 `!important` by accreting one small change at a time. Adding 50 KB of content without adding a single colour is the system working.

## Three smaller things

**Only three emoji across every story, and they never repeat within one.** They read as illustration rather than decoration \u2014 the mango, the wall, the taxi. Leave this alone.

**The stories are 2 or 3 screens and the guided examples 3 or 4, with no reason for which is which.** It is the difference between an authored course and a generated one. Pick a shape and hold it: two story screens, three guided steps, unless the maths genuinely needs a fourth.

**Seven *why?* buttons on a full worked example.** Each one is right on its own; seven small grey pills down the side of a screen reads as clutter. Consider one *why?* at the foot that expands all of them, or showing the reason only for the step just revealed.

## What is still not fixed from the last review

**Nothing accumulates.** A stop still ends on a tent and a score, and the shelf gains a tick. There is no collection, no total, nothing that makes finishing the eleventh stop feel different from finishing the first.

**The characters do not come back.** Fatou appears for two screens and vanishes, including from her own stop's practice. A returning character is worth more than an introduced one, and it costs a line per stop.

## What I would do, in order

**1. Add *I know this \u2014 let me practise* to the story screen.** One button, and it removes the main cost of what we just built.
**2. Let three wrong answers offer *Show me how*.** Teaching should be reachable from inside the practice, not only before it.
**3. Replace the frequency words with dots.** Three phrases for five camps is not information.
**4. Regularise the phases:** two story screens, three worked steps, three guided.