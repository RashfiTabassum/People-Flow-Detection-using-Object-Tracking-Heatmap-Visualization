# People-Flow-Detection-using-Object-Tracking-Heatmap-Visualization
# People Flow Detection

💡 **Real-time people detection, tracking, counting, and heatmap visualization using YOLOv8 + BoT-SORT**

This project detects and tracks people in videos, counts them based on crossing two horizontal lines, and generates heatmaps of high-activity areas — similar to smart surveillance systems.

---

## Features

- **Real-time detection and tracking** using YOLOv8 + BoT-SORT  
- **Counting logic:**  
  - Moving **down** across the **upper line** → counted as **IN**  
  - Moving **up** across the **lower line** → counted as **OUT**  
- Assigns **unique IDs** to prevent double counting  
- Generates **activity heatmaps** using Gaussian accumulation  
- Overlays all detection info (bounding boxes, counts, lines) directly on video  

---

## Tech Stack

- **Python** – programming language  
- **YOLOv8** – object detection  
- **BoT-SORT** – tracking across frames  
- **OpenCV** – video processing and drawing  
- **NumPy** – numerical computations  
- **Matplotlib** – optional visualization  

