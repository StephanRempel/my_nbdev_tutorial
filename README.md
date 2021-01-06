# my_nbdev_tutorial



This file will become your README and also the index of your documentation.

## Install

`pip install my_nbdev_tutorial`

## How to use

Playing cards in python!

```python
from my_nbdev_tutorial.deck import Deck
from my_nbdev_tutorial.card import Card
d = Deck()
print(f'Number of playing cards in the deck: {len(d.cards)}')
c = Card(2,3)
print(str(c))
d.add_card(c)
```

    Number of playing cards in the deck: 52
    3 of Hearts


```python
card = d.pop_card()
print(card)
```

    3 of Hearts

