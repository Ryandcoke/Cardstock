# Combat

A round of combat is split between turns between the hero and 1 spirit,
cycling between all the spirits.

## 1. Draw

Each player draws cards from their respective combat decks.
The hero draws from their hero combat deck.
All spirits draw from their monster combat deck.

By default:

- The hero draws 5 cards.
- Spirits draw 3 cards.

## 2. Spirit Reveal

The spirit chooses which cards to play for the round and reveals it to the hero.

## 3. Hero Reveal

After seeing which cards the spirit has revealed, the hero chooses and reveals which cards to play.

## 4. Turn Resolution

The revealed cards resolve simultaneously.

If the spirit is reduced to 0 hitpoints, they are removed from the rest of
the combat round.

If the hero is reduced to 0 hitpoints, the spirit that defeated them (even if
reduced to 0 hitpoints for that turn) becomes the hero. The combat round
ends.

If the hero is still alive, move onto the next turn. The hero rotates to
fight against the next spirit.

Once that round is complete, a new round of combat occurs between the hero
and cycling to the next spirit player.
Combat ends when either all spirits are defeated, or a spirits defeats the
hero.
