# Student Enrollment Form using JsonPowerDB

## Description
This project is a web-based **Student Enrollment Form** developed as a Micro Project. It is designed to store and manage student records in a database. The form allows users to perform **CRUD operations** (Create, Read, Update) on student data, which is stored in **JsonPowerDB**, a high-performance, real-time, NoSQL database.

The form includes the following input fields:
- Roll No (Primary Key)
- Full Name
- Class
- Birth Date
- Address
- Enrollment Date

## Benefits of using JsonPowerDB
JsonPowerDB (JPDB) is a Real-time, High Performance, Lightweight and Simple to Use, Rest API based Multi-mode DBMS. It has several advantages over traditional databases:
1. **Serverless Support:** It is purely serverless, meaning developers don't need to manage the backend infrastructure.
2. **High Performance:** It is built on top of PowerIndex, which makes data retrieval incredibly fast.
3. **Simple to Use:** It uses simple JSON for data exchange and standard HTTP requests (GET, PUT, POST), making it easy to integrate with any frontend technology like HTML/JS.
4. **Real-time:** Data updates and retrieval happen in real-time.
5. **NoSQL:** It is schema-free, allowing for flexible data structures.

## Release History
### v1.0.0 (2025-01-15)
- Initial release of the Student Enrollment Form.
- Implemented "Save" feature to add new student records.
- Implemented "Update" feature to modify existing records.
- Implemented "Reset" feature to clear the form.
- Integrated JsonPowerDB for backend storage.

## Scope of Functionalities
- **Data Validation:** Ensures all required fields are filled before submission.
- **Duplicate Check:** Automatically checks if a Roll No already exists in the database.
- **Dynamic UI:** Enables/disables buttons (Save/Update) based on data availability.
- **Data Persistence:** Stores data permanently in the `SCHOOL-DB` / `STUDENT-TABLE`.

## Examples of Use
1. **New Student Registration:**
   - Enter a new Roll No (e.g., `101`).
   - The "Save" button enables.
   - Fill in details and click "Save" to store the record.
2. **Updating Student Details:**
   - Enter an existing Roll No (e.g., `101`).
   - The form automatically retrieves and displays the student's data.
   - Edit the details (e.g., Address) and click "Update".

## Project Status
- **Current Status:** Completed
- **Future Enhancements:** Add "Delete" functionality and a "Show All Records" dashboard.

## Sources
- [JsonPowerDB Documentation](https://login2explore.com/jpdb/docs.html)
- [Bootstrap Framework](https://getbootstrap.com/)
