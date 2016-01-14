---
title       : A Journey into the inner workings of Ramnath's mind
subtitle    : Fumbling blindly thorough the labyrinthine CSS settings
author      : Nick Doylend
job         : 14 Jan 2016
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## This is the first slide after the YAML header

* Not sure how to set <span class='italic'>slide options</span> for this one...

--- .quote

## With Dot Quote Class

<q>The world is not necessarily just. Being <strong>good</strong> does often not pay off and there is no compensation for misfortune. You have a responsibility to do your best nonetheless.</q>

<span class='italic'>Sheldon Kopp - If You Meet the Buddha on the Road, Kill Him!</span>

---

## Without Dot Quote Class

<q>The world is not necessarily just. Being <strong>good</strong> does often not pay off and there is no compensation for misfortune. You have a responsibility to do your best nonetheless.</q>

<span class='italic'>Sheldon Kopp - If You Meet the Buddha on the Road, Kill Him!</span>

--- {class: segue, bg: indigo}

## Now Let's Look at Centring

---

## Centered Text & Code (0)

This is a basic slide, neither text nor code is centred.

```{}
This could be some wonderful code. But it's not.
```

It also works, with the margins and padding and whatever, so <strong>don't mess with it!</strong>

--- .centrepre &vcenter

## Centered Text & Code (1)

This is using `.centrepre and &vcenter`.

Text is centred.

```{}
The code box is centred too, and the code
is left aligned.
```

This is nice.

--- .centrepre 

## Centered Text & Code (2)

This is using `.centrepre` only.

The text is not centred.

```{}
The code box is centred, 70% of page width,
and the code is left aligned.
```

This is acceptable.

--- &vcenter

## Centered Text & Code (3)

This is using `&vcenter` only.

The text is centred.

```{}
The code box not quite centred, and the code
is left aligned.
```

So I guess to get the code box centred we also need `.centrepre`.

--- {class: segue, bg: indigo}

## Now Let's Look at Text Size

---

## Normal

What's the default size, and where in css is it defined?
Well, this is <span style='font-size: 40px'>40px</span> and this is <span style='font-size: 26px'>26px.</span> 26px is the default then. The default line height of 1.5 em keeps the text looking nice and readable.

--- .bigger

## Bigger

<span style='font-size: 26px'>If the default font size is 26px,</span> then the bigger size should be something like 32px. Keeping the default line height of 1.5 em keeps the text looking nice and readable.

--- .smaller

## Smaller

<span style='font-size: 26px'>If the default font size is 26px,</span> then the bigger size should be something like 22px. Keeping the default line height of 1.5 em keeps the text looking nice and readable.

---
