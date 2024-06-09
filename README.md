The Sorting Visualizer project is a detailed C++ application that uses the SDL2 library to create a visual representation of different sorting algorithms.

Key Features:
Graphical Display: The application opens an SDL window where bars of varying heights represent array elements, facilitating an intuitive understanding of sorting processes.
User Interactivity: Users can generate new random lists, and initiate different sorting algorithms using keyboard controls.
Sorting Algorithms:
Selection Sort: Repeatedly selects the minimum element from the unsorted portion and moves it to the beginning.
Insertion Sort: Builds the sorted array one element at a time by repeatedly picking the next element and inserting it into the correct position.
Bubble Sort: Repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order.
User Controls:
0: Generate a new random list.
1: Start selection sort.
2: Start insertion sort.
3: Start bubble sort.
q: Exit the visualizer.
Implementation Details:
Initialization: The init function sets up SDL, creating a window and renderer.
Visualization: The visualize function updates the display to show the current state of the array, highlighting elements being compared or swapped.
Sorting Functions: Each sorting algorithm is implemented with visualization calls to illustrate the algorithm's progress.
Main Execution Loop: The execute function handles events and controls the main loop of the application, calling sorting functions based on user input.
This project not only helps users understand how different sorting algorithms work but also provides a practical example of using SDL2 for graphical applications in C++.
