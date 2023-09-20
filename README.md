# Cockroach_Poker_CFR

The counterfactual regret algorithm (CFR) has recently been developed and successfully optimized to solve the imperfect information game of 2-player poker, and outcompetes top professionals in multiplayer tournaments. However, no one has yet used this algorithm to solve the silly game of Cockroach poker, a bluffing game similar to Bullshit but with stinkbugs and cockroaches. This project will attempt to do just that. I'm opening this project up to use the CFR algorithm and game theory to solve a two-player version of the game cockroach poker, basically using a bazooka to kill a fly.

# CFR algorithm, how it works

Read more about how the CFR algorithm works here, and find some featured python code that I'm heavily basing this project on: https://aipokertutorial.com/the-cfr-algorithm/#:~:text=The%20CFR%20algorithm%20works%20by,is%20then%20computed%20and%20returned.

# Cockroach Poker, the rules

In Cockroach Poker for two players, there are 64 cards consisting of 8 different types with 8 copies each. These cards are shuffled, 10 are set aside, and the remaining cards are dealt equally between the two players. The acting player (Player 1) picks a card from their hand and presents it to the opponent (player 2), either telling the truth about its type or lying. If player 2 correctly guesses whether Player 1 was truthful or lying, then Player 1 places the card face-up in their tableau. Otherwise, if Player 2's guess was wrong, they place the card in their own tableau. The next round begins with the player who just added a card to their tableau. The game ends when a player has five cards of the same type in their tableau or when a player runs out of cards in their hand; either way, that player loses.

The offical rules to Cockroach Poker contain a lot of typos but they say the same thing and can be found here: https://www.ultraboardgames.com/cockroach-poker/game-rules.php

# I need your help

I have little coding experience, so I need your help to finish this up. Your suggestions and adjustments are very welcome! If you have any math expertise, I would also like to run the numbers for an upper bound on the total number of informatio sets in this game. This would give me a good estimate of the compute time and memory space I need
