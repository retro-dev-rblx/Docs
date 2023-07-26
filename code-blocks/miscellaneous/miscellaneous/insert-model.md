---
description: Inserts a model with the model code.
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

# Loop Through Children

## Description

Loads the model from its retrostudio id. The success output returns true or false based on whether or not it successfully loads. If success is true and LoadedModel is nil then there was no model at that id. Loading blocks may only be used 5 + (5 * number of players) times per minute..

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### ID (Number)

The Retrostudio ID model code to load.

* [x] Can use Variable

#### Parent (Object)

The location the model will stay in the studio. For example, you could set a model to load in a model in Workspace or in Lighting.

* [ ] Can use variable

## Outputs

#### Success

A variable output that outputs a bool value of true and false if it has sucessfully loaded.

#### Loaded Model

A variable output that outputs the name of the model inserted.

