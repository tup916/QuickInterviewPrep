# QuickInterviewPrep
A cheat-sheet for interviews - reminder of things I don't generally use on a day-to-day basis


Data Structures and When To Use Them

HashTables
  Quick lookup/addition
  Need your data to be hashable
  
Heap
  Need your data to be comparable
  
Trees
  Need your data to be comparable
  
Stacks
  Used for recursion
  Any type of data

Queues
  Used for BFS
  Any type of data
  



The equals method implements an equivalence relation:
It is reflexive: for any reference value x, x.equals(x) should return true.
It is symmetric: for any reference values x and y, x.equals(y) should return true if and only if y.equals(x) returns true.
It is transitive: for any reference values x, y, and z, if x.equals(y) returns true and y.equals(z) returns true, then x.equals(z) should return true.
It is consistent: for any reference values x and y, multiple invocations of x.equals(y) consistently return true or consistently return false, provided no information used in equals comparisons on the object is modified.
For any non-null reference value x, x.equals(null) should return false.
