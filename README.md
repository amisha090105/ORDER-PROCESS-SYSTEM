# Order Management System

A web-based order management system built using Flask for managing products, customers, orders, and cost tracking.

## 🚀 Features

* Add and manage products
* Place and cancel orders
* View customer details and order history
* Generate customer summaries
* Track order costs and transactions
* Simple UI using HTML templates

## 🛠️ Tech Stack

* **Backend:** Flask (Python)
* **Frontend:** HTML, CSS (Jinja Templates)
* **Database:** MongoDB / SQLite

## 📂 Project Structure

```
app.py
templates/
  ├── base.html
  ├── index.html
  ├── products.html
  ├── customers.html
  ├── place_order.html
  ├── list_orders.html
  ├── order_details.html
  ├── customer_summary.html
```

## ⚙️ Setup Instructions

### 1. Clone repository

```
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install dependencies

```
pip install flask pymongo
```

### 3. Run the application

```
python app.py
```

### 4. Open in browser

```
http://localhost:5000
```

## 📊 Highlights

* Implemented RESTful routes for product management, order placement, and tracking
* Designed workflows for efficient order processing and customer summaries
* Structured application for scalable backend logic and reporting

## 🚀 Future Improvements

* Add user authentication
* Enhance UI/UX
* Deploy on cloud (Render / AWS)
* Add analytics dashboard

---
