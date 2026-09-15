## Overview

Sort an array of 9 integers using bubble sort. The array is worked on in place using pointers, following the compare/swap pattern discussed in the assignment. 

## Functions

### printValues

* Print an opening bracket
* Loop through each position in the array, from the first to the last
* Print the value at that position, followed by a space
* After the loop ends, print a closing bracket and move to a new line



### swap

* Create a temporary varable to hold a value during the swap
* Store the value pointed to by the first pointer into the temporary variable
* Store the value pointed to by the second pointer into the location of the first pointer
* Store the temporary variable's value into the location of the second pointer



### sort

* Create two counter variables, i and j
* Outer loop: repeat once for every position in the array, using i to count from the first position to the last
* Inner loop: for each pass of the outer loop, use j to count from the first position up to the second-to-last position
* If the value at position j is greater than the value at position j+1, swap those two positions
* After each swap, call printValues to show the array's current state
* Once both loops finish, the array is sorte

### main
* Create an array of 9 integers with the starting values {7, 3, 9, 4, 6, 1, 2, 8, 5}
* Print "Before:"
* Call printValues on the array
* Create two integer variables, x and y, set to 3 and 5
* Print the values of x and y
* Call swap on the addreses of x and y
* Print the values of x and y again to confirm the swap
* Call sort on the array
* Print "After:"
* Call printValues on the array

