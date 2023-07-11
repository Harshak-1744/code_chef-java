# code_chef-java

# 1) Dice Game

Chef and Chefina are playing a dice game. In each turn, both of them roll their dice at once. They consider a turn to be good if the sum of the numbers on their dice is greater than 6. Given the numbers Chef and Chefina rolled on their respective dice, determine whether the turn was good or not.

## Input Format

- The first line of the input contains a single integer T, denoting the number of test cases.
- Each test case consists of two space-separated integers X and Y, representing the numbers Chef and Chefina got on their respective dice.

## Output Format

For each test case, print "YES" if the turn was good, and "NO" otherwise, on a new line. The output can be in uppercase or lowercase. That is, the strings "NO", "no", "nO", and "No" will be treated as equivalent.

## Constraints

- 1 ≤ T ≤ 100
- 1 ≤ X, Y ≤ 6

## Sample Input

```
4
1 4
3 4
4 2
2 6
```

## Sample Output

```
NO
YES
NO
YES
```

## Explanation

- Test case 1: The sum of numbers on the dice is 1 + 4 = 5, which is smaller than 6. Thus, the turn is not good.
- Test case 2: The sum of numbers on the dice is 3 + 4 = 7, which is greater than 6. Thus, the turn is good.
- Test case 3: The sum of numbers on the dice is 4 + 2 = 6, which is equal to 6. Thus, the turn is not good.
- Test case 4: The sum of numbers on the dice is 2 + 6 = 8, which is greater than 6. Thus, the turn is good.

**Note:** The problem statement has been formatted into a readable structure and all the necessary details have been included.


# 2) Chef's Exam Eligibility

## Problem Statement

Chef wants to appear in a competitive exam. To take the exam, there are the following requirements:

- The minimum age limit is `X` (i.e. Age should be greater than or equal to `X`).
- Age should be strictly less than `Y`.
- Chef's current age is `A`.

You need to determine whether Chef is currently eligible to take the exam or not.

## Input

The input consists of the following:

- The first line contains an integer `T`, the number of test cases.
- Each of the next `T` lines contains three integers: `X`, `Y`, and `A`.

## Output

For each test case, output "YES" if Chef is eligible to give the exam, "NO" otherwise. You may print each character of the string in uppercase or lowercase (for example, the strings "YES", "yEs", "yes", and "yeS" will all be treated as identical).

## Constraints

- 1 ≤ `T` ≤ 1000
- 20 ≤ `X` < `Y` ≤ 40
- 10 ≤ `A` ≤ 50

## Example

Input:
```
5
21 34 30
25 31 31
22 29 25
20 40 15
28 29 28
```

Output:
```
YES
NO
YES
NO
YES
```

Explanation:
- Test case 1: The age of Chef is 30. His age satisfies the minimum age limit as 30 ≥ 21. Also, it is less than the upper limit as 30 < 34. Thus, Chef is eligible to take the exam.
- Test case 2: The age of Chef is 31. His age satisfies the minimum age limit as 31 ≥ 25. But, it is not less than the upper limit as 31 ≠ 31. Thus, Chef is not eligible to take the exam.
- Test case 3: The age of Chef is 25. His age satisfies the minimum age limit as 25 ≥ 22. Also, it is less than the upper limit as 25 < 29. Thus, Chef is eligible to take the exam.
- Test case 4: The age of Chef is 15. His age does not satisfy the minimum age limit as 15 < 20. Thus, Chef is not eligible to take the exam.

**Note:** Sample input and output are provided to give you a better understanding of the problem. Ensure that your solution handles edge cases and all possible scenarios.
