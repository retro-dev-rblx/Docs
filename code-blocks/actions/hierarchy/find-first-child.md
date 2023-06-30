---
description: >-
  Runs the connected block only if the given object has a child with the given
  name.
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

# Find First Child

## Description

Runs the connected block only if the given object has a child with the given name.

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

#### ChildName (String)

You give the block the name of a object.

* [x] Can use Variable

```
Tree
```

#### Recursive (Bool)

Whether or not the search should be conducted recursively.

* [x] Can use Variable

```
false
```

## Outputs

#### Result (Object)

You give the block the variable you want the found object to be saved to.

```
TreeModel
```
