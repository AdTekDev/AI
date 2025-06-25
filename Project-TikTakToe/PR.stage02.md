
# Stage 02
(update + api) 

## Heuristic

1. **Heuristic Function Design & Updates**:

   * Students must implement a **heuristic evaluation function** to estimate the value of non-terminal game states when the search depth limit is reached.
   * The heuristic function must consider factors such as:

     * Number of potential winning lines open to the AI.
     * Number of potential winning lines open to the opponent.
     * Immediate threats (e.g., 2-in-a-row with an empty third space).

2. **Heuristic Update and Improvement**:

   * Students are expected to **iteratively improve or tune their heuristic function** based on testing and gameplay outcomes.
   * Evidence of this process must be demonstrated through one or more of the following:

     * A changelog or version history of heuristic adjustments.
     * Written explanation or diagrams justifying how and why the heuristic was modified.
     * Experiments comparing different heuristic versions (e.g., win/loss rate vs. random or scripted players).


## 🔍 Algorithm

1. **Algorithm Requirement**:

   * The move-selection algorithm must implement **at least the Minimax algorithm** to determine optimal plays. (alpha-beta / expectimax, ...)
   * The algorithm should evaluate game states up to **a depth of 3 moves ahead** (3 plies). This includes alternating moves between the AI and the opponent.

2. **State Optimization**:

   * The implementation must demonstrate and explain an **efficient way to store and reuse game states** to minimize both memory usage and computation time.
   * Suggested techniques include:

     * Using **hashing or Zobrist hashing** to uniquely identify board positions.
     * Employing **memoization or transposition tables** to avoid redundant computation for previously seen game states.
     * Representing the board in a **compact format**, such as bitboards or flat arrays, to reduce space complexity.

## **Documentation Requirement**:

   * The source code must include **clear comments or a README section** explaining:

     * How the game state is represented internally.
     * How the Minimax decision tree is built and pruned (if alpha-beta pruning or other enhancements are used).
     * How previously evaluated states are stored and accessed to avoid recomputation.
