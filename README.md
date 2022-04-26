# Mortal-combat style game  
The players are objects of classes (i.e. hero = Superhero()). In each round, two characters (two superheroes, that is # two objects) will be drawn
be two characters (two superheroes, or two objects). Each of them can fight with a # random
a random weapon from the superpowers (it must be drawn) and deal a random number of points of damage
from a range of 1-10 (attack function). The player who draws the higher amount of damage will lower their # life_points
life_points to the opponent by their own number of damage minus the number the opponent has drawn
e.g. player S1 does 5 points of damage, player S2 does 6 points of damage
=> as a result, player S2 wins and deals 1 (i.e. 6 minus 5) point of damage.
After the attack, the loser's life points should be updated.
If it is <=0, the loser is out of the game. The game continues until..,
When the last player is left (he wins, of course;-) ).
If two players take the same amount of damage, no one takes damage and a
the two players are drawn again

Attributes:

* name - 'superman'
* superpowers - list of superpowers for example ['ab', 'bc', 'cd']
* life_points - a random number from the range 1-10 - random library (random.randint)

methods:

* attack - random number in range 1-10
* decreas_life - decreases life points by a given amount
* (x enters as parameter to function: def decreas_life(x))
* Create an object by: hero = Superman()
