# Ex02 Time Table
## Date:27.11.2025

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM

```
<html>
    <head>
        <title>Time Table</title>
    </head>
    <body>
        <center>
        <img src="logo.png" width="700" height="200">
        <br>
        <h2>SLOT TIME TABLE KEERTHANA M (25018580)</h2>
        <table border="4" cellpadding="2" cellspacing="5" bgcolor="purple" height="200" width="700">
            <tr bgcolor="pink" align="center">
                <th bgcolor="lightgreen">Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr align="center" bgcolor="violet">
                <th bgcolor="lightpink">8-10</th>
                <td>CP</td>
                <td>FREE SLOT</td>
                <td>CP</td>
                <td>FREE SLOT</td>
                <td>CP</td>
                <td>FREE SLOT</td>
            </tr>
            <tr align="center" bgcolor="violet">
                 <th bgcolor="lightpink">10-12</th>
                 <td colspan="3">FREE SLOT</td>
                 <td>ENG</td>
                 <td colspan="2">WEB</td>
            </tr>
            <tr align="center" bgcolor="violet">
                <th bgcolor="lightpink">12-1</th>
                <td colspan="6">LUNCH</td>

            </tr>
            <tr align="center" bgcolor="violet">
                <th bgcolor="lightpink">1-3</th>
                <td colspan="2">WEB</td>
                <td>MENTOR MEET</td>
                <td colspan="3">CP</td>
            </tr>
            <tr align="center" bgcolor="violet">
                <th bgcolor="lightpink ">3-5</th>
                <td>ENG</td>
                <td>FREE SLOT</td>
                <td>ENG</td>
                <td colspan="2">FREE SLOT</td>
                <td>ENG</td>
                
            </tr>  
        </table>
        <br>
        <table border="4" cellpadding="5" cellspacing="3" height="200" width="700">
            <tr>
                <th>S.No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI304</td>
                <td>FUNDAMENTALS OF C PROGRAMMING</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AI414</td>
                <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19EN101</td>
                <td>COMMUNICATIVE ENGLISH</td>
            </tr>
        </table>
        </center>
    </body>
</html>
```

## OUTPUT

![alt text](<Screenshot (20).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
