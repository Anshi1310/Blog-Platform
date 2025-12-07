# 📝 Blog Platform  
A simple and functional blogging platform built using **Django, HTML, CSS, and SQLite**.  
This project allows users to create, edit, update, and delete blog posts, upload images, organize posts with categories, and view them through a clean and responsive UI.

Developed as a full-stack learning project to practice **Django backend logic, template rendering, CRUD operations, and static/media file handling**.

---

## 🚀 Features

### ✏️ **CRUD Functionality**
- Create new blog posts  
- Edit/update existing posts  
- Delete posts  
- View full post details  

### 🖼 **Image Upload Support**
- Upload images with your blog posts  
- Stored inside Django media directory  

### 🗂 **Category-Based Filtering**
- Filter blog posts by category  
- Organized content structure for easy browsing  

### 🎨 **Responsive UI**
- Built using HTML + CSS  
- Works across desktop and mobile layouts  

### 🗄 **Database Integration**
- Uses **SQLite** as the database  
- Easy to run locally with no setup required  

### 🧹 **Admin Panel**
- Django admin auto-generated  
- Manage posts, categories, and media

---

## 🧠 Tech Stack

### **Frontend**
- HTML  
- CSS  
- Basic JavaScript  

### **Backend**
- Django  
- Python  
- SQLite  
- Django ORM  

---

## 📂 Folder Structure
blog-platform/
│
├── blog/ # Application logic
│ ├── models.py # Post & Category models
│ ├── views.py # CRUD logic
│ ├── urls.py # App routes
│ ├── templates/blog/ # HTML templates
│ └── migrations/ # Database migrations
│
├── blog_platform/ # Project configuration
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
│
├── static/ # CSS, JS, images
├── media/ # Uploaded post images
├── templates/ # Base templates
│
├── db.sqlite3 # Database file
├── manage.py
├── .gitignore
├── LICENSE
└── README.md


---

## ▶️ How to Run the Project Locally

### 1️⃣ Clone the repository
git clone https://github.com/Anshi1310/blog-platform.git


### 2️⃣ Navigate into the folder
cd blog-platform


### 3️⃣ Install dependencies (optional but recommended)
pip install -r requirements.txt


### 4️⃣ Apply migrations
python manage.py migrate


### 5️⃣ Run the development server
python manage.py runserver


### 6️⃣ Open in browser
http://127.0.0.1:8000/


---

## 📸 Screenshots (Add later)

You can include screenshots like:



**
---

## 👩‍💻 My Contribution

> I developed this project to strengthen my understanding of **Django backend development**, **template rendering**, and **CRUD operations**.  
> The project includes models, views, templates, URL routing, and static/media file handling.

---

## 📄 License
This project is licensed under the **MIT License**.

---

⭐ *If you like this project, feel free to give the repository a star!* ⭐
**
