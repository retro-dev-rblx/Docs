---
description: An introduction to looping scripts.
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


### While Loops

Well, what if you need something that lasts infinitley? A while loop lasts forever, which can be pretty useful in some cases.

This time, we'll be making a health monitor. Make sure to insert a local script instead of a regular one.

First, get your player by adding a `Set Variable` block to `game.Players.LocalPlayer`. I'll name the variable to "Player".
Next, insert your `While Loop` block, you don't need to change any properties because `nil` already equals `nil`.
Connect a wait block to the loop and set the time to 0 seconds. **DO NOT FORGET TO ADD THIS BLOCK OR ELSE YOUR GAME WILL CRASH.**
Then, get your health from the character. Connect a `Get Object Property` block. Set the object to `Player.Character.Humanoid` and set the property to `Health`. You can name the health variable anything you want, but I'll set it to "Health". Next, print out the `Health` variable and you're done!

<img width="191" alt="image" src="https://github.com/trademark-living-his-best-life/Docs/assets/93290253/c86c27ad-071f-43a5-b61e-f72a0b38f17c">

Nice! Now you have a basic health monitor.

<img width="224" alt="image" src="https://github.com/trademark-living-his-best-life/Docs/assets/93290253/87ece037-326c-4783-be7a-282af951aaea">

