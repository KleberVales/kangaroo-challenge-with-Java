# 🦘 Kangaroo – Number Line Jumps Challenge

## 📝 Challenge Description

In this challenge, two kangaroos are jumping along a number line. Each kangaroo has:

- A starting position (x1 and x2).
- A jump distance (v1 and v2).

You need to determine whether the two kangaroos will land on the same position at the same time after some number of jumps.

## 📥 Input Format

A single line containing four space-separated integers:
```java

x1 v1 x2 v2

```
Where:
- x1: Start position of Kangaroo 1.
- v1: Jump distance of Kangaroo 1.
- x2: Start position of Kangaroo 2.
- v2: Jump distance of Kangaroo 2.

## 📤 Output Format

- Print "YES" if the kangaroos land on the same position at the same time.
- Otherwise, print "NO".

## ✅ Example

Input 1:
```java

0 3 4 2

```
Output 1:
```java

YES

```
## 🔍 Explanation:

- Kangaroo 1 starts at 0 and jumps 3 meters per jump.
- Kangaroo 2 starts at 4 and jumps 2 meters per jump.
- After 4 jumps, both are at 12, so the answer is YES.

Input 2:
```java

0 2 5 3

```

Output 2:
```java

NO

```
## 🔍 Explanation:

- Kangaroo 1 starts at 0 and jumps 2 meters per jump.
- Kangaroo 2 starts at 5 and jumps 3 meters per jump.
- Kangaroo 2 is ahead and jumps farther, so they will never meet → NO.
