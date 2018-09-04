# itertools-snippets

Itertools functions with examples easy to reuse.

 1 # count(start=0, step= 1)
 2 # cycle(iterable)
 3 # repeat(object[,times])

 4 # accumulate(iterable[, funct])
 5 # chain(iterable1, iterable2)
 6 # chain.from_iterable(['ABC', 'DEF']) --> A B C D E 
 7 # compress(iterable, selectors)
 8 # dropwhile(predicate, iterable)
 9 # filterfalse(lambda x: x%2, range(10)) --> 0 2 4 6 8
10 # groupby(iterable, key=None)
11 # islice(iterable, start, stop[, step])
12 # starmap(func, iterable)
13 # takewhile(lambda x: x<5, [1,4,6,4,1]) --> 1 4
14 # tee(iterable, n=3)
15 # zip_longest(iterable, iterable, fillvalue)

16 # combinations(iterable, n=3)
17 # combinations_with_replacement(iterable, n=3)
18 # product(*iterable, repeat=1) 
19 # permutations(iterable, r=None)
