# 🛒 FruitMart – Django E-Commerce Grocery Store

FruitMart is a responsive, full-stack e-commerce web application for fresh fruit and grocery shopping. Built with Django and Bootstrap, it allows users to browse products, search for items, manage a cart, and place orders with a sleek, user-friendly interface.

![FruitMart Screenshot](assets/fruitmart_home.png)

---

## 🚀 Features

- 🧺 Product catalog with images, descriptions, and dynamic pricing
- 🛒 Cart system with "Add to Cart" and "Buy Now" functionality
- 🔍 Search bar for quick product lookup
- 👤 User authentication (sign up, login, session-based cart)
- 📦 Order placement and confirmation
- 📱 Mobile-responsive layout using Bootstrap
- 🧠 Scalable, modular Django app structure

---

## 🧰 Tech Stack

| Layer       | Tools Used                          |
|-------------|-------------------------------------|
| Frontend    | HTML5, CSS3, Bootstrap, JavaScript |
| Backend     | Django 4.x, Django ORM              |
| Database    | SQLite (PostgreSQL-compatible)      |
| Auth        | Django Auth                         |
| Deployment  | Render / Railway / Localhost        |
| Versioning  | Git & GitHub                        |

---

## 🗂️ Project Structure

```text
fruitmart/
├── manage.py
├── requirements.txt
├── db.sqlite3
├── media/                     # Uploaded product images
├── static/                    # Static files (CSS, JS, assets)
│
├── fruitmart/                 # Django project configuration
│   ├── __init__.py
│   ├── settings.py            # Global settings
│   ├── urls.py                # Root URL routing
│   ├── wsgi.py
│   └── asgi.py
│
├── store/                     # Core e-commerce logic
│   ├── admin.py
│   ├── apps.py
│   ├── models.py              # Product, Cart, Order models
│   ├── views.py               # Business logic
│   ├── urls.py                # App-level routing
│   ├── templates/store/       # Product listing templates
│   └── static/store/          # Store-specific CSS/JS
│
├── users/                     # Custom user app (auth)
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py              # (If extending default User)
│   ├── views.py
│   ├── urls.py
│   └── templates/registration/  # Login, signup templates
│
└── templates/                 # Base HTML templates (base.html, etc.)
```

---

## 🧪 Setup Instructions

