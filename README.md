# 🖥️ Real-Time System Monitor 📊

A live graph-based system monitor that visualizes CPU, RAM, Disk, and Network I/O usage using Python and Matplotlib.

---

## 🔍 Features

- 🚀 Real-time CPU usage tracking
- 🧠 Monitors RAM usage
- 💽 Displays Disk utilization
- 🌐 Visualizes Network I/O (sent & received MB)
- 📈 Refreshes every second with smooth live updates

---

## 🛠️ Requirements

Ensure Python 3.x is installed and install the following libraries:

```bash
pip install psutil matplotlib
````

---

## ▶️ How to Run

1. 📥 Download or clone this repository
2. Open terminal in the project directory
3. Run the script:

```bash
python system_monitor.py
```

---

## 🧠 How It Works

* Collects stats every second using `psutil`
* Plots:

  * 🔴 **CPU Usage**
  * 🔵 **RAM Usage**
  * 🟢 **Disk Usage**
  * 🟣 **Network Sent / 🟠 Network Received**
* Maintains a rolling window of the last 60 seconds (configurable)

---

## 📸 Output Preview

Your screen will show a live grid of 4 graphs updating every second:

```
+------------------+------------------+
|   CPU (%)        |    RAM (%)       |
|   🔴 Live Plot   |   🔵 Live Plot    |
+------------------+------------------+
|   Disk (%)       |   Network I/O    |
|   🟢 Live Plot   | 🟣🔶 Live Plot    |
+------------------+------------------+
```

---

## 🛑 Notes

* Runs in a pop-up window using `matplotlib.pyplot`
* Script stops when you close the plot window

---

## 📬 Feedback

Got ideas to add temperature monitoring, GPU stats, or export data? PRs and issues welcome!

---

Made with ⚡ by \Sohail-Ansari

