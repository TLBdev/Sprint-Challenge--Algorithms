#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)
polynomial complexity O(n^3)

b)
logarithmic complexity O(nlog(n))

c)
linear complexity O(n)
## Exercise II
drop the egg from the center floor if it breaks forget all floors above it, if not all floors below it
repeat until you only have one floor remaining that will be floor f

findsweetspot(n)
    floors = [i+1 for i in range n]
    while floors.length < 1:
        
        x = floors.length//2
        
        if egg dropped from n[x] breaks:
            floors = floors[:x]
        else:
            floors = floors[x+1]
    return floors[0]

O(log(n))


