# **Google Calendar Clone**

A full-featured Google Calendar clone built using **Next.js**, **React**, **Day.js**, **Neon Postgres**, and **Drizzle ORM**.  
This project demonstrates building a complete calendar system with event creation, date management, recurring logic, and backend integration.

---

## 🌐 **Features**
- Add Events  
- Month, Week & Day Views  
- Recurring Event Support  
- Conflict Detection  
- Responsive UI  

---

## 🧰 **Tech Stack**
- **React.js**  
- **Next.js**  
- **Shadcn UI**  
- **Tailwind CSS**  
- **Neon / PostgreSQL**  
- **Drizzle ORM**

---

## 🏗️ **Architecture & Technology Choices**

### **Next.js & React**
- Handles routing, server actions, and rendering.  
- Ideal for building highly interactive calendar UIs.

### **Day.js**
Used for:
- Generating month/week/day data  
- Parsing and formatting dates  
- Recurring event logic  
- Time calculations and comparisons  

### **Neon Postgres**
- Low-latency cloud Postgres  
- Stores events and recurring rules

### **Drizzle ORM**
- Strongly typed schema + migrations  
- Reliable, predictable database operations  

### **Shadcn UI + Tailwind CSS**
- Clean UI components  
- Smooth transitions, modals, and interactions  

---

## ⚙️ **Business Logic & Edge Cases**

### ✔ **Event Creation**
Supports:
- Title  
- Description  
- Start & end times  
- Event color labels  
- One-time or recurring events  

### ✔ **Recurring Events**
- Daily / weekly / monthly recurrence  
- Expands recurring events in UI  
- Avoids duplication  

### ✔ **Overlap & Conflict Detection**
- Detects overlapping events  
- Prevents conflicting schedules  
- Ensures accurate week/day layout  

### ✔ **Timezone Handling**
- Normalized DB date storage  
- Consistent rendering across timezones  

---

## ✨ **Animations & Interactions**
- Modal open/close animations  
- Hover interactions  
- Grid highlight on selection  
- Smooth Month ↔ Week ↔ Day transitions  

---

## 🚀 **Future Enhancements**
- Drag-and-drop event movement  
- Resizable event durations  
- Advanced RRULE recurring editor  
- Multiple calendars with color coding  
- Shared / collaborative calendars  
- Notifications & reminders  
- OAuth login (Google/GitHub)  
- Dark mode  


OAuth login (Google/GitHub)

Dark mode
