# Journey to the West / 名侦探孙悟空

## Intro

"Journey to the West" is a hidden information card game mixed with [ridiculous JiangHu](https://github.com/meteorode/ridiculous-JiangHu) and [Poker](https://en.wikipedia.org/wiki/Poker) mechanics, based on [the novel with the same name](https://en.wikipedia.org/wiki/Journey_to_the_West).

## Key Features

1.  108 Cards (2 Sets of Poker including Jokers) with "Journey to the West" theme,
2.  Each card has an on table skill(while flipped from deck) and a play effect(when played by players),
3.  Each Player has an hidden role, the goal is either find your teammate(s) and/or beat your opponent(s) by playing cards like Poker, see [Game Flow](#Game-Flow)

## Roles in Game

## Game Flow

1.  There're three types of cards in game: a) Char b) Encounter c) Artifact
2.  Each player has two Char cards, one is face down while the other face up , Shown chars must include Sun Wukong, while hidden chars must include Tang Xuanzang.
3.  Each round would has an 'active player', he/she should choose one other player to dual with:
    -   Active player play an 'Artifact Card', resolve with its play effect,
    -   Clockwisely, each player could choose to support a side: play an artifact card, resolve the effect, then add to the pool,
    -   Determine the winner via the Poker rule, shown as below:
![Poker Cards Ranking](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a1/PokerHandRankings.pdf/page1-593px-PokerHandRankings.pdf.jpg)
4. If the 'active player' loses:
    -   He/she must discard he/her card played,
    -   All the supporters lost must discard the card they played,
    -   The defender and his/her teammates could choose either take the cards they played back or discard it and draw a new one,
5.  If the 'active player' wins:
    -   He/she could take the card played and choose one loot from three:
        a)  check the face down Char of defender,
        b)  exchange one Char from defender, both face up and down is ok but must keep one face up and the other face down,
        c)  discard one card from the defender's hands.
    -   All the supporters could choose either take the cards they played back or discard it and draw a new one,
    -   All the defender's teammates must discard the card played,
6.  If drawn, nothing would happen,
7.  Each player could reveal his/her hidden Char to participate the dual, If so, he/she should either __MEET THE WINNING CONDITION__ or be KO.
8.  Whenever a player's hand is empty, he/she would be KO,
9.  The game ends while some player __MEET THE WINNING CONDITION__ or less than or equal to only one player survived.