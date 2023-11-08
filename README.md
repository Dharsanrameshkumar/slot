# Ex03 Time Table
## Date:08/11/2023

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
<title>time table</title>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<center>
<caption><h2>SLOT TIME TABLE-DHARSAN R(23012300)</h2></caption>
<table align="center" border="1" cellpadding="10" cellspacing="4">
<tr>
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">8-10</th>
<th bgcolor="yellow">10-12</th>
<th bgcolor="yellow">12-1</th>
<th bgcolor="yellow">1-3</th>
<th bgcolor="yellow">3-5</th>
</tr>
<tr>
<th bgcolor="yellow">MONDAY</th>
<td bgcolor="cyan">C ENGLISH</td>
<td bgcolor="cyan">CHEMISTRY</td>
<td>LUNCH</td>
<td bgcolor="cyan">FREE SLOT</td>
<td bgcolor="cyan">PHYSICS</td>
</tr>
<tr>
<th bgcolor="yellow">TUESDAY</th>
<td bgcolor="cyan">C ENGLISH</td>
<td bgcolor="cyan">LINEAR ALGEBRA</td>
<td>LUNCH</td>
<td bgcolor="cyan">CHEMISTRY</td>
<td bgcolor="cyan">FREE SLOT</td>
</tr>
<tr>
<th bgcolor="yellow">WEDNESDAY</th>
<td bgcolor="cyan">FWAD</td>
<td bgcolor="cyan">FREE SLOT</td>
<td>LUNCH</td>
<td bgcolor="cyan">FREE SLOT</td>
<td bgcolor="cyan">PYTHON</td>
</tr>
<tr>
<th bgcolor="yellow">THURSDAY</th>
<td bgcolor="cyan">FREE SLOT</td>
<td bgcolor="cyan">FWAD</td>
<td>LUNCH</td>
<td bgcolor="cyan">FREE SLOT</td>
<td bgcolor="cyan">LINEAR ALGEBRA</td>
</tr>
<tr>
<th bgcolor="yellow">FRIDAY</th>
<td bgcolor="cyan">PYTHON</td>
<td bgcolor="cyan">PHYSICS</td>
<td >LUNCH</td>
<td bgcolor="cyan">FWAD</td>
<td bgcolor="cyan">FREE SLOT</td>
</tr>
</table>
<br>
<table align="center" border="1" cellpadding="10" cellspacing="4">
<tr>
<th >SN.NO.</th>
<th >Subject Code</th>
<th >Subject Name</th>
</tr>
<tr>
<th >1</th>
<td >19EN101</td>
<td >COMMUNICATIVE ENGLISH</td>
</tr>
<tr>
<th >2</th>
<td >19CY205</td>
<td >PRINCIPLE OF CHEMISTRY IN ENGINEERING</td>
</tr>
<tr>
<th >3</th>
<td >19PH214</td>
<td >PHYSICS FOR QUANTUM COMPUTING</td>
</tr>
<tr>
<th >4</th>
<td >19AI301C</td>
<td >PYTHON AND LINEAR ALGEBRA</td>
</tr>
<tr>
<th >5</th>
<td >19AI414</td>
<td >FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
</tr>
</table>
</center>
</body>
</html>

```
## OUTPUT

![Alt text](<Screenshot (15).png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
