# Project Title: Project Management Form

## Description
This project is a web-based data entry form that includes validation for the primary key field, which checks if the value exists in the database. Based on whether the primary key is found in the database or not, the form behaves differently:
- If the primary key does **not** exist, the user can enter data in the form, and the **Save** button is enabled.
- If the primary key exists, the form displays the existing data, and the user can **Update** it.
The form also includes buttons for **Save**, **Update**, and **Reset** functionality, with data validation to ensure no empty fields are submitted.

## Benefits of Using JsonPowerDB
- **Simple JSON querying**: JsonPowerDB provides fast, real-time querying using JSON. It supports multiple databases and helps in building robust data-driven applications with minimal effort.
- **REST API support**: JsonPowerDB provides a REST API, enabling seamless integration with web applications.
- **Scalability**: Easily scalable for larger projects with no additional setup, making it ideal for both small and large applications.
- **High performance**: Optimized for speed and provides instant response times for database queries.

## Release History
- **v1.0** - Initial release with form validation and primary key functionality.
  - Features: Primary key validation, Save/Update functionality, Reset functionality.
  - Code available on [GitHub](https://github.com/yourusername/projectname).

## Table of Contents
- [Description](#description)
- [Benefits of Using JsonPowerDB](#benefits-of-using-jsonpowerdb)
- [Release History](#release-history)
- [Scope of Functionalities](#scope-of-functionalities)
- [Examples of Use](#examples-of-use)
- [Project Status](#project-status)
- [Sources](#sources)
- [Other Information](#other-information)

## Illustrations
**Figure 1**: Form layout with primary key field and input fields.

**Figure 2**: Validation behavior when primary key exists or not.

## Scope of Functionalities
- **Primary Key Check**: Check if the value in the primary key field exists in the database.
- **Data Validation**: Ensure no empty fields are submitted.
- **Save**: When the primary key doesn’t exist, save the new data to the database.
- **Update**: When the primary key exists, update the data in the database.
- **Reset**: Reset the form to its initial state, clearing all entered data.
- **UI Behavior**: Cursor placement and button enable/disable behavior based on primary key existence.

## Examples of Use
1. **Scenario 1**: When the user enters a primary key that doesn’t exist:
   - The form is unlocked for data entry, and the **Save** button is enabled.
   - After entering valid data, the user clicks **Save**, and the data is saved to the database.

2. **Scenario 2**: When the user enters a primary key that already exists:
   - The form is pre-filled with the existing data, and the **Update** button is enabled.
   - The user can modify the data and click **Update** to save the changes.

## Project Status
- **In Progress**: The project is currently being developed and tested.
- **Next Steps**: Implement additional features like error handling and form input enhancements.

## Sources
- JsonPowerDB Documentation: [Link to Documentation](https://www.jsonpowerdb.com)
- GitHub Repository: [GitHub Link](https://github.com/yourusername/projectname)

## Other Information
- The project uses basic HTML, CSS, and JavaScript for front-end functionality.
- Backend integration is done with JsonPowerDB for database management.
