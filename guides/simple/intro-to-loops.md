---
description:
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---
*Also refer to [For Loop](/code-blocks/miscellaneous/run/for-loop.md), [Loop Through Table](/code-blocks/miscellaneous/run/loop-through-table.md)*

# Loops

## Introduction

Let's say you need to automate something, like giving weapons to a team of players. Loops can automate tasks that could usually take longer when drawn out.
You can use loops for many different things, such as rounds for a game, timers, and much more.

For this guide, I'll be showing examples of all the different loops, and how you can use them.

### For Loops

Like I mentioned before, we can use the `For Loop` block for timers.

We'll start by counting down by 100. Set the `Initial` value to 100, set the `Increment` value to -1, and set the `Maximum` value to 0.
This makes it so you start at 100 and begin adding -1 (subtracting 1) to 100.
Set the `Place` output (what number the loop is currently at) to what ever name you want. I'll set it to "Place".

Now, connect a wait block and keep the `Time` value to it's default. Then connect a print block and set the text as a variable, and type your variable name.

Good job! Now you've made an easy timer.

<img width="132" alt="image" src="https://github.com/trademark-living-his-best-life/Docs/assets/93290253/3da8cbe3-b863-4557-bab1-60486d0eaa97">

Other examples where you can use the `For Loop` block for are:

* Typewriter text
* Stopwatch
* Moving multiple parts at once