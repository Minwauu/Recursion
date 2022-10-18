# Recursion

Recursion occurs in situations where an object partially consists of or is defined in terms of itself e.g tree braches. The power of recursion lies in its possibility of defining an infinite set of objects by a finite statement.

**E.g**

Recursive Picture = Recursive Picture + Recursive Picture x Magnification factor of 0.9

The recursive definition of a list is:

- The empty list with zero items in it, or
- An item followed by a list

The true usefulness of a recursive definiton comes from going the other way:
  
    If what you are dealing with meets the recursive definiton, then there is usually a way to move back towards the base     
    case, getting simpler and simpler along the way. 
    
**All recursive functions/procedures follow a similar pattern:**
- Am i at the base case? If so, return the easy solution if a function, and stop recursing; if a procedure stop recursing.
- Otherwise, think in terms of solving the current problem by moving closer to the base case with a slightly simpler problem and moving this simpler problem.

Examples:

https://replit.com/@Minwauu/Intro-to-Recursion#main.py

