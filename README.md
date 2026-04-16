# 🚀 Media Application

**Secure • Scalable • High-Performance Media Management System**

------------------------------------------------------------------------

## 📌 Overview

A full-stack media management application designed to handle large-scale
file uploads, downloads, and streaming with strong security and
performance optimization.

------------------------------------------------------------------------

## ✨ Features

-   🔐 Authentication & Authorization (Keycloak + JWT)\
-   📤 Multipart File Upload (Large files supported)\
-   📥 File Download\
-   🎥 Video Streaming (Byte-range support)\
-   📂 Metadata Management (MongoDB)\
-   📃 Paginated File Listing\
-   ❌ File Deletion APIs\
-   ⚡ Optimized Performance

------------------------------------------------------------------------

## 🏗️ Architecture

    Frontend (React)
            ↓
    Backend (Spring Boot)
            ↓
     -------------------------
     |                       |
    MinIO (Storage)     MongoDB (Metadata)

            ↓
       Keycloak (JWT Security)

------------------------------------------------------------------------

## ⚙️ Tech Stack

-   Frontend: React.js\
-   Backend: Spring Boot\
-   Storage: MinIO (S3-compatible)\
-   Database: MongoDB\
-   Security: Keycloak + Spring Security (JWT)

------------------------------------------------------------------------

## 🔒 Security Flow

1.  User authenticates via Keycloak\
2.  JWT token is issued\
3.  Token is attached to API requests\
4.  Spring Security validates token

------------------------------------------------------------------------

## 📸 API Endpoints

-   `POST /upload` → Upload file\
-   `GET /files` → List files\
-   `GET /download/{id}` → Download file\
-   `GET /stream/{id}` → Stream media\
-   `DELETE /delete/{id}` → Delete file

------------------------------------------------------------------------

## 🚀 Getting Started

``` bash
git clone https://github.com/your-username/media-app.git
cd media-app
```

------------------------------------------------------------------------

## 📊 Use Cases

-   Media Streaming Platforms\
-   Cloud Storage Systems\
-   Enterprise File Management\
-   Document Management Systems

------------------------------------------------------------------------

## 🧠 Key Learnings

-   Storage vs Metadata separation\
-   S3-compatible storage integration\
-   JWT-based authentication\
-   Handling large file streaming

------------------------------------------------------------------------

## 👨‍💻 Author

Kunal\
Software Developer

------------------------------------------------------------------------

⭐ Star this repository if you found it useful!
