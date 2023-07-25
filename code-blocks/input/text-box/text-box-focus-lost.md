---
description: >-
  Runs the blocks connected to it when the given TextBox is no longer focused.
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

# Text Box Focus Lost

## Description

Runs the blocks connected to it when the given TextBox is no longer focused.

#### Available to

* [ ] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### TextBox (Object)

You give the path to a TextBox.

* [x] Can use Variable

```
gui.Frame.TextBox
```

## Outputs

#### EnterPressed (Bool)
You give the block the variable you want if enter was pressed to be saved to.
```
EnterPressed
```