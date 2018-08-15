---
description: Adapted from M3D's "GCODE MANUAL" DRAFT rev2
---

# Supported G-Code

## Overview

G-Code first came about in the late 1950s and is considered a computer programming language.  It is standardized under ISO 6983-1 and NIST RS274.  Intimidating?

Don’t worry; we include this information just for completeness.  The 3D printing industry has only adopted portions of the code which has significantly simplified it from a full-blown programming language into a simpler set of instructions.  M3D has continued to optimize this set of instructions to be as efficient as possible which will account for differences between our G-Code and other G-Code flavors, though we strive to keep these differences to a minimum.

{% hint style="info" %}
What follows on this page may include information that is specific to M3D's implementation of G-Code in the Micro, Pro and Micro+ products.
{% endhint %}

Let’s go over a short overview.  G-Codes always have a standard format.  They are a list of pairs where a pair is a single character followed by a number.  The character defines how to interpret and apply the number that follows.  The first pair in a line \(command number\) is always the letter M or G which specifies the command set.  This is followed by the command number, which is an integer that specifies the command the printer will attempt to execute.  This is followed by a set of pairs that modify the command's behavior and differ based on what command is being sent.  These pairs are separated by a space.  Within each pair, there is no space between the letter and the number.  Don't worry, the rest of this page covers these fields and their formats and gives examples.  Lastly, the line is terminated by a newline character \(or enter on the keyboard\).

A semi-colon denotes a comment; any text written afterward will be ignored by the printer.

## G-Codes

## M-Codes



