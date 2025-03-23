<b>📟 Page Replacement Algorithm Simulator</b>

Python 

This Python-powered tool uses Tkinter and Matplotlib to make operating system concepts pop. Simulate and compare FIFO, LRU, and Optimal algorithms with dazzling visualizations and real-time stats. 🚀  
<b>✨ Features</b>

🧠 Algorithms: Explore FIFO, LRU, and Optimal page replacement strategies.  

🖼️ Interactive GUI: Input page strings and frame sizes effortlessly with Tkinter.  

📊 Visualizations:  

Frame states and fault/hit timelines in real-time.  

Side-by-side comparison of all algorithms with vibrant charts.

📈 Metrics: Instant page faults and hit ratios.  

🛠️ Debug Mode: Optional logs for a peek behind the scenes.

<b>📸 Screenshots</b>

![Screenshot 2025-03-07 171526](https://github.com/user-attachments/assets/13adb948-ecaa-4178-99e3-53cb075032bd)

![Screenshot 2025-03-07 171607](https://github.com/user-attachments/assets/c7eafce5-65d0-41a7-83d0-6c957480d82e)

![Screenshot 2025-03-07 171632](https://github.com/user-attachments/assets/4263f18c-2f26-49da-bc32-53719293252a)

![Screenshot 2025-03-07 171652](https://github.com/user-attachments/assets/0335f1b2-18a0-40aa-847b-c7988ded37a0)

<b>🌐 Flowcharts</b>

![WhatsApp Image 2025-03-07 at 17 04 13](https://github.com/user-attachments/assets/72aa9645-6758-4c86-b3ff-1ff168b46619)

<b>🛠️ Prerequisites</b>

🐍 Python 3.x  

📦 Libraries:  

tkinter (bundled with Python)  

matplotlib  

numpy

<b>🚀 Installation</b>

Clone the Repository:  
``` bash
git clone https://github.com/ArshiBansal/PageReplacementSimulator.git

```

Install Dependencies:  
```
pip install matplotlib
pip install numpy
pip install tkinter
```

Launch the Simulator:  
```
python Main_Code.py
```

<b>🔧 How to Use</b>

Start the App: Run the script to launch the GUI. 🔥  

Enter Inputs:  

Page String: Space-separated list (e.g., 7 0 1 2 0 3).  

Frames: Number of frames (e.g., 3).  

Algorithm: Choose FIFO, LRU, or Optimal. 🎯

Run It:  

Simulate: Click to run one algorithm. 📉  

Compare All: See all three in action with one click! ⚡  

Reset: Clear everything to start over. 🧹

🗂️ Code Breakdown

page_replacement_simulator.py:  

✨ __init__: Crafts the sleek GUI.  

🚀 simulate: Powers a single algorithm run.  

⚖️ compare_all: Battles all algorithms head-to-head.  

🧩 fifo, lru, optimal: The algorithmic brains.  

📊 plot_simulation: Creates the stunning visuals.

<b>🌟 Example</b>

Input:  

Page String: 7 0 1 2 0 3 0 4 2 1 0 3  

Frames: 3  

Algorithm: FIFO

Output:  
FIFO: 11 faults, 1 hit  

Optimal: 9 faults, 3 hits  

LRU: 10 faults, 2 hits

Step-by-step breakdown in the text box. 📜  

Faults and hit ratio stats. 📊  

Eye-catching plots of frame states and faults over time. 🎨


## 🚀 Authors  
👤 *Arshi Bansal*  
👤 *Mansi Tyagi*   
👤 *Tanvi Sharma*
