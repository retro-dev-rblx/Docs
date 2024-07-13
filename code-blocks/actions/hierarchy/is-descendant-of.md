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

# Is Descendant Of

## Description

Returns a boolean on whether or not the given object is a descendant of another object

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### Ancestor (Object)

You give the path to an object.

* [x] Can use Variable

```
script.Parent.Part
```

#### Descendant (Object)

You give the path to an object.

* [x] Can use Variable

```
workspace
```

## Outputs

#### OutputValue (Bool)

You give the block the variable you want the result to be saved to.

```
IsDescendant
```
