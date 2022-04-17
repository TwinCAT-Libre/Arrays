# Arrays
Library of functions for single dimension arrays


## Function Blocks
None

## Functions

### fn_ArrayAvg
Returns the average value of an array of any numerical type

Usage:
```
ArrAvg:REAL;
-----------------------
ArrAvg := fn_ArrayAvg(_array,array[0]);
```

### fn_ArrayInfo

Returns the information of an array of any numerical type:
average, sum, number of elements(size), largest value, location of largest value, smallest value, location of smallest value, range

Usage:
```
ArrInfo:st_ArrayInfo;
------------------------
ArrInfo := fn_ArrayInfo(_array,array[0]);
```

### fn_ArrayMax
Returns the largest value from an array of any numerical type

Usage:
```
ArrMax:REAL;
-----------------------
ArrMax := fn_ArrayMax(_array,array[0]);
```

### fn_ArrayMin
Returns the smallest value from an array of any numerical type

Usage:
```
ArrMin:REAL;
-----------------------
ArrMax := fn_ArrayMin(_array,array[0]);
```

### fn_ArraySize
Returns the number of elements in an array of any type

Usage:
```
ArrSize:UINT;
-----------------------
ArrSize := fn_ArraySize(_array,array[0]);
```

### fn_ArraySum
Returns the sum of all values in an array of any numerical type

Usage:
```
ArrSum:REAL;
-----------------------
ArrSum := fn_ArraySum(_array,array[0]);
```

## DUTs

### st_ArrayInfo
Structre of for use with fn_ArrayInfo

### st_ArrayInfoExt
Structre of for use with fn_ArrayInfoExt (Future)

### u_NumPointer

Union of pointers to all numerical types
