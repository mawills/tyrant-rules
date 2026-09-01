# 1. Game Concepts

## 1.1 Golden Rules

### 1.1.1 Precedence

Whenever a card's text contradicts these rules, the card takes precedence. The card overrides only the rule that applies to that specific situation.

### 1.1.2 Use of "Can't" or "Cannot"

When a rule or effect allows or directs something to happen, and another effect states that it can’t happen, the "can't" effect takes precedence.

*Example: If one effect reads "Whenever your Hero takes damage, ready it" and another reads "Heroes cannot ready," the effect that prevents Heroes from readying takes precedence.*

### 1.1.3 Simultaneous Effects

If multiple effects occur simultaneously, such as "at the start of the Hero Phase" or "at the end of the round," the players choose the order to resolve the effects in.

## 1.2 Effects

"Effect" refers to a single logical section in the Text Box ([2.5](#25-text-box)) of a card. A single card may have multiple distinct effects, often separated by a line break. Heroes, Tyrants, Allies, Minions, Attacks, Skills, Powers, and Quests can all have effects.

### 1.2.1 Activated Effects
Effects that only resolve when optionally activated by a player. Such effects will indicate some type of requirement, followed by a colon *(:)*, followed by the text of the effect. If the requirements of the effect cannot be met, the effect cannot be activated. Unless otherwise specified by the effect, activated effects may only be used during the Hero Phase ([5.2](#52-hero-phase)).

*Example: "Discard a card: Ready your Hero."*

### 1.2.2 Triggered Effects
Effects that only resolve when specific conditions are met, typically with the word "Whenever" or "When". Such effects will indicate the specific conditions, followed by any additional requirements, followed by the text of the effect. Even if the specific conditions occur, if any additional requirements are not met, the effect does not occur. Some triggered effects use the word "may" to indicate that they are optional, otherwise they are required.

*Example: "Whenever your hero takes damage, discard a card and ready your hero." Note that this effect has a specific condition "Whenever your hero takes damage," and an additional requirement "discard a card" If the player has no cards to discard, they will not be able to ready their hero. Because the text does not say "you may discard a card," if the player had a card to discard, they MUST do so.*

*Example: "Whenever your hero takes damage, you may discard a card to ready your Hero." In this case, the player MAY discard a card to ready their hero, but they can choose not to discard a card and not ready their hero.*

### 1.2.3 Static Effects
Any effect that is not an Activated Effect ([1.2.1](#121-activated-effects)) or Triggered Effect ([1.2.2](#122-triggered-effects)) is by default a Static Effect. The text of such an effect is always active so long as the source of that effect remains in play.

*Example: "Each Hero has +1 ATK."*

## 1.3 Numbers

### 1.3.1 Fractional Numbers

Only integers are used in the game. You can’t choose a fractional number, deal fractional damage, gain fractional HP, and so on. If an effect could generate a fractional number, it will instruct you to round up or down.  

### 1.3.2 Variable Numbers

Some cards and effects use a placeholder for a number that needs to be determined, usually "X". Sometimes the card or effect will provide instructions on how to calculate the value of X; the rest let their controller choose the value of X. Unless explicitly stated, X cannot be a negative number.

## 1.4 Choosing Targets

Card effects and game actions will often ask players to select a target for those effects. Unless specified by the effect, a player may choose any Hero, Tyrant, Ally, or Minion as a target.

If a card in hand specifies targets and there are no valid targets for that card in play, that card cannot be played.

If an activated effect specifies targets and there are no valid targets for that card in play, that effect cannot be activated.

If a triggered effect specifies targets and there are no valid targets in play, that effect does not resolve.

# 2. Parts of a Card

## 2.1 Name

A card's name is printed at the top of the card.

## 2.2 Cost

### 2.2.1 Paying Costs

All cards have a cost represented by a number in the upper-left corner. To play a card, you must pay that number of resources (✨)([10.4](#104-resources-)). Some effects ([1.2](#12-effects)) of cards may also require a player to spend ✨. A player may generate ✨ while playing a card or paying for an effect by:
- Discarding cards from their hand. Each card discarded generates one ✨.
- Activating the effects of one or more cards in play that generate ✨.

### 2.2.2 Reduced Costs

Some effects may reduce the cost of cards. Such an effect can never reduce a cost below 0. If a card or effect with X in its cost is reduced, it has no effect on the X value.

### 2.2.3 Cost Replacement

Instead of reducing a cost by a fixed amount, some cards overwrite a cost with a new value entirely.

If a cost replacement effect and a cost reduction effect are active simultaneously, the cost replacement effect is applied first.

If the cost of a card or effect with X in its cost is replaced, it DOES NOT change the value of X anywhere else on the card.

*Example: You play a card with the effect "The next Attack you play costs 0." Afterward, you play an Attack card with Cost: X and the effect "Deal X+1 damage." The cost of X is overwritten to be 0, and because the value of X in the effect can no longer be determined, it defaults to 0, meaning this card will deal 0+1 damage.*

## 2.3 Type

An card's type ([3](#3-card-types)) is printed above its text box.

## 2.4 Subtype

Cards may have subtypes printed after their type. Subtypes have no inherent effect, but effects may reference them.

*Example: You have an ally with "Ally - Goblin Spirit" "Ally" is its type and its subtypes are "Goblin" and "Spirit". If an effect said "Destroy all Goblins," it would destroy this ally.*

## 2.5 Text Box

A large area printed at the bottom of the card that contains the card's effects.

# 3. Card Types

## 3.1 Hero

### 3.1.1 Hero, Class, and Specialization

Each Hero has a class deck of 20 cards. Each class has one or more specialization decks of 20 cards. Before starting the game, each player will select their hero and class, then a specialization.

### 3.1.2 Stats

Heroes have an HP stat in the bottom right of the card. If the damage on a Hero ever meets or exceeds its HP, that hero is immediately slain. Heroes have an ATK, DEF, QST stat that determines the potency of their basic actions.

### 3.1.3 Basic Action

During the Hero Phase ([5.2](#52-hero-phase)), a hero may exhaust to perform a basic action. The basic actions are:
- **Basic Attack**: Deal damage equal to the hero's ATK to any target.
- **Basic Defend**: Give block to any target equal to the hero's DEF.
- **Basic Quest**: Add progress to the active quest equal to the hero's QST.

## 3.2 Tyrant

The Tyrant has an HP stat and is considered to be engaged with all players.

## 3.3 Ally

Allies remain in play and can be used to attack, quest, intercept minion attacks, or to benefit from their effects. If an Ally has any activated effects ([1.2.1](#121-activated-effects)), its controller may use them in the Hero Phase ([5.2](#52-hero-phase)).

### 3.3.1 Stats

Allies have an HP stat, as well as ATK and QST stats that determine the potency of their basic actions. If the damage on an ally ever meets or exceeds its HP, they are slain.

### 3.3.2 Basic Actions
- **Basic Attack**: Deal damage equal to the ally's ATK to any target.
- **Basic Quest**: Add progress to the active quest equal to the ally's QST.

### 3.3.3 Ally Limit

A player may have up to 3 allies in play at a time. If a player already has the maximum number of allies in play and wishes to play another, they may sacrifice an ally in play first.

### 3.3.4 Intercepting Minion Attacks

During the Tyrant Phase ([5.3](#53-tyrant-phase)), each minion in a player's active zone will attack that player's hero. A player may choose to have an ally they control intercept a single minion's attack, dealing ⚔️ equal to that minion's ATK to the ally instead of the hero. An ally does not need to be ready to intercept a minion's attack, and each ally may only intercept one minion attack per phase.

## 3.4 Minion

Minions remain in play and will attack the hero they are engaged with during the tyrant phase. They may also provide beneficial effects to the Tyrant.

### 3.4.1 Stats

Minions have an ATK and an HP stat. If the damage on an minion ever meets or exceeds its HP, they are slain.

### 3.4.2 Minion Limit

There is no limit to the number of Minions that can be in play or be engaged with a single player.

## 3.5 Attack

When playing an Attack card, resolve its effect immediately and then discard it. Attack cards typically inflict damage. Unless otherwise specified, attacks can target any character (Hero, Tyrant, Ally, Minion). The Tyrant’s Attacks target the player whose Engagement Zone they are resolving in, unless otherwise specified.

## 3.6 Skill

When playing a Skill card, resolve its effect immediately and then discard it. Skill cards typically block damage, draw cards, or provide utility.

## 3.7 Power

Once played, Power cards remain in play and provide static, activated, and/or triggered effects.

## 3.8 Innate

Starts the game in play and cannot be targeted, sacrificed, destroyed, discarded, change zones, or be removed from play by any means. Innate cards typically add additional core mechanics to a class or specialization.

# 4. Zones

## 4.1 Tyrant Zone

Contains the Tyrant, the Tyrant’s deck, and discard pile. There is one Tyrant Zone regardless of the number of players.

## 4.2 Intent Zone

Each player has an intent zone. When the Tyrant plays cards, they first go to a player's intent zone. The purpose of the intent zone is to telegraph to the players what the Tyrant will be doing in the Tyrant Phase([5.3](#53-tyrant-phase)) of the current round. Cards will move from the intent zone into the active zone.

## 4.3 Active Zone

Each player has an active zone. Cards more from the intent zone into the active zone. Minions in this zone will attack the heroes and the tyrant's Attack, Skill, and Power cards that enter this zone will be resolved (resolved tyrant Powers go to the tyrant zone).

## 4.4 Engagement Zone

Each player has an engagement zone. It contains both the Intent Zone and the Active Zone. Though it's not in the engagement zone, the Tyrant is also always considered to be engaged with each player.

*Example: You have a minion in your active zone and in your intent zone and play a card with the effect "1⚔️ to each enemy engaged with you." This would deal one damage to each of those minions and one damage to the tyrant.*

## 4.5 Player Zone

Contains a player's Hero, deck, discard pile, Allies, and Powers.

## 4.6 Hand

Each player has a hand of cards drawn from their deck and a maximum hand size of 7 cards.

## 4.7 Deck and Discard

Whenever an effect would draw cards from a deck, those cards are drawn one at a time.

Whenever a player or the tyrant would draw a card, but there are no cards left in their deck, that shuffle their discard pile and it becomes their deck.

## 4.8 Quest Area

### 4.8.1 Active Quest Area

Contains the currently active quest. Progress counters may be added to it and any effects it has are active.

### 4.8.2 Scored Quest Areas

Both the Heroes and the Tyrant have a Scored Quest Area to keep track of quests that they have scored.

# 5. Round Structure

## 5.1 Intent Phase

Place two cards from the Tyrant deck in the Tyrant Zone into each player's respective Intent Zone.

## 5.2 Hero Phase

The players take their turns simultaneously. They may play cards, activate allies, and activate effects in any order of their choosing.

## 5.3 Tyrant Phase

1. Cards in the Intent Zone are moved to their respective player's Engagement Zone.
2. All Tyrant Attack, Skill, or Power cards in a player's Active Zone are resolved in any order, and all ready Minions in a player's Active Zone will attack that player's hero in any order of the player's choosing.

## 5.4 Refresh Phase

1. All exhausted cards in play become ready.
2. If there is no Quest card in play, put a random Quest into play of the next highest Act.
3. Each player may discard any number of cards from their hand, then draw back up to their maximum hand size.

## 5.5 Setup

1. Each player forms their deck by choosing a hero, class, and specialization, then puts any Innate cards ([3.8](#38-innate)) into play. Put the Hero and Tyrant cards into play.
2. Shuffle each player's deck and the Tyrant deck.
3. Put a random Act I Quest card into play.
4. Each player draws up to their maximum hand size, then may discard any number of those cards and draw back up to their maximum hand size.

# 6. Quests

## 6.1 Quest Act

Each quest card has an "Act" level, starting at I and going up to III.

Each quest requires a number of progress counters to be scored, either by the Heroes or the Tyrant. When a side has scored a quest, it is removed from the active quest area and added to their scored area. During the Refresh Phase, if there is no active quest, a random quest of the next highest Act will come into play.

## 6.2 Progress Counters

Quest progress for the Heroes is represented by 🚩, while card progress for the Tyrant is represented by 💀. The number of progress counters required is represented by a number like "5N", meaning 5 * the number of Heroes in the game.

If both sides simultaneously add enough progress counters to the quest to score it, the Tyrant side will score the quest.

Quest progress counters cannot be reduced below 0. If an effect would reduce quest progress below zero, it reduces it to zero instead.

## 6.3 Quest Effects

Quests also have a unique effect while they are active, usually one that is beneficial to the Heroes and one that is detrimental. Higher stage quests typically have more impactful effects.

## 6.4 Quest Rewards

When either side scores a quest, they gain their respective reward printed on the card.

# 7. Victory

The game is played in a series of rounds until one of the following conditions is met:
- The Heroes win immediately if the Tyrant is slain.
- The Tyrant wins at the end of the round if any Heroes are slain.
- Either the Heroes or the Tyrant win immediately if they score the Act III quest.

If multiple victory conditions are achieved simultaneously, conditions higher in the list take priority.

# 8. Game Terms

## 8.1 Owner

The "owner" of a card in the game is the player who started the game with it in their deck. A player is also the owner of their Hero. The Tyrant is the owner of the Tyrant cards. Hero, Ally, Minion, Power, Attack, and Skill cards all have an owner. Whenever a card is discarded or returned to hand, it is always returned to its owner's discard pile or hand.

## 8.2 Controller

By default, the "controller" of a card is its owner, but some effects may grant control of a card to a different player. The controller of a card is who makes decisions about if or when to use its effects, if or when that card should participate in combat, and so on.

## 8.3 Destroy

When a card is destroyed, it is put into its owner's discard pile.

## 8.4 Slain

Heroes, Allies, Minions, and Tyrants can all be slain they accumulate enough damage to equal or exceed their HP. A slain Ally or Minion is destroyed. A slain Hero discards all of their cards and may no longer play cards or activate effects. If the Tyrant is slain, the Heroes win.

## 8.5 Sacrifice

When a player sacrifices a card, they will be instructed to sacrifice a specific card or a specific type of card. That player chooses among the cards they control and destroys it.

If a player must sacrifice a card, and one of those cards has an effect that prevents it from being destroyed, that player must choose a different card if able. If they are not able, no card is sacrificed.

## 8.6 Resolve

To resolve means to follow the text of an effect in its entirety.

*Example: You play a card with the effect "Deal 2 damage, discard a card." This effect would be resolved once you have selected a target for the damage, applied that damage, checked if that target is destroyed, and finally discarded a card from hand.*

### 8.6.1 Partially Resolve

Sometimes an effect can be only partially satisfied. If so, resolve as many parts of the effect as possible and ignore the others. If an effect has one or more parts that require selecting targets ([1.4](#14-choosing-targets)), AT LEAST ONE of those parts must be satisfied, or the effect is not resolved at all.

*Example: You play a card with the effect "Deal 2 damage to a minion, discard a card." If you have no cards in hand, the effect would partially resolve by dealing 2 damage to a minion and discarding nothing. If you have at least one card in hand, you must discard it. If there were no minions in play, thus no valid target for the effect, the effect would not resolve at all.*

## 8.7 Engage

Refers to cards within a player's Engagement Zone. For example, minions in a player's Engagement Zone are said to be engaged with that player. Though it is not in the engagement zone, the Tyrant is always considered to be engaged with all players.

## 8.8 Exhaust

To exhaust a card, rotate it 90 degrees. Only a ready ([8.9](#89-ready)) card may be exhausted, and once it is exhausted, it is no longer ready. Cards are exhausted to signify that they have been used, and cannot be exhausted again until they have become ready once again. Cards are typically readied during the Refresh Phase ([5.4](#54-refresh-phase)).

## 8.9 Ready

A card that is ready may be exhausted ([8.8](#88-exhaust)), typically as a cost or as a result of some effect.

## 8.10 Character

Hero, Tyrant, Ally, and Minion are all characters.

## 8.11 Enemy

The Tyrant and minions not controlled by the players are considered enemies of the players. The players and allies not controlled by the Tyrant are considered enemies of the Tyrant.

*Example: A Priest in the game has attached Mind Control to a minion, gaining control of it. A player then plays a card with the effect 1⚔️ to each enemy." This would deal one damage to the tyrant and to each minion, except for the mind controlled minion.*

# 9. Keyword Effects

## 9.1 Duration (X)

Cards with Duration (X) come into play with X time counters, and those counters are removed automatically at the end of the hero phase (if a player controls the card) or the tyrant phase (if the tyrant controls the card). When the last time counter is removed, the card is sacrificed. Cards with Duration may also specify an effect that resolves whenever a time counter is removed by specifying the effect after a colon (:).

*Example: You play a Power card with the effect "Duration(3). Your hero gains +1 ATK". This card will come into play with 3 time counters, removing one at the end of each hero phase. When the last is removed, sacrifice it. The entire time it is in play, your hero will have +1 ATK.*

*Example: You play a Power card with the effect "Attach. Duration(3): 1⚔️ to attached character". This card will come into play with 3 time counters, removing one and dealing 1⚔️ to the attached character at the end of each hero phase. When the last time counter is removed, sacrifice it.*

## 9.2 Attach

This card is placed underneath the card it attaches and typically applies some effect to the attached card. If the attached card leaves play for any reason, the attaching card is put into its owner's discard pile.

## 9.3 Taunt

You may move an Attack or minion from one player’s Intent Zone into your own OR you may move a minion from one player’s Engagement Zone into your own.

## 9.4 Scry X

Look at the top X cards of your deck. You may discard any and put the rest back in any order. If X is greater than the number of cards in the deck, then scry as many as possible. Do not shuffle the discard pile to refill the deck.

## 9.5 X Charges

Comes into play with X charge counters. They are simply used to track an amount of something--a card with charges on it must define what they do for them to have any effect.

## 9.6 Uses _____

This card is discarded when it no longer has any of the things it uses. For example, a card with "Uses 3 Charges" comes into play with 3 charge counters and is discarded when the last charge is removed.

## 9.7 Mill X

Place the top X cards from your deck into your discard pile. If X is greater than the number of cards in the deck, then mill as many as possible. Do not shuffle the discard pile to refill the deck.

## 9.8 Stealth

While a hero has stealth, if they have not played an Attack card or made a basic attack this round, they cannot be dealt ⚔️ by Attack cards and minions engaged with that player will not attack.

## 9.9 Tough

While a character has tough, whenever they would suffer ⚔️, suffer that much -1 instead. Multiple instances of tough do not stack.

# 10. Damage, Block, Healing, and Resource

## 10.1 Damage (⚔️)

Some effects deal damage to characters, represented by the ⚔️ icon. Damage accumulates on a character until it is healed or that character leaves play.

*Example: A card with the effect "3⚔️" deals 3 damage to any target character.*

*Example: A card with the effect "2⚔️, 2⚔️" deals 2 damage two times to a single target character.*

*Example: You have a Power card in play with the effect "Your Attacks deal +1⚔️". Then, you play an Attack card with the effect "2⚔️, 2⚔️". This Attack would deal 3 damage two times to a single target character.*

## 10.2 Block (🛡️)

Some effects prevent damage, represented by the 🛡️ icon. Block applied to a hero or ally lasts until the beginning of the next Hero Phase. Block applied to the tyrant or a minion lasts until the beginning of the next Tyrant Phase.

*Example: A card with the effect "3🛡️" prevents the next 3 damage to any target character.*

## 10.3 Heal (❤️‍)

Some effects heal damage from characters, represented by the ❤️‍ icon. If a healing effect would remove more damage than is present on a target, remove all damage and ignore the excess healing.

*Example: A card with the effect "2❤️‍ " heals 2 damage from any target character. A card with the effect "1❤️‍  an ally" heals 1 damage from a target ally.*

## 10.4 Resources (✨)

Resources, represented by the ✨ icon, are used to pay the costs of cards and effects ([2.2.1](#221-paying-costs)). Resources may be generated the following ways any number of times during the Hero Phase:
- Discard a card to generate 1✨
- Activate an activated effect that generates ✨.

Whenever a player generates ✨, it exists in a "pool" that is available for that player to spend until the end of the phase. Whenever a phase ends, any unspent ✨ is lost.
