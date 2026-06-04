# Ballet Net - Dance School Management System

**Ballet Net** is a responsive frontend prototype designed to streamline the daily operations and communication of a modern dance academy. It provides tailored digital dashboards for different roles within the school, focusing on scheduling, academic progress tracking, and social media content management.

**Live Demo:** [View Ballet Net on GitHub Pages](https://johnkol19.github.io/Ballet_Net/index.html)

---

## Key Features & Use Cases

The prototype visualizes the User Interface (UI) and User Experience (UX) for four main operational modules:

1. **Manage Schedule (Secretary):** An intuitive dashboard with tabbed navigation for different dance rooms. Allows the administration to view, organize, and edit class schedules.
2. **Update Syllabus (Teachers):** A dedicated interface for instructors to track the progress of the RAD/ISTD syllabus using interactive sliders, and to maintain a daily class log.
3. **Approve Content (Director):** A grid-based evaluation dashboard for reviewing, approving, or rejecting social media materials (images/videos) submitted by the Social Media Manager. Includes a statistics modal.
4. **View Schedule & Syllabus (Students):** A personalized digital folder where students can seamlessly view their weekly timetable and track their academic progression.

---

## Technologies Used

* **HTML5:** Semantic structuring of the application.
* **CSS3:** Custom styling and visually appealing color schemes (Ballet-themed).
* **Bootstrap 5:** Extensive use of the grid system, Flexbox, responsive utility classes, and Modals for a 100% mobile-friendly experience.

---

## Note on Architecture (Role-Based Access Control)

Since this project is currently a **static frontend prototype**, navigation between the different dashboards is deliberately left "flat" and accessible via the main navigation bar. This design choice was made to allow easy demonstration and evaluation of all UI components without requiring multiple authenticated accounts.

In a fully functional production environment (with a backend infrastructure), strict **Role-Based Access Control (RBAC)** would be enforced. For instance, the *Approve Content* page would be strictly restricted to the Director, while the *Update Syllabus* page would only be accessible to authorized Teachers.

---

## How to Run Locally

You don't need any local server to run this frontend prototype. 
1. Clone the repository: git clone [https://github.com/Johnkol19/Ballet_Net.git](https://github.com/Johnkol19/Ballet_Net.git)
2. Navigate to the project folder.
3. Open index.html in your preferred web browser.
