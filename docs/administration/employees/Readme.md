# Employees

The **Employees** section manages users (employees or administrators) who have access to the back office,ensuring proper access control, and enhancing security by configuring account settings and password policies.

 ![employees](./Employee.png)

It helps maintain an organized, role-based workflow in the admin panel.It allows administrators to add, edit, and configure employee accounts, control their roles, and set preferences for their usage of the system.


 ![employees](./Employees.png)

### **Add New Employee**
Administrators can add new employee accounts by providing the following details:
1. **ID:** A unique identifier for each employee (auto-generated by the system).
2. **First Name:** The employee's first name.
3. **Last Name:** The employee's last name.
4. **Email Address:** The employee's email address, used for login and communication.
5. **Profile:** The role or permission level assigned to the employee (e.g., SuperAdmin, Manager).
6. **Active:** Indicates whether the employee's account is active.
     - **Enable**: Employee can log in and use the admin panel.
     - **Disable**: Employee account is disabled.


## Employee Options
1. **Password Regeneration (in minutes):**
     - Sets the minimum time (in minutes) between two password regeneration requests for employees.
     - Example: If set to `360 minutes`, employees must wait 6 hours before requesting another password reset.

2. **Memorize the language used in Admin Panel forms (Yes/No):**
     - It allow employees to select a specific langauge for the admin panel form.
     - **Yes**: Saves the selected language for future use.
     - **No**: Resets the language setting to default upon each session.