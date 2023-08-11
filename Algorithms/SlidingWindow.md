The sliding window technique consistently follows a specific pattern. Initially, two pointers, denoted as `l` (left inclusive) and `r` (right exclusive), are established. Additionally, a container is utilized to store elements within the window, which can take the form of a `Set`, `Map`, or a simple array. During each progression of the right pointer (`r++`), conditions are evaluated, prompting adjustments to the left pointer as necessary.

```javascript
let l = 0, r = 0;
while(r < arr.length) {
    const ele = arr[r]; // ele is the element which is going to load into the sliding window.
    // other algorithm
    /**
     * while( ... ) {
     *     // other algorithms about the left boundary
     *     l++
     * }
     *
    */
    r++;
}
```