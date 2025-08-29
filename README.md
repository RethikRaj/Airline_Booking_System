# ✈️ Airline Booking System  

A **microservices-based airline booking platform** built using Node.js, Express, and MySQL.  
This project demonstrates **scalable system design**, **service-to-service communication**  for a real-world use case of flight booking.  

---

## 📌 Overview  
The system is designed with a **microservices architecture**, where each service is independently developed and deployed. It ensures **loose coupling**, **scalability**, and **maintainability**.

### 🔑 Key Features  
- ✈️ **Flight Service** – Manage flights search, schedules, and availability.  
- 🎟 **Booking Service** – Handle seat reservations and booking management.  
- 🌐 **API Gateway** – Entry point for clients, handles reverse proxy , authentication and authorization
- 🗄 **Database Integration** – MySQL for structured storage.  
- 📨 **Inter-service Communication** – REST APIs for service coordination.  

---


---

## 📂 Microservices  

🔹 **[Flights Service](https://github.com/RethikRaj/Flights_Service)**  
Handles flight creation, updates, and availability.  

🔹 **[Flights Booking Service](https://github.com/RethikRaj/Flights_Booking_Service)**  
Manages reservations, seat availability, and user bookings.  

🔹 **[Flights API Gateway](https://github.com/RethikRaj/Flights_API_Gateway)**  
Central entry point for clients; routes requests to the appropriate microservice.  

---

## 🚀 Tech Stack  

- **Backend:** Node.js, Express  
- **Database:** MySQL  
- **Architecture:** Microservices  
- **API Gateway:** Express Gateway  
- **Deployment:** Docker, Docker Compose  
- **Communication:** REST APIs  

---


---

## 📂 Microservices  

🔹 **[Flights Service](https://github.com/RethikRaj/Flights_Service)**  
Handles flight creation, search ,updates, and availability.  

🔹 **[Flights Booking Service](https://github.com/RethikRaj/Flights_Booking_Service)**  
Manages reservations, seat availability, and user bookings.  

🔹 **[Flights API Gateway](https://github.com/RethikRaj/Flights_API_Gateway)**  
Central entry point for clients; routes requests to the appropriate microservice.  

---

## 🚀 Tech Stack  

- **Backend:** Node.js, Express  
- **Database:** MySQL  
- **ORM** : Sequelize
- **Architecture:** Microservices  

---

## ⚙️ Setup Instructions  

1. Clone the repositories:  
   ```bash
   git clone https://github.com/RethikRaj/Flights_Service
   git clone https://github.com/RethikRaj/Flights_Booking_Service
   git clone https://github.com/RethikRaj/Flights_API_Gateway

2. Install dependencies for each service

3. Set up .env files for each service with database and port configurations.


