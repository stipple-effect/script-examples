# *Stipple Effect* script examples

This repository contains example scripts written for [*Stipple Effect*](https://github.com/jbunke/stipple-effect).

## What is *Stipple Effect*?

*Stipple Effect* is a pixel art editor that will change your workflow with its approach to **scripting**. It has all the standard features of a raster graphics editor, as well as features specifically intended to support you in making pixel art for video games or online distribution.

You can learn more about the applications of scripting in *Stipple Effect* [here](https://jbunke.github.io/se/docs/scripting).

## Language

Scripts are written in [*DeltaScript*](https://github.com/jbunke/deltascript), a scripting language skeleton that I designed. *DeltaScript* is designed to make writing scripts easy and fast. The language has **no boilerplate**, and code is highly **readable, yet concise**.

*Stipple Effect* extends the *DeltaScript* base language with several types and namespaces specific to the program. The best way to understand the limits of the scripting system are by reading the [API specification](https://jbunke.github.io/se/api).

The file extension for *Stipple Effect* scripts is `.ses`. This is the file mask that *Stipple Effect* will use to identify scripts in the file system.

## *DeltaScript for Stipple Effect* - VS Code syntax highlighting extension

To make it easier to write scripts for *Stipple Effect*, I have published [a VS Code extension](https://marketplace.visualstudio.com/items?itemName=jordanbunke.deltascript-for-stipple-effect) that provides syntax highlighting for scripts.
