---
description: Changes the Physical Properties of a Part.
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

# Get Part Physical Properties

## Description

Sets the elasiticity, friction, density, elasiticityweight and the frictionweight of a part.

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### Part (Object)

You give the path to an object, that you want to get the physical properties.

* [x] Can use Variable

```
game.Workspace.Part
```

## Outputs

#### Result (Table)

Returns a Table with the Keys Density, Friction, Elasticity, FrictionWeight, ElasticityWeight.

```
{
    Density = 1;
    Friction= 1;
    Elasticity = 1;
    FrictionWeight = 1;
    ElasticityWeight = 1;
}
```
