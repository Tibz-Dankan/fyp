# The  marks management system for a  secondary school in Uganda.
## This system will handle all marks operations from entry to generating a final  term report card for any given student.
## Tools and technologies to be used (Languages , frameworks, libraries, run-times)
 The frontend is going to be written in **react**, **redux** and **sass** *meanwhile*  the backend will be  in **nodejs** and **express** . **Postgres** is the database to be used.

## Entities (Schemas)
1.  Users (Teachers of all major roles such as class teacher, DOS, HM etc...)
1. Students
1. Marks
1. Subjects
1. Academic terms
1. Announcements
1. Activities (derived)
1. Notifications (derived)

## Functionalities (Features)
- Authentication (signup and login). 2 factor authentication will be added if time allows.
- Marks operations . These are marks entry, view and edit.
- Grading students performance basing on the marks.
- Generating students report card
- posting and viewing announcements 
- Tracking all activities taking place in the system.

## User title and responsibilities
| Title | Responsibilities |
| :---: | :--- |
| Teacher | 1. Add marks, View marks, Edit marks, check my activities |
| Class-teacher | view graded performance for the whole class |
| head of department | view graded performance in each class |
| Dean of studies (DOS) | check all activities in the system, add a student into the system, view each class performance, view each subject performance |
| Dean of student affairs (DOSA) | view each student performance |
| head master  | Initialize staff registration into the system, add student into system, view all activities in the system, allocate and deallocate additional roles for teachers, block any teachers account including DOS and DOSA, lock any students account |


## Tables (Relations)
- users
- students
- marks
- subjects
- terms
- announcements
- notifications

>  **Note that this documentation is not final.**

 



