# smart-alloc-dashboard
A corporate resource analytics dashboard built with React.js and Tailwind CSS. Features real-time task allocation, workload visualization, and efficiency tracking to optimize team performance.
# Smart-Alloc: Corporate Resource Analytics Dashboard 📊

**Smart-Alloc** is a Single Page Application (SPA) designed to streamline internal team task allocation and visualize project timelines. It solves the problem of manual resource tracking by providing a real-time dashboard for managers to monitor employee workload and project status.

🔗 **[Live Demo](PUT_YOUR_NETLIFY_OR_GITHUB_PAGES_LINK_HERE)**

## 🚀 Key Features

* **Real-time Analytics:** Visualizes total projects, efficiency rates, and resource workload using interactive Bar and Pie charts (powered by Recharts).
* **Task Management:** A dynamic system to assign, track, and delete tasks with immediate state updates.
* **Workload Balancing:** Helps identify overloaded employees to prevent burnout and optimize team output.
* **Data Persistence:** Uses the browser's `LocalStorage API` to save tasks even after a page refresh.
* **Responsive Design:** Fully adaptive UI built with Tailwind CSS that works on desktop and mobile.

## 🛠️ Tech Stack

* **Frontend Library:** React.js (Functional Components, Hooks: `useState`, `useEffect`)
* **Styling:** Tailwind CSS
* **Data Visualization:** Recharts
* **Architecture:** Single Page Application (SPA)

## 💡 How It Works

This project uses a centralized state management approach. When a task is added via the **Task Management** tab, the React state updates immediately. This change automatically triggers a re-render of the **Analytics Dashboard**, updating the graphs without requiring a page reload.

## 📦 How to Run

This project is engineered as a lightweight, single-file application for zero-dependency deployment.

1.  Clone the repository:
    ```bash
    git clone [https://github.com/YOUR_USERNAME/smart-alloc-dashboard.git](https://github.com/YOUR_USERNAME/smart-alloc-dashboard.git)
    ```
2.  Open `index.html` in any modern web browser (Chrome, Edge, Firefox).
3.  No `npm install` or backend server is required!

---
*Built by Yashasvi Raj Singh for the Deloitte NLA Engineering Track.*
