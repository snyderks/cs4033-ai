## Run 1

Bubble sort as small sort, quicksort as large sort, 5 as threshold, input list above threshold

```
?((hybridSort (54 70 -3 -93 89 -46 9 57 8 82 -67) bubbleSort quickSort 5 SL)(pp SL))
Checking length
Got length 11
Above threshold. Using quicksort
Split into two lists: (-3 -93 -46 9 8 -67) (70 89 57 82)
Checking length
Got length 6
Above threshold. Using quicksort
Split into two lists: (-93 -46 -67) (9 8)
Checking length
Got length 3
Using small sort for length 3
Checking length
Got length 2
Using small sort for length 2
Checking length
Got length 4
Using small sort for length 4
(-93 -67 -46 -3 8 9 54 57 70 82 89)

yes
```

## Run 2

Bubble sort as small sort, mergesort as large sort, 5 as threshold, input list above threshold

```
Fril >?((hybridSort (54 70 -3 -93 89 -46 9 57 8 82 -67) bubbleSort mergeSort 5 SL)(pp SL))
Checking length
Got length 11
Above threshold. Using mergesort
Split into two lists: (54 70 -3 -93 89) (-46 9 57 8 82 -67)
Checking length
Got length 5
Above threshold. Using mergesort
Split into two lists: (54 70) (-3 -93 89)
Checking length
Got length 2
Using small sort for length 2
Checking length
Got length 3
Using small sort for length 3
Checking length
Got length 6
Above threshold. Using mergesort
Split into two lists: (-46 9 57) (8 82 -67)
Checking length
Got length 3
Using small sort for length 3
Checking length
Got length 3
Using small sort for length 3
(-93 -67 -46 -3 8 9 54 57 70 82 89)

yes
```

## Run 3

Insertion sort as small sort, quicksort as large sort, 5 as threshold, input list above threshold

```
?((hybridSort (54 70 -3 -93 89 -46 9 57 8 82 -67) insertionSort quickSort 5 SL)(pp SL))
Checking length
Got length 11
Above threshold. Using quicksort
Split into two lists: (-3 -93 -46 9 8 -67) (70 89 57 82)
Checking length
Got length 6
Above threshold. Using quicksort
Split into two lists: (-93 -46 -67) (9 8)
Checking length
Got length 3
Using small sort for length 3
Checking length
Got length 2
Using small sort for length 2
Checking length
Got length 4
Using small sort for length 4
(-93 -67 -46 -3 8 9 54 57 70 82 89)

yes
```

## Run 4

Insertion sort as small sort, mergesort as large sort, 5 as threshold, input list above threshold

```
?((hybridSort (54 70 -3 -93 89 -46 9 57 8 82 -67) insertionSort mergeSort 5 SL)(pp SL))
Checking length
Got length 11
Above threshold. Using mergesort
Split into two lists: (54 70 -3 -93 89) (-46 9 57 8 82 -67)
Checking length
Got length 5
Above threshold. Using mergesort
Split into two lists: (54 70) (-3 -93 89)
Checking length
Got length 2
Using small sort for length 2
Checking length
Got length 3
Using small sort for length 3
Checking length
Got length 6
Above threshold. Using mergesort
Split into two lists: (-46 9 57) (8 82 -67)
Checking length
Got length 3
Using small sort for length 3
Checking length
Got length 3
Using small sort for length 3
(-93 -67 -46 -3 8 9 54 57 70 82 89)

yes
```

## Run 5

Bubble sort as small sort, mergesort as large sort, 5 as threshold, input list below threshold

```
?((hybridSort (54 70 -3 -93) bubbleSort mergeSort 5 SL)(pp SL)) 
Checking length
Got length 4
Using small sort for length 4
(-93 -3 54 70)

yes
```

## Run 6

Bubble sort as small sort, quicksort as large sort, 5 as threshold, input list below threshold

```
?((hybridSort (54 70 -3 -93) bubbleSort quickSort 5 SL)(pp SL)) 
Checking length
Got length 4
Using small sort for length 4
(-93 -3 54 70)

yes
```

## Run 7

Insertion sort as small sort, mergesort as large sort, 5 as threshold, input list below threshold

```
?((hybridSort (54 70 -3 -93) insertionSort mergeSort 5 SL)(pp SL))
Checking length
Got length 4
Using small sort for length 4
(-93 -3 54 70)

yes
```

## Run 8

Insertion sort as small sort, quicksort as large sort, 5 as threshold, input list below threshold

```
?((hybridSort (54 70 -3 -93) insertionSort quickSort 5 SL)(pp SL))
Checking length
Got length 4
Using small sort for length 4
(-93 -3 54 70)

yes
```
