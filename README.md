# Page Replacement Algorithm Simulator

A **Python Tkinter-based simulator** that demonstrates the working of FIFO, LRU, and Optimal page replacement algorithms. The application allows users to input a page reference string and number of frames, visualize step-by-step execution, and compare algorithm performance.

---

## Features

- Input page reference string (space-separated) and number of frames.
- Choose between **FIFO**, **LRU**, and **Optimal** algorithms.
- Step-by-step simulation showing page hits and page faults.
- Visual representation of:
  - Frame content over time
  - Faults vs. hits over time
- Compare all algorithms side-by-side using charts.
- Clear input and output with a single click.

---

## Technologies Used

- **Python 3**
- **Tkinter** for GUI
- **Matplotlib** for plotting and visualization
- **NumPy** for data handling

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/PageReplacementSimulator.git
   ```
2. Navigate to the project folder:
   ```bash
   cd PageReplacementSimulator/src
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

 ---

## How to Run

Run the simulator using:

```bash
python simulator.py
```

---

## Usage

1. Enter a **page reference string** (space-separated integers) in the input field.
2. Enter the **number of frames**.
3. Select the **algorithm** (FIFO, LRU, or Optimal).
4. Click **Simulate** to view step-by-step page replacement results.
5. Click **Compare All** to see a comparison of all three algorithms.
6. Use **Clear** to reset inputs and outputs.

---

## Future Improvements

- Add additional page replacement algorithms such as MFU or Second-Chance.
- Export simulation results to **CSV or PDF**.
- Implement animated step-by-step visualization for clearer understanding.
- Allow customization of GUI colors and themes.
