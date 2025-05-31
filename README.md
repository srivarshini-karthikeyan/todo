# NexusTask - Advanced Task Management System

NexusTask is a modern and fully responsive web-based task management application developed using HTML5, CSS3, and vanilla JavaScript. It is designed to help individuals and professionals streamline their workflow by providing an intuitive interface, powerful task organization tools, and built-in productivity analytics — all running entirely in the browser with no dependencies or backend.

You can view the live application here:
https://srivarshini-karthikeyan.github.io/todo

You can view the sample of the application here:
https://github.com/user-attachments/assets/b9a89b44-afe6-439b-850d-b7a1c3d93ae8

Key Features
NexusTask offers a rich set of features designed to make task management efficient and user-friendly:

Comprehensive Task Management
Easily create, update, delete, and complete tasks through a streamlined interface designed for minimal friction and maximum productivity.

Task Categorization and Prioritization
Tasks can be assigned to categories such as Work, Personal, or Urgent, and tagged with priority levels (High, Medium, Low) to visually differentiate their importance.

Deadline and Overdue Tracking
Assign due dates to each task and receive visual indicators for overdue items to ensure deadlines are always top of mind.

Advanced Filtering and Search
Locate tasks instantly using real-time filtering and search tools based on task name, category, or status.

Performance Analytics
View daily and weekly progress statistics, track ongoing productivity streaks, and visualize task completion rates with intuitive charts and indicators.

Theme Switching (Light/Dark Mode)
The application includes a built-in toggle to switch between light and dark themes, enhancing usability in different lighting conditions.

Data Import and Export
Users can export their task list to a JSON file for backup or transfer purposes and re-import data at any time.

Local Data Persistence
All data is stored locally in the browser using the LocalStorage API, ensuring tasks remain saved across sessions without requiring a server.

Mobile-Responsive Design
The layout is fully responsive and optimized for desktops, tablets, and mobile devices, delivering a consistent experience across all screen sizes.

Technologies Used
NexusTask is developed using open web standards to ensure maximum compatibility and maintainability:

HTML5 for semantic structure and accessibility

CSS3 including Flexbox, Grid, and CSS variables for layout and theming

JavaScript (ES6+) with a modular, object-oriented architecture for interaction and data handling

Font Awesome for a consistent and professional icon set

Architectural Overview
The application is built following the Model-View-Controller (MVC) architectural pattern, separating logic, user interface, and data handling for better scalability and maintainability. It leverages an event-driven approach to handle user interactions and state changes efficiently. Styling is managed with CSS custom properties, which makes theming straightforward and centralized.

Getting Started
To use NexusTask locally:

Clone the Repository

bash
Copy
Edit
git clone https://github.com/srivarshini-karthikeyan/todo.git
cd todo
Launch the Application
You can open the index.html file directly in your browser, or run a local server using one of the following commands:

bash
Copy
Edit
python -m http.server 8000
# or
npx serve .
Access the Application

Directly via file: file:///path-to-project/index.html

Or in your browser: http://localhost:8000

Analytics and Reporting
NexusTask includes an integrated analytics panel that provides insights into your task completion trends. Users can monitor their daily and weekly progress, track the number of tasks completed, identify overdue tasks, and maintain productivity streaks. These metrics are presented in a clear and user-friendly format to support goal-oriented workflows.

Customization
The application is designed with flexibility in mind. Developers can easily modify the visual theme by adjusting CSS variables in the root stylesheet. New categories or priority types can also be added by editing the HTML markup and related JavaScript configuration.

Example of theme variables:

css
Copy
Edit
:root {
  --primary-color: #6c5ce7;
  --secondary-color: #74b9ff;
  --accent-color: #fd79a8;
  --success-color: #00b894;
  --warning-color: #fdcb6e;
  --danger-color: #e17055;
}
Deployment
The application is currently deployed using GitHub Pages and can be accessed at:
https://srivarshini-karthikeyan.github.io/todo

No build tools are required. For alternative deployment options, services like Netlify or Vercel can also be used by linking the GitHub repository and enabling automatic deployment.

License
This project is licensed under the MIT License. You are free to use, modify, and distribute it in accordance with the terms outlined in the LICENSE file.

Author
Developed and maintained by Srivarshini Karthikeyan
GitHub: @srivarshini-karthikeyan
