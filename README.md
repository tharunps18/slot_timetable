# Ex02 Time Table
## Date:11/02/2026

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
```html
<html>
<head>
<title>Slot Time Table</title>
</head>

<body bgcolor="lightyellow">
    <center>
        <img src="/static/logo.png" width="800">

    </center>

<table border="2" cellpadding="10" align="center" width="90%" bgcolor="black">

<caption>
<b>SLOT TIME TABLE - THARUN P S (212224110055) </b>
</caption>

<tr bgcolor="yellow">
<th>Day/Time</th>
<th>Monday</th>
<th>Tuesday</th>
<th>Wednesday</th>
<th>Thursday</th>
<th>Friday</th>
<th>Saturday</th>
</tr>

<tr align="center" bgcolor="cyan">
<td>8-10</td>
<td >FWAD</td>
<td>FWAD</td>
<td>DBMS</td>
<td>FREE SLOT</td>
<td>DBMS</td>
<td rowspan="2" >FREE SLOT</td>
</tr>


<tr align="center" bgcolor="cyan">
<td>10-12</td>
<td>FREE SLOT</td>
<td>PYTHON</td>
<td>FWAD</td>
<td>DBMS</td>
<td>FWAD</td>
</tr>


<tr align="center" bgcolor="cyan">
<td>12-1</td>
<td colspan="6" >L U N C H</td>
</tr>

<tr align="center" bgcolor="cyan">
<td>1-3</td>
<td>DBMS</td>
<td rowspan="2" >FREE SLOT</td>
<td>MENTOR MEET</td>
<td>FWAD</td>
<td>PYTHON</td>
<td>DBMS</td>
</tr>


<tr align="center" bgcolor="cyan">
<td>3-5</td>
<td>FREE SLOT</td>
<td>PYTHON</td>
<td>PYTHON</td>
<td>FREE SLOT</td>
<td>PYTHON</td>
</tr>


</table>

<br><br>

<table border="2" cellpadding="8" align="center" width="80%" bgcolor="black">

<caption>
<b>SUBJECT DETAILS</b>
</caption>

<tr align="center" bgcolor="white">
<th>S.No</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>

<tr align="center" bgcolor="white">
<td>1</td>
<td>19AI414</td>
<td>FUNDAMENTALS OF WEB APPLICATION(FWAD)</td>
</tr>

<tr align="center" bgcolor="white">
<td>2</td>
<td>19AI301</td>
<td>PYTHON PROGRAMMING</td>
</tr>

<tr align="center" bgcolor="white">
<td>3</td>
<td>19CS404</td>
<td>DATABASE MANAGEMENT SYSTEM AND ITS APPLICATION</td>
</tr>

</table>


</body>
</html>
```
 
## OUTPUT
![alt text](<Screenshot 2026-02-11 213914.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
