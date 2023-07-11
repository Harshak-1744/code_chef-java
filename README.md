# code_chef-java

# Dice Game

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
