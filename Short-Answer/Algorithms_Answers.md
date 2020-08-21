#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) because it is a single loop that runs n amount of times


b) O(n^2) because of the nested loop


c) O(n) because it calculates the number of ears based on the bunnies recursively n amount of times

## Exercise II

My first pass solution would be to drop eggs off of each story till you find floor f but that is too slow and doesnt minimize the eggs dropped. So my second solution would be me making a binary search that checks for the levels that the eggs have been broken. Then we could find the eggs that werent broken and grab the solve floor f. The time complexity of this would be (log(n)).
