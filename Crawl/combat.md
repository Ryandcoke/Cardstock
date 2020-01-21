# Combat

A round of combat is split between turns between the hero and 1 spirit,
cycling between all the spirits.

## 1. Draw

Each player draws cards from their respective combat decks.
The hero draws from their hero combat deck.
All spirits draw from their monster combat deck.

By default all spirits draw 3 cards.

The hero draws cards depending on the number of players.

| Player count | Cards drawn |
|:------------:|:-----------:|
| 2            | 3           |
| 3            | 4           |
| 4            | 5           |

## 2. Spirit Reveal

The spirits each choose one card to play for the round and **reveals** it to the hero.
One **instant** spirit card may optionally be played at no cost.

## 3. Hero Reveal

After the spirits have **revealed** their cards, the hero chooses and **reveals** one
card in response to each spirit card.
One **instant** hero card may optionally be played at no cost.

## 4. Turn Resolution

The all cards resolve simultaneously.

If a spirit is reduced to 0 hitpoints, they are removed from the rest of
the combat round.

If the hero is reduced to 0 hitpoints, the spirit that defeated them (even if the
spirit is reduced to 0 hitpoints for that turn) becomes the hero. If there is a tie,
the winner priority is clockwise.

Combat ends when either all spirits are defeated, or a spirits defeats the
hero.
