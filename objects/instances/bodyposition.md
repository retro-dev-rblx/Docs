---
description: >-
  The BodyPosition Instance applies a force onto the basepart it is parented to in such a way that it will maintain a constant position in the workspace.
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

# BodyPosition

#### Description

The BodyPosition object applies a force on a BasePart such that it will maintain a constant position in the world.
  The Position property, not to be confused with BasePart.Position, controls the target world position.
  This is the translational counterpart to a [BodyGyro](bodygyro.md). 
  If you need further control on a force applied to an object, consider using a [BodyForce](bodyforce.md) or [BodyThrust](bodythrust.md) instead.

#### Available to

* [x] Early 2009
* [x] Late 2009
* [x] Late 2010
* [x] Early 2011
* [x] Mid 2011
* [x] Late 2011
* [x] Early 2012
* [x] Mid 2012
* [x] Late 2012
* [x] Early 2013
* [x] Mid 2013
* [x] Late 2013
* [x] Early 2014
* [x] Mid 2014
* [x] Late 2014
* [x] Early 2015
* [x] Mid 2015

## Data

#### ClassName (String)

* [ ] Editable without script
* [x] Read only

```
BodyPosition
```

#### Name (String)

* [x] Editable without script
* [ ] Read only

```
BodyPosition
```

#### Parent (Object)

* [ ] Editable without script
* [ ] Read only

```
workspace
```

## Behavior

#### Archivable (Boolean)

* [x] Editable without script
* [ ] Read only

```
true
```

## Goals

### D (Number)

* [x] Editable without script
* [ ] Read Only
      
```
500
```

### P (Number)

* [x] Editable without script
* [ ] Read Only

```
3000
```

#### maxForce (Vector3)

* [x] Editable without script
* [ ] Read only

```
4000, 4000, 4000
```

#### position (Vector3)

* [x] Editable without script
* [ ] Read only

```
0, 0, 0
```
