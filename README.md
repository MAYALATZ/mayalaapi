Requirements for Building and Deploying a Simple API
To build and deploy a simple API with the specified endpoints, you will need to follow several steps. Below is a detailed breakdown of the requirements and tasks involved.
Choose Your Technology Stack
Programming Language: Select a programming language for your API development. Common choices include:

Python (with Flask or FastAPI)
Relational Database Management System (RDBMS): Choose an RDBMS to store your data. Popular options include:

MySQL
Set Up Your Development Environment
Install Required Software:

Install the chosen programming language runtime.
Install the necessary libraries or frameworks for building APIs.
Install the selected RDBMS and set up a database instance.
Create a Project Directory: Organize your project files in a dedicated directory.
Design Your Database Schema
Students Table:

Create a table named students with at least the following columns:
id: Primary key (integer).
name: Student’s name (string).
program: Enrolled program (string).
Subjects Table:

Create a table named subjects with at least the following columns:
id: Primary key (integer).
name: Subject name (string).
year: Academic year associated with the subject (integer).
Step 4: Populate Your Database
Insert Sample Data:
Add at least 10 student records into the students table.
Insert subjects related to the Software Engineering program spanning from Year 1 to Year 4 into the subjects table.
Step 5: Develop Your API Endpoints
Endpoint 1: /students

Implement a GET request handler for /students.
Query the database to retrieve all student records.
Format the response as JSON, including each student’s name and enrolled program.
Endpoint 2: /subjects
Add at least 10 student records into the students table.
Insert subjects related to the Software Engineering program spanning from Year 1 to Year 4 into the subjects table.
Step 5: Develop Your API Endpoints
Endpoint 1: /students

Implement a GET request handler for /students.
Query the database to retrieve all student records.
Format the response as JSON, including each student’s name and enrolled program.
Endpoint 2: /subjects
Conclusion
By following these steps, you will be able to successfully create and deploy an API that meets the specified requirements of returning student information and subjects related to Software Engineering programs.


  The three different backup are 
  i.Incremental Backup,
 ii. Differential backup, 
  iii.and Full backup.
 i. A full backup is the most complete type of backup where you clone all the selected data. This includes files, folders, SaaS applications, hard drives and more. The highlight of a full backup is the minimal time it requires to restore data.The highlight of a full backup is the minimal time it requires to restore data.
 
 Advantages.
Simplified Restoration, Since all data is consolidated in a single backup, restoring data is straightforward and typically the fastest method.
Comprehensive Coverage, A full backup includes everything, ensuring no data is missed.
Good for Initial Setup Useful for first-time backups and for setting a baseline for future backups.

Disadvantages.

Time-Consuming. Full backups can take a long time to complete, especially for large datasets.
Storage Requirements. They require significant storage space, as all data is duplicated each time a full backup is performed.
Administrative Overhead. Performing full backups can be resource-intensive, requiring regular scheduling and monitoring.

 ii.A differential backup straddles the line between a full and an incremental backup. This type of backup involves backing up data that was created or changed since the last full backup. To put it simply, a full backup is done initially, and then subsequent backups are run to include all the changes made to the files and folders.
 
 Advantages.

Easier Restoration Process, To restore data, only the last full backup and the most recent differential backup are needed, making it less complex than an incremental backup restoration.
Balanced Approach, Offers a middle ground between full and incremental backups in terms of storage and restoration complexity.
Less Storage than Full Backup, Requires less storage space than full backups since it only captures changes since the last full backup.

Disadvantages:

Increasing Backup Times, Over time, as more data changes accumulate, differential backups can take longer to complete than incremental backups.
Larger Storage Needs, While smaller than full backups, differential backups can consume more space than incremental backups because they continuously accumulate changes.
Possible Performance Impact, If large amounts of data change frequently, differential backups can become substantial and may slow down performance on the backup server.

 iii.Incremental Backup
The first backup in an incremental backup is a full backup. The succeeding backups will only store changes that were made to the previous backup. Businesses have more flexibility in spinning these types of backups as often as they want, with only the most recent changes stored.Incremental backup requires space to store only the changes (increments), which allows for lightning-fast backups.

  Advantages:
Efficiency, Incremental backups save time and storage space, as only changed or new data is backed up.
Faster Backup Times, Since less data is being copied, backups can be completed more quickly, allowing for more frequent backups.
Reduced Storage Costs, Less storage space is needed compared to full backups since only changes are captured.

Disadvantages:
Complex Restoration Process, Restoring data can be slower and more complicated, as it requires the last full backup plus all incremental backups made since then.
Risk of Loss, If one incremental backup file becomes corrupted or is lost, all subsequent backups may also be affected, complicating data recovery.
Dependency Chain, The longer the chain of incremental backups, the more dependent the process becomes, which may increase the risk of failure.

read reference are,
https://www.spanning.com/blog/types-of-backup-understanding-full-differential-incremental-backup/
https://www.techtarget.com/searchdatabackup/feature/Full-incremental-or-differential-How-to-choose-the-correct-backup-type
https://www.unitrends.com/blog/types-of-backup-full-incremental-differential/
  
