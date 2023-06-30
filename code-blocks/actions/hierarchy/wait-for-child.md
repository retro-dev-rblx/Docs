---
description: >-
  Wait until the given object has a child with the given name, and then run the
  connected blocks.
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

# Wait For Child

## Description

Wait until the given object has a child with the given name, and then run the connected blocks.

#### Available to

* [x] Scripts
* [x] LocalScripts
* [x] Yields

## Inputs

#### Parent (Object)

You give the path to an object.

* [x] Can use Variable

```
workspace
```

#### ChildName (String)

You give the block the Name of a object that you are looking for.

* [x] Can use Variable

```
Tree
```

#### TimeOut (Number)



* [x] Can use Variable

```
5
```

## Outputs

#### Result (Object)

You give the block the variable you want the found object to be saved to.

```
TreeModel
```
