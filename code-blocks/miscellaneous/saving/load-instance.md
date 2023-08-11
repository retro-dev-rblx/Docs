---
description: Loads the model stored to a key. Loading blocks may only be used 5 + (5 * number of players) times per minute.
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

# Load Instance

## Description

Loads the model stored to a key. The success output returns true or false based on whether or not it successfully loads.
Loading blocks may only be used 5 + (5 * number of players) times per minute.

#### Available to

* [x] Scripts
* [ ] LocalScripts
* [ ] Yields

## Inputs

#### Key (String)

The index in which Instance will be saved.

* [x] Can use Variable

```
KeyToSave
```

#### Parent (Object)

Where the loaded Instance will be parented to.

* [x] Can use Variable

```
game.Workspace.Baseplate
```

#### Shared (Bool)

Determines if you're getting the a key that is synced across all your places.

* [x] Can use Variable

```
false
```

## Outputs

#### Success (bool)

Whether or not it successfully saved your Instance.

```
false
```

#### LoadedModel (Object)

The model which had been saved into the specified key.

```
ExampleVariable
```
