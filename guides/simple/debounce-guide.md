---
description: A simple guide on how to make a debounce script.
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

# Making a debounce script

## Introduction

You make a simple script that when you touch, it gives you a tool!

You test it out, but the script rapidly and spontaneously giving tools. That's because you don't have a debounce part of your script.

### How to make it

To make a debounce script, we need to create a variable. This variable will track when the tool has been touched and on cooldown or not. Then, before the event block, you want to set the variable to false,
to first, indicate that the part hasn't been touched when the game loads, and second, to allow the following if statement to work. Just after the event block, add an if statement. Now, we're going to set the first
parameter of the if statement to be the variable we just created. The second parameter will be set to false. (Click the dropdown menu, select "Bool" then type in the name of your variable) Next, set the variable back to  After, insert your code for whatever you want to do! The next step is to add the actual delay, and to set the variable back to false.

<img width="327" alt="image" src="https://github.com/retro-dev-rblx/Docs/assets/75546373/f2d780e7-bd73-481b-8059-1867d5cb2b2b">

### How does it work?

The very first set variable makes it so the cooldown is off when the game first loads. The if statement runs when the event block is fufilled, (ex: once part is touched, when remote event is received, etc.) and
if the cooldown is on. If it is on, it prevents the script from continuing further and cause the rapid and spontaneous burst of tools. The wait is to actually add the cooldown part of the script. The final set
variable is to turn the cooldown back off.
