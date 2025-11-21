# CI2025_lab3
lab3 for computational intelligence

Helloooo, some important notes:

- my initial thinking was to use A* as it's cool and has a cool name (joking)
then i ran into the fact that A* does not work with negative weights, so i started thinking in 2 ways:
--  the first: i can use an EA solution, but i will be repeating the same thing as we did in the last 2 labs
--  the second: to implement something that we already checked, but nothing was able to handle negative weights,
    maybe i could use DFS to find all possible routes and then choose the one that has the lower cost, bad idea, it will take forever on larger problems.

so i decided to just implement bellman-ford after watching a ton of videos explaining it!
if i was not supposed to do this, then i am sorry, please do not penalize me that much (picture of puss in boots)


- i decided to use permutations instead of combinations as the graphs are directed (1->3 is not equal to 3->1)
