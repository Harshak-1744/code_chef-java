# code_chef-java

# 1) Good Turn

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

---

# 2) Age Limit

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

## Explanation:
- Test case 1: The age of Chef is 30. His age satisfies the minimum age limit as 30 ≥ 21. Also, it is less than the upper limit as 30 < 34. Thus, Chef is eligible to take the exam.
- Test case 2: The age of Chef is 31. His age satisfies the minimum age limit as 31 ≥ 25. But, it is not less than the upper limit as 31 ≠ 31. Thus, Chef is not eligible to take the exam.
- Test case 3: The age of Chef is 25. His age satisfies the minimum age limit as 25 ≥ 22. Also, it is less than the upper limit as 25 < 29. Thus, Chef is eligible to take the exam.
- Test case 4: The age of Chef is 15. His age does not satisfy the minimum age limit as 15 < 20. Thus, Chef is not eligible to take the exam.

**Note:** Sample input and output are provided to give you a better understanding of the problem. Ensure that your solution handles edge cases and all possible scenarios.

---

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

---

# 4) Saving Taxes

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

---

# 5) Water Consumption

Recently, Chef visited his doctor. The doctor advised Chef to drink at least 2000 ml of water each day. Chef drank X ml of water today. Determine if Chef followed the doctor's advice or not.

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

---

# 6) Masterchef finals

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

---

# 7) Biryani Classes

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

---

# 8) Fitness

Chef wants to become fit, so he decided to walk to the office and return home by walking. The distance between Chef's home and office is X km.

If Chef's office is open on 5 days in a week, the task is to find the total number of kilometers Chef travels through office trips in a week.

## Input Format

The first line of input contains an integer T, representing the number of test cases. Each test case consists of a single line containing a single integer X, representing the distance between Chef's home and office.

## Output Format

For each test case, output the number of kilometers Chef travels through office trips in a week.

## Constraints

- 1 ≤ T ≤ 10
- 1 ≤ X ≤ 10

## Example

Input:
```
4
1
3
7
10
```

Output:
```
10
30
70
100
```

## Explanation:

- Test case 1: The office is 1 km away. Thus, to go to the office and come back home, Chef has to walk 2 km in a day. In a week with 5 working days, Chef has to travel 2 * 5 = 10 km in total.

- Test case 2: The office is 3 km away. Thus, to go to the office and come back home, Chef has to walk 6 km in a day. In a week with 5 working days, Chef has to travel 6 * 5 = 30 km in total.

- Test case 3: The office is 7 km away. Thus, to go to the office and come back home, Chef has to walk 14 km in a day. In a week with 5 working days, Chef has to travel 14 * 5 = 70 km in total.

- Test case 4: The office is 10 km away. Thus, to go to the office and come back home, Chef has to walk 20 km in a day. In a week with 5 working days, Chef has to travel 20 * 5 = 100 km in total.

---

# 9) Chef's Ludo Game

Chef is playing Ludo and needs to determine whether he can enter a new token into the play based on the number rolled on the die. According to Ludo rules, a player can enter a new token into the game only when they roll a 6 on the die.

## Problem Statement

In this problem, you are given a series of test cases. For each test case, you will be given the number rolled by Chef on the die (X). Your task is to determine whether Chef can enter a new token into the play or not.

## Input Format

The first line of the input contains a single integer T, representing the number of test cases. Then, the test cases follow, where each test case consists of a single integer X, representing the number rolled by Chef on the die.

## Output Format

For each test case, you need to output "YES" if Chef can enter a new token into the play, and "NO" otherwise. The output should be in uppercase.

## Constraints

1 ≤ T ≤ 6\
1 ≤ X ≤ 6

## Sample Input

```
3
1
6
3
```

## Sample Output

```
NO
YES
NO
```

## Explanation

- Test Case 1: Chef rolled a 1 on the die, so he cannot enter a new token in the play.
- Test Case 2: Chef rolled a 6 on the die, so he can enter a new token in the play.
- Test Case 3: Chef rolled a 3 on the die, so he cannot enter a new token in the play.

---

# 10) Burgers

Chef is fond of burgers and wants to make as many burgers as possible given the number of patties and buns he has. Each burger requires one patty and one bun.

## Problem Statement

Chef has A patties and B buns. Find the maximum number of burgers that Chef can make.

## Input Format

The first line of input will contain an integer T — the number of test cases. Each test case consists of a single line containing two space-separated integers A and B, representing the number of patties and buns, respectively.

## Output Format

For each test case, output the maximum number of burgers that Chef can make.

## Constraints

- 1 ≤ T ≤ 1000
- 1 ≤ A, B ≤ 10^5

## Example

Input:

