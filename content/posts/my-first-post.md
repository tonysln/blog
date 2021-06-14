---
title: "My First Post"
date: 2021-05-29T19:35:38+03:00
draft: true
---

[Tanka](https://github.com/nanxstats/hugo-tanka) is a Bootstrap-based minimalist theme for Hugo.

<div class="figure">

![](/images/example.jpg)

<p class="caption">Vik, Iceland. Photo by <a href="https://unsplash.com/photos/MLKrf51NV8w">Adam Jang</a>.</p>

</div>

## Typography

Follows the Bootstrap typography.

# h1 Heading

## h2 Heading

### h3 Heading

#### h4 Heading

##### h5 Heading

###### h6 Heading

---

**This is bold text**

__This is bold text__

*This is italic text*

_This is italic text_

~~Deleted text~~

> Block quotes are
> written like so.
>
> They can span multiple paragraphs,
> if you like.

Some text, and some `code` and then a nice plain [link with title](https://nanx.me "title text!").

and then

+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    * Ac tristique libero volutpat at
+ Very easy!

vs.

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa

## Math

Inline formula `$S_n = \sum_{i=1}^n X_i$` example.

$$S(n, k) = \frac{1}{k!}\sum_{i=0}^{k} (-1)^{i} \binom{k}{i} (k-i)^n.$$

## Code

Inline `code` example

### Python

```python
@requires_authorization(roles=["ADMIN"])
def somefunc(param1='', param2=0):
    r'''A docstring'''
    if param1 > param2: # interesting
        print 'Gre\'ater'
    return (param2 - param1 + 1 + 0b10l) or None

class SomeClass:
    pass

>>> message = '''interpreter
... prompt'''
```
