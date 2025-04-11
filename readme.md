# 🏢 Meeting Room Solution – Power Apps

This Power Apps solution helps manage meeting room bookings effectively and resolves scheduling conflicts. Users can create, view, and manage meetings through great user experience interface.

---

## 🚀 Features

- 📊 **Dashboard Page**  
  View all scheduled meetings in a consolidated format. Quickly assess room usage and avoid overlapping bookings.
  
- ➕ **Create Meeting Page**  
  Add new meeting details including room, date, time, attendees, and purpose. Built-in logic ensures no time conflicts.

- 📅 **Calendar View Page**  
  View meetings by calendar date. Easily navigate and filter meetings by date, room, or organizer.

---

## 🧩 Components Used

- Power Apps Canvas App  
- SharePoint List (data storage)  
- Power Automate (optional for notifications)  
- Office 365 Outlook Connector (calendar sync)

---

## 🗂️ Data Structure

| Field Name    | Type        | Description                             |
|---------------|-------------|-----------------------------------------|
| MeetingTitle  | Text        | Title or purpose of the meeting         |
| Organizer     | Person      | User who booked the meeting             |
| Room          | Choice/Text | Selected meeting room                   |
| StartTime     | DateTime    | Meeting start date and time             |
| EndTime       | DateTime    | Meeting end date and time               |
| Attendees     | People      | List of participants                    |
| Description   | Text        | Additional meeting details              |

---

## 📥 How to Add a Meeting

1. Go to the **Create Meeting** page.
2. Fill in the required details.
3. Submit to save the meeting.
4. If a conflict is detected (same room and overlapping time), the app will prompt you to reschedule.

---

## 🔄 Conflict Resolution Logic

- Checks for:
  - Overlapping meetings in the same room.
  - Double-booked organizers.
- Users are notified of conflicts before saving.
- Encourages selecting a different room or time slot.

---

## 📸 Screenshots

### 🔷 Dashboard Page – All Meetings Overview  
![Image](https://github.com/user-attachments/assets/171e8dbe-cf43-47a9-91c6-621ec41da706)

### 🔷 Create Meeting Page – Booking Interface  
![Image](https://github.com/user-attachments/assets/df1e7751-7004-4848-ab54-882e0f811a89)

### 🔷 Calendar View – Date-wise Meetings  
![Image](https://github.com/user-attachments/assets/771c5958-9976-4241-a5f6-0c8add2f34b5)

---

## 🔧 Features
- Microsoft Outlook calendar sync  
- Power Automate notifications and approvals  
- Admin panel for managing rooms and users  
- Visual indicators for available/unavailable time slots

---

## 👨‍💻 Developed By

**Shuvo Kumar Das**  

📧 shuvokd1210@gmail.com 
🌐 https://www.linkedin.com/in/shuvookd/

