# ExternalSort
Java: External Sort
In this programming assignment, I am tasked with implementing an external sort solution. The objective is to sort a large number of data elements in ascending order, taking advantage of disk operations and utilizing the Comparable natural ordering of the elements.

Due to the size of the data, it cannot all be accommodated in the main memory. As a result, the external sort approach involves a series of steps. Firstly, I need to load a portion of the data into memory, sort it, and save it as a new file known as a run. This process is repeated until all the data is saved in separate runs.

The next step is to merge these runs together through a series of merges, gradually creating a single sorted run that contains all the data. This allows for efficient access to the data in the desired ascending order.
