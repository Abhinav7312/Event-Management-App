# 🎉 Event Management System

A fully functional web application for managing events, built with Django, HTML, CSS, and JavaScript. This system allows users to create, update, and delete events, categorize them, and visualize upcoming events through interactive charts.

🔗 **Live Demo**: [https://abhinav1122.pythonanywhere.com/](https://abhinav1122.pythonanywhere.com/)

---

## 🚀 Features

* **Event Management**: Create, update, and delete events with details like name, category, dates, priority, description, location, and organizer.
* **Category Management**: Organize events into categories for better classification.
* **Interactive Charts**: Visual representation of pending events by category using Chart.js.
* **Responsive Design**: Mobile-friendly interface using Bootstrap 4.
* **User-Friendly Forms**: Client-side validation to ensure data integrity.
* **Django Admin Panel**: Manage events and categories through Django's built-in admin interface.

---

## 🛠️ Technologies Used

* **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 4
* **Backend**: Python 3, Django Framework
* **Database**: SQLite (default Django database)
* **Charts**: Chart.js for data visualization
* **Hosting**: PythonAnywhere

---

## 📂 Project Structure

```
event_management/
├── event_management/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── events/
│   ├── migrations/
│   ├── templates/
│   │   └── events/
│   │       ├── base.html
│   │       ├── category_list.html
│   │       ├── create_event.html
│   │       ├── update_event.html
│   │       └── event_chart.html
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
├── db.sqlite3
└── manage.py
```

---

## ⚙️ Installation & Setup

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Abhinav7312/Event-Management-App.git
   cd Event-Management-App
   ```

2. **Create a virtual environment**:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations**:

   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Create a superuser**:

   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server**:

   ```bash
   python manage.py runserver
   ```

   Access the application at `(https://abhinav1122.pythonanywhere.com/)`

---

## 📝 Usage

* **Home Page**: Lists all categories. Click on a category to view its events.
* **Add Category**: Create a new category to classify events.
* **Add Event**: Fill out the form with event details. Ensure that the end date is after the start date.
* **Edit/Delete Event**: Modify or remove existing events.
* **Event Chart**: Visual representation of pending events by category.

---

## 🌐 Deployment

The application is deployed on [PythonAnywhere](https://www.pythonanywhere.com/). To deploy your own version:

1. **Create an account** on PythonAnywhere.
2. **Upload your project files** to your PythonAnywhere account.
3. **Set up a virtual environment** and install dependencies.
4. **Configure the web app** settings, including WSGI configuration and static files.
5. **Run migrations** and create a superuser.
6. **Reload the web app** to apply changes.

For detailed instructions, refer to PythonAnywhere's [official documentation](https://help.pythonanywhere.com/pages/DeployingDjango/).

---

## 🧑‍💻 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 📬 Contact

For any inquiries or feedback, please contact [Abhinav7312](mailto:your-abhinav.prakash.me@gmail.com).

---

