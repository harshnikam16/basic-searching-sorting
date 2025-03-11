# Insertion Sort Algorithm

## Algorithm
1. **Start**
2. Define an array
3. For each element `i` from array:
   - Compare `key` with elements before it (`j = i-1`)
   - Shift elements greater than `key` one position to the right
   - Insert `key` at the correct position
4. **End**

## Pseudocode
```
START
    INPUT array
    FOR i from 1 to length of array - 1
        key = array[i]
        j = i - 1
        WHILE j >= 0 AND array[j] > key
            array[j + 1] = array[j]
            j = j - 1
        array[j + 1] = key
    END FOR
END
```