```
4
2 2
2 3
3 2
23 17
```

Output:

```
2
2
2
17
```

## Explanation:

- Test case 1: Chef has 2 patties and 2 buns, so he can make 2 burgers.
- Test case 2: Chef has 2 patties and 3 buns. He can make at most 2 burgers by using 2 patties and 2 buns.
- Test case 3: Chef has 3 patties and 2 buns. He can make at most 2 burgers by using 2 patties and 2 buns.
- Test case 4: Chef has 23 patties and 17 buns. He can make at most 17 burgers by using 17 patties and 17 buns.
---

# 11) How many unattempted problems

## Problem Statement

CodeChef recently revamped its practice page to make it easier for users to identify the next problems they should solve by introducing some new features:
- Recent Contest Problems - contains only problems from the last 2 contests
- Separate Un-Attempted, Attempted, and All tabs
- Problem Difficulty Rating - the Recommended dropdown menu has various difficulty ranges so that you can attempt the problems most suited to your experience
- Popular Topics and Tags

Our Chef is currently practicing on CodeChef and is a beginner. The count of ‘All Problems’ in the Beginner section is X. Our Chef has already ‘Attempted’ Y problems among them. How many problems are yet ‘Un-attempted’?

## Input Format

The first and only line of input contains two space-separated integers X and Y — the count of 'All problems' in the Beginner's section and the count of Chef's 'Attempted' problems, respectively.

## Output Format

Output a single integer in a single line — the number of problems that are yet 'Un-attempted'

## Constraints

1 ≤ X ≤ 1000
1 ≤ Y ≤ X

## Examples

Input:
```
10 4
```
Output: 
```
6
```

Input: 
```
10 10
```
Output: 
```
0
```

Input: 
```
1000 990
```
Output: 
```
10
```
Input: 
```
500 1
```
Output: 
```
499
```
---

# 12) Determine the Score

Chef appeared for a placement test that consists of a problem with exactly 10 test cases. Each test case is worth the same number of points.

For each test case, Chef passes a certain number of test cases among them. The task is to determine Chef's score based on the points he scored in each test case.

## Input Format

- The first line of input contains an integer T, the number of test cases.
- Each of the following T lines contains two space-separated integers, X and N, where X represents the total points for the problem and N represents the number of test cases passed by Chef's solution.

## Output Format

For each test case, output a single integer representing the points scored by Chef.

## Constraints

- 1 ≤ T ≤ 100 (number of test cases)
- 10 ≤ X ≤ 200 (total points for the problem)
- 0 ≤ N ≤ 10 (number of test cases passed by Chef)
- X is a multiple of 10.

## Sample Input

```
4
10 3
100 10
130 4
70 0
```

## Sample Output

```
3
100
52
0
```

## Explanation

- Test Case 1: The problem is worth 10 points, and since there are 10 test cases, each test case is worth 1 point. Chef passes 3 test cases, so his score will be 1 * 3 = 3 points.
- Test Case 2: The problem is worth 100 points, and each test case is worth 10 points. Chef passes all 10 test cases, so his score will be 10 * 10 = 100 points.
- Test Case 3: The problem is worth 130 points, and each test case is worth 13 points. Chef passes 4 test cases, so his score will be 13 * 4 = 52 points.
- Test Case 4: The problem is worth 70 points, and each test case is worth 7 points. Chef passes 0 test cases, so his score will be 7 * 0 = 0 points.

---

# 13) Donation Drive

## Problem Description

A blood drive aims to collect N number of blood donations. The drive has already collected X donations so far. The task is to find the remaining number of donations needed to reach the target.

## Input Format

The input consists of multiple test cases. The first line of input contains a single integer T, denoting the number of test cases. Each test case is represented by two space-separated integers N and X, where N is the number of required donations and X is the number of collected donations.

## Output Format

For each test case, the program will output on a new line, the remaining number of donations needed to reach the target.

## Constraints

- 1 ≤ T ≤ 200
- 1 ≤ N ≤ 20
- 1 ≤ X ≤ N

## Example

Input:
```
4
5 2
3 3
5 4
7 5
```

Output:
```
3
0
1
2
```

## Explanation:

- Test case 1: The drive aims to collect 5 donations and has collected 2 already. Thus, they need to collect 3 more donations to reach the target.
- Test case 2: The drive aims to collect 3 donations and has collected 3 already. Thus, they need to collect no more donations to reach the target.
- Test case 3: The drive aims to collect 5 donations and has collected 4 already. Thus, they need to collect 1 more donation to reach the target.
- Test case 4: The drive aims to collect 7 donations and has collected 5 already. Thus, they need to collect 2 more donations to reach the target.
---

