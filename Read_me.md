# Grade 11a Cs team project_Hotel managementsystem
Grp members: Eshan, Jonathen and Joshua

---

# 🏨 **Hotel Management System **

Welcome to the github collaboration codespace, here we work tgthr for our cs grade 11 team project
  once u finish reading this, paste the code u created and programmed into ur respective file names.py file then once thats over i will compile it into the Main_app.py file making all edits, modifications and changes.

---

## 👑 Roles & Responsibilities

### **Joshua (Lead Developer — GUI & Flow)**

* Build the **Tkinter GUI** (Signup/Login → Dashboard → Tabs).
* Add **hotel\_main.png** as background on Login/Signup.
* Dashboard should have 3 buttons:

  1. **Rooms** (show 2–3 room images + Book button → call Jonathan’s booking function).
  2. **Services** (just show a list: Food, Gym, Pool, Plantation Tour).
  3. **Customer Service** (textbox + chatbot area for Eshan).
* If user = VIP → switch to **black+gold theme** (premium look).

✅ That’s it. Just GUI + buttons + themes.

---

### **Jonathan (Backend — Database & Booking)**

* Create **SQLite database** with:

  * `users(username, password, vip_status)`
  * `bookings(username, room, date)`
* Functions to:

  1. **Signup/Login** (check from DB).
  2. **Book Room** (insert into bookings table).
  3. **Check VIP** (if user booked 3+ times → vip\_status = True).
* Provide these functions for Joshua to call from GUI.

✅ Just 2 tables + 3 functions. Nothing heavy.

---

### **Eshan (Chatbot + Documentation)**

* Make a **simple rule-based chatbot**:

  * If input contains “room” → reply “Please go to Rooms tab to book.”
  * If input contains “food” → reply “Room service will deliver your order.”
  * Else → “Our staff will assist you shortly.”
* Connect chatbot box into Joshua’s **Customer Service tab**.
* Write **submission PDF** for mam:

  * Project Title, Aim, Features, Screenshots, Roles & Responsibilities, Conclusion.

✅ Just if-else chatbot + PDF.

---
