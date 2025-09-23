public:: true

-
- ### Overview
  This system replaces traditional modifier-based dice rolls with a category-based outcome resolution on a d20. The result of a roll is not just a number, but a quality of success or failure mapped into one of five outcome categories.
  
  Instead of modifying rolls, unit skill affects how many die faces are allocated to each category — more skill compresses the failure range and expands the success ranges.
  
  ---
- ### Outcome Categories
  
  | Outcome       | Value | Description                          |
  |---------------|--------|--------------------------------------|
  | Not           | 0      | Task fails, maybe even lead to critical failure.      |
  | Poor          | 1      | Weak or compromised success.         |
  | Appropriate   | 2      | Adequate, functional, expected result.|
  | Good          | 3      | Strong or efficient success.         |
  | Excellent     | 4      | Exceptional, best-case scenario.     |
  
  The numeric boundaries vary by unit skill. A skilled unit has fewer "Bad" outcomes and more "Good" or "Excellent" ones.
  
  ---
- ### Simplified Notation
  
  For brevity, skill tables may use shortened notation to define result thresholds. For example:
  
  `3+/7+/15+/19+`
  
  This shorthand maps d20 results directly to outcome categories:
	- 3+ →  "Poor"
	- 7+ → "Appropriate"
	- 15+ → "Good"
	- 19+ → "Excellent"
- This format makes it easier to reference skill ratings and expected outcomes at a glance. It also saves a lot of space. Calling it "P/A/G/E - notation" might also help memorizing the result tiers.
  
  ---
- ### Adjusting the Table (Optional/ Campaign game)
  When a unit improves a skill:
	- It transfers one die face from a worse outcome to a better one.
	- Each outcome must have at least 1 die face.
- ---
- ### Damage
  id:: 68d22ec9-35ad-4056-8224-5551b426832e
	- Every major unit has a damagetrack of 20 "Hitpoints" - when damage is dealt it is deducted from the corresponding track.
	- When a roll is affected by the damage, every roll that surpasses (20-Damage) is counted as a 1 and thereby as a result of #not
-
- prev: [[Introduction]]
- next: [[Initiative]]