# code_chef-java

# 1) [Good Turn](https://github.com/Harshak-1744/code_chef-java/blob/main/Good%20Turn)

# 2) [Age Limit](https://github.com/Harshak-1744/code_chef-java/blob/main/Age%20Limit)

# 3) [Squats](https://github.com/Harshak-1744/code_chef-java/blob/main/Squats)

# 4) [Saving Taxes](https://github.com/Harshak-1744/code_chef-java/blob/main/Saving_Taxes)

# 5) [Water Consumption](https://github.com/Harshak-1744/code_chef-java/blob/main/Water%20Consumption)

# 6) [Masterchef finals](https://github.com/Harshak-1744/code_chef-java/blob/main/Masterchef%20finals)

# 7) [Biryani Classes](https://github.com/Harshak-1744/code_chef-java/blob/main/Biryani%20classes)

# 8) [Fitness](https://github.com/Harshak-1744/code_chef-java/blob/main/Fitness)

# 9) [Chef's Ludo Game](https://github.com/Harshak-1744/code_chef-java/blob/main/Chef%20Plays%20Ludo)

# 10) [Burgers](https://github.com/Harshak-1744/code_chef-java/blob/main/Burgers)

# 11) [How many unattempted problems](https://github.com/Harshak-1744/code_chef-java/blob/main/How%20many%20unattempted%20problems)

# 12) [Determine the Score](https://github.com/Harshak-1744/code_chef-java/blob/main/Determine%20the%20Score)

# 13) [Donation Drive](https://github.com/Harshak-1744/code_chef-java/blob/main/Donation%20Drive)

# 14) [IPL Ticket Rush](https://github.com/Harshak-1744/code_chef-java/blob/main/IPL%20Ticket%20Rush)

## Problem Description

A total of N students from the college want to attend the IPL match, while only M tickets are available for the match. The task is to determine how many students won't be able to book tickets.

## Input Format

The input consists of multiple test cases. The first line of input contains a single integer T, denoting the number of test cases. Each test case is represented by two space-separated integers N and M, where N is the number of students who want to go, and M is the total number of tickets available.

## Output Format

For each test case, the program will output on a new line the number of students who won't be able to book tickets.

## Constraints

- 1 ≤ T ≤ 1000
- 1 ≤ N, M ≤ 10^5

## Example

Input:
```
4
5 3
5 7
4 1
8 8
```

Output:
```
2
0
3
0
```

## Explanation:

- Test case 1: There are 5 students who want to go, and only 3 tickets are available. Hence, 2 students won't be able to get tickets.
- Test case 2: There are 5 students who want to go, and 7 tickets are available. So, every one of them will get the tickets.
- Test case 3: There are 4 students who want to go, and only 1 ticket is available. Hence, 3 students won't be able to get tickets.
- Test case 4: There are 8 students who want to go, and 8 tickets are available. So, every one of them will get the tickets.
---
Certainly! Below is the content for the "README.md" file for the Chef's Kitchen Working Hours problem:

# 15) [Kitchen Timings](https://github.com/Harshak-1744/code_chef-java/blob/main/Kitchen%20Timings)

## Problem Description

The working hours of Chef's kitchen are from X pm to Y pm, where 1 ≤ X < Y ≤ 12. The task is to find the number of hours Chef works during these hours.

## Input Format

The input consists of multiple test cases. The first line of input contains a single integer T, denoting the number of test cases. Each test case is represented by two space-separated integers X and Y, where X is the starting time of working hours, and Y is the ending time of working hours.

## Output Format

For each test case, the program will output on a new line the number of hours Chef works.

## Constraints

- 1 ≤ T ≤ 100
- 1 ≤ X < Y ≤ 12

## Example

Input:
```
4
1 2
3 7
9 11
2 10
```

Output:
```
1
4
2
8
```

## Explanation:

