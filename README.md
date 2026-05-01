# Lab-5-SIS.github.io
This project is a simple Student Information System, or SIS, that uses an SQLite
database and a web portal. The system allows clear management of students, faculty,
courses, enrollments, and grades. In the project, students can enroll in or drop courses,
faculty can submit grades, and the system can generate reports such as seats
remaining in a course and a student’s transcript with courses and grades. The database
has four main tables: students, faculty, courses, and enrollments. The students table
stores student information like ID, name, email, and major. The faculty table stores
faculty information, including ID, name, email, and department. The courses table keeps
track of course details, credits, capacity, and which faculty member is teaching the
course. The enrollments table connects students and courses, keeping track of which
student is enrolled in which course for which term, and it also stores grades. This table
prevents duplicate enrollments so a student cannot enroll in the same course in the
same term more than once. The web portal allows users to add students, faculty, and
courses, let students enroll or drop courses, allow faculty to submit grades, and view
reports. To run the project, you first create the database using the SQL script, then use
the web portal to perform the operations. This setup makes managing students,
courses, and grades easier and keeps all the data organized in one system.
