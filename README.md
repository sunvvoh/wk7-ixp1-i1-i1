# Taco Shop - Interactive Narrative 1

## Game Overview
Help run a taco shop! Listen to customer orders, memorize them, and prepare the correct tacos to earn money for rent. You need to earn $20 across 4 customers to pay your rent!

## How to Play
1. A cat customer will tell you their order
2. Type the order correctly to proceed
3. Drag and drop ingredients onto the tortilla
4. The cat's expression changes based on your accuracy
5. Earn money based on how well you did
6. Repeat for 4 customers total

## Required Image Assets

Place all image files in the `interaction1/assets/` folder:

### Cat Expressions (required)
- `cat neutral.png` - Neutral expression (correctness value: 0)
- `cat sad.png` - Sad expression (correctness value: -1)
- `cat saddest.png` - Saddest expression (correctness value: -2)
- `cat happy.png` - Happy expression (correctness value: 1)
- `cat happiest.png` - Happiest expression (correctness value: 2)
- `cat talking.png` - Talking/ordering expression

### Protein Options (required)
- `beef.png`
- `pork.png`
- `chicken.png`

### Vegetable Options (required)
- `cilantro.png`
- `onions.png`

### Sauce Options (required)
- `salsa verde.png`
- `salsa roja.png`

### Other (required)
- `tortilla.png`

## Game Mechanics

### Correctness Value System
- Start each round at 0
- Correct ingredient: +1
- Wrong ingredient: -1
- Range: -2 to +2

### Money Earned
- Value +2: $6.00 - $10.00
- Value +1: $3.00 - $6.00
- Value 0: $1.00 - $3.00
- Value -1: $0.10 - $1.00
- Value -2: $0.00

### Win Condition
Earn $20 or more after 4 rounds to pay rent!

## Technical Details
- Drag and drop functionality for ingredient selection
- Typing animation for cat dialogue
- Real-time correctness tracking
- Smooth animations for round transitions
