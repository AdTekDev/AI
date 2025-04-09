
# L.03 - Logic Programming [3]

## Miscellaneous Problems

### 03.01 Eight queens problem
This is a classical problem in computer science. 
The objective is to place eight queens on a chessboard so that no two queens are attacking each other; i.e., no two queens are in the same row, the same column, or on the same diagonal.
  
Hint: Represent the positions of the queens as a list of numbers 1..N.   
Example: [4,2,7,3,6,8,5,1] means that the queen in the first column is in row 4, the queen in the second column is in row 2, etc.   
Use the generate-and-test paradigm.  


### 03.02 Gray code.
An n-bit Gray code is a sequence of n-bit strings constructed according to certain rules. For example,  
n = 1: C(1) = ['0','1'].  
n = 2: C(2) = ['00','01','11','10'].  
n = 3: C(3) = ['000','001','011','010',´110´,´111´,´101´,´100´].  

Find out the construction rules and write a predicate with the following specification:  

% gray(N,C) :- C is the N-bit Gray code  

Can you apply the method of "result caching" in order to make the predicate more efficient, when it is to be used repeatedly?    


## Others

https://www.nosco.ch/ai/en/exercise_07.php   
-  Car Driving in Switzerland
- Two Canisters
- River Crossing

