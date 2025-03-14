

# 📌 Minus -TodoList : Todo List Application

🚀 A simple **Todo List Application** built with **Flask** and **SQLite3**, featuring user authentication, CRUD operations, and a sleek **Tron Legacy** theme.

## 🔧 Tech Stack

- 🟠 **Flask** – Lightweight WSGI web application framework
- 🛢️ **Flask-SQLAlchemy** – ORM for seamless database interactions
- 📝 **Flask-WTF & WTForms** – Streamlined form handling and validation
- ⚡ **Gunicorn** – Production-ready WSGI server for deployment
- 🎨 **Bootstrap** – Responsive UI components

## 🌟 Features

✅ **User Authentication** – Secure login and task management  
📝 **CRUD Operations** – Create, read, update, delete tasks  
📱 **Responsive Design** – Works smoothly across all devices  
🌙 **Dark Mode Toggle** – Enhances user experience  
💬 **Flash Messages** – Instant feedback on user actions  
🎨 **Custom Styling** – Futuristic **Tron Legacy** theme  

## 📂 Project Structure

```
📦 Todo List Application
├── 📂 Assets/images/  # Contains images like favicon
│  ├── 🖼️ favicon.png  
├── 📂 instance/     # Contains SQLite database file
│  ├── 🗄️ site.db    
├── 📂 templates/    # HTML templates for frontend
│  ├── 📜 add.html    
│  ├── 📜 base.html   
│  ├── 📜 delete.html  
│  ├── 📜 edit.html   
│  ├── 📜 index.html   
├── 📜 LICENSE
├── 📜 app.py      # Main application logic
├── 📜 forms.py     # Handles form validation and processing
├── 📜 models.py     # Database schema and interactions
├── 📜 routes.py     # Defines application routes
├── 📜 requirements.txt # Required Python packages
├── 📜 SECURITY.md    # Security guidelines
├── 📜 README.md     # Project documentation
```

## 💻 Installation & Setup

1️⃣ **Clone the repository:**
```bash
git clone https://github.com/yourusername/todolist.git
cd todolist
```

2️⃣ **Create a virtual environment & activate it:**
```bash
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate
```

3️⃣ **Install dependencies:**
```bash
pip install -r requirements.txt
```

4️⃣ **Run the application:**
```bash
python app.py
```

🚀 Open `http://127.0.0.1:5000` in your browser!

## 🌍 Deployment

Deploy using **Gunicorn**:
```bash
gunicorn app:app
```
Under [ https://render.com ]


## 🔗 Links

🔹 **GitHub Repository**: [GitHub Link](https://github.com/AlienMinus/Todolist)  
🌍 **Live Demo**: [Live App](https://minus-todolist.onrender.com)  

## 🎯 Contributing

Contributions are welcome! Feel free to **fork** the repo, create a **pull request**, or open an **issue**. 🚀

## 📜 License

📄 This project is licensed under the **MIT License**.

---

💡 **Let's build something amazing together!** 🚀
