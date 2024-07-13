---
description: Finds a part on a ray. See page for more information.
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

# Find Part On Ray

## Description

Sends out a invisible ray from a point in space with a specific direction and length, and then detects if it hits a part. If nothing is hit, the output will all be nil.

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### Origin (Vector3)

You set the Origin of the Raycast.

* [x] Can use Variable

```
0,0,0
```

#### Direction (Vector3)

You set the Direction of the Raycast.

* [x] Can use Variable

```
0,-5,0
```

#### FilterType (Choice)

You set the FilterType of the Raycast.

* [ ] Can use Variable

```
Blacklist
```

#### Filter DescendantsTable (Table)

You set the filter table for the given FilterType.

* [x] Can use Variable

```
BlacklistedParts
```

## Outputs

#### Instance (Object)

Returns the Object that got found by the raycast.

<mark style="background-color:orange;">Returns nil if no object was found.</mark>

<pre><code><strong>HitPart
</strong></code></pre>

#### Position (Vector3)

Returns the Position, where the raycast hitted the Instance.

<mark style="background-color:orange;">Returns nil if no object was found.</mark>

```
HitPosition
```

#### Normal (Vector3)



<mark style="background-color:orange;">Returns nil if no object was found.</mark>

```
```
