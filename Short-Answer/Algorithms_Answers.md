snippet 1:  well the first code snippet works out to n^3 but i dont recognize that so
maybe it's O(n^2).

snippet 2:  O(n^2) this one 

snippet 3: bunny ears: O(n) it is a 1 to 1 increase. input increase by 1 so does the steps to complete.

Exercise 2:

n = stories
f = unknown floor

Step 0: do this until you get a return of zero
Step 1: find the median of stories  len(n) / 2
    do until it returns a zero
Step 2: Drop an egg at the median and see if it breaks.
    while loop until it returns a zero
        If it breaks then choose the left number and find the median between it and 0.
            (recursion). repeat until you reach the last value
        else if it doesnt break choose the number to the right and find the median between it and the highest floor.
            (recursion)repeat this loop until you reach the last value
        else
            the safe floor is either going to be one less or one more than 
            the current value - depending on if you came from the left or the
            right side of the recursion sort.