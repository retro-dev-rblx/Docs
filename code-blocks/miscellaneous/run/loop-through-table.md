---
description: Runs the connected blocks once for each value in a table.
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

# Loop Through Table

## Description

Runs the connected blocks once for each value in a table.

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### Table (Table)

The table used for the loop.

* [x] Can use Variable

```
ExampleTable
```

## Outputs

#### Index (Number)

The current index in the table that is being looped through. 

```
TableIndex
```

#### Value (Variable)

The current value in the table that attributes to the index.

```
IndexValue
```
