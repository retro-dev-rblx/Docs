---
description: >-
  An Accoutrement welds its child part called "Handle" to the player's
  character. See page for more information.
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

# Accoutrement

#### Description

An Accoutrement welds its child part called "Handle" to the player's character. You can change the position and rotation of the Handle part using the [AttachmentPos](accoutrement.md#attachmentpos-vector3), [Right](accoutrement.md#attachmentright-vector3), [Forward](accoutrement.md#attachmentforward-vector3), and [Up](accoutrement.md#attachmentup-vector3) properties.

Parts descending from an accoutrement are massless when attach to other parts (e.g. with a Weld) as long as they are not the root part of the assembly, and it doesn't add to the total mass or rotational inertia of the Assembly.

This doesn't apply to a part descending from an accoutrement when an accoutrement welds to another part that is massless or one if its parts otherwise becomes root. This also doesn't apply for the root part, and it has mass like a normal part.

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

## Appearance

#### AttachmentForward (Vector3)

* [x] Editable without script
* [ ] Read only

```
0, 0, -1
```

#### AttachmentPos (Vector3)

* [x] Editable without script
* [ ] Read only

```
0, 0, 0
```

#### AttachmentRight (Vector3)

* [x] Editable without script
* [ ] Read only

```
1, 0, 0
```

#### AttachmentUp (Vector3)

* [x] Editable without script
* [ ] Read only

```
0, 1, 0
```

## Data

#### ClassName (String)

* [ ] Editable without script
* [x] Read only

```
Accoutrement
```

#### Name (String)

* [x] Editable without script
* [ ] Read only

```
Accountrement
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
