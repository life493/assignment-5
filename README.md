# ASSIGNMENT - 5 
## TASK 1- CREATING A DICTIONARY OF STUDENT'S MARKS 
<b>DESCRIPTION</b>-The following python program creates a dictionary of student's names along with their names and then asks the user for input and return their corresponding marks.If the student name is not there it displays a appropriate message 

<b>STEP 1-CREATING A DICTIONARY</b><br>
In the first step we create a dictionary of various student names and their marks .
student_marks = { "Alice": 85,"Bob":78,"Charlie":92,"David":56,"Eve":45}
Here,the student's names are keys and their marks are values.

<b>STEP 2-ASKING THE USER FOR THE INPUT</b><br>
In the second step we use the built-in function input() which allows the user to enter the student's name.

<b>STEP 3-CHECKING WHETHER THE NAME IS THERE IN THE DICTIONARY</b><br>
In this step we use if-else statement whether the name entered by the user is there in the dictionary .If the name is there, then it returns the corresponding marks of the student and if no then it displays a message "Student not found".

## TASK 2 -DEMONSTATE LIST SLICING 
DESCRIPTION-The following python programme creates a list from number 1 to 10, extracts and prints the first five elements and then reverses the first five elements and prints it.

<b>STEP 1-CREATING THE LIST </b><br>
In the first step we create a list named 'l' from number 1 to 10 and use the print() function to print the list .

<b>STEP 2- EXTRACTING THE FIRST FIVE ELEMENTS </b><br>
In the next step we extract the first five elements from the list using the list slicing <br>
l[0:5] means that starting from index 0 and going till (not including) till 5 which gives us [1,2,3,4,5] and the extracted elements are printed.

<b>STEP 3-REVERSING THE LIST AND PRINTING IT </b><br>
In the next step we reverse the extracted list using list slicing using [::-1] <br>
<b> [::-1] </b> means the step backwards (-1), effectively reversing the list <br>
List [1,2,3,4,5] becomes [5,4,3,2,1] and the reversed list gets printed.



