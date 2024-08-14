# Cloud-Based Face Recognition Attendance System

## 📌 Project Description
This project is a **cloud-based automated attendance system** that uses **face recognition** to mark attendance in real-time. It detects and verifies faces from a database, ensuring accurate and efficient attendance tracking.

## 🚀 Features
- Face detection using **OpenCV**.
- Face recognition with a pre-trained model.
- Cloud integration for **storage and real-time updates**.
- Automatic attendance marking.
- User-friendly interface with live updates.

## 🛠️ Technologies Used
- **Python** (Core Programming Language)
- **OpenCV** (Face Detection & Recognition)
- **NumPy & Pandas** (Data Handling)
- **Cloud Storage** (Firebase/AWS/Google Cloud)
- **Flask/Django** (Web Backend - If applicable)

## 📥 Installation
### Prerequisites:
- Install Python (3.x recommended)
- Install required dependencies
  ```sh
  pip install opencv-python numpy pandas flask
  ```
- Configure cloud storage (Firebase, AWS S3, or Google Cloud)

## 🔧 Usage
1. Run the face detection module:
   ```sh
   python face_detection.py
   ```
2. Start the attendance marking system:
   ```sh
   python attendance.py
   ```
3. View attendance records stored in the cloud.

## 📷 Working Mechanism
1. Captures live video stream.
2. Detects faces using **OpenCV**.
3. Matches detected faces with the database.
4. If a match is found, attendance is marked in **cloud storage**.
5. The system displays a confirmation message (**Active, Marked, Already Marked**).

## 📂 Folder Structure
```
📁 Cloud_Attendance_System
 ┣ 📂 models/             # Pre-trained ML models (if used)
 ┣ 📂 dataset/            # Training images & records
 ┣ 📜 face_detection.py   # Face detection module
 ┣ 📜 attendance.py       # Attendance processing script
 ┣ 📜 requirements.txt    # Dependencies
 ┗ 📜 README.md           # Documentation
```

## 📜 License
This project is licensed under the **MIT License**.

## 🙌 Contributors
- **Pankaj Gupta** *(Developer)*
- Team Members gaurav gupta & vaishnavi kasurade
## ⭐ Acknowledgments
Special thanks to **OpenCV & Cloud Services** for enabling real-time face recognition.

