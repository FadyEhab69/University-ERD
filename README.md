# University-ERD
This Entity-Relationship Diagram (ERD) represents a university database system with the following entities and their relationships :

STUDENT: Contains attributes like Student_ID (primary key), Name, Phone Number, Gender, Age, Date of Birth, House Number, Street Number, Town, and City. A student belongs to a DEPARTMENT and studies a COURSE.
DEPARTMENT: Includes attributes such as Department_ID (primary key), Name, and is linked to both STUDENTS and FACULTY through their respective IDs.
COURSE: Has attributes like Course_ID (primary key), Name, Code, Department_ID, and is associated with STUDENTS and FACULTY. A student studies a course, and faculty teach courses.
FACULTY: Contains attributes including Faculty_ID (primary key), Name, Gender, Salary, Date of Birth, Age, Designation, Course_ID, and Grade. Faculty members teach courses and work on RESEARCH PROJECTS.
RESEARCH PROJECT: Includes attributes such as Project_ID (primary key), Name, NewAttribute, Area, Duration, and Faculty_ID. Faculty members work on research projects.
# Relationships:

A STUDENT belongs to one DEPARTMENT.
A STUDENT studies one or more COURSES.
A COURSE is taught by one or more FACULTY members.
A FACULTY member teaches one or more COURSES.
A FACULTY member works on one or more RESEARCH PROJECTS.
A RESEARCH PROJECT involves one or more FACULTY members.
The diagram uses diamonds to represent relationships (e.g., "belongs to," "studies," "teaches," "works") and ovals for attributes, with primary keys underlined.


