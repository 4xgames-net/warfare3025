public:: true

- ### Basics
	- every unit has at least one movement action noted as: `[movement mode]: (X+Y) Hexes for (t) ticks `
		- #+BEGIN_EXAMPLE
		  A GRF-1N Griffin has it's movement action noted as "Walker, 4Hx for 5ticks"
		  #+END_EXAMPLE
		- #+BEGIN_EXAMPLE
		  An LCT-3M Locusts movement action look like: Walker, 6+1Hx for 5 ticks
		  #+END_EXAMPLE
	- the movement action must always be paid in full, even when the unit moves significantly less than the max allowed (X+Y) Hexes
	- units that move more than (X) Hexes count as #fast and gain a corresponding token.
	- units may choose to spend more ticks for their movement (in order to fire using more aiming ticks, see [[Stabilisation]] )
	- facing changes are free, a unit may chose any facing after it finishes its movement
- ### Jumping
	- Jump jets can be used to improve existing movement action. They provide Thrust points.
	- All jump movement is in a straigt line.
	- Thrust points can be spend for vertical movement, where 2 Thrustpoints are enough to change 1 level of height (and safely back down)
	- Thrust points can be spend horizontally, where one Thrustpoints increases the movement by 1 Hex
	- In order to jump any horizontal distance, the unit first has to leave the ground. this is usually done by spending Thrust vertically, but can also be achieved by walking over a ledge.
	- Landing requires a piloting action as per the rules of the terrain landed in.
- ### Falling
	- In order to prevent damage from Falling, a unit must spend 1 Thrust point for every two levels of height, rounded down. A fall of 1 level of height never results in damage for mechs
	- TODO actual falling damage
	- When preventing a fall by using Thrust points, a piloting skill roll is necessary as if it was a normal jump
- ### Terrain
	- terrain does not automatically slow units down, but may prove hazardous depending on the terrain and the movement type. Every time the unit enters a hex with differing terrain, it might need to accomplish a piloting check with a difficulty detailed in the table below. the consequences are also listed there.
	- TODO #test currently, only one roll is required when new terrain is entered. from a logical perspective, a roll should be required for every hex. check if that gets too cumbersome.
	- a pilot may opt to enter the hex carefully; if they do, the movement costs 2 ticks extra and is never fast. in return, the required success tier is one lower than detailed (that means a "poor" result may be required occasionally.)
	- {{embed ((68aaf6fa-b647-4293-ac9e-0622ce8f5b0b))}}
	- prev: [[Initiative]]
	- next: [[Terrain]]