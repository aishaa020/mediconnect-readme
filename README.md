# 🩺 MediConnect – Your Smart Medical Appointment App

> A full-stack medical appointment platform where **patients and doctors connect seamlessly**. Built with ❤️ using **Flutter**, **Spring Boot**, **Firebase**, and **MySQL**.

---

## 🚀 Overview

**MediConnect** is a modern mobile solution for managing medical appointments, enabling patients to:

- 🔍 Browse doctors by specialization  
- 📅 Book and manage appointments  
- 💬 Chat securely with doctors  
- 📁 Download test results and X-rays  
- 📲 Receive real-time notifications  

Meanwhile, doctors can:

- 🧑‍⚕️ Manage their schedule and availability  
- 📄 View patient histories and files  
- 📷 Upload their profile photos  
- 🗨️ Communicate with patients in-app  

This was my **graduation project**, and I built the **mobile app from scratch** using Flutter. My teammate built the React web interface for doctors, and we worked together on the backend.

---

## 🛠️ Tech Stack

| Layer        | Tech Used                  |
|--------------|----------------------------|
| Frontend     | Flutter (Dart)             |
| Backend      | Spring Boot (Java)         |
| Auth & Chat  | Firebase Auth & Firestore  |
| Database     | MySQL                      |
| Storage      | Firebase Storage           |

---

## 📱 App Features (Mobile - Patient Side)

- 👤 Patient sign-up & login  
- 🔎 Search for doctors by specialty  
- 📅 Book, cancel, and manage appointments  
- 📁 Upload and view medical files (X-rays, test results)  
- 🧑‍⚕️ View doctor profiles with photos and details  
- 📨 Chat in real-time (Firebase)  
- 🔔 Push notifications (coming soon!)

---

## 🎥 Demo

### **1- Sign up**
<video width="300" controls>
  <source src="https://github.com/user-attachments/assets/30fecdba-20d5-48d5-8495-2ad58844579b" type="video/mp4">
  Your browser does not support the video tag.
</video>

### **2- Sign In**
<video width="300" controls>
  <source src="https://github.com/user-attachments/assets/acb30e96-37fa-4c7c-a665-87e7cead2d2f" type="video/mp4">
  Your browser does not support the video tag.
</video>

### **3- Homepage**
<video width="300" controls>
  <source src="https://github.com/user-attachments/assets/b2a767db-7e6f-429b-8a30-c1a5b9e2e67e" type="video/mp4">
  Your browser does not support the video tag.
</video>

### **4- Notifications in foreground**
<video width="300" controls>
  <source src="https://github.com/user-attachments/assets/093c4d6f-b701-4a48-8c43-7125285cefef" type="video/mp4">
  Your browser does not support the video tag.
</video>

### **5- Notifications in background**
<video width="300" controls>
  <source src="https://github.com/user-attachments/assets/c27530f6-db9f-4655-aa01-9031d7b376ca" type="video/mp4">
  Your browser does not support the video tag.
</video>

### **6- Viewing visits documentation**
<video width="300" controls>
  <source src="https://github.com/user-attachments/assets/4c5a97f2-f890-48ff-a417-238eeef46dac" type="video/mp4">
  Your browser does not support the video tag.
</video>

### **7- Viewing/Cancelling Appointments**
<video width="300" controls>
  <source src="https://github.com/user-attachments/assets/f57f8d40-f1bb-4dc4-8720-54a4bfc6afb1" type="video/mp4">
  Your browser does not support the video tag.
</video>

### **8- Chat**
<video width="300" controls>
  <source src="https://github.com/user-attachments/assets/e024ac8b-cd47-4c33-8285-da56846c3360" type="video/mp4">
  Your browser does not support the video tag.
</video>

### **9- Booking an appointment**
<video width="300" controls>
  <source src="https://github.com/user-attachments/assets/69c6780f-cc71-45db-9b7a-f6d803108e1a" type="video/mp4">
  Your browser does not support the video tag.
</video>

### **10- View Doctors**
<video width="300" controls>
  <source src="https://github.com/user-attachments/assets/abfc0569-ff0b-4323-adc4-ecc43f3283a3" type="video/mp4">
  Your browser does not support the video tag.
</video>

### **11- Liked doctors**
<video width="300" controls>
  <source src="https://github.com/user-attachments/assets/a9e1f149-e0e6-4e2a-a7ae-30ea140a490d" type="video/mp4">
  Your browser does not support the video tag.
</video>

### **12- Profile Setting History**
<video width="300" controls>
  <source src="https://github.com/user-attachments/assets/81d7a770-0884-4bc0-a9ae-1440a4758ad9" type="video/mp4">
  Your browser does not support the video tag.
</video>

### **13- Editing Personal Info**
<video width="300" controls>
  <source src="https://github.com/user-attachments/assets/524d040d-a8be-42fb-9ac7-2a14371f0722" type="video/mp4">
  Your browser does not support the video tag.
</video>

### **14- Log out**
<video width="300" controls>
  <source src="https://github.com/user-attachments/assets/5361f983-cc8b-445a-a552-523a19278d6f" type="video/mp4">
  Your browser does not support the video tag.
</video>




---

## 🧠 How It Works (Architecture)

1. **Flutter** app communicates with:
   - **Firebase** for authentication and real-time chat  
   - **Spring Boot API** for authentication, fetching info like appointments, doctors, history  
2. **Spring Boot** connects to **MySQL** for structured data  



