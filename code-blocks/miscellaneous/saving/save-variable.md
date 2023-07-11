---
description: Saves a variable to a key. This variable can be accessed across servers via the Load Variable block if the same key is given. This block may only be used 5 + (5 * number of players) times per minute.
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

# Save Variable

## Description

Saves a variable to a key. This variable can be accessed across servers with the Load Variable block if the same key is given.
The success output returns true or false based on whether or not it successfully saves.
This block may only be used 5 + (5 * number of players) times per minute.

#### Available to

* [x] Scripts
* [ ] LocalScripts
* [ ] Yields

## Inputs

#### Value (Any)

The value that will be saved into the datastore with the key input.

* [x] Can use Variable

```
ValueToSave
```

#### Key (String)

The index in which Value will be saved.

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

Whether or not it successfully saved your variable.

```
false
```
