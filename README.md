# Secure Multi-Tenant Cloud File Management System with Time-Based Access Control using AWS

A secure, scalable, and serverless cloud-based file management platform developed using AWS services. The system enables authenticated users to upload, organize, preview, download, and securely share files through time-based access control mechanisms within an isolated multi-tenant environment.

---

## 📌 Overview

This project demonstrates the implementation of a modern cloud-native file storage solution using AWS serverless architecture. Each user operates within a securely isolated storage space, ensuring privacy, scalability, and efficient resource management.

The platform integrates authentication, cloud storage, API management, and monitoring services to provide a reliable and secure file management experience.

---

## 🚀 Key Features

- Secure User Authentication using AWS Cognito
- Multi-Tenant File Isolation
- File Upload, Download, Rename, and Delete Operations
- Folder Creation and Navigation
- File Preview Support
- Time-Based Secure File Sharing
- JWT-Based API Authorization
- Responsive Dashboard Interface
- Multiple File View Modes (Grid, List, Details)
- CloudWatch Logging and Monitoring
- Scalable Serverless Architecture

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript

### Cloud & Backend
- AWS S3
- AWS Lambda
- AWS API Gateway
- AWS Cognito
- AWS IAM
- AWS CloudWatch

### Additional Libraries
- Amazon Cognito Identity SDK
- EmailJS

---

## ☁️ AWS Architecture

```text
Client Application
        │
        ▼
AWS API Gateway
        │
        ▼
AWS Lambda Functions
   ┌───────────────┬───────────────┐
   ▼               ▼               ▼
AWS S3       AWS Cognito     CloudWatch
(File Storage) (Authentication) (Monitoring)
```

---
<center><img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/72360aa6-020e-438e-b1da-5231e89a367e" /></center>

--- 

## 🔐 Security Features

- JWT Token Authentication
- IAM-Based Access Control
- Secure API Authorization
- User-Specific File Isolation
- Temporary Access Links
- Time-Limited File Sharing

---

## 📂 Core Functionalities

### Authentication Module
- User Registration
- Email Verification
- Login & Logout
- Password Recovery

### File Management Module
- Upload Files
- Download Files
- Rename Files
- Delete Files
- Create Folders
- File Preview

### Access Control Module
- Secure Shareable Links
- Expiration-Based Access Control

---

## 🎨 User Interface

The project includes a responsive and interactive cloud dashboard with:

- Modern Sidebar Navigation
- Dynamic File Rendering
- Statistics Dashboard
- Multiple View Modes
- Animated UI Components

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/cloud-file-management-system.git
```

### 2. Configure AWS Services

Set up the following AWS services:

- AWS S3 Bucket
- AWS Lambda Functions
- API Gateway Endpoints
- Cognito User Pool
- IAM Roles & Policies

### 3. Configure API Endpoints

Update the API URLs inside:

- `Dashboard.html`
- `index.html`

### 4. Run the Application

Open:

```text
index.html
```

in your browser.

---

## 📈 Advantages

- Fully Serverless Infrastructure
- Highly Scalable Architecture
- Cost-Effective Deployment
- Secure Multi-Tenant Environment
- Reduced Maintenance Overhead
- High Availability and Reliability

---

## 🔮 Future Enhancements

- End-to-End File Encryption
- File Versioning
- Drag-and-Drop Upload Support
- AI-Based File Classification
- Real-Time Collaboration
- Mobile Application Support
- Administrative Analytics Dashboard

---

## 📚 Learning Outcomes

This project provided practical experience in:

- AWS Cloud Services Integration
- Serverless Application Development
- Authentication & Authorization
- REST API Development
- Cloud Security Best Practices
- Multi-Tenant Architecture Design
- Frontend Dashboard Engineering

---

## 👨‍💻 Author

**Harish**  
MCA Student | Cloud & Web Development Enthusiast

---

## 📄 License

This project is developed for educational and academic purposes.
