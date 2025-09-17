# 🏛️ Club Event Organizer Website

A comprehensive web application for **club event management**, built with **Flask**, **MySQL**, and **Bootstrap 5**.

[![Python](https://img.shields.io/badge/Python-3.8+-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## 🎬 Project Preview

![Website Screenshot](https://via.placeholder.com/600x300?text=Club+Event+Organizer+Preview)

> Replace the above placeholder with actual screenshots or GIFs of your website.  
> For example, show the homepage, event registration page, or admin dashboard.

---

## 🚀 Features

### User Features
- Browse and register for upcoming events  
- User authentication (login, registration, profile management)  
- View registered events in **My Events** section  
- Explore club information and photo gallery  

### Admin Features
- Secure admin dashboard  
- Event management (create, edit, delete, publish/unpublish)  
- User management (view, edit roles, delete)  
- Registration tracking and management  
- Content and gallery management  

---

## 🛠️ Technical Stack
- **Backend**: Python Flask  
- **Frontend**: HTML, CSS, JavaScript, Bootstrap 5  
- **Database**: MySQL  
- **Authentication**: Session-based with password hashing  

---

## ⚙️ Installation & Setup

1. **Clone the repository**

    ```bash
    git clone <repository-url>
    cd club_event_organizer
    ```

2. **Create & activate a virtual environment**

    ```bash
    python -m venv venv
    # On Windows:
    venv\Scripts\activate
    # On Linux/Mac:
    source venv/bin/activate
    ```

3. **Install dependencies**

    ```bash
    pip install -r requirements.txt
    ```

4. **Configure database**

    ```python
    # Update database connection in src/main.py if needed
    ```

5. **Run the application**

    ```bash
    python -m src.main
    ```

6. **Access locally**
    - Open [http://localhost:5000](http://localhost:5000) in your browser  
    - Default admin credentials:
        - Username: `admin`
        - Password: `admin123` *(change immediately after first login)*

---

## 🚀 Deployment

**Requirements:** Python 3.8+, MySQL, WSGI-compatible web server (Gunicorn/uWSGI)

**Steps:**
1. Set up a production database  
2. Update database connection string in `src/main.py`  
3. Configure WSGI server  
4. Set up reverse proxy with Nginx or Apache  
5. Enable HTTPS & secure cookies  

---

## 🎨 Customization

### Content Management
- Admin dashboard → update text and gallery  

### Styling
- Add custom CSS in `src/static/css/style.css`  
- Bootstrap 5 ensures responsive design  

---

## 🔒 Security Notes
- Change default admin password immediately  
- Update `SECRET_KEY` for production  
- Consider additional security measures for live deployment  

---

## 📄 License
MIT License – see the `LICENSE` file for details  

---

## 📦 Download
You can also provide your `.rar` archive for offline use:  
[Download Interact Website (RAR)](https://github.com/Kaftej1/interact-website/raw/master/interact-website.rar)

---

## 📷 Screenshots / GIFs (Optional)

Include screenshots or GIFs to make your project visually appealing. Example:

- Homepage  
- Event registration page  
- Admin dashboard

```markdown
![Homepage](screenshots/homepage.png)
![Admin Dashboard](screenshots/admin_dashboard.png)
