# ParallelQuickSort

This repository features a project that was undertaken as a part of a student assignment, aiming to delve into the intricacies of the QuickSort algorithm, notably its parallel and non-parallel versions, implemented in C++. The QuickSort algorithm is a powerful and efficient sorting technique based on the divide-and-conquer approach, renowned for its superior average-case time complexity of O(n log n).

This implementation uses a random number function to generate a large array of floating-point values. The QuickSort algorithm is then applied to this array, with both parallel and non-parallel variants of the algorithm being used.

The parallel QuickSort version stands as a focal point of this project. It embodies the principles of multi-threading, a concept that allows a single process to be divided into multiple threads, thereby harnessing the power of modern multi-core processors. This parallel version dynamically creates new threads for each recursive call to the sorting function up to a defined maximum level, contributing to a significant reduction in sorting time when dealing with large data sets.

On the other hand, the non-parallel QuickSort provides a baseline for comparison, demonstrating the traditional single-threaded execution of the algorithm. The program meticulously measures and outputs the execution times for both parallel and non-parallel modes, clearly showcasing the performance advantage conferred by parallel computing.

The project also incorporates a check function, confirming the correct sorting of the array after each run, thereby ensuring the reliability and accuracy of the implemented algorithms.
