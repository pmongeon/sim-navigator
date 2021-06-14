# SIM_Navigator
A repository that lays out the data and information about the SIM Navigator project. The project aims to make it easier for faculty and students to navigate through courses in the School of Information Management at Dalhousie University. Eventually we hope that this framework can be applied to other programs and their courses. 

### Application

- data from all syllabi in the SIM program
- complimentary Zotero library for course readings
- application created using R Shiny
- see Issues for current work in progress and Projects for cards identifying what needs to be done.

##Specifications for application

### Input

- syllabi data (course information, readings, assignments, etc.)
- Zotero library links for course readings

### Process

The tool performs the following tasks:

- Checks the required readings, prerequisites, and assignments for each course.
- Checks cross-listingg, and lists which program each course comes from. 
- Checks what courses are required for the completion of specialized certificates available in the program.
- Lists the courses available from different programs that all come under the Information Management umbrella.
- Allows users to store information relevant to their own academic journey in the application.


### *Timeline

- *Input all course syllabi data into shared Excel document. (May-June)

- *Create ERD, and import data into MySQL Workbench. (June)

- *Clean data, fill information gaps, and create documentation for application. (June)

- *Create github, begin amalgamating readings into Zotero library. (June)

- *Begin developing application in R Shiny. (June)

- *Complete application in first draft.
