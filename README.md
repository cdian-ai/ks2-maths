# KS2 maths

A revision app for the Key Stage 2 maths tests. Years 5 and 6, ages 9 to 11.
One HTML file, no build step, no backend, no dependencies. English and French.

## What it is built from

Not the programme of study. **The 2025 and 2026 mark schemes** — every question
in all six papers, tagged by the Standards and Testing Agency with the content
domain it assesses. 177 questions. The subtopics that carry the most marks get
the most time, and nothing is included because a syllabus lists it.

Two things that came out of that count and shaped everything:

- Calculation and fractions are **56% of the paper** between them.
- **Nearly a third of the paper is Year 3 and Year 4 content.** The single
  most-asked code across both years is `4C6b`, a Year 4 objective. A course
  that teaches only Y5 and Y6 walks past a third of the marks.

## How it works

**Five topics, 47 subtopics, 486 questions.** Questions are generated rather
than listed, so a subtopic a child returns to is not the same twenty sums, and
each one names the content-domain codes it serves so the weighting can be
checked rather than trusted.

**Every subtopic teaches before it asks.** A video explains it; a jump index
under the player lets a child re-enter at the exact step that broke; a quick
reminder card carries the bare steps for checking mid-question; then practice,
one question at a time, on a keypad — because Paper 1 is 36 constructed
answers and offering four options would train the wrong skill.

**The arithmetic paper** is the real format: 36 questions, 40 marks, 30
minutes, long multiplication and long division worth two each and placed late.

## The videos

`vid/` holds them. 70 films: 35 subtopics × English and French.
Scripts and timecodes are in `scripts/`.

Attaching one is a single line in `index.html`:

```js
VIDEO.longDiv = { en:"vid/longDiv-en.mp4", fr:"vid/longDiv-fr.mp4" };
```

Until a film exists the subtopic shows its full written explanation instead, so
the app is usable while you record and you can record in any order.

The scripts were generated from the app's own teaching data, so a script and
the subtopic it explains cannot drift apart. Change a line in the app and
regenerate rather than editing the script.

## Running it

Open `index.html`. That is all. Progress is kept in the browser on the device.

## Files

    index.html        the whole app
    vid/              explainer videos (70 when complete)
    scripts/          video scripts, English and French, with timecodes
    docs/             the evidence the course was built on, and the design reviews

## Still to do

- Record the 70 videos and replace the estimated timecodes with real ones
- Geometry and statistics are under-weighted against the papers: 2.5% and 1.6%
  of the course against 7.4% and 5.6% of the test. Pie charts, line graphs,
  co-ordinates, reflection and translation need a drawn grid rather than a
  keypad, which is a different kind of screen from anything built so far.
- The app has a placeholder name.
