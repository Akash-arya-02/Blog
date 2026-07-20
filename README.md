# 📝 Django Blog Project
A simple and responsive blog application built with Django that allows users to create, update, delete, and categorize blog posts. It features a clean and intuitive interface for managing content while demonstrating Django's powerful class-based views, forms, and template system. The project serves as a practical example of implementing CRUD operations and category-based filtering in a modern web application

## 🚀 Features

- 📖 View all blog posts
- 📄 Read complete blog articles
- ✍️ Create new blog posts
- 📝 Update existing posts
- 🗑️ Delete blog posts
- 🏷️ Create blog categories
- 📂 Filter posts by category
- 📅 Posts ordered by latest publication date
- 🎨 Responsive user interface using Django Templates

---

## 🛠️ Tech Stack

- Python
- Django
- HTML5
- CSS3
- Bootstrap
- SQLite (Default Django Database)

---

## 📁 Project Structure

```
ablog/
│
├── blog/
│   ├── migrations/
│   ├── templates/
│   │   ├── base.html
│   │   ├── home.html
│   │   ├── article_details.html
│   │   ├── add_post.html
│   │   ├── update_post.html
│   │   ├── delete_post.html
│   │   ├── add_category.html
│   │   └── categories.html
│   │
│   ├── models.py
│   ├── forms.py
│   ├── views.py
│   ├── urls.py
│   └── admin.py
│
├── manage.py
└── db.sqlite3
```

---

## 📌 Functionalities

### Home Page

Displays all blog posts ordered by the latest publication date.

### Article Details

View the complete content of a selected blog post.

### Add Post

Create a new blog post using a custom Django form.

### Edit Post

Update existing blog posts.

### Delete Post

Delete unwanted blog posts.

### Categories

Organize posts into different categories and browse posts by category.

### Add Category

Create new blog categories directly from the application.

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/ablog.git
```

### Navigate to the project

```bash
cd ablog
```

### Create a virtual environment

```bash
python -m venv venv
```

### Activate the virtual environment

Windows

```bash
venv\Scripts\activate
```

Linux / macOS

```bash
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Apply migrations

```bash
python manage.py migrate
```

### Create a superuser

```bash
python manage.py createsuperuser
```

### Run the development server

```bash
python manage.py runserver
```

Open:

```
http://127.0.0.1:8000/
```

---

## 📂 Main Views

| View | Description |
|------|-------------|
| HomeView | Displays all blog posts |
| ArticleDetailView | Displays a single blog post |
| AddPostView | Creates a new blog post |
| UpdatePostView | Updates an existing blog post |
| DeletePostView | Deletes a blog post |
| AddCategoryView | Creates a new category |
| CategoryView | Filters posts by category |

---

## 📷 Screens

- Home Page
- Blog Details
- Add Post
- Edit Post
- Delete Post
- Add Category
- Category Listing

---

## 🔮 Future Improvements

- User Authentication
- Rich Text Editor
- Comments System
- Likes & Reactions
- Search Functionality
- Pagination
- Tags
- User Profiles
- Image Uploads
- REST API

---

## 👨‍💻 Author

**Akash Gautam**

Frontend Developer | React.js | Django | Python

---

## 📄 License

This project is developed for learning purposes and is open for educational use.
