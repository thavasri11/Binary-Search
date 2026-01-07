# Binary Search in Java

## Description
This program demonstrates the Binary Search algorithm using Java.
Binary Search works on a sorted array by repeatedly dividing the search interval in half.

## Algorithm
1. Start
2. Initialize a sorted array
3. Read the element to be searched
4. Set low = 0 and high = array length - 1
5. While low <= high:
   - Find mid = (low + high) / 2
   - If array[mid] == key, element is found
   - If array[mid] < key, search right half
   - Else search left half
6. If element not found, display message
7. End

## Output
The program prints the index if the element is found,
otherwise it prints "Element not found".
