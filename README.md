🚀 Live Network Monitoring System

A real-time network monitoring application built using Python. It continuously tracks latency, packet loss, upload and download bandwidth, and displays results on dynamic live graphs to help analyze network performance effectively.

✨ Features

1. Real-time latency & packet loss monitoring

2. Upload / Download bandwidth visualization

3. Continuous monitoring using a scheduler

4. Dynamic Matplotlib live graphs

5. Lightweight and simple to run

🛠️ Tech Stack

* Python

* psutil

* ping3

* Matplotlib

* Schedule

* Threading

⚙️ How It Works

1. Pings a host to measure network delay and connectivity

2. Calculates bandwidth using system network I/O counters

3. Stores recent data points for visual representation

4. Automatically updates graphs in interactive mode

5. Scheduler triggers monitoring at fixed intervals

▶️ Getting Started

🔧 Install the required Python modules: pip install psutil ping3 matplotlib schedule

▶️ Run the Program: python app.py

A live network monitoring dashboard will appear. Close the window to stop monitoring.


👤 Author

S Krithika https://github.com/krithika1104
