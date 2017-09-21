# Homework from 20th September 2017

1. Write a function to read a graph given in the format ``facebook_combined.txt``. The function should take as input the file name, and return the Sage graph.

2. Write a function to take a random sample of size ``n`` pairs of vertices from a graph ``G``, and return the average of the distances betweem those points. Suggested format is:
```
def average_distance_from_sample(G, n):
    """
    Return the average distance between ``n`` randomly selected
    pairs of points from the graph ``n``.

    INPUT:

    ``G`` - Sage graph.
    ``n`` - positibe integer (sample size)

    OUTPUT:

    floating point real number.
    """
 ```
 You can assume that the graph is connected.
 