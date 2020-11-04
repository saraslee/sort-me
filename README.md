# Sort Me


## About: 
I created a web app that allows a user to visualize different sorting algorithms.  The sorting algorithms were coded using JS and the user interface was programmed using HTML and CSS.  I completed this project to solidify my understanding of bubble sort and merge sort while also practicing front end development and efficient designs.  I plan on adding a timer and more sorting algorithms to my web app.  


## Bubble Sort 
Bubble Sort is the simplest sorting algorithm that works by repeatedly swapping the adjacent elements if they are in wrong order. Bubble sort has a worst-case and average complexity of О(n2), where n is the number of items being sorted. 

First Pass:
( 5 1 4 2 8 ) –> ( 1 5 4 2 8 ), Here, algorithm compares the first two elements, and swaps since 5 > 1.
( 1 5 4 2 8 ) –>  ( 1 4 5 2 8 ), Swap since 5 > 4
( 1 4 5 2 8 ) –>  ( 1 4 2 5 8 ), Swap since 5 > 2
( 1 4 2 5 8 ) –> ( 1 4 2 5 8 ), Now, since these elements are already in order (8 > 5), algorithm does not swap them.

Second Pass:
( 1 4 2 5 8 ) –> ( 1 4 2 5 8 )
( 1 4 2 5 8 ) –> ( 1 2 4 5 8 ), Swap since 4 > 2
( 1 2 4 5 8 ) –> ( 1 2 4 5 8 )
( 1 2 4 5 8 ) –>  ( 1 2 4 5 8 )

And so forth.  


## Merge Sort 
Merge Sort is a divide and conquer algorithm. It divides the input array into two halves, calls itself for the two halves, and then merges the two sorted halves.  Merge sort has a worst case time complexity of O(n log n).  





