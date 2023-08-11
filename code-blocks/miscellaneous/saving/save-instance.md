---
description: Saves a model to a key. This model can be accessed across servers via the Load Instance block if the same key is given. This block may only be used 5 + (5 * number of players) times per minute.
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

# Save Instance

## Description

Saves a model to a key. This model can be accessed across servers with the Load Instance block if the same key is given.
The success output returns true or false based on whether or not it successfully saves.
This block may only be used 5 + (5 * number of players) times per minute.

#### Available to

* [x] Scripts
* [ ] LocalScripts
* [ ] Yields

## Inputs

#### Model (Object)

The Instance that will be saved into the datastore with the key input.

* [x] Can use Variable

```
Game.Workspace.Baseplate
```

#### Key (String)

The index in which Instance will be saved.

* [x] Can use Variable

```
KeyToSave
```

#### Shared (Bool)

Determines if the key will be synced across all your retrostudio places.

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
