---
description: >-
  Smoothly transitions a property to another value over a set time. Connected
  blocks are ran after the tween is completed.
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

# Tween Object Property

## Description

Smoothly transitions a property to another value over a set time. Connected blocks are ran **after** the tween is completed.

#### Available to

* [x] Scripts
* [x] LocalScripts
* [x] Yields

## Inputs

#### Object (Object)

You give the path to an object.

* [x] Can use Variable

```
workspace.Baseplate
```

#### Property (String)

You give the block the name of a property.

* [x] Can use Variable

```
Transparency
```

#### Value (Any)

You give the block the new value you want to tween the property to. Make sure you are assigning the correct property type.

* [x] Can use Variable

{% code fullWidth="false" %}
```
1
```
{% endcode %}

#### Time (Number)

The amount of time the tween takes in seconds.

* [x] Can use Variable

```
1
```

#### EasingStyle (Choice)

You give the block the EasingStyle of the tween.

* [ ] Can use Variable

```
Linear
```

#### EasingDirection (Choice)

You give the block the EasingDirection of the tween.

* [ ] Can use Variable

```
In
```

#### RepeatCount (Number)

The number of times the tween repeats after tweening once.

* [x] Can use Variable

```
0
```

#### Reverses (Bool)

Whether or not the tween does the reverse tween once the initial tween completes.

* [x] Can use Variable

```
false
```

## Outputs

This block does not have any outputs.
