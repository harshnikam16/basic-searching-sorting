# Selection Sort Algorithm

## Algorithm
1. **Start**
2. Define an array
3. For each element `i` from array
   - For each element `j` from array:
     - If `array[j] < array[minIndex]`, update `minIndex`
   - Swap `array[i]` with `array[minIndex]`
4. **End**

## Pseudocode
```
START
    INPUT array
    FOR i from 0 to length of array - 1
        minIndex = i
        FOR j from i + 1 to length of array
            IF array[j] < array[minIndex]
                minIndex = j
        SWAP array[i] and array[minIndex]
    END FOR
END
```
