# Design review \u2014 why it feels like a worksheet

The Climb, KS2 maths. 7 September 2026. On the charge that it does not feel like it is for children.

## The charge is right, and here is the evidence

I measured what a child can actually *do* in this app.

| | |
|---|---|
| Ways to answer a question | **2** \u2014 type a number, or tap from a list |
| Questions answered by typing a number | **40 of 42 question types** |
| Anything that can be dragged | **0** |
| Anything that can be cut, drawn, coloured or built | **0** |
| Anything with sound | **0** |
| Animations | **0 keyframes** |
| Strings that encourage the child | **0 of 224** |

Nought for encouragement is the one that stopped me. Two hundred and twenty-four things this app says to a child, and **not one of them is a kind word.** Not "nice one", not "that is the one everybody gets wrong", not "you have got this now". It explains, it asks, it marks. It never reacts.

**What happens when a child gets an answer right:** the counter goes up and the next question appears. That is the entire reward, 486 times.

## The real problem is not decoration

It would be easy to read the above as "add confetti". That is not the diagnosis.

**The diagnosis is that this app talks about maths a child cannot touch.**

Look at what the stories promise and what the screen delivers:

- *A pizza cut into 8. You eat 3 slices.* \u2014 the child never sees a pizza, never cuts one, never takes a slice. They read a sentence about pizza and then type 5/8.
- *Fatou has 486 mangoes, 18 to a box.* \u2014 no mangoes, no boxes.
- *Picture it as rows of one-metre squares: 5 rows of 8.* \u2014 the app literally says *picture it*, because it will not draw it.
- *24 tiles. Can you lay them in a perfect rectangle?* \u2014 you cannot lay anything. You tap numbers from a list.

Every single story is **a picture that was never drawn**. I wrote "picture it" into the teaching because I knew the image was needed and I gave the child a sentence instead. For nine to eleven year olds, maths is still concrete: fractions are cut, arrays are arranged, place value is moved between columns. A course that describes manipulation without offering it is a textbook with a keypad on the end.

**This is one change, not many:** make the worked examples *show*. A pizza that visibly divides. Digits that slide one place left when you multiply by ten. 24 tiles that snap into 4\u00d76 and refuse to snap into 5\u00d7anything. The maths does not change and the teaching does not change \u2014 the child stops reading about it and starts watching it happen.

## Nobody is speaking to the child

224 strings. **35 say "you". 9 ask a question. 0 encourage.** The voice throughout is a narrator explaining a method to nobody in particular:

> *Multiplication happens first, wherever it sits.*
> *The remainder must be smaller than 4.*
> *Angles sitting on a straight line always add to 180.*

Every one of those is well written and none of them is addressed to a person. Compare what a good teacher actually says: *"Careful \u2014 this is the one everyone gets wrong."* *"You already know 3 sevens. That is the whole trick."* *"Look what happens when I move it."*

The second person, a warning before a known trap, and a reaction after an answer. None of the three exist in this app.

## The palette belongs to a productivity tool

--ink #1B2430 \u00b7 --muted #8494A4 \u00b7 --paper #F7F9FA \u00b7 --band #4E8C6A

Slate, granite, moss. It is restrained, it is coherent, and **it is the colour scheme of a note-taking app for adults.** The smallest type on screen is 9px. I built a design system for someone reading a dashboard and then wrote children's copy inside it.

This does not mean primary colours and cartoon fonts \u2014 ten and eleven year olds resent being talked down to more than any other age. It means the restraint is currently indistinguishable from austerity, and one warm, saturated accent used only for the child's own progress would change the temperature without making it babyish.

## What I would actually build, in order

**1. Draw the worked examples.** Not all 47 at once \u2014 the eight where the picture *is* the explanation: fractions, place value, area, arrays, volume, angles, ratio, the number line. This is the fix. Everything else on this list is small beside it.

**2. Say something when the child is right.** A short, varied, non-saccharine line. Ten of them, rotated, so it does not become wallpaper. And one specific line for a question they got wrong before and have now got right \u2014 that is the moment worth marking.

**3. Warn before the known traps.** The mark schemes told us what children get wrong: adding denominators, forgetting the zero row, 7\u00b2 = 14, forgetting to halve the triangle. The app knows all four and says none of them before the child falls in.

**4. Give the right answer a reaction.** Not confetti \u2014 the answer landing, the counter ticking, something that acknowledges a person did something. Currently the screen changes as if a form was submitted.

**5. Turn the running total into something.** A number that goes up is not a collection. The five camps could each fill in as their stops are finished \u2014 progress you can see the shape of rather than count.

## What to keep

The teaching itself is good and should not be touched. Fatou and the mangoes, the builder's wall explaining the zero row, the taxi with one child left standing \u2014 those are properly taught. **The problem is not that the course does not teach. It is that it teaches and then never plays.**