> Follow the steps below to run the project locally:

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/fruitmart.git
cd fruitmart
```

### 2. Create a virtual environment & install dependencies

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### 3. Apply migrations and run the server

```bash
python manage.py migrate
python manage.py runserver
```

### 4. Access the app

Open [http://localhost:8000](http://localhost:8000) in your browser.

---

## 🌐 Live Demo

[🔗 https://fruitmart.onrender.com](https://fruitmart.onrender.com) *(Deployed on Render)*

---

## 📸 Screenshots

| Homepage | Product Grid | Cart |
|----------|--------------|------|
| ![Home](assets/homepage.png) | ![Grid](assets/products.png) | ![Cart](assets/cart.png) |

---

## 🧩 Potential Improvements & Roadmap

### 🔧 Core Technical Improvements
- **Stripe/PayPal Integration** for secure payments.
- Enhanced **Django Admin** with product management tools.
- Add **Django REST Framework** APIs for products, orders, and cart.
- **User Profiles** with saved addresses and order history.

### 🎯 UX and Frontend Enhancements
- **AJAX-based interactions** for cart, search, and auth.
- Add **product filtering, sorting, and pagination**.
- Improve search with **full-text search** or `django-haystack`.
- Fully optimized **mobile experience** (sticky cart, mobile nav).

### 🔒 Security & Robustness
- Secure uploads, strong auth, CSRF protection (production-ready config).
- Add unit and integration tests (`pytest-django`).
- CI/CD using **GitHub Actions** or GitLab CI.

### ☁️ DevOps & Deployment
- Add **Docker** support (`Dockerfile`, `docker-compose.yml`).
- Use `.env` for environment variables (`python-decouple` or `django-environ`).
- Add **error logging/monitoring** (e.g., Sentry).

### 🧠 AI/ML & Smart Features
- **Product Recommendations** (based on cart or popularity).
- Add a **FAQ chatbot** for customer support.

### 📈 Business-Ready Features
- **Discount Codes / Coupons** with expiry and limits.
- **Email Notifications** for order confirmations and status.
- **Abandoned Cart Reminders** via email or alerts.

---

## 👤 Author

**Daniel** – [LinkedIn](https://linkedin.com/in/daniel-agblevor) | [GitHub](https://github.com/daniel-agblevor)  
_Data Scientist & Backend Developer passionate about full-stack innovation._

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

### ✅ Next Steps:

1. **Update screenshot paths** (replace `assets/homepage.png`, etc.)
2. **Deploy** the site to [Render](https://render.com/) or [Railway](https://railway.app/) and update the Live Demo link.
3. Replace `yourusername` and `yourname` with actual GitHub/LinkedIn info.
4. Push the `README.md` to your GitHub repo root.

Let me know if you'd like help automating deployment or implementing any of the enhancements above.iendly interface.

![FruitMart Screenshot](assets/screenshot.png)

---

## 🚀 Features

- 🧺 Product catalog with images, descriptions, and dynamic pricing
- 🛒 Cart system with "Add to Cart" and "Buy Now" functionality
- 🔍 Search bar for quick product lookup
- 👤 User authentication (sign up, login, session-based cart)
- 📦 Order placement and confirmation
- 📱 Mobile-responsive layout using Bootstrap
- 🧠 Scalable, modular Django app structure

---

## 🧰 Tech Stack

| Layer       | Tools Used                          |
|---          |        |
|-------------|-----------|
| Frontend    | HTML5, CSS3, Bootstrap, JavaScript |
| Backend     | Django 4.x, Django ORM              |
| Database    | SQLite (PostgreSQL-compatible)      |
| Auth        | Django Auth                         |
| Deployment  | Render / Railway / Localhost        |
| Versioning  | Git & GitHub                        |

---

## 🗂️ Project Structure

```
fruitmart/
├── manage.py
├── fruitmart/             # Project config
│   ├── settings.py
│   ├── urls.py
├── store/                 # Core app
│   ├── models.py          # Product, Order, Cart models
│   ├── views.py           # Logic for views
│   ├── urls.py            # App routing
│   ├── templates/store/   # HTML templates
├── users/                 # User auth system
│   ├── views.py, forms.py
│   ├── templates/registration/
├── static/                # CSS, JS, images
├── media/                 # Product images
└── requirements.txt
```

---

## 🧪 Setup Instructions

> Follow the steps below to run the project locally:

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/fruitmart.git
cd fruitmart
```

### 2. Create a virtual environment & install dependencies

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### 3. Apply migrations and run the server

```bash
python manage.py migrate
python manage.py runserver
```

### 4. Access the app

Open [http://localhost:8000](http://localhost:8000) in your browser.

---

## 🌐 Live Demo

[🔗 https://fruitmart.onrender.com](https://fruitmart.onrender.com) &nbsp; *(Deployed on Render)*

---

## 📸 Screenshots

| Homepage | Product Grid | Cart |
|----------|--------------|------|
| ![Home](assets/homepage.png) | ![Grid](assets/products.png) | ![Cart](assets/cart.png) |

---

## 🔒 Optional Improvements

- Stripe/PayPal integration for payments
- REST API with Django REST Framework
- Admin dashboard enhancements
- Docker support (`Dockerfile`, `docker-compose.yml`)
- Unit testing with `pytest-django`

---

## 👤 Author

**Daniel** – [LinkedIn](https://linkedin.com/in/daniel-agblevor) | [GitHub](https://github.com/daniel-aglevor)  
_Data Scientist & Backend Developer passionate about full-stack innovation._

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
```

---
