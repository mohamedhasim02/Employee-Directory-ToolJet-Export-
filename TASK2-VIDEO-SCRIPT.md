# Task 2 Video Presentation Script



### SECTION 1: Introduction

"Hello! I'm presenting my Employee Directory Application built using ToolJet. This application manages employee data with an intuitive interface and provides statistical insights about the workforce."

### SECTION 2: Application Demo 

#### Part A: Overview
"Let me show you the main interface. On the left, we have an interactive table displaying all employee records. On the right, we have our statistics dashboard."



#### Part B: Table Features
"The table shows 4 employees with their complete information - ID, name, email, phone, department, role, age, and date of joining. You can search for specific employees using the search bar."



"Let me scroll right to show the date of joining column and the action buttons."



#### Part C: Statistics
"The statistics dashboard shows the total employee count - currently 4 employees. Below that, we have a pie chart showing employee distribution by department: 50% in Engineering, 25% in Marketing, and 25% in HR."

#### Part D: Action Buttons
"Each employee row has an action button. When clicked, it displays an alert with the employee's information."



"As you can see, it shows 'Employee: John Doe - john.doe@company.com'."

### SECTION 3: Challenges & Solutions 

"During development, I faced several challenges:

**Challenge 1: Date of Joining Column**
The date_of_joining column existed in my database but wasn't visible in the application. I resolved this by accessing the table component properties and manually adding the column to the visible columns list. This taught me about the separation between database schema and UI configuration in ToolJet.

**Challenge 2: Non-functional Action Buttons**
Initially, the action buttons in the ACTIONS column did nothing when clicked. I discovered they had no event handlers configured. I fixed this by adding an 'On Click' event handler with a 'Show Alert' action. This showed me the importance of properly connecting UI components to actions.

**Challenge 3: Understanding Component Configuration**
Navigating ToolJet's interface to find where to configure table columns and button actions was initially challenging. I learned to use the Inspector panel and Component properties sidebar effectively, which greatly improved my workflow."

### SECTION 4: Future Improvements

"For future enhancements, I would implement:

1. **Complete CRUD Operations**: Add forms to create, edit, and delete employees directly from the interface with proper data validation.

2. **Enhanced Action Buttons**: Instead of a simple alert, I'd create a detailed employee profile modal showing all information in a well-designed format.

3. **Advanced Filtering**: Add dropdown filters for department and role, plus date range filtering for joining dates.

4. **More Analytics**: Include average age by department, employee tenure calculations, and hiring trends over time displayed in additional charts.

5. **Data Validation**: Implement comprehensive validation for email formats, phone numbers, and ensure no required fields are left empty."

### SECTION 5: Conclusion 

"This project helped me understand low-code development with ToolJet, database connections, UI/UX design, and problem-solving when components don't work as expected. The application successfully manages employee data and provides valuable insights through visual statistics. Thank you for watching!"

