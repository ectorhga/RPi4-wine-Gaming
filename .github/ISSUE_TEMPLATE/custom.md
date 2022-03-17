---
name: Custom issue template
about: Describe this issue template's purpose here.
title: ''
labels: ''
assignees: ''

---

## Game settings
# Official patch version
Usually latest.
# Custom patches 
Compatibility or widescreen patches? Please link to patches.
# Changes to any ```.cfg``` file or registry entry of the game
Which? Why?
# Installation method

## Wine
# Version
Stable / staging
# Prefix 
Any winetricks verbs used? Which (preferably only the ones really needed)?
# DLL overrides 
Wrappers (ddraw), CD audio (winmm), xinput? Which versions?

## Mesa
# Version
# Env-vars

## Box86
# Version
Should always be latest (!)
# Env-vars
Especially ```BOX86_DYNAREC_BIGBLOCK```, ```BOX86_DYNAREC_STRONGMEM``` or ```BOX86_DYNAREC_X87DOUBLE```.
