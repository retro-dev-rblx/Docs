---
description: >-
  The BodyThrust Instance exerts a force relative to the BasePart in which it is parented to at a specific location.
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

# BodyThrust

#### Description

The BodyThrust object applies (or exerts) a force relative to the part to which it is parented at a specific location.
  It behaves similar to a BodyForce, except that this object's force applies at a specific point (BodyThrust.Location), allowing you to exert a torque (rotational force).
  To apply a force dynamically so that a part maintains a constant angular velocity, use a BodyAngularVelocity instead.
  To apply a force dynamically so that a part maintains a constant orientation (angular position), use a BodyGyro.

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
BodyThrust
```

#### Name (String)

* [x] Editable without script
* [ ] Read only

```
BodyThrust
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

#### Force (Vector3)

* [x] Editable without script
* [ ] Read only

```
0, 1, 0
```

#### location (Vector3)

* [x] Editable without script
* [ ] Read only

```
0, 0, 0
```
