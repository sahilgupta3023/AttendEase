# AttendEase 🎓📷

An AI-powered, real-time facial recognition-based attendance system built using OpenCV and Python. Designed to streamline classroom attendance processes by automating student check-ins with high accuracy and minimal human intervention.

## 🚀 Features

- 🎥 **Live Face Detection & Recognition**  
  Uses webcam input to detect and recognize student faces in real time.

- 📁 **Student Database Management**  
  Easily add and manage student profiles using images and unique IDs.

- 🗂️ **Automated Attendance Logging**  
  Records attendance to a CSV file with timestamps and recognition confidence.

- 📊 **Report Generation**  
  Generates daily attendance reports for easy review and administrative use.

- 🔐 **Proxy Prevention**  
  Reduces chances of proxy attendance by ensuring face-to-ID matching.

---

## 🧠 Technologies Used

- **Python**
- **OpenCV**
- **face_recognition** (built on dlib)
- **NumPy**
- **Pandas**

---

## 🖥️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/sahilgupta3023/AttendEase.git
   cd AttendEase
   ```

2. **Create a virtual environment (optional but recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate 
   ```

3. **Add student images**  
   Add labeled student images to the `dataset/` folder. The folder name should be the student's name or ID.

4. **Run the application**
   ```bash
   python attendEase.py
   ```

---

## ✅ Future Improvements

- GUI using Tkinter or PyQt
- Integration with a cloud database
- Email/SMS alerts for absentee notifications
- Admin dashboard for managing records

---

## 🙋‍♂️ Author

**Sahil Gupta**  
📫 [sahilgupta3023@gmail.com](mailto:sahilgupta3023@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/sahil-gupta-912992229)  
🔗 [GitHub](https://github.com/sahilgupta3023)

---

## ⭐️ Show Your Support

If you found this project helpful, feel free to **star** this repo and share it with others!  
Pull requests and feedback are always welcome!
