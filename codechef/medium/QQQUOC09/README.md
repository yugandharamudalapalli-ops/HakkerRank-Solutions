# QQQUOC09

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### Unique String Reversal

You are given a string `S`. Your task is to process it in two steps.

- First Remove all duplicate characters, ensuring that only the first occurrence of each character is kept.
- Second Reverse the resulting string.
### Input Format
- The first and only line of input contains a single string, S.
### Output Format
- Print a single line containing the final processed string.
### Constraints
- $1≤|S|≤10^5$
- The string $S$ contains only printable ASCII characters.
### Sample 1:
Input
Output

```
google
```

```
elog
```

## Solution

**Language:** Java  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-08-14T08:34:15.515Z  

```java
import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
	    Scanner sc = new Scanner(System.in);
	    
	    String s = sc.nextLine();
	    boolean[] seen = new boolean[128];
	    StringBuilder result = new StringBuilder();
	    
	    for (char c : s.toCharArray()){
	        if(!seen[c]){
	            seen[c] = true;
	            result.append(c);
	            
	        }
	    }
	    result.reverse();
	    System.out.println(result);

	}
}

```

---

[View on CodeChef](https://www.codechef.com/problems/QQQUOC09)