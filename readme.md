## What is a Code Retreat? (10 min)

Corey Hanes is a visionary in the software development community.  Since 2009, he has been running Code Retreats all around the world.  Why?  What is it?

Play video (to 04:00): http://coderetreat.org/about

Q. Why would we, as developers, attend a Code Retreat?
---

> Getting away from the pressures of getting things done.

> Mammals learn through play.

> To focus on doing the "right" thing. This is way more important that getting something working.

> There is a gap between how you think you should code and how you are “forced” to code in the workplace.  That gap, is a measure of how much you suck.

## Why? (5 min)

> After attending and facilitating more than 50 code retreats, I've become convinced that it is a valuable way to disseminate the idea and implementation of focused practice. - Corey Haines


### Practice

Actors practice. World class athletes get there through practice.  When do we practice?  We don’t.  We’re always on stage.

- Practice doesn’t makes perfect.
- *Perfect* practice makes perfect.

### Development is not rote.

Development is not rote. There isn't a series of steps to follow to do Git right. We could give steps for specialized situations, but we can only cover a small subset. You are much better off learning how to read the situation, understand where you are AND where you need to go, and pick the appropriate tool.

- read the situation,
- understand where you are AND where you need to go, and
- pick the appropriate tool.



## Code Retreat style (10)

Push yourself to do what you have been skipping.  Take your time.

1. You will work on the problem for 25 minutes.
- We will discuss what you have learned.
- You will delete the code.  Throw it away.  **Yes, ALL of it.** This is an important step.
- Switch to a different pair partner.
- Lather, rinse, repeat (with the next variation)

We should make it through 4 variations.

### Variations

1. Pseudo code first.  Really feel like you have a handle on what to code before you pick up the keyboard.  If you've done this before, do it again.  This is practice.  Make it cleaner, clearer, more exacting, or more concise.
- Skip pseudocode.  Only code for the easy cases, up to 1000.  Ignore 4, 9, 40 etc.
- Switch programming methods.  If you've been following OOP, don't for this one (only variables and functions).  If you haven't used OOP, use it religiously this time.
- Follow [Sandi Metz’ Rules](https://robots.thoughtbot.com/sandi-metz-rules-for-developers)


## Sandi Metz' Rules
1. Classes/Objects can be no longer than 100 lines of code.
2. Methods can be no longer than five lines of code.
3. Pass no more than four parameters into a method. Hash options are parameters.

## What is the problem? Romanize (120 min)

We are going to be converting Arabic numerals to Roman numerals.
https://github.com/ga-wdi-exercises/romanize

This repo has some specs prepared for you: https://github.com/ga-wdi-exercises/roman_js

Use either.

Reminder. You are not supposed to finish.  You are supposed to practice.

Now, start the first, of many, [variations](#variations).

---

## Resources:

- http://coderetreat.org/about
- Global Code Retreat http://gdcr.coderetreat.org

## Other variations

- Only code for the "hard" numbers (4, 9 40, 90).  Your romanize() function should only work for these numbers.
- No mapping tables.  Only algorithms
- Follow 4 Rules of Simple Design

## Four Rules of Simple Design
1. Tests Pass
2. No Duplication (every piece of knowledge has one canonical representation)
3. Reveals Intent (good naming)
4. Small
