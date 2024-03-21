# Chromaway-Assignment

Assignment:

Write a simple Rell program with the purpose of storing information about students and courses. These are the requirements:

- There should be necessary entities and operations for the system to function properly. There should also be admin operations to administrate the platform, only callable by the admin.
- The operation to enroll in a course can normally only be called by the specific student getting enrolled. The operation should place students in a waitlist if the course capacity for the total number of students has been reached.
- If a student drops the course, the spot should be taken by another student from the waitlist.
- There should also be queries to get the following information:
      - How many students are enrolled in a specific course
      - Which courses a specific student is enrolled in

Advanced:
- When enrolling from the waitlist, pick one of the students at random instead
