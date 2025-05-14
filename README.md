
# 🏥 Patient Tracker Web Application

A secure, full-stack Doctor/Patient portal built using React and Django to streamline healthcare workflows such as appointment scheduling, medical record access, and real-time doctor-patient communication. It emphasizes role-based access, usability, and data security.

---

## 📌 Overview

This application allows:
- Patients to create profiles, manage medical histories, and book appointments
- Doctors to view schedules, review patient histories, and document consultations
- Real-time, role-based access for seamless coordination between healthcare providers and patients

---

## 🧠 How It Works

1. Patients and doctors register and log in.
2. Patients book appointments, attach notes, and update health details.
3. Doctors view upcoming appointments and prepare using patient history.
4. Doctors document appointments.
5. Patients review past notes and manage their care.

---

## 💻 Application Features

- Patient and doctor registration/login
- Real-time appointment scheduling
- Role-based dashboards
- Medical history and medication tracking
- Secure appointment documentation
- Appointment reminders and history

---

## 🛠️ Tech Stack

| Component     | Technology         |
|---------------|--------------------|
| Frontend      | React, JavaScript  |
| Backend       | Django, Python     |
| Database      | PostgreSQL         |
| Security      | SHA256, HTTPS, JWT |
| DevOps        | Git, GitHub, Shell |

---

## ⚙️ How to Run

### 🧩 Backend Setup

1. Ensure Python and PostgreSQL are installed.
2. Navigate to the backend directory:

```bash
cd patientTacker/
pip install -r requirements.txt
```

3. Create a `.env` file with the following fields:

```env
DB_NAME=
DB_USER=
DB_PASSWORD=
DB_HOST=
DB_PORT=
FIELD_ENCRYPTION_KEY=
```

4. Apply migrations and start the server:

```bash
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

---

### 💻 Frontend Setup

1. Navigate to the frontend directory:

```bash
cd patient_tracker_fe/
npm install
npm start
```

---

### 🔄 Combined Startup

To run both frontend and backend together:

```bash
./run.sh
```

---

## ✅ Functional Highlights

- View and manage upcoming appointments  
- Update medical details and medications  
- Secure authentication for both user roles  
- Doctors access patient records before appointments  
- Record post-visit notes for review and documentation  
- Real-time filtering and schedule visibility for doctors  

---

## 🔐 Security Considerations

- All data encrypted using SHA256  
- HTTPS enforced throughout the application  
- Role-Based Access Control (RBAC) ensures restricted visibility  
- Authentication with JWT tokens  
- Environment-based database credentials and encryption keys  

---

## 🛣️ Future Enhancements

- Doctor-defined availability settings  
- Real-time email/SMS appointment alerts  
- Patient file uploads (e.g., PDFs, prescriptions)  
- Cloud deployment with HIPAA compliance  
- Responsive mobile interface  

---

## 🧪 Testing & Validation

- **Backend**: Django unit tests (79% test coverage)  
- **Frontend**: Jest-based testing for React components  
- **Security**: Manual review of encryption and endpoint access  
- **Usability**: Validated via user testing and feedback  
