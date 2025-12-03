# Herfa – Craft Management System (Flutter Mobile Application)
## 🎥 Project Demo Video  
🔗 [https://drive.google.com/file/d/1z7fuuZPHD-76o-yVQ6ZOWEMdpVOZpnfo/view](https://drive.google.com/drive/folders/1ylFxDSrxGY35DbrjV0BTdRjoWb2VQsHJ?usp=drive_link)

Herfa is a **Craft Management System** mobile application designed to support local artisans by helping them showcase and sell their handmade products.  
The app ensures transparency and trust through **AI-powered product classification** (Handmade vs Manufactured) and provides a smooth and efficient experience for **customers, artisans, and admins**.

This repository contains the **Flutter application**, fully implemented by me, including user flows, **admin and artisan interfaces**, and direct integration with the machine learning model.

---

## 🚀 Features

### 🧵 Customer Features
- Browse handmade products through organized categories.  
- View artisan profiles and product details.  
- Real-time product verification using an AI model (YOLOv8).  
- Smooth and modern user interface designed for easy navigation.  

### 🛠️ Admin Features
The app includes a dedicated admin panel inside the Flutter application:
- Dashboard overview for system activity.  
- Manage artisans, customers, and products.  
- Review AI classification results for product verification.  
- Monitor platform analytics and performance.  

### 👩‍🎨 Artisan Features
The app includes a dedicated artisan panel inside the Flutter application:
- Manage and showcase handmade products.  
- Add, edit, or remove products with real-time AI verification (Handmade vs Manufactured).  
- Track orders, approve or complete them, and view order status.  
- Monitor product performance, sales, and customer interactions through the artisan dashboard.  
- Update profile information and upload verification documents.  
- Receive notifications for new orders, verification results, and account updates.  

---

## 🤖 AI Model Integration (Handmade vs Manufactured)
Although the machine learning model itself is developed separately,  
**the Flutter app is fully integrated with the model** using API communication:

- Send product images to the server.  
- Receive classification results from the YOLOv8 model.  
- Display instant verification to customers and artisans.  
- Prevent publishing manufactured items as handmade.

This ensures transparency and builds trust between artisans and customers.

---

## 📱 Mobile App (Flutter)

### My Responsibilities:
- Built the entire Flutter application (UI/UX + logic).  
- Implemented customer, artisan, and admin screens with clean architecture.  
- Integrated the app with the deep learning model using REST APIs.  
- Organized project structure for scalability and maintainability.  
- Added analytics screens for artisans and admins.  
- Ensured full responsiveness across devices.  

### Main Screens:
- Home & Categories  
- Product Details  
- Artisan Profile  
- Authentication  
- Admin Dashboard  
- Admin Product Management  
- Admin User Management  
- Analytics & Statistics  

---

## 🏗️ Tech Stack

### **Frontend (Mobile)**
- Flutter  
- Dart  
- REST API Integration
- FireBase

### **AI**
- YOLOv8 (used through API)

