# Over-view

Implementation of sorting visualizers using the concepts of JavaScript and ReactJS.
Usage of class components and functional components to highlight the element that is being used during sorting process.
To help visualize complex sorting algorithms easily by colouring of the required element.

# User Interface & Explanation

This is a simple front end User Interface for sorting visualizers, wherein the randomly generated array is being represented in the form lines. Wherein each line is a element within it.

![Screenshot 2024-05-24 220228](https://github.com/AdityaDighe/Sorting-Analyzers/assets/98305705/bb46d264-6511-403b-b519-be0bc2b9bf3a)

After clicking on whichever sort function the user prefers to the sorting algorithm is started such that DOM gets manipulated and the elements are swapped in sequential order.
If there is a partition that is being used then it is also represented by colours of different variety.

![Screenshot 2024-05-24 220359](https://github.com/AdityaDighe/Sorting-Analyzers/assets/98305705/f3dedef8-973f-40f3-ae28-6cc342616384)

Until the time the sorting process is not completed all the elements or div on the page remain disabled.
The user can also manually adjust the speed of sorting (which is kept at 1000ms) as the delay.
Also the user can adjust the size of the array using the slider.

![image](https://github.com/AdityaDighe/Sorting-Analyzers/assets/98305705/a0b91eb4-0019-4121-9e9f-40f137e592c4)

Once the sorting is done and all the array elements are in green, the enable parameter is passed to the elements document query selector and a person can restart the process again.
