# Daily Nexus Grades Search Data Files

The published data in this repository includes the total number of UC Santa Barbara students receiving each grade — before pass/fail and satisfactory/unsatisfactory conversions — for courses offered from Fall 2009 until Fall 2025 that had five or more students enrolled. Instructors of optionally-graded courses do not know what grading option students have selected, according to the Office of the Registrar. The data is visualized on the [Daily Nexus Grades Search Website](https://dailynexus.com/interactives/grades/), and the website and the repository will be regularly updated as new data arrives. All data is free to reuse.

- ``courseGrades.csv`` The Daily Nexus obtained this data from the Office of the Registrar via multiple Public Records Act requests. The file is made up of all the original data acquired from the Registrar's office combined, and it contains UCSB course grade data from Fall 2009 to Summer 2025 in wide-form with statistics calculated by the Nexus. Data includes quarter, course level, course number, instructor, average GPA for a course, and the total number of students who chose each grading option. Columns with "p" after a letter refer to plus grades, and columns with "m" after a letter refer to minus grades. "S" represents satisfactory grades, and "su" represents unsatisfactory grades.
- ``ges_long_form.csv`` The Daily Nexus obtained this data from the College of Letters and Science's degree requirements website. The file is made up of all the 2023-24 courses that apply to each General Education and special subject requirement, and the data in this file is in long-form. 
- ``ges.csv`` This file contains the data from ``ges_long_form.csv`` formatted in wide-form by the Nexus. "AHI" represents the American History and Institutions requirement.

**About the Data**

1 row = 1 course instance

  **Columns:**
  - `course`: Course Code (e.g., MATH 3A)
  - `instructor`: Instructor last name, first initial, and middle initial if applicable (e.g., DEAN C W)
  - `quarter`: Academic Quarter (Fall, Winter, Summer, Spring)
  - `year`: Academic Year (e.g., 2020).\n",
  - `A`: Number of A grades (NOT including + and -)
  - `B`: Number of B grades (NOT including + and -)
  - `C`: Number of C grades (NOT including + and -)
  - `D`: Number of D grades (NOT including + and -)
  - `F`: Number of F grades (NOT including + and -)
  - `nLetterStudents`: Number of students in all classes that either require letter grading or have optional grading (letter grading or pass/no pass grading). If a class has optional grading, this number still includes all students.
  - `nPNP students`: Number of students in undergraduate classes that require pass/no pass grading
  - `avgGPA`: Average Grade Point Average for the course instance
  - `P`: Number of Pass grades in undergraduate classes that require pass/no pass grading
  - `dept`: Department code (e.g., PSTAT)
  - `s`: Number of Satisfactory grades in graduate classes with satisfactory/unsatisfactory grading
  - `su`: Number of Unsatisfactory grades in graduate classes with satisfactory/unsatisfactory grading
  - `Ap`: Number of A+ grades
  - `Bp`: Number of B+ grades
  - `Cp`: Number of C+ grades
  - `Dp`: Number of D+ grades
  - `Am`: Number of A- grades
  - `Bm`: Number of B- grades
  - `Cm`: Number of C- grades
  - `Dm`: Number of D- grades
  - `IP`: Number of In Progress grades


Please direct any questions or suggestions to [data@dailynexus.com](mailto:data@dailynexus.com).
