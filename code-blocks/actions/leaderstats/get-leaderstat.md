---
description: Gets the value of a leaderstat.
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

# Get Leaderstat

## Description

Gets the current value of a players leaderstat.

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### Player (Object)

Player that you want to get the leaderstat from.

* [x] Can use Variable

```
game.Players.Roblox
```

#### StatName (String)

Name of the stat you want to get from the leaderstat.

* [x] Can use Variable

```
Coins
```

## Outputs

#### Value (Number)

Returns the current leaderstats value of the given player,

```
CurrentPlayerCoins
```
