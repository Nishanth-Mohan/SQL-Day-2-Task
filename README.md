<h1 align="center">Hi 👋, I'm Nishanth M</h1>
<h3 align="center">A passionate frontend developer from India</h3>

-  Task name: **DB Model design for GUVI Zen Class**
-  Language used: **MySQL**
-  Discription: **I have displayed the database schema which is designed to manage courses, batches, mentors and students for GUVI. It allows for the organization and tracking of various courses, their associated batches, mentors assigned to those batches and students enrolled in specific courses.**

   **Tables:**
   
     **1)courses:**
       Stores information about different courses offered.<br>
         *Columns:* <br>
             => Course_id: Unique identifier for each course.<br>
             => Course_Name: Name of the course.<br>
             => Course_fee: Fee associated with the course.<br>
             => Duration: Duration of the course in weeks or months.

     **2)batch:**
       Represents batches of courses with specific start and end dates.<br>
        *Columns:*<br>
             => Batch_id: Unique identifier for each batch.<br>
             => Course_id: Foreign key referencing the Course_id in the courses table.<br>
             => Start_Date: Start date of the batch.<br>
             => End_Date: End date of the batch.
   
     **3)mentor:**
        Contains information about mentors assigned to batches.<br>
         *Columns:*<br>
             => Mentor_id: Unique identifier for each mentor.<br>
             => Mentor_Name: Name of the mentor.<br>
             => Mentor_email: Email address of the mentor.<br>
             => Mentor_phone: Phone number of the mentor.<br>
             => Course_id: Foreign key referencing the Course_id in the courses table.<br>
             => Batch_id: Foreign key referencing the Batch_id in the batch table.
   
     **4)students:**
        Stores details of students enrolled in courses.<br>
         *Columns:*<br>
             => Student_id: Unique identifier for each student.<br>
             => Student_Name: Name of the student.<br>
             => Student_email: Email address of the student.<br>
             => Student_phone: Phone number of the student.<br>
             => Course_id: Foreign key referencing the Course_id in the courses table.<br>
             => Batch_id: Foreign key referencing the Batch_id in the batch table.<br>
             => Mentor_id: Foreign key referencing the Mentor_id in the mentor table.
   
    **Usage:** <br>
       - Use SQL queries to interact with the database.<br>
       - Insert, update, delete, and select data as required.<br>
       - Ensure referential integrity by respecting foreign key constraints.<br>
       - Regularly back up the database to prevent data loss.<br>

-  How to reach me: **6369303696**

<h3 align="left">📫 Connect with me: nishanthmohan2k15@gmailcom</h3>
<p align="left">
</p>
