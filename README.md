## 🚆 Online Reservation System

This is a *Java-based console application* for simulating an *Online Railway Reservation System. The application allows users to **make reservations, **cancel reservations, and **view confirmation details* through a simple command-line interface.

 💻 Features

 ✅ *User Login Authentication*
 📝 *Make a Reservation* (Enter details like train number, class type, journey date, source, and destination)
 ❌ *Cancel Reservation* (With confirmation prompt)
 🔐 *Secure Access* using predefined user credentials
 📄 *PNR Generation* for each reservation
 🧾 *Reservation Data Handling* using HashMaps

 🖥 Sample Run (Screenshot)

<img width="1920" height="1080" alt="Screenshot (96)" src="https://github.com/user-attachments/assets/92b1a57a-3343-47ad-baae-3a94bb560843" />




> In this run:
>
> * The user successfully logs in.
> * Makes a reservation with details (e.g., Train Number: 12345, Class Type: AC).
> * A PNR number is generated (PNR1000).
> * Then the user opts to cancel the reservation using the same PNR.

---

### 🛠 Technologies Used

* *Java*
* *HashMap* for storing reservation data
* *Scanner* for user input
* *Console-based UI*

### 📂 File Structure

├── OnlineReservationSystem.java   # Main logic file
├── Reservation.class              # Reservation data model
├── User.class                     # User authentication
├── Screenshot (96).png            # Sample execution screenshot

### 🔒 Default Login Credentials

```
Login ID: user1
Password: pass1
