#### Name: Thomas Antle
#### Date: 05 April 2021
#### What this is: Calculations from the manual work out of the Needleman-Wunsch algorithm.

### Instructions: Local Alignment calculations
For each entry in the matrix in the lab assignment, there is a letter and you are to place your calculations for each letter below. The first calculation for entry (a) is done for you. Please follow this example in your calculations for the rest of the letters.

Scoring table:


|Score or penalty| value |
|----------------|-------|
|gap penalty      |-1     |
|Mismatch penalty | 0     |
|Match score     | 1     |


a)
- Match or Mismatch: A = A is a match
- Left entry calculation: -1 - 1 = -2
- Above entry calculation: -1 -1 = -2
- Diagonal entry calculation: 0 + 1 = 1
- Max score: 1 from the Diagonal


b)
- Match or Mismatch: A = T is a mismatch
- Left entry calculation: -1 - 2 = -3
- Above entry calculation: -2 - 1 = -3
- Diagonal entry calculation: -1 -1 = -2
- Max score: -2 from the Diagonal


c)
- Match or Mismatch: T = A is a mismatch
- Left entry calculation: -2 - 1 = -3
- Above entry calculation: -1 - 2 = -3
- Diagonal entry calculation: -1 - 1 = -2
- Max score: -2 from the Diagonal


d)
- Match or Mismatch: T = T is a match
- Left entry calculation: -2 - 2 = -4
- Above entry calculation: -2 - 2 = -4
- Diagonal entry calculation: 0 + 1 = 1
- Max score: 1 from the Diagonal


e)
- Match or Mismatch: G = A is a mismatch
- Left entry calculation: -3 -1 = -4
- Above entry calculation: -1 - 3 = -4
- Diagonal entry calculation: -2 - 1 = -3
- Max score: -3 from the Diagonal


f)
- Match or Mismatch: G = T is a mismatch
- Left entry calculation: -3 - 2 = -5
- Above entry calculation: -2 - 3 = -5
- Diagonal entry calculation: -1 - 1 = -2
- Max score: -2 from the Diagonal



(Did you remember to add your name to this Markdown file?)
