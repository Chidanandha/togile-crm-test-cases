# Togile CRM Test Cases

## User Authentication

### Verify User Login
- **Preconditions:** User must have valid credentials.
- **Steps:**
  1. Open the Togile CRM login page.
  2. Enter valid username and password.
  3. Click 'Login'.
- **Expected Result:** User is logged in and redirected to the dashboard.

### Verify Invalid Login
- **Preconditions:** User enters invalid credentials.
- **Steps:**
  1. Open the Togile CRM login page.
  2. Enter invalid username and password.
  3. Click 'Login'.
- **Expected Result:** Error message is displayed.

## Lead Management

### Create New Lead
- **Preconditions:** User is logged in.
- **Steps:**
  1. Navigate to 'Leads'.
  2. Click 'New Lead'.
  3. Enter lead details.
  4. Click 'Save'.
- **Expected Result:** New lead is created and displayed in the lead list.

### Edit Existing Lead
- **Preconditions:** Lead exists in the system.
- **Steps:**
  1. Select a lead from the lead list.
  2. Click 'Edit'.
  3. Modify lead details.
  4. Click 'Save'.
- **Expected Result:** Lead details are updated.

### Delete Lead
- **Preconditions:** Lead exists in the system.
- **Steps:**
  1. Select a lead from the lead list.
  2. Click 'Delete'.
  3. Confirm deletion.
- **Expected Result:** Lead is removed from the list.

## Contact Management

### Create New Contact
- **Preconditions:** User is logged in.
- **Steps:**
  1. Navigate to 'Contacts'.
  2. Click 'New Contact'.
  3. Enter contact details.
  4. Click 'Save'.
- **Expected Result:** New contact is created and displayed in the contact list.

### Edit Existing Contact
- **Preconditions:** Contact exists in the system.
- **Steps:**
  1. Select a contact from the contact list.
  2. Click 'Edit'.
  3. Modify contact details.
  4. Click 'Save'.
- **Expected Result:** Contact details are updated.

### Delete Contact
- **Preconditions:** Contact exists in the system.
- **Steps:**
  1. Select a contact from the contact list.
  2. Click 'Delete'.
  3. Confirm deletion.
- **Expected Result:** Contact is removed from the list.

## Deal Management

### Create New Deal
- **Preconditions:** User is logged in.
- **Steps:**
  1. Navigate to 'Deals'.
  2. Click 'New Deal'.
  3. Enter deal details.
  4. Click 'Save'.
- **Expected Result:** New deal is created and displayed in the deal list.

### Edit Existing Deal
- **Preconditions:** Deal exists in the system.
- **Steps:**
  1. Select a deal from the deal list.
  2. Click 'Edit'.
  3. Modify deal details.
  4. Click 'Save'.
- **Expected Result:** Deal details are updated.

### Delete Deal
- **Preconditions:** Deal exists in the system.
- **Steps:**
  1. Select a deal from the deal list.
  2. Click 'Delete'.
  3. Confirm deletion.
- **Expected Result:** Deal is removed from the list.

## Task Management

### Create New Task
- **Preconditions:** User is logged in.
- **Steps:**
  1. Navigate to 'Tasks'.
  2. Click 'New Task'.
  3. Enter task details.
  4. Click 'Save'.
- **Expected Result:** New task is created and displayed in the task list.

### Edit Existing Task
- **Preconditions:** Task exists in the system.
- **Steps:**
  1. Select a task from the task list.
  2. Click 'Edit'.
  3. Modify task details.
  4. Click 'Save'.
- **Expected Result:** Task details are updated.

### Delete Task
- **Preconditions:** Task exists in the system.
- **Steps:**
  1. Select a task from the task list.
  2. Click 'Delete'.
  3. Confirm deletion.
- **Expected Result:** Task is removed from the list.

## Reporting and Analytics

### Generate Goals(Sales) Report
- **Preconditions:** User is logged in and data is available.
- **Steps:**
  1. Navigate to 'Reports'.
  2. Select 'Sales Report'.
  3. Set report parameters.
  4. Click 'Generate'.
- **Expected Result:** Sales report is generated and displayed.

### Generate Lead Conversion Report
- **Preconditions:** User is logged in and data is available.
- **Steps:**
  1. Navigate to 'Reports'.
  2. Select 'Lead Conversion Report'.
  3. Set report parameters.
  4. Click 'Generate'.
- **Expected Result:** Lead conversion report is generated and displayed.

## Integration

### Verify Import Integration
- **Preconditions:** User is logged in and has Import integration setup.
- **Steps:**
  1. Import data from Data Management.
  2. Verify data in CRM.
- **Expected Result:** Data is imported correctly and displayed in CRM.

### Verify Email Integration
- **Preconditions:** User is logged in and has email integration setup.
- **Steps:**
  1. Send an email from the CRM.
  2. Verify email in recipient's inbox.
- **Expected Result:** Email is sent and received correctly.

## User Role and Permissions

### Verify Admin Access
- **Preconditions:** User is logged in as Admin.
- **Steps:**
  1. Access admin-specific features.
- **Expected Result:** Admin has access to all features.

### Verify User Access
- **Preconditions:** User is logged in with standard user role.
- **Steps:**
  1. Attempt to access restricted features.
- **Expected Result:** User is restricted from accessing admin features.
