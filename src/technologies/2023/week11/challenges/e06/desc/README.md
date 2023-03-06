# Mod

## Description

The following description is taken from [this source](https://blog.mattclemente.com/2019/07/12/modulus-operator-modulo-operation/), feel free to read it, this is just a sub-set of the whole post

In computing, the modulo operation returns the remainder or signed remainder of a division, after one number is divided by another (called the modulus of the operation). In this challenge, you are going to learn and practice this arithmetic operator

```python
5 % 1 = 0
// 5 divided by 1 equals 5, with a remainder of 0

5 % 2 = 1
// 5 divided by 2 equals 2, with a remainder of 1

5 % 3 = 2
// 5 divided by 3 equals 1, with a remainder of 2

5 % 4 = 1
// 5 divided by 4 equals 1, with a remainder of 1

5 % 5 = 0
// 5 divided by 5 equals 1, with a remainder of 0
```

It may be helpful to think back to your early math lessons, before you learned fractions and decimals. Mathematics with whole numbers behaves differently - when dividing numbers that aren't even multiples, there's always some amount left over. That remainder is what the modulo operation returns.

## The Modulo Operation Expressed As a Formula

As one final means of explication, for those more mathematically inclined, here's a formula that describes the modulo operation:

```python
a - n * floor(a / n);
```

By substituting values, we can see how the modulo operation works in practice:

```python
100 % 7 = 2
// a = 100, n = 7
100 - (7 * floor(100/7)) = 2
```

If you don't find the formula helpful, don't worry - I didn't either at first. Some people find this abstract representation helps deepen or clarify their understanding of the operation, but you don't need to know it.

## Even / Odd

One of the most basic use cases for the modulus operator is to determine if a number is even or odd. This is possible because x % 2 always returns either 0 or 1. Even numbers, because they are evenly divisible by 2, always return 0, while odd numbers always return the remainder of 1.

## Mod in PSeInt Challenge

The challenge for you now is to create a PSeInt program that will receive a number from the user and add the mod operator using the even/odd case ( X % 2 ) where X is the user input

## Expected output

For `even` numbers the expected output will be 0, as in the picture above

![oddeven00](../../../assets/oddeven00.png 'oddeven00')

For `odd` numbers the expected output will be 1, as in the picture above

![oddeven01](../../../assets/oddeven01.png 'oddeven01')

## How to submit my solution?

Add your solution to your README file

## More Help?

Slack us 😉

# Solution

## PLEASE DON'T CHECK THE SOLUTION UNTIL YOU HAVE FINISH YOURS

### Take in mind that this is an example solution, your implementation can be different and that's ok

[Solution](../sol)
