# Movie Store - Project Overview

## 🎬 Introduction

Welcome to the **Movie Store** project! This academic project was developed as part of my studies in **.NET** and **C#**, with the goal of creating a fully functional web application using **ASP.NET Core MVC 6**. This project showcases an online movie store platform, with features including **authentication**, a distinct **admin panel**, **searching**, **pagination**, and **file handling** (image upload). The system is built to industry standards, ensuring a secure, high-performance, and scalable application.

## 🚀 Key Features

### 1. **Modern MVC Architecture**
The application is built on the **Model-View-Controller (MVC)** architecture, ensuring a clear separation of concerns between the business logic, user interface, and data handling. This makes the code maintainable and scalable.

### 2. **Authentication and Authorization with ASP.NET Identity**
The project integrates **ASP.NET Identity**, allowing for secure **user management**, **logins**, and **roles** (admin and user). The authentication system also provides a **custom admin panel** where only authorized users can manage movies and users.

### 3. **Separation of Admin and User Views**
The system provides distinct interfaces for **customers** (browsing and purchasing movies) and **administrators** (managing movies and users). This ensures a clear distinction of roles and access control.

### 4. **Server-Side Searching**
A **server-side search** feature enables users to quickly search for movies by various criteria such as genre, title, director, etc. This optimizes performance and ensures a smooth user experience.

### 5. **Server-Side Pagination**
The application implements **server-side pagination**, ensuring only the necessary data is sent to the client. This improves performance and avoids overloading the client with large datasets.

### 6. **File Handling and Image Uploads**
The system allows **image uploads** (such as movie posters) and ensures that only valid image files are uploaded. File management is handled securely to ensure data integrity.

## 🔧 Technologies Used

- **ASP.NET Core MVC 6** for web development
- **ASP.NET Identity** for user management and authentication
- **Entity Framework Core** for data access
- **SQL Server** as the database
- **Bootstrap** for responsive UI design
- **JavaScript/jQuery** for dynamic client-side interactions
- **File Handling** for movie image uploads

## 🛠️ Installation & Setup

### ✅ Prerequisites  
Assurez-vous d’avoir installé :  
- **.NET 6 SDK**  
- **SQL Server** (ou SQL Server Express)  
- **Visual Studio** ou **Visual Studio Code**  

### 📌 Installation Steps  


### 1️⃣ Clone the repository  
git clone https://github.com/CharfeddineFredj/movie-store.git  

### 2️⃣ Navigate to the project folder  
cd movie-store  

### 3️⃣ Restore NuGet dependencies  
dotnet restore  

### 4️⃣ Configure the database connection  
### (Modifiez le fichier appsettings.json)  
"ConnectionStrings": {  
   "DefaultConnection": "Server=localhost;Database=MovieStoreDB;Trusted_Connection=True;"  
}  

### 5️⃣ Apply database migrations  
dotnet ef database update  

### 6️⃣ Run the application  
dotnet run  


   ---
## 📸 Screenshots
### 🔑 Authentication Page
![309056048-2dfbd7fd-6225-4acb-9a18-607f831e607b](https://github.com/user-attachments/assets/8d939d53-4863-45a1-b66a-74924afde8c1)

### 🎬 Customer Movie List
![Screenshot_13](https://github.com/user-attachments/assets/e12c6f5c-0944-47bb-8d2f-6d711d7e2984)

### 🎬 Admin - Manage Customer
![hq720](https://github.com/user-attachments/assets/9b7ae4ec-9efd-4d3c-b22b-f8bbd172445e)

  ---



