---
description: Loads the variable stored to a key. Loading blocks may only be used 5 + (5 * number of players) times per minute.
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

# Load Variable

## Description

Loads the variable stored to a key. The success output returns true or false based on whether or not it successfully loads.
Loading blocks may only be used 5 + (5 * number of players) times per minute.

#### Available to

* [x] Scripts
* [ ] LocalScripts
* [ ] Yields

## Inputs

#### Key (String)

The index which will be saved from the datastore.

* [x] Can use Variable

```
KeyToRetrieve
```

#### Shared (Bool)

Determines if you're getting the a key that is synced across all your places.

* [x] Can use Variable

```
false
```

## Outputs

#### Success (bool)

Whether or not it successfully load your variable.

```
false
```

#### LoadedData (Any)

The Data which resided inside of the datastore's key.

```
false
```
