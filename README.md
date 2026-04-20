🎯 Smart Face Attendance System

An AI-powered attendance system using **real-time Face Recognition** — no manual marking, no proxy.

 ✨ Features

- 📷 Real-time face detection & recognition via webcam
- ✅ Auto attendance marking with timestamp
- 📅 Timetable-based subject detection
- 👥 Role-based dashboards — Admin / Faculty / Student
- 📊 Attendance analytics & 75% risk alerts
- 📥 Excel report download (color-coded Present / Absent)



#🛠 Tech Stack

`Python` `Flask` `OpenCV` `face_recognition` `SQLite` `HTML/CSS` `OpenPyXL`



 ⚙️ Setup & Run

```bash
# 1. Clone the repo
git clone https://github.com/your-username/SMART_FACE_ATTENDANCE.git
cd SMART_FACE_ATTENDANCE

# 2. Create & activate virtual environment
python -m venv venv
venv\Scripts\activate        # Windows
# source venv/bin/activate   # Mac/Linux

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run
python run.py
```

Open in browser → `http://127.0.0.1:5000`



 🔐 Default Login

| Role  | Username | Password |
|-------|----------|----------|
| Admin | admin    | admin   |



 🗂 Project Structure

```
SMART_FACE_ATTENDANCE/
├── app/
│   ├── routes/
│   ├── templates/
│   └── static/
├── dataset/
├── timetable.xlsx
├── requirements.txt
├── run.py
└── database.db
```



 🚀 Future Scope

- Mobile app integration
- Cloud deployment (AWS / Firebase)
- Deep learning model (CNN / YOLO)
- Liveness detection & mask handling



 👥 Team

| Name | Role |
|------|------|
| Sunaina Sahu | Developer |
| Mridul Paradkar | Developer |
| Diya Singh | Developer |
| Harshal Salekar | Developer |

⭐ Star this repo if you found it useful!
