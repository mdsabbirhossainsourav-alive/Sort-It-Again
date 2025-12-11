## Problem Statement
You will be given data for N students, where each student will have a name (nm), class (cls), section (s), student ID (id), math marks (math_marks), and English marks (eng_marks).

Your task is to sort the students data according to the eng_marks in descending order. If multiple student have the same eng_marks then sort them according to the math_marks in descending order. If multiple student have the same math_marks then sort them accoding to the id in ascending order as the id will be unique.

## Input Format
First line will contain N.

Next N lines will contain nm, cls, s, id, math_marks and eng_marks respectively.
## Constraints
1 <= N <= 1000

1 <= |nm| <= 100 and will contain only English alphabets.

1 <= cls <= 10

'A' <= s <= 'Z'

1 <= id <= 10^9

0 <= math_marks, eng_marks <= 100
## Output Format
Output the data in sorted order as instructed.
## Sample Input 0
6

akib 2 R 1001 32 53

rakib 1 E 1002 93 97

sakib 8 M 1003 34 88

bokib 3 Q 1004 93 58

jessica 4 F 1005 94 88

noname 8 R 1006 17 61
## Sample Output 0
rakib 1 E 1002 93 97

jessica 4 F 1005 94 88

sakib 8 M 1003 34 88

noname 8 R 1006 17 61

bokib 3 Q 1004 93 58

akib 2 R 1001 32 53
## Sample Input 1
6

akib 2 R 1001 32 53

rakib 1 E 1002 94 88

sakib 8 M 1003 34 88

bokib 3 Q 1004 93 58

jessica 4 F 1005 94 88

noname 8 R 1006 17 61
## Sample Output 1
rakib 1 E 1002 94 88

jessica 4 F 1005 94 88

sakib 8 M 1003 34 88

noname 8 R 1006 17 61

bokib 3 Q 1004 93 58

akib 2 R 1001 32 53
