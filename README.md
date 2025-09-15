# 🖥️ Employee Attendance & Leave Management Backend

This is the **backend server** for the Employee Attendance & Leave Management Mobile App.  
It is built with **Node.js + Express** and uses **MySQL** as the database.  
The backend provides secure APIs for employee login, attendance marking, leave management, and profile handling.

---

## ✨ Features

- 🔑 **Secure Login** with unique employee ID (only from admin-approved devices)  
- 📍 **Location-Based Attendance**  
  - Mark **In-Time / Out-Time** only if within office geofence  
  - If outside, system shows **"Out of Location"**  
- 🕑 **Attendance Management**  
  - Record **In-Time & Out-Time** with optional remarks  
- 📝 **Leave Management**  
  - Apply for **CL (Casual Leave), ML (Medical Leave), PL (Privilege Leave)**  
  - Upload supporting documents  
  - Track leave status (Pending / Approved / Rejected)  
- 👤 **Employee Profile**  
  - View personal details  
  - Track remaining **CL, ML, PL** leave balances  
- 🛠 **Admin APIs**  
  - Approve mobile devices  
  - Manage employees and leave requests  
  - Generate attendance & leave reports  

---

## 🛠 Tech Stack

- **Backend Framework:** Node.js + Express  
- **Database:** MySQL  
- **Authentication:** JWT  
- **File Uploads:** Multer / Cloud Storage (for leave documents)  
- **Location Services:** GPS / Google Maps API integration (validation on client, verified by backend)  

---



