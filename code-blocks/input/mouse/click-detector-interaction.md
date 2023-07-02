---
description: >-
  Runs the connected blocks when a ClickDetector is pressed.
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

# Click Detector Interaction

## Description

Runs the connected blocks when a ClickDetector is pressed.

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### ClickDetector (Object)

You give the path to a ClickDetector.

* [x] Can use Variable

```
workspace.Baseplate.ClickDetector
```

#### InteractionType (Choice)

You give the block the type of interaction with the ClickDetector.

* [ ] Can use Variable

```
Clicked
```

## Outputs

#### Player (Object)
You give the block the variable you want the path to the object of the player who interacted with the ClickDetector to be saved to.
```
ClickedPlayer
```
