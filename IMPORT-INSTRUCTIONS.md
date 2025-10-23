# Import Instructions

## Prerequisites
- ToolJet account (free tier works)
- Web browser

## Step 1: Import Application
1. Login to ToolJet at https://app.tooljet.ai
2. Go to Applications dashboard
3. Click "Create an app" dropdown
4. Select "Import"
5. Choose `employee-directory-app.json`
6. Click "Import application"
7. Wait for import to complete

## Step 2: Setup Database
1. Click ToolJet logo → **Database**
2. Click "Create new table"
3. Name it: `employees`
4. Add these columns:

| Column Name     | Data Type  | Constraints       |
|-----------------|------------|-------------------|
| id              | serial     | Primary Key       |
| name            | varchar    | -                 |
| email           | varchar    | -                 |
| phone           | varchar    | -                 |
| department      | varchar    | -                 |
| role            | varchar    | -                 |
| age             | integer    | -                 |
| date_of_joining | timestamp  | -                 |

## Step 3: Import Data
1. Select the employees table
2. Click "Add new data" for each employee:

**Employee 1:**
- name: John Doe
- email: john.doe@company.com
- phone: +1-555-0000
- department: Engineering
- role: Software Engineer
- age: 30
- date_of_joining: 2025-10-31 12:00:00

**Employee 2:**
- name: Jane Smith
- email: jane.smith@company.com
- phone: +1-555-0000
- department: Marketing
- role: Marketing Manager
- age: 30
- date_of_joining: 2025-10-14 12:00:00

**Employee 3:**
- name: Bob Johnson
- email: bob.johnson@company.com
- phone: +1-555-0000
- department: Engineering
- role: Senior Developer
- age: 30
- date_of_joining: 2025-03-05 12:00:00

**Employee 4:**
- name: Sarah Wilson
- email: sarah.wilson@company.com
- phone: +1-555-0000
- department: HR
- role: HR Manager
- age: 35
- date_of_joining: 2025-07-21 12:00:00

## Step 4: Verify Connection
1. Open the imported app
2. Go to Queries panel
3. Find "tooljetdb1" query
4. Click "Run" to test connection
5. Verify data appears in table

## Step 5: Test Application
1. Click "Preview" button
2. Verify table displays all 4 employees
3. Test search functionality
4. Check statistics card shows "4" employees
5. Verify pie chart shows distribution
6. Click action buttons to test functionality

## Troubleshooting
- **No data showing**: Re-run the tooljetdb1 query
- **Chart not displaying**: Check if query data is loaded
- **Buttons not working**: Verify event handlers are imported correctly
