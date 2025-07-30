# 🎫 IRCTC Ticket Booking System (Java Console App)

A beginner-friendly ticket booking application built using Java. Inspired by the IRCTC system, this app allows users to register, log in, search for trains, and book or cancel tickets — all via a console-based menu.

---

## 📌 Table of Contents

- [Features](#-features)
- [Project Structure](#-project-structure)
- [Tech Stack](#-tech-stack)
- [Installation](#-installation)
- [Usage](#-usage)
- [Screenshots](#-screenshots)
- [Author](#-author)
- [License](#-license)

---

## 🚀 Features

- 🔐 User Registration & Login (with hashed passwords)
- 🚆 Train search by source & destination
- 🎟️ Ticket booking and cancellation
- 🧾 JSON file storage (no database needed)
- ☑️ Clean, modular Java architecture

---

## 📁 Project Structure

ticket-booking/
├── app/
│ └── src/
│ └── main/
│ └── java/
│ └── ticket.booking/
│ ├── entities/
│ │ ├── Ticket.java
│ │ ├── Train.java
│ │ └── User.java
│ ├── services/
│ │ ├── TrainService.java
│ │ └── UserBookingService.java
│ ├── util/
│ │ ├── UserServiceUtil.java
│ │ └── App.java
│ └── localDb/
│ ├── trains.json
│ └── users.json
├── build.gradle
└── settings.gradle

---

## ⚙️ Tech Stack

- **Java 17**
- **Gradle 8+**
- **IntelliJ IDEA**
- **Local JSON Storage**

---

## 🧪 Installation

### 1. Clone the repository


git clone https://github.com/viizznuu/ticket-booking.git
cd ticket-booking

Build the project
./gradlew build

Run the application
./gradlew run

📦 Usage
The application launches with a console menu:

markdown
Copy
Edit
Choose option:
1. Sign up
2. Login
3. Fetch Bookings
4. Search Trains
5. Book a Seat
6. Cancel my Booking
7. Exit the App

👨‍💻 Author
Vishnu V. K.

GitHub: @viizznuu

Email: vishnu77vr77@gmail.com

📄 License
This project is licensed under the MIT License.

You are free to use, modify, and distribute this code with credit. No warranties provided.

🙌 Contributions
Suggestions, pull requests, and forks are welcome. Let’s build something better together!
