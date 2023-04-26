# bubble-sort
Bubble Sort is the simplest sorting algorithm that works by repeatedly swapping the adjacent elements if they are in the wrong order. This algorithm is not suitable for large data sets as its average and worst-case time complexity is quite high.

 ![image](https://user-images.githubusercontent.com/125429673/234466931-e6ed5065-a8b3-42cf-8707-85b869d8b6a1.png)


Follow the below steps to solve the problem:

Run a nested for loop to traverse the input array using two variables i and j, such that 0 ≤ i < n-1 and 0 ≤ j < n-i-1

If arr[j] is greater than arr[j+1] then swap these adjacent elements, else move on

Print the sorted array

Start with an array of unsorted numbers

Define a function called “bubbleSort” that takes in the array and the length of the array as parameters

In the function, create a variable called “sorted” that is set to true

Create a for loop that iterates through the array starting at index 0 and ending at the length of the array -1

Within the for loop, compare the current element with the next element in the array

If the current element is greater than the next element, swap their positions and set “sorted” to false

After the for loop, check if “sorted” is false

If “sorted” is false, call the “bubbleSort” function again with the same array and length as parameters

If “sorted” is true, the array is now sorted and the function will return the sorted array

Call the “bubbleSort” function with the initial unsorted array and its length as parameters to begin the sorting process.
