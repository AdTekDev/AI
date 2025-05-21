# Tik Tak Toe - Heuristic Function

**Objective:**  
This exercise is designed to help students understand how decision-making processes are modeled in Artificial Intelligence through the implementation of a simple turn-based game: Tic-Tac-Toe. Students will explore how rule-based systems and evaluation functions guide an AI agent to make optimal moves.

**Group Task:**  
Each group of students is required to complete the following tasks:

1. **Define Move Selection Rules:**  
   - Develop a clear set of rules or heuristics that an AI player can use to select the next move in a Tic-Tac-Toe game.  
   - These rules should reflect rational decision-making aimed at achieving a win or preventing the opponent from winning (e.g., prioritizing a winning move, blocking an opponent’s winning move, or optimizing for future opportunities).  
   - Ensure the rules are concise, prioritized, and easy for an AI to follow.

2. **Define Evaluation Functions or Formulas:**  
   - Create a mathematical function or algorithm to evaluate the desirability of a given Tic-Tac-Toe game state from the AI’s perspective.  
   - The function should assign a numerical score to each possible move, enabling the AI to select the most promising option among all available moves.  
   - Explain how the function accounts for key factors, such as:  
     - Potential for a win in the current or future turns.  
     - Threats posed by the opponent’s potential winning moves.  
     - Opportunities to block the opponent or create strategic advantages.  
   - Provide a clear example of how the function evaluates a sample board state.

3. **Scenario Description:**  
   - Describe a specific Tic-Tac-Toe game scenario where player X (controlled by the AI) must make a move immediately after player O places their mark at position A.  
```
- - -
O - -
- - -
```

   - Using the move selection rules and evaluation function defined above, explain step-by-step how the AI-controlled X determines its next move. Include:  
     - The evaluation scores for all possible moves.  
     - The rationale for selecting the optimal move based on the rules and function.

