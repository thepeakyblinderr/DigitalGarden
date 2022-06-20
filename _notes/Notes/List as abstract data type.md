[[list]]

![[List as abstract data type 2022-05-28 22.59.31.excalidraw|700]]

When array is full , create new array and copy previous array and free the memory of old array
This is **time costly**
*We create new array double the size of previous array* 

**Access** : read/write element in array , it takes *constant time*
hence *O(1)* {big O of 1}

**Insert** : T $\propto$ n
hence *O(n)* {big O of n}
because depending on the position
- if i want to insert at first position then all the remaining has to move
- if i want to insert at middle then half has to move
- so above both operation has *different time* 

**Adding ele at end** : it will be *constant time* *O(1)*, if array is not full 
but if full then *O(n)*
