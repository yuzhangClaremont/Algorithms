readme.md

MIT algo
https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/lecture-videos/lecture-1-algorithmic-thinking-peak-finding/

# Greedy algorithm
fast, easy, but only locally optimal

## most interval problem
have as many intervel as pussible: https://www.youtube.com/watch?v=BWlXudP7Unk
1. pick shortest
2. cross off all the overlaps
3. pick the next shortest

__not correct__

or
1. pick the earlist intervels

__not work__

or
1. pick intervals finish earlest
2. cross off overlaps
3. pick the next finish earlest

https://www.youtube.com/watch?v=277RLZmhTK4
__this works, run time theta(n^2)__
__the brute force method will be O(2^n)__

or
1. pick the one starts latest
2. corss overlapps
3. recurse to next starts latest

## make change problem
https://www.youtube.com/watch?v=UcIW0AqSQ4g
make change of the target using lest coins in a list

<img src="https://user-images.githubusercontent.com/31321544/40359796-891841fc-5df6-11e8-9051-2cfd3d617629.png" width="400">
greedy algorithm works iff A=[1, b, b^2, b^3...]


## greedy path problem: 
for every decision tree, choose branch with least cost

39 min
2-d array peak, point is a peak iff it's >= than all points in the east, west, north,and south
find a peak in a 2-d array

# Divide and Conquer

why want to sort?
1. after sort, use O(1) to find median
2. able to use binary sort to find certain element, use O(lgn) time instead of O(n)
3. to compress data

## insertion sort
insert A[i] to an sorted array A[0:i-1] by pair swapping to the correct position
A = [5,2,4,6,1,3]
A= A[0] = [5], key A[1]= 2 -> swap 5,2 -> A[2,5,4,6,1,3]
key move to 2, A[2]=4 -> swap 5,4 ->A[2,4,5,6,1,3]

key move n times, O(n^2) runtime
(http://csrgxtu.github.io/2015/03/20/Writing-Mathematic-Fomulars-in-Markdown/ markdown math)

## Merge Sort
1. divide array into two part
2. recursively divide the two arrays until they have 1 elements, and they are natually sorted
3. merge the two sorted arrays by two finger methods. Comparing two tracks, and copy to a merged array
4. runtime O(n)
5. recursive relation: T(n) = c1(divide) + 2T(n/2) (recurse) + cn (merge)
<img src="https://user-images.githubusercontent.com/31321544/40533633-f9a7b11e-6035-11e8-8f84-edced62009eb.png" width = 400>
