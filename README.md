
# 🧠 MindJournal – A Mental Health Journal & Mood Tracker

MindJournal is a fully responsive and modern web application built with React.js and Vite, designed to help users log their thoughts, track daily moods, and gain insights into their mental well-being.

---

## 🚀 Features

- **User Authentication:** Secure login and registration system using GoogleAuth and Context API for session management.
- **Dashboard Overview:** A centralized dashboard displaying recent journal entries, current mood status, a quick mood chart, and an integrated **Heatmap Visualization** — an interactive, color-coded view of mood trends with a dropdown to filter by Week, Month, or Year.
- **Mood Tracker & Visual Insights:**
  - Log daily moods with emoji-based selection.
  - View interactive charts powered by Recharts for mood trends over time.
  - Explore detailed mood analytics on the Insights page.
- **Calendar View:** Navigate past journal entries and moods using an interactive calendar component.
- **Journal Entry Management (CRUD):**
  - Create, edit, view, and delete personal journal entries.
  - Clean UI for daily reflections and personal notes.
- **Gratitude Journal:**
  - A new page for users to record 3 things they’re grateful for daily.
  - Data is stored locally for privacy. Accessible from the main navigation.
- **Insights & Analytics Page:**  
  - Visualize mood trends over **Week, Month, or Year** using interactive **Pie Charts, Bar Charts for   better   tracking of your mental well-being.
- **Settings Page:**
  - Manage user preferences.
  - Toggle between Dark and Light themes.
- **MindBot AI:**
  - An AI-powered chatbot for personalized mental health journaling support.
  - Suggests reflection prompts, coping strategies, and mood improvement tips.
- **Theme Support:** Responsive dark/light mode with Context-based toggle.
- **Navigation:** Smooth and intuitive routing with React Router.
- **Modern UI/UX:**
  - Built using Tailwind CSS.
  - Consistent styling with reusable components.
  - Smooth scrolling for seamless navigation.
  - Hover effects and interactive animations for enhanced user experience.
  - Responsive design optimized for all devices.
- **Clean Architecture:**
  - Modular React component structure.
  - Efficient use of React Hooks and Context API for state and theme management.

---

## 📚 Table of Contents

- [🚀 Features](#-features)
- [🛠 Tech Stack](#-tech-stack)
- [💻 Installation](#-installation)
- [📖 Usage](#-usage)
- [📁 Folder Structure](#-folder-structure)
- [📸 Demo](#-demo)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [🙏 Acknowledgments](#-acknowledgments)

---

## 🛠 Tech Stack

- **Frontend:** React.js, Vite
- **Styling:** Tailwind CSS
- **State Management:** Context API, React Hooks
- **Routing:** React Router
- **Charts:** Recharts
- **Icons:** React Icons
- **Backend:** Node.js, Express.js

---

## 💻 Installation

**Prerequisites**
- Node.js (v14 or higher)
- npm or yarn

**Steps**
```bash
git clone https://github.com/your-username/MindJournal.git
cd MindJournal
npm install
npm run dev
````

Visit [http://localhost:5173](http://localhost:5173) in your browser.

---

## 📖 Usage

1. Log in or register to create an account.
2. Use the dashboard to quickly view mood status and past entries.
3. Navigate to the calendar to see or edit past logs.
4. Head to the Insights page to visualize mood trends.
5. Switch between light/dark themes from the Settings tab.

---

## 📁 Folder Structure

```plaintext
MindJournal/
├── Backend
├── public/               # Static files
├── src/
│   ├── components/       # Reusable components
│   │   ├── calendar/     # Calendar view
│   │   ├── common/       # Shared UI elements (e.g., ThemeToggle)
│   │   ├── dashboard/    # Dashboard widgets
│   │   └── ...           
│   ├── App.jsx           # Main app component
│   ├── main.jsx          # Entry point
│   ├── App.css, index.css
├── index.html
├── tailwind.config.js
├── vite.config.js
└── README.md
```

---

## 📸 Demo

Here are some screenshots of MindJournal in action:

 <img src="public/demo1.jpg" width="300"> &nbsp;&nbsp;&nbsp;  &nbsp;&nbsp;&nbsp; <img src="public/demo2.jpg" width="300"> <br><br>
 <img src="public/demo3.jpg" width="300"> &nbsp;&nbsp;&nbsp;  &nbsp;&nbsp;&nbsp; <img src="public/demo4.jpg" width="300"> <br><br>

---

## 🤝 Contributing

We welcome all kinds of contributions!

### How to Contribute

1. Fork the repository.
2. Create your branch:

   ```bash
   git checkout -b feature-name
   ```
3. Make your changes.
4. Commit your changes:

   ```bash
   git commit -m "Add feature"
   ```
5. Push to the branch:

   ```bash
   git push origin feature-name
   ```
6. Submit a Pull Request.

Please refer to our `CONTRIBUTION.md` for detailed guidelines.

---

## 📄 License

This project is licensed under the **MIT License**.
You’re free to use, modify, and share under the license terms.

---

## 🙏 Acknowledgments

* Inspired by mental wellness tools like Daylio, Moodpath, and Reflectly
* Built using open-source tools and love 💖
* Thanks to the developer community!

---

⬆ **[Back to Top](#-mindjournal--a-mental-health-journal--mood-tracker)**
