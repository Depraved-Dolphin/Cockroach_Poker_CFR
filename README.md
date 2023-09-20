# Cockroach_Poker_CFR

The counterfactual regret algorithm (CFR) has recently been developed and successfully optimized to solve and play the imperfect information game of poker, outcompeting top professionals in tournaments. However, no one has yet used this algorithm to solve Cockroach poker, a bluffing game similar to Bullshit but with stinkbugs and cockroaches. This project will attempt to do just that. Use state-of-the-art CFR algorithm and game theory to solve a two-player version of the game cockroach poker, basically using a bazooka to kill a fly.

Read more about how the CFR algorithm works here, and find some featured python code that I'm heavily basing this project on: https://aipokertutorial.com/the-cfr-algorithm/#:~:text=The%20CFR%20algorithm%20works%20by,is%20then%20computed%20and%20returned.

Read the offical rules to Cockroach Poker here: https://www.ultraboardgames.com/cockroach-poker/game-rules.php

The official rules contain a lot of typos, so I will also summarize the rules here:

In Cockroach Poker for two players, there are 64 cards consisting of 8 different types with 8 copies each. These cards are shuffled, 10 are set aside, and the remaining cards are dealt equally between the two players. The acting player (Player 1) picks a card from their hand and presents it to the opponent (player 2), either telling the truth about its type or lying. If player 2 correctly guesses whether Player 1 was truthful or lying, then Player 1 places the card face-up in their tableau. Otherwise, if Player 2's guess was wrong, they place the card in their own tableau. The next round begins with the player who just added a card to their tableau. The game ends when a player has five cards of the same type in their tableau or when a player runs out of cards in their hand; either way, that player loses.

I have little coding experience, so I need your help to finish it up. Your suggestions and adjustments are very welcome!
