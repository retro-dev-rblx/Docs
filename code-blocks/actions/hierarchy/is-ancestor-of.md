---
description: >-
  Returns a boolean on whether or not the given object is a descendant of
  another object
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

# Is Ancestor Of

## Description

Returns a boolean on whether or not the given object is a descendant of another object

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### Descendant (Object)

You give the path to an object.

* [x] Can use Variable

```
workspace.Player.Humanoid
```

#### Ancestor (Object)

You give the path to an object.

* [x] Can use Variable

```
workspace
```

## Outputs

#### OutputValue (Bool)

You give the block the variable you want the result to be saved to.

```
IsAncestor
```
