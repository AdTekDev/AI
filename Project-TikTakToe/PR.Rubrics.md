
# Tik Tak Toe - Rubrics

## Stage/Sprint 1

---

### **1. Score Function / Heuristic Function – 3.5 points**

| Score       | Description                                                                                                                                                                                                                                                 |
| ----------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **3.5 pts** | The heuristic function is well-designed, effectively evaluates board states considering both offensive and defensive strategies. It prioritizes winning moves, blocks losing moves, and weighs different patterns (rows, columns, diagonals) appropriately. |
| **2.5 pts** | The heuristic function works reasonably but lacks depth in evaluating strategic situations (e.g., considers only wins but not threats).                                                                                                                     |
| **1.5 pts** | The function exists but is overly simplistic, focusing only on basic counts without strategic value.                                                                                                                                                        |
| **0.5 pt**  | The function is written but incorrect or ineffective in real gameplay.                                                                                                                                                                                      |
| **0 pt**    | No heuristic function implemented or it crashes.                                                                                                                                                                                                            |

---

### **2. Selection (Best Move Selection) – 1.5 points**

| Score       | Description                                                                                                                                               |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1.5 pts** | Move selection is correctly based on the heuristic function (e.g., using Minimax, Alpha-Beta, or similar), consistently choosing the best move available. |
| **1 pt**    | Move selection uses logic but is not optimal, or contains minor flaws in applying the evaluation.                                                         |
| **0.5 pt**  | Move selection is random or not aligned with the evaluation function.                                                                                     |
| **0 pt**    | No move selection logic implemented or incorrect.                                                                                                         |

---

### **3. Checking for Win – 1 point**

| Score      | Description                                                                                          |
| ---------- | ---------------------------------------------------------------------------------------------------- |
| **1 pt**   | Fully correct win condition checking for all directions (rows, columns, diagonals) and both players. |
| **0.5 pt** | Win checking is present but incomplete or buggy (e.g., misses diagonals).                            |
| **0 pt**   | No win checking or completely incorrect logic.                                                       |

---

### **4. Running Game – 2 points**

| Score      | Description                                                                                                                                                       |
| ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **2 pts**  | The game runs completely from start to finish. Has basic interface (console or GUI). Supports human vs AI or AI vs AI. Game flow and rules are correctly handled. |
| **1 pt**   | Game runs but has minor issues (e.g., improper end conditions, limited input handling).                                                                           |
| **0.5 pt** | Only partial gameplay runs (e.g., individual moves work but no full loop).                                                                                        |
| **0 pt**   | Game does not run or has critical errors.                                                                                                                         |

---

### **5. Answering / Presentation – 2 points**

| Score      | Description                                                                                                                   |
| ---------- | ----------------------------------------------------------------------------------------------------------------------------- |
| **2 pts**  | Student clearly explains their approach, heuristic logic, and gameplay strategy. Answers questions confidently and correctly. |
| **1 pt**   | Can describe general ideas but lacks clarity or depth in explanation.                                                         |
| **0.5 pt** | Weak explanation, shows limited understanding of their own solution.                                                          |
| **0 pt**   | Unable to explain or did not participate in the presentation.                                                                 |

---

## Stage/Sprint 2

---

### **1. Updated Heuristic Function – 3 points**

| Score     | Description                                                                                                                                                                                                          |
| --------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **3 pts** | Heuristic is significantly improved with better evaluation logic (e.g., considers multiple strategic patterns, blocks opponent threats effectively, prioritizes win). Justification of changes is clearly explained. |
| **2 pts** | Heuristic shows some improvements and reflects moderate updates; explanation is provided but may lack depth.                                                                                                         |
| **1 pt**  | Only minimal or cosmetic changes to the heuristic; limited or no impact on AI performance.                                                                                                                           |
| **0 pt**  | No update made, or update is invalid/ineffective.                                                                                                                                                                    |

---

### **2. Online Playing (API Communication) – 2 points**

| Score     | Description                                                                                                                                       |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| **2 pts** | Online gameplay works smoothly using APIs (e.g., REST, sockets). Player can play against another machine in real-time. Communication is reliable. |
| **1 pt**  | Online play is implemented but buggy or partially working (e.g., desyncs, missing turns, or limited to local network only).                       |
| **0 pt**  | Online feature does not function or is missing.                                                                                                   |

---

### **3. Ontime (Online Response Latency) – 1 point**

| Score      | Description                                                        |
| ---------- | ------------------------------------------------------------------ |
| **1 pt**   | Latency is **under 1 second** (real-time response experience).     |
| **0.5 pt** | Latency is **between 1–2 seconds** (acceptable, minor delay).      |
| **0 pt**   | Latency is **over 2 seconds**, or gameplay suffers noticeable lag. |

---

### **4. Running Game – 2 points**

| Score     | Description                                                                                                                  |
| --------- | ---------------------------------------------------------------------------------------------------------------------------- |
| **2 pts** | Game is fully operational, integrates both AI logic and online play. User interface (even console) is stable and responsive. |
| **1 pt**  | Game runs with some minor bugs or missing features.                                                                          |
| **0 pt**  | Game crashes or is unplayable.                                                                                               |

---

### **5. Q\&A / Presentation – 2 points**

| Score     | Description                                                                                                                                      |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **2 pts** | Student explains updated heuristic, online logic, and system architecture clearly. Answers questions confidently and shows strong understanding. |
| **1 pt**  | Student explains partially or with some confusion.                                                                                               |
| **0 pt**  | Cannot explain or does not participate in discussion.                                                                                            |

---

