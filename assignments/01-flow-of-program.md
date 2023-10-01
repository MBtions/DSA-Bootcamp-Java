[Video Link](https://youtu.be/lhELGQAV4gg)

## Create flowchart and pseudocode for the following:

**1. Input a year and find whether it is a leap year or not.**
Solution: 
_PseudoCode:_
1. INPUT a number N
2. IF (N % 4 == 0)
3. THEN DISPLAY "Leap Year"
4. ELSE DISPLAY "Not a Leap Year"
5. END

**2. Take two numbers and print the sum of both.**
Solution:
_Pseudocode:_
1. INPUT num1, num2
2. LET sum = num1 + num2
3. DISPLAY sum
4. END
   
**3. Take a number as input and print the multiplication table for it.**
Solution:
_Pseudocode:_
1. INPUT a number N
2. LET i = 0
3. WHILE (i <= 10)
4. DISPLAY (i * N)
5. i = i + 1
6. END WHILE
7. END

**4. Take 2 numbers as inputs and find their HCF and LCM.**
Solution:
_Pseudocode:_
1. INPUT n1, n2
2. LET x = n1, y = n2
3. WHILE (y != 0)
4. LET t = y
5. y = x % y
6. x = t
7. END WHILE
8. hcf = x
9. lcm = (n1 * n2) / hcf
10. DISPLAY hcf, lcm
11. END

**5. Keep taking numbers as inputs till the user enters ‘x’, after that print sum of all.**
Solution:
_Pseudocode:_
1. LET Sum = 0
2. DO
3. INPUT number N
4. Sum = Sum + N
5. WHILE (n != x)
6. END DO WHILE
7. DISPLAY Sum
8. END

