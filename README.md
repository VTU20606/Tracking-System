**Employee Time Tracker**  
A comprehensive role-based application designed to streamline task logging and time tracking for employees. The system enables employees to record their daily activities, along with associated details such as project, task category, duration, and description. It provides detailed insights through interactive charts for daily, weekly, and monthly task analysis, ensuring efficient time management.  

### Key Features:  
- **Task Management**: Employees can add, edit, and delete tasks with validations to prevent duplicate entries or durations exceeding 8 hours.  
- **Role-Based Access Control (RBAC)**: Differentiated access for Associates and Admins.  
- **Interactive Visualizations**:  
  - Pie charts for daily task summaries.  
  - Bar charts for weekly and monthly task distributions.  
- **Admin Dashboard**: Enables Admins to view tasks and performance metrics for specific projects or employees over customizable timeframes.  
- **Reports**: Consolidated data views for time tracking across tasks, projects, and roles.  

### Technical Highlights:  
- **Data Validation**: Ensures accuracy by restricting duplicate task entries and excessive durations.  
- **Charts and Insights**: Uses Chart.js for dynamic visualizations tailored to user roles.  
- **Authentication**: Secure login for both employees and admins, ensuring only authorized access to features.  
- **Data Aggregation**: Displays total hours worked daily, weekly, and monthly.  

**Technologies Used**: Java (Spring Boot), MySQL, Thymeleaf, Chart.js, and Eclipse IDE.
