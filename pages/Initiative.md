public:: true

- ### Overview
	- Instead of a turn by turn resolution, where one unit activates after another, units gain action-ticks (/Tokens) when they perform actions.
	- the unit with the currently least amount of ticks goes next
	- in case of draw, roll a piloting action. loser goes first
	- in most cases, when units with the  same amount of ticks don't interfere with one another, it is sufficient to just resolve one after the other.
- ### Interrupts
	- interrupting an opponent is possible if the interrupting unit sees the action and has less ticks than the actor will have after finishing the action
		- #+BEGIN_EXAMPLE
		  Unit A moves around the corner to attack Unit T, this actions requires 5 ticks. 
		  Unit A currently has 3 ticks, Unit T is at 5 Ticks. 
		  Because Unit A will end its action at a total of 8 Ticks, Unit T is entitled to an interrupt.
		  #+END_EXAMPLE
	- only one interrupt per action
	- interrupts may not be interrupted
	- If the interrupting action is specifically designed to prevent the action question, it may do so. Ranged attack cannot be dodged.
		- #+BEGIN_EXAMPLE
		  Unit A starts at 3 ticks and engages Unit T in close quarter combat for 5 Ticks. Unit T starts at 5 Ticks and may try to dodge the attack, possibly preventing all damage.
		  #+END_EXAMPLE
	- Interrupting actions not specifically countering the original action (e.g. a shield block) only occur first if the ticks of the interrupting unit are still lower after the resolution of the entire situation.
		- #+BEGIN_EXAMPLE
		  Unit A starts with 3 Ticks and attacks Unit T *at range* for 5 Ticks. Unit T, currently at 4 Ticks decide to shoot first - it may only spend 3 Ticks on this attack, as this will result in a total of 7 Ticks for Unit T - still less than the 8 of Unit A.
		  #+END_EXAMPLE
- ### Preflight
	- If no scenario is given to determine who starts, we recommend that both sides roll tactics or maneuvering skill and place their result tier (1 for poor, 4 for excellent) worth of ticks on the opponent. continue until one unit is a clear beginner.
-
- prev: [[Rolling Dice]]
- next [[Movement]]