- Test case 1: Chef starts working at 1 pm and works till 2 pm. Thus, he works for 1 hour.
- Test case 2: Chef starts working at 3 pm and works till 7 pm. Thus, he works for 4 hours.
- Test case 3: Chef starts working at 9 pm and works till 11 pm. Thus, he works for 2 hours.
- Test case 4: Chef starts working at 2 pm and works till 10 pm. Thus, he works for 8 hours.

# 16) [Tax in Chefland](https://github.com/Harshak-1744/code_chef-java/blob/main/Tax%20in%20Chefland)

## Problem Description

In Chefland, a tax of rupees 10 is deducted if the total income is strictly greater than rupees 100.

You are given a number of test cases (T), and for each test case, you need to find out the amount of money you get after tax deduction.

## Input Format

The first line of input will contain a single integer T, denoting the number of test cases.

The first and only line of each test case contains a single integer X — your total income.

## Output Format

For each test case, output on a new line, the amount of money you get after tax deduction.

## Constraints

- 1 ≤ T ≤ 100
- 1 ≤ X ≤ 1000

## Sample Input

```
4
5
105
101
100
```

## Sample Output

```
5
95
91
100
```

## Explanation

- Test case 1: Your total income is 5 rupees, which is less than 100 rupees. Thus, no tax would be deducted, and you get 5 rupees.
- Test case 2: Your total income is 105 rupees, which is greater than 100 rupees. Thus, a tax of 10 rupees would be deducted, and you get 105 - 10 = 95 rupees.
- Test case 3: Your total income is 101 rupees, which is greater than 100 rupees. Thus, a tax of 10 rupees would be deducted, and you get 101 - 10 = 91 rupees.
- Test case 4: Your total income is 100 rupees, which is equal to 100 rupees. Thus, no tax would be deducted, and you get 100 rupees.

# Reach on Time

## Problem Description

Chef has recently moved into an apartment. It takes 30 minutes for Chef to reach the office from the apartment.

Chef left for the office X minutes before Chef was supposed to reach. Determine whether or not Chef will be able to reach on time.

## Input Format

The first line of input will contain a single integer T, denoting the number of test cases.
Each test case consists of a single integer X.

## Output Format

For each test case, output "YES" if Chef will reach on time, "NO" otherwise. The output is case-insensitive. Thus, the strings "YES," "yes," "yeS," and "Yes" are all considered the same.

## Constraints

1 ≤ T ≤ 60
1 ≤ X ≤ 60

## Sample Input

```
6
30
60
14
29
31
42
```

## Sample Output

```
YES
YES
NO
NO
YES
YES
```

## Explanation

- Test case 1: Chef leaves 30 minutes before he is supposed to reach, so he will reach the office exactly on time since it takes 30 minutes to commute.

- Test case 2: Chef will reach 30 minutes early.

- Test case 3: Chef will reach 16 minutes late.

---

# Audible Range

## Problem Description

Chef's dog, binary, hears frequencies starting from 67 Hertz to 45000 Hertz (both inclusive). Given the frequency of Chef's commands, find out whether binary can hear them or not.

## Input Format

The first line of input will contain a single integer T, denoting the number of test cases.
Each test case consists of a single integer X - the frequency of Chef's commands in Hertz.

## Output Format

For each test case, output on a new line "YES" if binary can hear Chef's commands, and "NO" otherwise. The output is case-insensitive. Thus, the strings "YES," "yes," "yeS," and "Yes" are all considered the same.

## Constraints

1 ≤ T ≤ 10^4
1 ≤ X ≤ 10^6

## Sample Input

```
5
42
67
402
45000
45005
```

## Sample Output

```
NO
YES
YES
YES
NO
```

## Explanation

- Test case 1: Chef's command has a frequency of 42 Hertz, which is less than 67. Thus, it would not be audible to binary.

- Test case 2: Chef's command has a frequency of 67 Hertz, which lies in the range [67, 45000]. Thus, it would be audible to binary.

- Test case 3: Chef's command has a frequency of 402 Hertz, which lies in the range [67, 45000]. Thus, it would be audible to binary.

- Test case 4: Chef's command has a frequency of 45000 Hertz, which lies in the range [67, 45000]. Thus, it would be audible to binary.

