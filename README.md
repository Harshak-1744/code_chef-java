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

- 1 ≤ T ≤ 1000
- 20 ≤ X < Y ≤ 40
- 10 ≤ A ≤ 50

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


# 3) Squats

## Problem Statement

Somu went to the gym today. He decided to do X sets of squats. Each set consists of 15 squats. Determine the total number of squats that he did today.

## Input Format

The first line contains a single integer T — the number of test cases. Then the test cases follow.
The first and only line of each test case contains an integer X — the total number of sets of squats that Somu did.

## Output Format

For each test case, output the total number of squats done by Somu.

## Constraints

1 ≤ T ≤ 1000
1 ≤ X ≤ 10^5

## Examples

Input:
```
3
1
4
99

```
Output:
```
15
60
1485

```

## Explanation

- Test Case 1: Since he does only 1 set of squats, the total number of squats done by him is 15.

- Test Case 2: Since he does 4 sets of squats, the total number of squats is 15 + 15 + 15 + 15 = 60.

- Test Case 3: Since he does 99 sets of squats, the total number of squats is 99 * 15 = 1485.

# 4) Chef's Tax Exemption Scheme

## Problem Description
In Chefland, everyone who earns strictly more than Y rupees per year has to pay a tax to Chef. However, Chef has allowed a special scheme where individuals can invest any amount of money and claim exemption for it.

Given the amount X you earned this year and the tax threshold Y, find the minimum amount of money you need to invest to avoid paying taxes.

## Input Format
- The first line of input contains a single integer T, denoting the number of test cases.
- Each test case consists of a single line containing two space-separated integers X and Y, representing the amount earned and the tax threshold, respectively.

## Output Format
For each test case, output a single integer on a new line, denoting the minimum amount you need to invest.

## Constraints
1 ≤ T ≤ 100
1 ≤ Y < X ≤ 100

## Example
Input:
```
4
4 2
8 7
5 1
2 1
```
Output:
```
2
1
4
1
```
## Explanation
- Test case 1: The tax threshold is 2, and you earned 4 rupees. You need to invest at least 2 rupees to avoid taxes.
- Test case 2: The tax threshold is 7, and you earned 8 rupees. You need to invest at least 1 rupee to avoid taxes.
- Test case 3: The tax threshold is 1, and you earned 5 rupees. You need to invest at least 4 rupees to avoid taxes.
- Test case 4: The tax threshold is 1, and you earned 2 rupees. You need to invest at least 1 rupee to avoid taxes.

# 5) Water Intake Tracker

This is a simple program that determines whether Chef followed the doctor's advice to drink at least 2000 ml of water each day.

## Input Format

The program takes the following input:

- The number of test cases, T
- For each test case, the amount of water Chef drank today, X

## Output Format

The program outputs the following:

- For each test case, `YES` if Chef followed the doctor's advice or `NO` if he did not.

## Constraints

The following constraints apply to the input:

- 1 ≤ T ≤ 2000
- 1 ≤ X ≤ 4000

## Sample Input

```
3
2999
1450
2000
```

## Sample Output

```
YES
NO
YES
```
## Explanation
In the above example, Chef followed the doctor's advice in the first and third test cases by drinking at least 2000 ml of water. However, he did not follow the advice in the second test case.


# 6) MasterChef Ranking Checker

This repository contains a solution for the "MasterChef Ranking Checker" problem. It is written in [programming language], and it helps determine whether a contestant named Chef made it to the top 10 or not based on their current rank.

## Problem Description

Chef is participating in the MasterChef competition and wants to know if he made it to the top 10 contestants. The program takes the current rank of Chef as input and checks whether it is within the top 10 or not. The program should output "YES" if Chef made it to the top 10, and "NO" otherwise.

## Input Format

The input consists of multiple test cases. The first line contains an integer T, representing the number of test cases. Each subsequent line contains a single integer X, representing the current rank of Chef.

## Output Format

For each test case, the program outputs a single line with either "YES" or "NO", indicating whether Chef made it to the top 10 or not.

## Constraints

- 1 ≤ T ≤ 100
- 1 ≤ X ≤ 100


## Example

Input:
```
4
15
10
1
50
```

Output:
```
NO
YES
YES
NO
```
## Explanation

- Test case 1:
Chef's rank is 15, which is greater than 10. Thus, Chef did not make it to the top 10.

- Test case 2:
Chef's rank is 10, which is equal to 10. Thus, Chef made it to the top 10.

- Test case 3:
Chef made it to the top 10, as his rank is 1.

- Test case 4:
Chef did not make it to the top 10 as his rank is 50.

# 7) Chef's Biryani Classes

According to a recent survey, Biryani is the most ordered food. Chef wants to learn how to make world-class Biryani from a MasterChef. Chef will be required to attend the MasterChef's classes for X weeks, and the cost of classes per week is Y coins. Chef wants to know the total amount of money he will have to pay for the classes.

## Input Format

The first line of input contains an integer T, representing the number of test cases. Each test case consists of a single line containing two space-separated integers X and Y, representing the number of weeks Chef needs to attend the classes and the cost of classes per week, respectively.

## Output Format

For each test case, output on a new line the total amount of money that Chef will have to pay.

## Constraints

- 1 ≤ T ≤ 10^4
- 1 ≤ X, Y ≤ 100

## Example

Input:
```
4
1 10
1 15
2 10
2 15
```

Output:
```
10
15
20
30
```

## Explanation

- Test case 1: Chef will be required to attend the MasterChef's classes for 1 week and the cost of classes per week is 10 coins. Hence, Chef will have to pay 10 coins in total.

- Test case 2: Chef will be required to attend the MasterChef's classes for 1 week and the cost of classes per week is 15 coins. Hence, Chef will have to pay 15 coins in total.

- Test case 3: Chef will be required to attend the MasterChef's classes for 2 weeks and the cost of classes per week is 10 coins. Hence, Chef will have to pay 20 coins in total.

- Test case 4: Chef will be required to attend the MasterChef's classes for 2 weeks and the cost of classes per week is 15 coins. Hence, Chef will have to pay 30 coins in total.




