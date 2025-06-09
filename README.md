# Gamified_User_Dashboard

Welcome to the Gamified User Dashboard! This React-based web application allows users to track their points, progress, and activity streaks in a fun and engaging way. It features a mock user login, displays key metrics like XP, level, and streak, and includes a mood check-in/journaling feature.

## ✨ Features

*   **User Authentication:** Mock login/registration system (currently using localStorage).
*   **Gamified Stats:**
    *   Experience Points (XP) tracking.
    *   Level progression.
    *   Daily activity streak counter.
    *   Display of the last action performed.
*   **Mood Journal:**
    *   Emoji-based mood selection.
    *   Text input for journaling thoughts.
*   **Progress Visualization:**
    *   Progress bar showing XP towards the next level.
*   **Quick Actions:** Buttons to simulate common tasks and earn XP.
*   **Visually Appealing UI:**
    *   Modern design with gradients, glassmorphism, and smooth animations.
    *   Built with TailwindCSS and shadcn/ui components.
    *   Animations powered by Framer Motion.
*   **Toast Notifications:** For user feedback on actions and achievements.

## 🚀 Tech Stack

*   **Frontend:**
    *   React 18.2.0
    *   Vite (Build Tool & Dev Server)
    *   JavaScript (ES6+)
*   **Styling:**
    *   TailwindCSS 3.3.2
    *   shadcn/ui (component library)
*   **Animations:**
    *   Framer Motion 10.16.4
*   **Icons:**
    *   Lucide React 0.292.0
*   **State Management:**
    *   React Hooks (useState, useEffect, custom hooks)
    *   localStorage (for current mock data persistence)

## 🛠️ Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

*   Node.js (v20 or higher recommended)
*   npm (comes with Node.js)

### Installation & Setup

1.  **Clone the repository (or download the source code):**
    ```bash
    git clone https://github.com/Utkrisht2/Gamified_User_Dashboard
    cd gamified-user-dashboard
    ```
    If you've exported the project, simply navigate to the extracted folder.

2.  **Install NPM packages:**
    Open your terminal in the project's root directory and run:
    ```bash
    npm install
    ```

3.  **Run the development server:**
    Once the dependencies are installed, start the Vite development server:
    ```bash
    npm run dev
    ```
    This will typically start the application on `http://localhost:5173`. Open this URL in your web browser to see the app.

## 📜 Available Scripts

In the project directory, you can run:

*   `npm run dev`: Runs the app in development mode.
*   `npm run build`: Builds the app for production to the `dist` folder.
*   `npm run preview`: Serves the production build locally for testing.

## 📁 Project Structure

```
gamified-user-dashboard/
├── public/               # Static assets
├── src/
│   ├── components/       # React components
│   │   ├── ui/           # shadcn/ui components
│   │   ├── Dashboard.jsx
│   │   ├── LoginForm.jsx
│   │   └── MoodCheckIn.jsx
│   ├── hooks/            # Custom React Hooks (useAuth.js, useGameData.js)
│   ├── lib/              # Utility functions (utils.js)
│   ├── App.jsx           # Main application component
│   ├── index.css         # Global styles and TailwindCSS setup
│   └── main.jsx          # Application entry point
├── .gitignore
├── index.html            # Main HTML file
├── package.json          # Project dependencies and scripts
├── postcss.config.js     # PostCSS configuration
├── tailwind.config.js    # TailwindCSS configuration
└── vite.config.js        # Vite configuration
```

## 🔮 Future Enhancements (Suggestions)

*   **Backend Integration:** Migrate from localStorage to a proper backend solution like Supabase or Firebase for persistent data storage and real user authentication.
*   **Advanced Gamification:**
    *   Badges and achievements system.
    *   Leaderboards.
    *   Customizable avatars or themes.
*   **More Activities:** Expand the types of activities users can track.
*   **Data Visualization:** Charts or graphs for mood trends or activity history.
*   **Notifications:** In-app or push notifications for reminders or achievements.

##🤝 Contributing

Contributions, issues, and feature requests are welcome!

---

This README provides a good overview of your project. Enjoy developing your Gamified User Dashboard!