- Test case 5: Chef's command has a frequency of 45005 Hertz, which is greater than 45000. Thus, it would not be audible to binary.

---

# Reach the Target

## Problem Description

There is a cricket match going on between two teams A and B. Team B is batting second and has a target of X runs. Currently, Team B has scored Y runs. Determine how many more runs Team B should score to win the match.

Note: The target score in cricket matches is one more than the number of runs scored by the team that batted first.

## Input Format

The first line of input will contain a single integer T, denoting the number of test cases.
Each test case consists of two space-separated integers X and Y, representing the target for Team B and the current score of Team B, respectively.

## Output Format

For each test case, output how many more runs Team B should score to win the match.

## Constraints

1 ≤ T ≤ 10
50 ≤ Y < X ≤ 200

## Sample Input

```
4
200 50
100 99
130 97
53 51
```

## Sample Output

```
150
1
33
2
```

## Explanation

- Test case 1: The target is 200 runs, and Team B has already made 50 runs. Thus, the team needs to make 200 - 50 = 150 runs more to win the match.

- Test case 2: The target is 100 runs, and Team B has already made 99 runs. Thus, the team needs to make 100 - 99 = 1 run more to win the match.

- Test case 3: The target is 130 runs, and Team B has already made 97 runs. Thus, the team needs to make 130 - 97 = 33 runs more to win the match.

- Test case 4: The target is 53 runs, and Team B has already made 51 runs. Thus, the team needs to make 53 - 51 = 2 runs more to win the match.

---

# Who is Taller?

## Problem Description

Alice and Bob were having an argument about which of them is taller than the other. Charlie got irritated by the argument, and decided to settle the matter once and for all.

Charlie measured the heights of Alice and Bob and found out that Alice's height is X centimeters and Bob's height is Y centimeters.

Help Charlie decide who is taller.

It is guaranteed that X ≠ Y.

## Input Format

The first line of input will contain an integer T, denoting the number of test cases. The description of T test cases follows.
The first and only line of each test case contains two integers X and Y, as described in the problem statement.

## Output Format

For each test case, output on a new line "A" if Alice is taller than Bob, else output "B". The output is case insensitive, i.e., both "A" and "a" will be accepted as correct answers when Alice is taller.

## Constraints

1 ≤ T ≤ 1000
100 ≤ X, Y ≤ 200
X ≠ Y

## Sample Input

```
2
150 160
160 150
```

## Sample Output

```
B
A
```

## Explanation

- Test case 1: In this case, 150 < 160, so Bob is taller than Alice.

- Test case 2: In this case, 160 > 150, so Alice is taller than Bob.

---

# Tour of King

## Problem Description

King loves to go on tours with his friends.

King has N cars that can seat 5 people each and M cars that can seat 7 people each. Determine the maximum number of people that can travel together in these cars.

## Input Format

The first line of input contains a single integer T, denoting the number of test cases.
The first and only line of each test case contains two space-separated integers N and M, representing the number of 5-seaters and 7-seaters, respectively.

## Output Format

For each test case, output on a new line the maximum number of people that can travel together.

## Constraints

1 ≤ T ≤ 100
0 ≤ N, M ≤ 100

## Sample Input

```
4
4 8
2 13
14 5
8 8
```

## Sample Output

```
76
101
105
96
```

## Explanation

- Test case 1: King has 4 cars that seat 5 each and 8 cars that seat 7 each. So, 4 * 5 + 8 * 7 = 76 people can travel together.

- Test case 2: King has 2 cars that seat 5 each and 13 cars that seat 7 each. So, 2 * 5 + 13 * 7 = 101 people can travel together.

- Test case 3: King has 14 cars that seat 5 each and 5 cars that seat 7 each. So, 14 * 5 + 5 * 7 = 105 people can travel together.

- Test case 4: King has 8 cars that seat 5 each and 8 cars that seat 7 each. So, 8 * 5 + 8 * 7 = 96 people can travel together.

---
# [Paying with Rs. 500 Notes]()

# [Best of Two]()


