# Priority Scheduling Algorithm Visualizer

This is a simple web-based visualizer made using AI for the **Priority Scheduling Algorithm**, which schedules processes based on their priority. The scheduler assigns the CPU to the process with the highest priority (lowest priority number) and calculates metrics such as **completion time**, **turnaround time**, and **waiting time** for each process.

## Features

- **Process Input**: Add processes with the following parameters:
  - **Process Name**
  - **Arrival Time**
  - **Burst Time**
  - **Priority** (Lower number means higher priority)
  
- **Calculate Scheduling**: The scheduler runs the Priority Scheduling algorithm to determine the execution order.
  
- **Result Display**: Displays the scheduling result in a table, including:
  - Completion Time
  - Turnaround Time
  - Waiting Time
  
- **Average Metrics**: Shows the average **Turnaround Time** and **Waiting Time** for all processes.

## How to Use

1. **Add Process**:
   - Enter the process name, arrival time, burst time, and priority for each process.
   - Click **Submit** to add the process to the scheduler.

2. **View Results**:
   - After adding all processes, the scheduler will run and display the scheduling order, along with detailed results for each process in a table format.

3. **Metrics**:
   - The **Average Turnaround Time** and **Average Waiting Time** will be calculated and displayed at the bottom of the results.

## Example

### Example Input:
- Process Name: P1, Arrival Time: 0, Burst Time: 5, Priority: 1
- Process Name: P2, Arrival Time: 2, Burst Time: 3, Priority: 2
- Process Name: P3, Arrival Time: 3, Burst Time: 2, Priority: 3

### Example Output:
- A table will be displayed showing the calculated **Completion Time**, **Turnaround Time**, and **Waiting Time** for each process, as well as the averages.

## Installation

You can use this project directly by opening the `index.html` file in your web browser. There is no need for a server or additional installation.

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/priority-scheduling-visualizer.git

2. Open the index.html file in any web browser.
