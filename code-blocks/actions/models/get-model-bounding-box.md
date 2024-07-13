---
description: >-
  Gives the size, rotation and position of a box containing all the parts in a
  model.
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

# Get Model Bounding Box

## Description

Gives the size, rotation and position of a box containing all the parts in a model.

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### Model (Object)

You give the path to an object that you want go get the bounding box.

* [x] Can use Variable

```
workspace.Tree
```

## Outputs

#### Position (Vector3)

Returns the Center Position of the model bounding box.

```
20,30,10
```

#### Rotation(Vector3)

Returns the Rotation of the model bounding box.

```
45,90,180
```

#### Size (Vector3)

Returns the Size of the model bounding box.

```
5,10,5
```
