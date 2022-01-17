# sorting-time-complexity-analysis

## Overview
This assignment demonstrated how each sorting algorithms' time complexity behaves in relation to the amount of input(n). By calculating the amount of time spent on sorting incremented amount of random integers into each sorting algorithms, I was able to obtain a graphical relationship between numbers of input and the amount of time it used to complete each sorting task. 

## Implementation
This demonstration compares 4 of the common sorting algorithms: insertionSort, mergeSort, quickSort, and heapSort. Each sorting algorithms will be sorting 10,000 random integers with incrementation of 10,000 more random integers for 10 times.

To ensure each sorting algorithms are getting the same set of random nubmers in each increments, deep copies of random integer array were implemented

![image](https://user-images.githubusercontent.com/84875731/149714345-f8596480-f49d-4b20-bc86-4ebd6783c230.png)

The amount of time each algorithms used was conducted by subtracting the ending System.currentTimeMillis() and starting System.currentTimeMillis().

![image](https://user-images.githubusercontent.com/84875731/149714828-a8b42822-b818-4c45-b967-eb76e8dc0447.png)



