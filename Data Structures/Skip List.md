#DataStructures #ProbabilisticDataStructures 

A set of [Linked Lists](./Linked%20List.md).

# Prerequsites
Let's assume that we have a page with items to sell, so we have next use-cases:
* Put up item for sale (Insertion)
* Search an item by criteria (Search)
* Remove item from sale (Deletion)

Linked list doesn't fit these requirements well, because a search is linear. [Array](./Array.md) too, because we can't insert items there. So, we will combine the best features of both.

# Description
We have a base linked list with all the items and additional layers where half of the previous layer items are skipped (this is why it is called a skip list). We start a search from the top layer; if the search fails, we move to the next item in the next layer (this is why we use linked lists for implementation). Therefore we have a logarithmic search complexity because the number of layers is log(length), as every layer contains only half of the items from the previous layer.

# Complexity

| Operation | Complexity |
|-----------|------------|
| Insertion | O(log n)   |
| Search    | O(log n)   |
| Deletion  | O(log n)   |
| Space     | O(n)       |
