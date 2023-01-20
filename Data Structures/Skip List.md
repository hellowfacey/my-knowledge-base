#DataStructures #ProbabilisticDataStructures 

A set of [[Linked List]]s.

# Prerequsites
Let's assume, that we have a view of items to sell, and we have next use-cases:
* Put up item for sale (Insertion)
* Search an item by criteria (Search)
* Remove item from sale (Deletion)

[[Linked List]] doesn't fit these requirements well, because search is linear. [[Array]] too, because we can't insert item there. So, we will combine the best features of both.

# Description
We have a base [[Linked List]] with all the items, and we have additional layers, where half of items of previous layer are skipped (this is why it called a skip list). We start search from the top layer, if search failed, then we moved to the next item in the next layer (this is why we choose [[Linked List]]), therefore we got a logarithmic search, because number of layers is log(length) as every layer contain only a half of items from previous layer.

# Complexity

| Operation | Complexity |
|-----------|------------|
| Insertion | O(log n)   |
| Search    | O(log n)   |
| Deletion  | O(log n)   |
| Space     | O(n)       |
