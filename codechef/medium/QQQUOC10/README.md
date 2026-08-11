# QQQUOC10

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

_Description not available._

## Solution

**Language:** Java  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-08-11T07:11:42.476Z  

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

[View on CodeChef](https://www.codechef.com/problems/QQQUOC10)