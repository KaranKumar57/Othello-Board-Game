# Othello-Board-Game

Othello Board Game in Java. The Game is playable on the console. There have to be Three (3) versions for playing. 

1. Human vs Human
2. Ai vs Human
3. Ai vs Ai

1. Familiarize with Othello Rules:

2. The game is played on an 8x8 grid with initial positions for black and white pieces.

3. Design the Game Board: Data Structure: Choose a suitable data structure (like a 2D array) to represent the 8x8 game board in your program.

4. Implement Game Mechanics:
i.   Move Validation: Create functions to check for valid moves based on Othello rules (flanking and capturing opponent's pieces).
ii.  Move Execution: Write code to place pieces on the board and flip the opponent’s pieces where applicable.
iii. Game State: Develop functions to track the game's current state, including player turns and remaining valid moves.

5. Create Player Classes:
i.  Human Player: Implement a class for human players to input their moves.
ii. AI Player: Develop an AI player class. Initially, it can make random moves.

6. Enhance AI with Advanced Strategy (MiniMax Algorithm):
i.  Understand MiniMax: Research and understand the MiniMax algorithm, a common AI strategy for two-player games.
ii. Implement MiniMax: Integrate the MiniMax algorithm into the AI player class. This involves creating a recursive function that simulates possible moves and their outcomes.

7. Optimize with α/β Pruning:
i.  Learn α/β Pruning: Understand how α/β pruning optimizes the MiniMax algorithm by eliminating unnecessary branches in the decision tree.
ii. Apply α/β Pruning: Modify the MiniMax implementation to include α/β pruning, enhancing the efficiency of the AI’s decision-making process.

8. Incorporate Heuristic Evaluation:
i.  Heuristic Function: Develop a heuristic function to evaluate game positions. This might consider factors like the number of pieces, board control, edge control, etc.
ii. Integrate with AI: Use this heuristic in the MiniMax algorithm to help the AI assess and choose the best moves.

Finally implemented two classes. these classes cannot be changed. The player interface can only be used once. The goal is to let the ai play the game on a server against other ai.
