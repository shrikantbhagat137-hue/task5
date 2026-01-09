DeleteStudent Program
This project is a small Java application that connects to an Oracle XE database and allows you to delete a student record by entering the student’s ID.

Requirements
Oracle XE installed and running

Oracle JDBC driver (ojdbc8.jar) added to your project

IntelliJ IDEA (or any Java IDE)

Java JDK 8 or higher

Setup Steps
Install Oracle XE and make sure the database service is running.

Create the students table in your database with columns like id, name, age, and marks.

Insert sample data into the table so you have records to test with.

Add the JDBC driver (ojdbc8.jar) to your IntelliJ project.

Update database credentials in the program (username, password, and connection string).

How It Works
When you run the program, it asks you to enter a student ID.

It connects to the Oracle database.

It deletes the student record with the matching ID.

If the record exists, you’ll see a success message.

If no record is found, it shows a message saying so.

Example Run
Input: 2

Output: Student record deleted successfully.

If you enter an ID that doesn’t exist, it will say: No student found with that ID.

Notes
Make sure the database is running before you execute the program.

Always close connections after use.

It’s better to create your own Oracle user/schema instead of using the default system account.