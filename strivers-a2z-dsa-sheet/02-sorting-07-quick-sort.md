Implement quick sort algorithm.

> [!NOTE]
> Pick a element (generally first element of the array) as pivot and partition the array in two halfs such that left half contains all elements smaller than or equal to pivot and right half contains all elements greater than pivot.  
> **Algorithm**
> 1. Pick first element as `pivot`. 
> 2. Maintain two pointers `l` (points to first index) and `r` (points to last index).
> 3. Move `l` to right until it is less than `r` and element at index `l` is less than or equal to `pivot`.
> 4. Move `r` to left until it is greater than `l` and element at index `r` is greater than `pivot`.
> 5. If `l < r`, it means element at index `l` is greater than `pivot` and element at index `r` is less than or equal to `pivot`.
> 6. Swap element at index `l` and `r`.
> 7. Repeat steps `3` to `6` until `l` is less than `r`.
> 8. Now `r` is the index of pivot in sorted order, i.e. if array would have been sorted, `pivot` would have been at index `r`.