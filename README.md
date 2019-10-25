# cs310-csv-json


The purpose of this assignment is to convert data of the CSV format into Json format, and
vice versa. The converted data is presented as strings afterwards. This was an assignment
in a CS 310 class, and the entirety of the Main.java class was composed by the instructor
for the students to analyze and utilize in the construction of a working converter. As I
had no part in coding Main.java, I'll not cover it's contents in this README file. This 
code wasn't completed due to poor time management on my part, though the instructor deemed
the assignment a success regardless due to my status as a student.


Converter.java's function is to parse a spreadsheet of data from CSV format to Json format,
using key identifiers to identify what should be converted into a string or an integer.
The identifier for strings is denoted with "Quotation marks" and integers with [Brackets].

Before writing the variables of the program, @SuppressWarnings("unchecked") is written to
avoid any errors while in the process of parsing the rows and columns. The columns of this
are labled: ID, Total, Assignment 1, Assignment 2, and Exam 1.

Within the try block, a buffered reader is used to read the CSV or Json data before converting
them and assigning the data to the rows as Longs. A catch(IOException e) is made at the end
of the try block before returning the Json data as a string.

In the public stati String jsonToCsv(String jsonString) block, another try block is made.
The try block parses Json data to CSV format.

After the Json parser in the try block comes the conversion portion of the class. This 
section takes the data parsed from a Json formatted spreadsheet and converts it into CSV
format. At least it would had I enough time to complete this assigned part of the code.
As of now, this is naught but proper parsing program which converts Json to CSV only.
