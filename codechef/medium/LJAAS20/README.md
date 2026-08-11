# LJAAS20

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### Print Squares

Write a program to output the squares (using multiplication) of numbers from 1 to 5 on separate lines.

### Sample 1:
Input
Output

```

```

```
1 - 1
2 - 4
3 - 9
4 - 16
5 - 25
```

## Solution

**Language:** Java  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-08-11T05:29:14.609Z  

```java
class Codechef {
    public static void main(String[] args) {

        for (int i = 1; i <= 5; i++) {
            int result = (int) Math.pow(i, 2);
            System.out.println(i + " - " + result);
        }
    }
}
```

---

[View on CodeChef](https://www.codechef.com/problems/LJAAS20)