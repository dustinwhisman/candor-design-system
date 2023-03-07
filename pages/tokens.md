---
title: Tokens
description: Use Tokens to adjust the look and feel of the design.
layout: default
---

# Tokens

When you want to change the look and feel of the design, you can change the values of Tokens. Tokens are meant to cascade and build off each other, so changing one value can affect many different elements, layouts, and components.

Since Tokens are CSS Custom Properties (a.k.a. CSS Variables), you can override them as needed in `style` attributes, or by writing CSS that changes the value of the custom property.

## `generic.tokens.css`

```css
{% include 'css/generic.tokens.css' %}
```
