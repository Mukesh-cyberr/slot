# Ex03 Time Table
## Date:22-04-2025

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
```<html>
<head>
<title> Course Schedule </title>
</head>
<body>
    <center>
<img src="/static/logo.png" alt="Italian Trulli" width="800" height="130">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="lavender">
<br>
<caption><b>SLOT TIMETABLE-Mukesh Raj D(212224100038)</b></caption>
<br>
<tr align="center">
<th bgcolor="skyblue">Day/Time</th>
<th bgcolor="skyblue">Monday</th>
<th bgcolor="skyblue">Tuesday</th>
<th bgcolor="skyblue">Wednesday</th>
<th bgcolor="skyblue">Thursday</th>
<th bgcolor="skyblue">Friday</th>
<th bgcolor="skyblue">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="skyblue">8-10</th>
<td >COMMUNICATIVE ENGLISH</td>
<td>FREE SLOT</td>
<td>FREE SLOT </td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="skyblue">10-12</th>
<td>C PROGRAMMING</td>
<td> COMPUTER ARCHITECTURE </td>
<td> COMPUTER ARCHITECTURE </td>
<td> FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT </td>
<td> SNM</td>
<td> EDM </td>
</tr>
<tr>
<th bgcolor="skyblue">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="skyblue">1-3</th>
<td > SNM </td>
<td> FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>MENTOR MEET</td>
<td> COMMUNICATIVE ENGLISH</td>
<td> C PROGRAMMING </td>
<td> REASONING ABILITY</td>
</tr>
<tr align="center">
<th bgcolor="skyblue">3-5</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td> EDM </td>
<td> PROBABILITY AND QUEUEING MODELS</td>
<td>FREE SLOT</td>
<td> PROBABILITY AND QUEUEING MODELS</td>

</tr>
</table>
<br>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>FUNDAMENTALS OF WEB (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI304</td>
<td>C PROGRAMMING </td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19MA222</td>
<td>PROBABILITY AND QUEUEING MODELS </td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CS305</td>
<td>COMPUTER ARCHITECTURE</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MA211</td>
<td>SNM</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EY709</td>
<td>REASONING ABILITY</td>

</tr>
<tr>
    <td align="center">7.</td>
    <td align="center">19AI302</td>
    <td> EDM </td>
    
</tr>
<tr>
    <td align="center">8.</td>
    <td align="center">19EN101</td>
    <td>COMMUNICATIVE ENGLISH</td>
    
</tr>
    
    
</table>
</body>
</html> 
```

## OUTPUT

![alt text](<Screenshot 2025-04-22 095515.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
