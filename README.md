# Dynamic Memory Management Visualizer


##  Description
The project is a tool to simulate and visualize memory management techniques like paging, segmentation, and virtual memory. It allows user-defined inputs for memory allocation, page faults, and replacement algorithms (FIFO, LRU).

## Module-Wise Breakdown
### Module 1: Paging Module
- Implements **FIFO** and **LRU** page replacement algorithms.
- Tracks page faults and updates memory frames dynamically.
- Maintains a history of page allocations for visualization.

#### Key Functions:
- Dynamically allocates memory in the heap at runtime.
- Supports single and multiple block memory allocation.
- Allows resizing of previously allocated memory.
- Frees allocated memory to prevent memory leaks.

#### Key Functions:
- Manages memory blocks dynamically in the heap.
- Allocates and deallocates memory as per user/program needs.
- Tracks memory fragmentation and available memory.
- Ensures efficient memory utilization and prevents memory leaks.

### Module 3: Visualization Module
- Uses **Matplotlib** to graphically represent memory changes over time.
- Displays page frames and their updates at each step.
- Provides a clear timeline of memory allocation.

#### Key Functions:
- Allocates memory for function calls and local variables.
- Automatically frees memory when function execution completes.
- Manages function call stack and recursion depth.
- Prevents stack overflow by managing function calls effectively.

### Module 4: Graphical User Interface (GUI) Module
- Built with **Tkinter** to provide a user-friendly interface.
- Allows users to input page requests, frame sizes, and segment details.
- Displays results and page fault counts using message boxes.

#### Key Functions:
- Graphically represents memory usage (Heap vs Stack).
- Tracks memory allocation, deallocation, and fragmentation.
- Provides real-time updates on memory consumption.
- Helps in identifying inefficient memory usage.

Contributors:
- @Muneendra007
- @rishav-18
- @MANOJKORPU

