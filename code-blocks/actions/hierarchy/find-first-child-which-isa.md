---
description: >-
  Runs the connected block only if the given object has a child with the given
  super class.
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

# Find First Child Which IsA

## Description

Runs the connected block only if the given object has a child with the given super class.

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### Parent (Object)

You give the path to an object.

* [x] Can use Variable

```
workspace
```

#### ChildClass (String)

You give the block the ClassName of a object that you are looking for.

* [x] Can use Variable

```
BasePart
```

## Outputs

#### Result (Object)

You give the block the variable you want the found object to be saved to.

```
Part
```
