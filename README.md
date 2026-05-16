# Activity-4a

1) Insertion sort works by inserting each element into it's correct postion.
   The average case, the total operation follow thus pattern:
   1+2+3+...+(N-1) = N(N-1)/2
   Big 0 ignores constants, so the average case time complexity is 0(N^2)


 2a -> i=1 
        i comparison + 1 shift =2
        i =2 +2 =4
        i=3 +3 =6
        i=4 +4 =8
 Total = 2+4+6+8 = 20 operations

   b -> i=2 =4 operations
        i=3 =6 operations
        i=4 =8 operations
 Total = 4+6+8 = 18 operations
    i=3 = 6
    i=4 = 8
 Total = 6+8 = 14 operations

   c -> No it doesnt sort the entire array bc trhe insertion sort assumes the left side of the array is already sorted.

3)
   a -> The function loops through the entore strong from 0 to string.length -1. Even if the value is found early the fucntion still checks all the N characters so, the time complexity grow linear. Time Complextiy = 0(N)

  b -> (on a diff file 3b codex.js)
  Improved version stops immediately when x/value is found
  Best case = 0(1)
  Worst case = 0(N)
