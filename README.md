# 📚 Online Courses Platform

A dynamic web-based learning management system built with Django, enabling seamless course registration and administration.

## 🎥 Demo

[📹 Watch the Video Demonstration](your-demo-link-here)

## 📖 About

Online Courses is a lightweight yet powerful platform designed to simplify online education. Users can browse and enroll in courses with a single click, while administrators manage content through Django's intuitive admin interface. The project emphasizes clean design, responsiveness, and ease of use for both learners and instructors.

## ✨ Key Features

### For Students
- 🔍 **Course Browsing** - Explore available courses with detailed information
- 🎯 **One-Click Enrollment** - Register for courses instantly
- 📱 **Responsive Design** - Seamless experience across all devices
- 🎨 **Modern UI** - Clean interface powered by Bootstrap 5

### For Administrators
- 🛠️ **Course Management** - Add, edit, and delete courses easily
- 📊 **Django Admin Panel** - Powerful built-in administration tools
- 📸 **Media Upload** - Support for course images and materials
- 🤖 **AI-Assisted Development** - Optimized database models

## 🛠️ Technical Stack

- **Python 3.13**
- **Django 5.2** - Web framework
- **SQLite3** - Database
- **Bootstrap 5** - Frontend styling
- **Django Crispy Forms** - Enhanced form rendering
- **Crispy Bootstrap5** - Bootstrap 5 template pack
- **NumPy** - For future analytics features
scikit-learn
## 📁 Project Structure
```
onlinecourses/
├── courses/              # Main Django app for course logic
│   ├── models.py         # Database models
│   ├── views.py          # View controllers
│   ├── urls.py           # URL routing
│   └── templates/        # HTML templates
├── media/                # User-uploaded content (images, files)
├── onlinecourses/        # Project configuration
│   ├── settings.py       # Django settings
│   ├── urls.py           # Main URL configuration
│   └── wsgi.py           # WSGI configuration
├── db.sqlite3            # SQLite database file
├── manage.py             # Django management script
└── requirements.txt      # Python dependencies
```

## 🚀 Installation & Setup

### Prerequisites

- Python 3.13 or higher
- pip package manager
- Git

### Step-by-Step Installation

1. **Clone the repository**
```bash
git clone https://github.com/Nurmukhammedcoder/onlinecourses.git
cd onlinecourses
```

2. **Create virtual environment** (recommended)
```bash
python -m venv venv

# Windows
venv\Scripts\activate

# Linux/macOS
source venv/bin/activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

Or install manually:
```bash
pip install django
pip install django-crispy-forms
pip install crispy-bootstrap5
pip install numpy
```

4. **Apply database migrations**
```bash
python manage.py makemigrations
python manage.py migrate
```

5. **Create superuser** (for admin access)
```bash
python manage.py createsuperuser
```

Follow the prompts to set username, email, and password.

6. **Run the development server**
```bash
python manage.py runserver
```

7. **Access the application**

- **Frontend**: http://127.0.0.1:8000/
- **Admin Panel**: http://127.0.0.1:8000/admin/

## 💻 Usage

### For Students

1. Visit the homepage
2. Browse available courses
3. Click "Enroll" to register for a course
4. View your enrolled courses in your dashboard

### For Administrators

1. Log in to the admin panel at `/admin`
2. Navigate to "Courses" section
3. Add new courses with:
   - Course title
   - Description
   - Duration
   - Instructor name
   - Course image
4. Manage enrollments and user data

## 🤖 AI-Assisted Development

This project leverages AI tools for:

- **Database Schema Design** - Auto-generated Django models for consistency
- **Code Optimization** - AI suggestions for improving code quality
- **Development Speed** - Faster prototyping and implementation

The use of AI helped ensure:
- Clean model structure
- Proper field relationships
- Best practices in Django development

## 🎨 Screenshots

### Homepage
![Homepage](screenshots/homepage.png)

### Course Details
![Course Details](screenshots/course-details.png)

### Admin Panel
![Admin Panel](screenshots/admin-panel.png)

*Note: Add actual screenshots to `screenshots/` folder*

## 📦 Requirements

Create `requirements.txt`:
```
Django==5.2
django-crispy-forms>=2.4
crispy-bootstrap5>=2024.1
numpy>=1.24.0
Pillow>=10.0.0
scikit-learn
```

## 🗺️ Future Roadmap

### Phase 1 (Completed)
- ✅ Basic course listing and enrollment
- ✅ Admin panel integration
- ✅ Responsive design
- ✅ AI-assisted model generation

### Phase 2 (Planned)
- 📋 User authentication and profiles
- 📋 Course progress tracking
- 📋 Certificate generation
- 📋 Payment integration
- 📋 Course ratings and reviews

### Phase 3 (Future)
- 🔮 Video lessons integration
- 🔮 Live class scheduling
- 🔮 Discussion forums
- 🔮 Mobile app version
- 🔮 Analytics dashboard

## 🔧 Configuration

### Database Settings

By default, the project uses SQLite. To use PostgreSQL or MySQL:

1. Update `settings.py`:
```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'your_db_name',
        'USER': 'your_db_user',
        'PASSWORD': 'your_password',
        'HOST': 'localhost',
        'PORT': '5432',
    }
}
```

2. Install database driver:
```bash
pip install psycopg2-binary  # for PostgreSQL
# or
pip install mysqlclient  # for MySQL
```

## 🐛 Troubleshooting

### Common Issues

**Issue**: `django-admin: command not found`  
**Solution**: Ensure Django is installed: `pip install django`

**Issue**: Static files not loading  
**Solution**: Run `python manage.py collectstatic`

**Issue**: Database errors  
**Solution**: Delete `db.sqlite3` and run migrations again

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/NewFeature`)
3. Commit your changes (`git commit -m 'Add NewFeature'`)
4. Push to the branch (`git push origin feature/NewFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Nurmukhammed**

- GitHub: [@Nurmuhammedcoder](https://github.com/Nurmuhammedcoder)
- Email: nekulov@internet.ru

## 🙏 Acknowledgments

- Django community for excellent documentation
- Bootstrap team for responsive CSS framework
- AI tools for accelerating development process

## 📧 Support

Having issues? Feel free to:
- Open an issue on GitHub
- Contact me with email
- Check Django documentation

---

⭐ **If you find this project useful, please give it a star!**

🚀 **Perfect for**: Learning Django, building educational platforms, or starting your own online course business!
