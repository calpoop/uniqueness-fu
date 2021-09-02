# Uniqueness-fu

Each round presents a finite set of "poses" or "moves" that each character could choose, and without communicating to each other, each player chooses one of these moves. At the end of the round, each player performs the move she chose, and the goal is to perform a move that no other player performs.

One stylistic consideration is to make it like a "dance-off" showdown type of thing, similar to WarioWare's aesthetic. Somewhat of a silly party game.

1 vs many (AI or not):
goal of the many players is to pick the move that the single player makes

team vs team:
goal of each team is to pick as few overlapping moves within the team as possible

free for all?
goal is to be the person that has picked the least popular moves over successive rounds.

1 v 1 (actually collaborative):
goal is to pick the same move as your "opponent" so you both win


the "moveset" can be procedurally generated, so that it is not known exactly which moves are available before playing. This is to prevent, for example, teams from just assigning a move to each player and picking the exact same move every time.


Challenges:
- what does it take to make AI players tough to play against besides just picking a random move? Should the AI try to "learn" a human player's patterns in order to guess what he/she picks?
- also about AI: tough to model the "externalities" that allow human players to guess what each other might pick, what patterns might appeal to some players over others
- actually coming up with the "procedural" generation of the "moves": a bunch of blocks on a grid arranged in random ways? Randomly generated "poses" for a character to be in?
- should the moveset reset each round, or should the same moveset sometimes be repeated, so that there can be a guessing game of whether the same players repeat the same moves? Does this detract or add to the gameplay?
