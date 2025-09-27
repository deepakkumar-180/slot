# Ex03 Time Table
## Date:20/9/2025

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
    <head>
        <title>deepak</title>
    </head>
    <body>
        <center>
            <img src="logo.png" width="700",hight="200">
        <h1>
            SLOT TIME TABLE-DEEPAKKUMAR.S(25016457)
        </h1>
        <table border="5" cellspacing="3" cellpading="3">
        <tr>
            <th bgcolor="blue">day/time</th>
            <th bgcolor="blue">Monday</th>
            <th bgcolor="blue">Tuesday</th>
            <th bgcolor="blue">Wedensday</th>
            <th bgcolor="blue">Thursday</th>
            <th bgcolor="blue">Friday</th>
            <th bgcolor="blue">Saturday</th>
        </tr>
        <tr>
            <th bgcolor="blue">8am-10am</th>
            
            <td colpan="2" align="center">Free slot</td>
            <td>FWAD</td>
            <td colspan="2" align="center">FREE SLOT</td>
            <td>FWAD</td>
        </tr>
        <tr>
            <th bgcolor="blue">10am-12pm</th>
            <td>PYTHON</td>
            <td>C.ENGLISH</td>
            <td>FWAD</td>
            <td>C.ENGLISH</td>
            <td colspan="2" align="center">FREE</td>
        </tr>
        <tr>
            <th bgcolor="blue">12pm-1pm</th>
            <center>
            <td colspan="6" align="center">LUNCH</td>
            </center>
        </tr>
        <tr>
            <th bgcolor="blue">1pm-3pm</th>
            <td colspan="2" align="center">python</td>
            <td>FREE SLOT</td>
            <td colspan="2" align="center">FWAD</td>
        </tr>
        <tr>
            <th bgcolor="blue">3pm-5pm</th>
            <td colspan="3" align="center">C.ENGLISH</td>
            <td>PYTHON</td>
            <td>FREE SLOT</td>
            <td>C.ENGLISH</td>
        </tr>
        </table>
        <br>
    
    <table border="2" width="700" height="200">
        <tr>
          <th>S.NO></th>
          <th>SUBJECT CODE</th> 
          <th>SUBJECT NAME</th> 
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of web application development(FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19AI301</td>
            <td>PYTHON PROGRAMMING(python)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19EN101</td>
            <td>COMMUNICATIVE ENGLISH(C.ENGLISH)</td>
        </tr>

    </table>
    </center>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2025-09-27 131159.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
