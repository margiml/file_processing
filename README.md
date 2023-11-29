# file_processing

This program processes a text file called **Notes.txt** that contains information about students with their notes. The file must be located in the same directory where the Jupyter Notebook is located, which contains the code that processes the file. Each line of the text file contains the name, last name of the student and the number of points that the student received during classes. Elements are separated with "|". Each student can appear more than once within the text file.

Processes a text file that contains student information with their grades. Each line of the text file has three elements: the student's first name, the student's last name, and the number of points the student received in classes. Elements are separated with "|". Each student can appear more than once within the text file.

The program must:

- Ask the user for the name of the teacher file to process.
- Read the content of the file and add the points that each student received
- Print a report ordered by screen


For example, if the file contains a line with: abCc

John|Williams|5

Annita|Smith|4.5

John|Williams|2

Annita|Smith|11

Andrew|Jones|1.5



the result will be seen as follows:

Andrew Jones 1.5

Annita Smith 15.5

John Williams 7.0
