# SIEM-Visualization-Example-1-Failed-Logon-Attempts-All-Users-
SIEM Visualization Example 1: Failed Logon Attempts (All Users)

**Lab Summary: Security Monitoring & SIEM Fundamentals**

In this lab, we created a dashboard and visualizations using a SIEM (Security Information and Event Management) tool. The goal was to visualize data related to failed logon attempts for all users.

### Steps Involved:
1. **Creating the Dashboard:**
   - We accessed the SIEM interface and deleted the existing "SOC-Alerts" dashboard.
   - A new dashboard was created by clicking on "Create new dashboard."

2. **Creating the Visualization:**
   - A new visualization was initiated, setting the date range to "last 15 years."
   - We applied a filter to only include event IDs that correspond to failed logon attempts (event ID 4625).
   - We selected the "Table" visualization type and configured it to display user names, machine names, and the count of failed logon attempts.

3. **Refining the Visualization:**
   - We improved the clarity of column names and added the "Logon Type" field.
   - Specific usernames and computer accounts were excluded to ensure accurate monitoring.
   - The results were sorted for better readability.

4. **Final Adjustments:**
   - The visualization was given a title and saved to the dashboard.
   - Filters were applied to exclude certain logs, ensuring only relevant data was displayed.

### Key Learnings:
- **Dashboard Management:** Understanding how to create and manage dashboards in a SIEM tool.
- **Data Filtering and Visualization:** Learning to apply filters and choose appropriate visualization types for different data sets.
- **Customization:** Refining visualizations to meet specific requirements, such as excluding unnecessary data and ensuring the display of relevant information.

The lab concluded with a task to verify the number of logins for a specific account using the refined visualization, demonstrating the practical application of the concepts learned.

![Screenshot 2024-07-29 at 4 48 03 PM](https://github.com/user-attachments/assets/b5975f66-9699-4761-8879-dac3e560679f)




