# Dynamic Memory Management Visualizer


##  Description
This project is a step-by-step simulation tool built using HTML, CSS, and JavaScript that demonstrates core memory management techniques such as paging, segmentation, and virtual memory. The user can input parameters like page references, frame sizes, or segment details, and the tool visually represents how memory is allocated and managed. Unlike real-time systems, this simulator updates memory status based on user actions (e.g., clicking "Next Step" or "Simulate") rather than continuous live updates.LRU).

## Module-Wise Breakdown
### Module 1: Paging Module
-Implements FIFO and LRU page replacement algorithms.
-Simulates how pages are loaded, replaced, and faults are handled.
-Operates step-by-step through a user-controlled interface.

#### Key Functions:
-Accepts page reference strings and frame size from the user.
-Updates memory frames on each step (button click).
-Highlights page hits and faults visually.

###Module 2: Segmentation Simulation Module
-Simulates logical segmentation (e.g., stack, code, heap).
-Accepts user-defined segments and memory size.
-Displays how segments are mapped into memory blocks.

###Key Features:

-User submits segment base and limit values.
-Simulator displays segment allocation statically or in steps.
-Detects and flags invalid segment accesses.

###Module 3: Visualization Module
-Uses HTML elements (e.g., grids, tables, or canvas) to represent memory.
-Updates visuals only after user input or step command.
-No background animation or automatic update loop.

Key Features:
-Color-coded memory cells.
-Visual representation of memory frames or segments.
-Optional step-tracking to review past allocations.

###Module 4: Graphical User Interface (GUI) Module
-Designed with HTML/CSS for layout and styling.
-Controlled using JavaScript to handle simulation logic and DOM updates.
-Provides a clean, intuitive interface for user interaction.

###Key Features:
-Input forms for memory size, page/segment data.
-Buttons for simulation control (Start, Next Step, Reset).
-Displays output such as page fault count, memory usage, etc.

Contributors:
- @Muneendra007
- @rishav-18
- @MANOJKORPU

