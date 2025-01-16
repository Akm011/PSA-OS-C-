### **C++ Project: OS CPU Scheduling Algorithms**

**Project Description:**
This project is an implementation of various **CPU scheduling algorithms** in C++ to simulate and analyze how different scheduling techniques manage process execution in an operating system. These algorithms are fundamental to optimizing CPU usage, reducing waiting time, and ensuring fair resource distribution.

---

### **Key Features and Algorithms:**

1. **First Come First Serve (FCFS)**:
   - Processes are executed in the order of their arrival.
   - Non-preemptive scheduling with simple queue-based implementation.
   - Suitable for batch systems.

2. **Round Robin (RR)**:
   - Processes are executed in a cyclic manner with a fixed time quantum.
   - Preemptive scheduling designed for time-sharing systems.
   - Ensures fair CPU allocation among all processes.

3. **Shortest Process Next (SPN)**:
   - Selects the process with the shortest execution time next.
   - Non-preemptive, favoring shorter processes.
   - May cause starvation for longer processes.

4. **Shortest Remaining Time (SRT)**:
   - Preemptive version of SPN, where the process with the shortest remaining time is executed next.
   - Minimizes turnaround time but can lead to starvation.

5. **Highest Response Ratio Next (HRRN)**:
   - Non-preemptive algorithm that prioritizes processes based on their response ratio:
     \[
     \text{Response Ratio} = \frac{\text{Waiting Time} + \text{Service Time}}{\text{Service Time}}
     \]
   - Balances fairness and turnaround time.

6. **Feedback (FB)**:
   - Uses multiple queues with varying priorities and time slices.
   - Processes are dynamically moved between queues based on their execution behavior.
   - Addresses fairness and prevents starvation.

7. **Aging**:
   - Dynamically increases the priority of older processes to prevent starvation.
   - Enhances fairness in priority scheduling systems.

---

### **Project Functionalities:**
- **Input Handling**: Accepts process details such as arrival time, burst time, and priority.
- **Simulation**: Simulates process execution based on the selected scheduling algorithm.
- **Output Metrics**:
  - Average waiting time.
  - Turnaround time.
  - Gantt chart visualization of CPU execution order.
- **Comparison**: Allows comparing the performance of different algorithms for the same process set.

---

### **Technologies and Concepts Used:**
- **Programming Language**: C++.
- **Data Structures**:
  - Arrays, queues, and priority queues for process management.
  - Linked lists for multi-level queue scheduling.
- **Core Concepts**:
  - Process scheduling and management.
  - Time-sharing and priority-based execution.
  - Algorithm optimization for real-time systems.

---

### **Applications of the Project:**
- **Educational Tool**: Helps students understand and compare different CPU scheduling algorithms.
- **Performance Analysis**: Evaluates algorithm efficiency in terms of waiting and turnaround times.
- **Real-world Simulation**: Models scheduling behavior in operating systems.

This project demonstrates a strong understanding of **operating system concepts**, **data structures**, and **algorithmic problem-solving** in C++.
