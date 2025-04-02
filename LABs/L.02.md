
# L.02 - Logic Programming [2] 

## List 

Syntax:  [Head|Tail]  

## Exercises

Consider a representation of sets as lists. Define the following predicates:  
- member(X,L), which holds iff the element X occurs in L.
- subset(L,K), which holds iff L is a subset of K.
- disjoint(L,K), which holds iff L and K are disjoint (i.e. they have no elements in common).
- union(L,K,M), which holds iff M is the union of L and K.
- intersection(L,K,M), which holds iff M is the intersection of L and K.
- difference(L,K,M), which holds iff M is the difference of L and K.

Ex.  
- Find the last element of a list.
- Find the K'th element of a list.
- Reverse a list.


## REF
- https://www.let.rug.nl/bos/lpn//lpnpage.php?pagetype=html&pageid=lpn-htmlse13
- https://swish.swi-prolog.org/p/qXEEGEnH.swinb
