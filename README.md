# CPPDS_selection_insertion_bubble_sorting
A Sorting Algorithm is used to rearrange a given array or list of elements according to a comparison operator on the elements. The comparison operator is used to decide the new order of elements in the respective data structure.
![image](https://github.com/Yaduraj01/CPPDS_selection_insertion_bubble_sorting/assets/110488113/4f33da69-65f7-4a63-9fdb-51d59df620b6)

Selection Sort
In selection sorting technique, the smallest element is fetched by comparing itself with the rest of the elements and sorted at the array's first position. The complete array is divided into two halves, the sorted subarray on the left and the unsorted subarray on the right. Once the first element is sorted, the search for the second minimum element begins from the rest of the array and is positioned at second place.

Insertion Sort
In this sorting technique, the elements are sorted by comparing the elements with their previous elements. It starts by comparing the second element with the first element. If the second element is smaller than the first, then we will swap it.

Bubble Sort
Bubble sort is one of the most straightforward sorting algorithms. In this sorting technique, we begin by comparing the first two elements of the array and checking if the first element is greater than the second element; if it is, we will swap those elements and move forward to the next element.

## Algorithm
Here's the algorithm for the provided C++ program that sorts an array using Selection Sort, Insertion Sort, or Bubble Sort based on user input:

1.Start
2.Declare an integer variable n to store the number of elements in the array.
Output "Enter the number of elements in the array: " to prompt the user for input.
Read the value of n from the user.
3.Declare an integer array arr of size n to store the elements of the array.
Output "Enter n elements of the array: " to prompt the user for the array elements.
Use a loop to read and store the n elements in the arr array.
4.Declare an integer variable choice to store the user's choice of sorting algorithm.
Output "Choose a sorting algorithm:".
Output "1. Selection Sort".
Output "2. Insertion Sort".
Output "3. Bubble Sort".
Output "Enter your choice: " to prompt the user for their choice.
5.Read the value of choice from the user.
6.Use a switch statement to perform the selected sorting algorithm based on the value of choice:
a. If choice is 1, call the selectionSort(arr, n) function to perform Selection Sort.
b. If choice is 2, call the insertionSort(arr, n) function to perform Insertion Sort.
c. If choice is 3, call the bubbleSort(arr, n) function to perform Bubble Sort.
d. If choice is none of the above, output "Invalid choice" and return 1 to exit the program.
Output "Sorted array: " to indicate the sorted array.
7.Use a loop to display the elements of the sorted arr array.
8.End
The program provides the user with a menu to choose a sorting algorithm and then displays the sorted array using the selected sorting technique.

## Output
![image](https://github.com/Yaduraj01/CPPDS_selection_insertion_bubble_sorting/assets/110488113/749fdd53-27c6-43d2-a210-2d905f7d91f2)

![image](https://github.com/Yaduraj01/CPPDS_selection_insertion_bubble_sorting/assets/110488113/2c31b2d7-0bdf-43f7-8445-905a5f541c50)

![image](https://github.com/Yaduraj01/CPPDS_selection_insertion_bubble_sorting/assets/110488113/62f59d1b-5634-4939-a3de-0916a29990a2)

![image](https://github.com/Yaduraj01/CPPDS_selection_insertion_bubble_sorting/assets/110488113/fb2c320f-a7b2-44f4-80b0-a5ac28ecd808)

![image](https://github.com/Yaduraj01/CPPDS_selection_insertion_bubble_sorting/assets/110488113/7df952ff-ca1e-4999-88c0-cfc53b9b2517)

![image](https://github.com/Yaduraj01/CPPDS_selection_insertion_bubble_sorting/assets/110488113/55e28374-6415-4f7e-832f-877ab61afcde)






