
*Also refer to [For Loop](/code-blocks/miscellaneous/run/for-loop.md), [Loop Through Table](/code-blocks/miscellaneous/run/loop-through-table.md)*

# Making a debounce script

## Introduction

You make a simple script that when you touch, it gives you a tool!

You test it out, but the script rapidly and spontaneously giving tools. That's because you don't have a debounce part of your script.

### How to make it

To make a debounce script, we need to create a variable. This variable will track when the tool has been touched and on cooldown or not. Then, before the event block, you want to set the variable to false,
to first, indicate that the part hasn't been touched when the game loads, and second, to allow the following if statement to work. Just after the event block, add an if statement. Now, we're going to set the first
parameter of the if statement to be the variable we just created. The second parameter will be set to false. (Click the dropdown menu, select "Bool" then type in the name of your variable) After, insert your code for
whatever you want to do! 

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
