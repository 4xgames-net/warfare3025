public:: true

-
- ### Overview
  id:: 68b57825-c230-476c-9970-c984cafd26aa
  This system replaces traditional modifier-based dice rolls with a category-based outcome resolution on a d20. The result of a roll is not just a number, but a quality of success or failure mapped into one of five outcome categories.
  
  Instead of modifying rolls, unit skill affects how many die faces are allocated to each category — more skill compresses the failure range and expands the success ranges.
  
  No matter how skilled a pilot is, or how refined an armor, each outcome category must be represented by at least one side of the D20, meaning the "poor" result starts on 2+ at best, appropriate on 3+ etc.
-
- ### Outcome Categories
  id:: 6930a730-5e66-4207-99f6-61b2fd035702
  
  | Outcome       | Value | Description                          |
  |---------------|--------|--------------------------------------|
  | Not           | 0      | Task fails, maybe even lead to critical failure.      |
  | Poor          | 1      | Weak or compromised success. rarely ever sufficient         |
  | Appropriate   | 2      | Adequate, functional, expected result.|
  | Good          | 3      | Strong or efficient success.         |
  | Excellent     | 4      | Exceptional, best-case scenario.     |
  
  The numeric boundaries vary by unit skill. A skilled unit has fewer "Bad" outcomes and more "Good" or "Excellent" ones.
-
- ### Simplified (PAGE-) Notation
  id:: 68b57825-d969-4c45-97a5-fc336b675bd7
  
  For brevity, skill tables may use shortened notation to define result thresholds. For example:
  `3+/7+/15+/19+`
  This shorthand maps d20 results directly to outcome categories:
	- 3+ →  "Poor"
	- 7+ → "Appropriate"
	- 15+ → "Good"
	- 19+ → "Excellent"
- This format makes it easier to reference skill ratings and expected outcomes at a glance. It also saves a lot of space. Calling it "P/A/G/E - notation" might also help memorizing the result tiers.
-
- ### Dis-/advantage
  id:: 6930a788-706e-42c2-bcb6-b0780ffd7fb8
	- you might find your unit in situations where they have an advantage over their enemy, or where the odds are stacked against them. In these cases, you roll your D20 twice and keep the higher result for advantage, or the lower result when at disadvantage.
	- If you gain 2 advantages for one roll, you may force your opponent to roll his corresponding roll at disadvantage
	- More than two advantages have no further effect
	- Advantages from opposing units cancel each other. Only one side has a net-advantage in an opposed roll
- ### Damage
  id:: 68d22ec9-35ad-4056-8224-5551b426832e
	- Every major unit, or destructable component has a damage capacity of 20 "Hitpoints" - when damage is dealt, it is marked to the component / unit in question.
	  id:: 68d22ece-6ac6-4bab-a1d1-6857f4958487
	- When a roll is affected by the damage (e.g. firing a damaged weapon system or a piloting roll with a damaged movement system), every roll-result that surpasses (20-Damage) is counted as a 1 and thereby as a result of #not
	- some components / units may be given the opportunity to resist incoming damage - the overall structural integrity of a mech, for example. In this case, incoming damage is temporarily added to existing damage. An "appropriate" roll is required to discard the incoming damage. On a poor result or worse, the damage stays on the
-
- ### Adjusting the Table (Optional/ Campaign game)
  When a unit improves a skill:
	- It transfers one die face from a worse outcome to a better one.
	- Each outcome must have at least 1 die face.
	-
- prev: [[Introduction]]
- next: [[Initiative]]