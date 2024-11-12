# Real-Time People Counting in Railways 🚆

This project utilizes **computer vision** and **YOLO-based object detection** to count people in a specified zone within a railway station. The system processes a **pre-recorded video** and identifies the number of individuals in real-time as they move within a defined area. It can easily be adapted for live-stream applications for real-time crowd monitoring.

---
## Demo

https://github.com/user-attachments/assets/4369f014-fca8-44e1-9e7a-bd873956a917


## 🛠️ **How It Works**

1. **Zone-based Detection**: 
   - A custom **polygon zone** is defined within the railway station to track individuals.
   - The zone acts as a boundary within which people are detected and counted.

2. **Object Detection**:
   - The **YOLO model** detects individuals (people) in the video.
   - Each person detected within the defined zone is counted as they move through it.

3. **Real-Time Processing**:
   - While this demo uses a **pre-recorded video**, the system can be extended to **live-stream video feeds** for real-time processing and crowd monitoring.

---

## 🌟 **Why It Matters**

- **Safety**: Helps prevent overcrowding on railway platforms and ensures the safety of passengers.
- **Operational Efficiency**: Provides valuable insights into crowd patterns, assisting with platform management during peak times.
- **Scalability**: Can easily be integrated into live-streaming video systems, making it ideal for real-time monitoring in busy transportation hubs or public events.

---

## 📦 **Workflow**
 Just go through the notebook to complete this project.

 🚀 Future Work
Integration with live video streams for real-time crowd monitoring.
Implementation of more advanced tracking and prediction models.
Extend functionality to other transportation hubs, such as airports or bus stations.
