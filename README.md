# Ex02 Time Table
## Date:

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
~~~
<html>
<head>
<title>Slot Timetable</title>

<style>

body{
    background:#f3f5f7;
    font-family:Arial;
}

table{
    width:100%;
    border-collapse:collapse;
}

th,td{
    border:1px solid black;
    padding:10px;
    text-align:center;
}

.subject{
    background:#6ea8ca;
    color:white;
    padding:10px;
    border-radius:5px;
}

</style>

</head>

<body>

<h1 align="center">COLLEGE TIMETABLE</h1>

<table>

<tr>
<th>Time</th>
<th>Monday</th>
<th>Tuesday</th>
<th>Wednesday</th>
</tr>

<tr>
<td>8am</td>
<td><div class="subject">Machine Learning</div></td>
<td><div class="subject">Web Application</div></td>
<td><div class="subject">Python</div></td>
</tr>

<tr>
<td>10am</td>
<td><div class="subject">Career Skills</div></td>
<td><div class="subject">Mentor Meet</div></td>
<td><div class="subject">Machine Learning</div></td>
</tr>

</table>

</body>
</html>
~~~


## OUTPUT
<img width="1233" height="823" alt="Screenshot 2026-05-19 180552" src="https://github.com/user-attachments/assets/7bad4f25-06a8-44da-99be-ac9aa14b3f04" />



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
