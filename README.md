<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! -->

This repo uses code from [Allen Downey’s](http://allendowney.com/)
[ThinkPython2](https://github.com/AllenDowney/ThinkPython2). *This file
was automatically generated from a Jupyter Notebook using
[nbprocess](https://nbprocess.fast.ai/). to change it you must edit
[index.ipynb](https://github.com/isaac-flath/deck_of_cards/blob/master/index.ipynb).*

## Install

After cloning this repository:

`pip install -e .`

> There is already a project called [deck_of_cards on
> pypi](https://pypi.org/project/deck-of-cards/). This project has no
> relation to that. This project is an example of how to create python
> packages with [nbprocess](https://github.com/fastai/nbprocess).

## How to use

Playing cards in python!

``` python
from deck_of_cards.deck import Deck
d = Deck()
print(f'Number of playing cards in the deck: {len(d.cards)}')
```

    Number of playing cards in the deck: 52

``` python
card = d.pop_card()
print(card)
```

    King of Spades

See [the docs](https://isaac-flath.github.io/deck_of_cards/) for more
info.
