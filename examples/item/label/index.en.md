---
title: Long Label
order: 7
---

Proccess the long label in G6.

## Usage

When the label of a node or edge has long text, we recommend calculating the length with JavaScript and using `\n` to wrap the words. G6 has `Util.getLetterWidth` and `Util.getTextSize` to help users calculate the length of the text, but they are only precise for the default font family.
