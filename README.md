# 🎓 Campus Nexus

A modern, responsive, and interactive web application designed to bridge the gap between faculty management and student campus life. Built with a stunning **glassmorphism UI**, this portal operates entirely on the client side, utilizing `localStorage` for robust, database-free state management.

## ✨ Key Features

### 👨‍🏫 Faculty Console
* **Dataset Import & Backup:** Easily import student data using `.xlsx` or `.csv` files and export daily backups.
* **Talent Search & Filtering:** Instantly search students by name, skills, or roll number.
* **Student Management:** View detailed student profiles, mark them as "Hired/Assigned", or delete records.
* **Direct WhatsApp Integration:** Auto-generates customized WhatsApp messages to invite students to tasks based on their primary skills.
* **Academic Year Promotion:** A dedicated utility to promote students to the next academic year while automatically graduating out-going batches (e.g., 4th Year BCA, 2nd Year MCA).

### 🎉 Campus Event Hub
* **Gamified Event Discovery:** Browse upcoming events categorized by Technical, Cultural, and Sports.
* **Live Countdowns & Capacity Tracking:** Real-time countdown timers for upcoming events and visual progress bars for RSVP capacity.
* **Trending Section:** Automatically highlights the top 2 events with the highest RSVP counts.
* **Instant RSVP System:** Students can register for events, triggering a celebratory confetti animation and a WhatsApp ticket confirmation.

### 🎨 UI & Customization
* **Four Unique Themes:** Instantly switch between *Light Mode*, *Dark Mode*, *Traditional*, and *Holi Special*.
* **Micro-interactions:** Custom toast notifications, fluid page transitions, and interactive ripple effects on buttons.

---

## 🛠️ Tech Stack

* **HTML5 & CSS3:** For structuring and styling the glassmorphism interface.
* **Vanilla JavaScript:** Handles DOM manipulation, state management, and logic without heavy frameworks.
* **LocalStorage API:** Ensures persistent data storage across sessions without needing a backend server.
* **Libraries:**
    * [SheetJS (xlsx.js)](https://sheetjs.com/): For parsing and exporting Excel/CSV files.
    * [Canvas-Confetti](https://www.npmjs.com/package/canvas-confetti): For gamified micro-interactions upon task completion or event RSVP.

---

## 🚀 Getting Started

Since this project relies completely on client-side technologies, setting it up is incredibly simple. No server configuration or database setup is required!

### Installation
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/met-campus-portal.git](https://github.com/your-username/met-campus-portal.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd met-campus-portal
    ```
3.  **Run the application:**
    Simply open the `MET edge.html` file in any modern web browser (Chrome, Firefox, Safari, Edge).

---

## 📖 Usage Guide

### Importing Student Data
To populate the Faculty Console, prepare an Excel (`.xlsx`) or CSV file with the following suggested headers:
* `Add your full name` (or `name`)
* `Add your contact number` (or `phone`)
* `Your Section` (or `section` - e.g., "First Year BCA")
* `What are your Primary Creative Interests ?` (or `skills`)
* `Your Roll no.`

Click **"📥 Import Dataset"** and select your file. The portal will automatically parse the data and generate interactive student cards grouped by their section.

### Resetting the App
If you need to clear the data and start fresh, navigate to the Faculty Console and click the **"Wipe Data"** button. *Note: This cannot be undone.*

---

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/your-username/met-campus-portal/issues).

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📜 License
Distributed under the MIT License. See `LICENSE` for more information.

> **Established 2026 // CLRT FREAKS - 10 // MET IOM NSK**
