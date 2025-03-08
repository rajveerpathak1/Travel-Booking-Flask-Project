# Travel Booking System

##  Overview
This is a **Flask-based Travel Booking System** that allows users to:
- Book **buses, trains, flights, and hotels**.
- Register and log in as a **user or admin**.
- Manage bookings and seat reservations.
- Make payments using **Stripe**.
- Communicate via **AI Chatbot integration**.

##  Project Structure
```
📂 travel_booking_system
│-- 📂 templates/      # HTML templates (home, booking, login, etc.)
│-- 📂 static/         # CSS, JS, Images
│-- 📂 migrations/     # Database migrations (if using Flask-Migrate)
│-- 📂 routes/         # Flask route handlers
│-- 📂 models.py       # Database models (SQLAlchemy)
│-- 📄 app.py          # Main Flask application
│-- 📄 config.py       # App configurations
│-- 📄 requirements.txt # Project dependencies
│-- 📄 README.md       # Project documentation
```

##  Installation & Setup
### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/your-username/travel-booking-system.git
cd travel-booking-system
```

### **2️⃣ Create and Activate a Virtual Environment**
```sh
# For Windows\python -m venv venv
venv\Scripts\activate

# For macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

### **3️⃣ Install Dependencies**
```sh
pip install -r requirements.txt
```

### **4️⃣ Configure MySQL Database**
Update `config.py` with your **MySQL credentials**:
```python
app.config['SQLALCHEMY_DATABASE_URI'] = 'mysql://root:your_password@localhost/travel_db'
app.config['SQLALCHEMY_TRACK_MODIFICATIONS'] = False
app.secret_key = 'your_secret_key'
```

### **5️⃣ Initialize the Database**
```sh
flask db init
flask db migrate -m "Initial migration."
flask db upgrade
```

### **6️⃣ Run the Application**
```sh
flask run
```
Visit **http://127.0.0.1:5000/** in your browser.

---

##  Features
✅ **User & Admin Login System** 
✅ **Bus, Train, Flight & Hotel Booking**  
✅ **Seat Reservation & Management** 
✅ **MySQL Database for Data Persistence**   
✅ **Stripe Payment Integration**   
✅ **Chatbot Integration with OpenAI**   
✅ **Session-based Shopping Cart for Booking Management**
✅ **Secure Password Hashing & Authentication**   

## 📷 Screenshots
(Include images of the working application)

##  Technologies Used
- **Flask** (Python Web Framework)
- **MySQL** (Database)
- **SQLAlchemy** (ORM for database management)
- **Jinja2** (HTML templating)
- **Stripe API** (Payment processing)
- **Flask-CORS** (Handling CORS issues)
- **Flask-Session** (User session management)
- **OpenAI API** (Chatbot integration)

##  License
This project is licensed under the MIT License.

##  Contributing
Feel free to submit a pull request if you’d like to contribute! 😊

