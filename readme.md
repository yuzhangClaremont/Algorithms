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

![makechange](https://user-images.githubusercontent.com/31321544/40359796-891841fc-5df6-11e8-9051-2cfd3d617629.png = 200x200)



path problem: for every decision tree, choose branch with least cost

39 min
2-d array peak, point is a peak iff it's >= than all points in the east, west, north,and south
find a peak in a 2-d array

