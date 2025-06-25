
## Stage 02
(update + api) 

## 🔍 Requirements for Tic-Tac-Toe AI Logic

1. **Algorithm Requirement**:

   * The move-selection algorithm must implement **at least the Minimax algorithm** to determine optimal plays. (alpha-beta / expectimax, ...)
   * The algorithm should evaluate game states up to **a depth of 3 moves ahead** (3 plies). This includes alternating moves between the AI and the opponent.

2. **State Optimization**:

   * The implementation must demonstrate and explain an **efficient way to store and reuse game states** to minimize both memory usage and computation time.
   * Suggested techniques include:

     * Using **hashing or Zobrist hashing** to uniquely identify board positions.
     * Employing **memoization or transposition tables** to avoid redundant computation for previously seen game states.
     * Representing the board in a **compact format**, such as bitboards or flat arrays, to reduce space complexity.

3. **Documentation Requirement**:

   * The source code must include **clear comments or a README section** explaining:

     * How the game state is represented internally.
     * How the Minimax decision tree is built and pruned (if alpha-beta pruning or other enhancements are used).
     * How previously evaluated states are stored and accessed to avoid recomputation.
