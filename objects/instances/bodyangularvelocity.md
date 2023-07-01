---
description: >-
  The BodyAngularVelocity object applies a torque (or rotational force) on a
  BasePart. See page for more information.
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

# BodyAngularVelocity

#### Description

The BodyAngularVelocity object applies a torque (or rotational force) on a BasePart such that it maintains a constant angular velocity as determined by its [AngularVelocity](#angularvelocity-vector3). This allows for the creation of parts that continually rotate. It is the rotational counterpart to a BodyVelocity. If you would like to maintain a constant angular displacement, use a BodyGyro instead.

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
BodyAngularVelocity
```

#### Name (String)

* [x] Editable without script
* [ ] Read only

```
BodyAngularVelocity
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

#### P (Number)

* [x] Editable without script
* [ ] Read only

```
1250
```

#### angularvelocity (Vector3)

* [x] Editable without script
* [ ] Read only

```
0, 2, 0
```

#### maxTorque (Vector3)

* [x] Editable without script
* [ ] Read only

```
4000, 4000, 4000
```
