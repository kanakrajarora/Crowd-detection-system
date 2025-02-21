# 🕵️‍♂️ Crowd Detection System  

## 📌 Overview  
This project implements a **Crowd Detection System** using **YOLOv8** to detect persons in a video and analyze their proximity to identify crowd formations. The system logs detected crowd events and saves the results in a CSV file.  

## Video Demonstration
https://youtu.be/X5xJhQbEhP4

## 🔍 Features  
✅ Detects persons in a video using **YOLOv8**  
✅ Identifies **crowds** (3 or more persons standing close together for 10 consecutive frames)  
✅ Logs frame numbers and crowd size  
✅ Saves results in a **CSV file**  


## 🔧 Installation  
### 1️⃣ Clone the repository  
```bash
git clone https://github.com/your-username/crowd-detection-system.git
cd crowd-detection-system
```
### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Download and set up YOLOv8
```bash
pip install ultralytics
```

## 🏗️ Future Enhancements
🔹 Implement real-time streaming support
🔹 Improve distance measurement using depth estimation
🔹 Add alerts for detected crowds

## 🤝 Contributing
Pull requests are welcome! Please ensure your changes align with the project’s objectives.

## 📜 License
This project is licensed under the MIT License.
