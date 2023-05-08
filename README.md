Download Link: https://assignmentchef.com/product/solved-program-to-manage-records-and-do-analysis-regarding-projects
<br>
A company wants you to create a program to manage records and do analysis regarding projects. The company stores all information in a file as follows:  The PROJECT file contains project characteristics such as the project name and project code.  The EMPLOYEE file contains the employee names, phone number, address, etc.  The JOB file contains the billing charge per hour for each of the job types – a biological engineer, a computer technician, and electrical engineer would generate different billing charges per hour.  The CHARGE file would be used to keep track of the number of hours by job type that will be billed for each employee who worked on the project. Requirements 1. This problem must be solved using structures and arrays. Create the struct for each file. In the driver program, read the files into the respective arrays. The analysis should happen through these arrays. 2. Your program should do the following:  Read the data file and store details in arrays.  Create a menu for the user that can do the following: o Exit program o Display all projects handled by the company o Display Employee ID, Employee Name, Job Description and Total amount earned by each employee. Amount can be calculated using CHG_HOURS and JOB_CHARGE

PROJ_CODE JOB_CODE EMP_ID CHG_HOURS(Charge.txt)1 CT 105 16.201 CT 110 14.301 EE 101 13.302 BE 108 17.502 EE 101 19.803 CT 105 23.403 CT 110 11.60

Employee.txt:

EMP_ID EMP_LNAME EMP_FNAME EMP_INITIAL EMP_AREA_CODE EMP_PHONE101 Newson John   D 653 234-3245105 Schwann David F 653 234-1123108 Sattlemeier June H 905 554-7812110 Ramoras Anne R 615 233-5568

Job.txt:

JOB_CODE JOB_DESCRIPTION JOB_CHARGEBE BiologicalEngineer 55.00CT ComputerTechnician 62.00EE ElectricalEngineer 65.00

Project.txt:

PROJ_CODE PROJ_NAME1 Hurricane2 Coast3 Satellite

The output should allow users to enter choices upon which choices from menu bar must be displayed eg :

………………….(1)…………..Exit the program………………………………………….

………………….(2)………….Display project txt file ………………………………….

………………….(3)………….Display change.txt file …………………………………

………………….(4) …………calculate total of all ………………………………………

………………….(5)…….display all files with respective totals ……………………