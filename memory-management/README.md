# Memory Management Laboratory Activities

This project implements various memory management techniques in Java, focusing on key concepts such as memory allocation strategies, paging, segmentation, page replacement algorithms, and demand paging.

## Laboratory Activities

### Lab Activity 1: Memory Allocation Strategies
- **Objective**: Implement and compare First-Fit, Best-Fit, and Worst-Fit memory allocation strategies.
- **Description**: The program accepts a list of block sizes and process sizes, allocates memory based on the chosen strategy, and outputs the allocation results along with remaining memory.

### Lab Activity 2: Paging System Simulation
- **Objective**: Understand paging by simulating logical-to-physical address translation.
- **Description**: Users provide the number of pages, frame size, and page table mapping. The system translates logical addresses to physical addresses and visualizes memory frames.

### Lab Activity 3: Segmentation Implementation
- **Objective**: Implement a segmentation-based memory management system.
- **Description**: Simulates segmentation by defining segments (e.g., Code, Data, Stack), allowing user input for segment sizes and logical addresses, and converting logical addresses to physical addresses with error handling for out-of-bound access.

### Lab Activity 4: Page Replacement Algorithms
- **Objective**: Understand memory management under demand paging and page replacement.
- **Description**: Implements FIFO, LRU, and Optimal page replacement algorithms. Given a reference string and number of frames, it simulates page replacement and counts page faults.

### Lab Activity 5: Demand Paging Simulation
- **Objective**: Simulate how demand paging works in virtual memory systems.
- **Description**: Implements a basic demand paging system that handles page requests, loads pages into memory as needed, and logs page faults and memory state during execution.

## Running the Project

1. Ensure you have Java and Maven installed on your machine.
2. Clone the repository or download the project files.
3. Navigate to the project directory in your terminal.
4. Use the following command to compile and run the project:
   ```
   mvn clean install
   mvn exec:java -Dexec.mainClass="src.LabActivity1"  # Replace with the desired LabActivity class
   ```

## Contribution

Feel free to contribute to this project by adding new features or improving existing functionalities. Please ensure to follow the coding standards and guidelines.

## License

This project is licensed under the MIT License - see the LICENSE file for details.