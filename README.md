# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag

### STEP 2
Add header row using th tag

### STEP 3
Add your timetable

### STEP 4
Execute the program

# CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/images/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - DEEKSHA P (22008761)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td>ENG</td>
<td>PROG C</td>
<td>FWAD</td>
<td>FWAD</td>
<td>FWAD</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td colspan="2" align="center">FREE SLOT</td>
<td>PROG C</td>
<td>CN</td>
<td>FREE SLOT</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td> CN </td>
<td>GER</td>
<td>MAT</td>
<td>ENG</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td> PHY </td>
<td>FREE SLOT</td>
<td>PHY</td>
<td>GER</td>
<td>MAT</td>
</tr>
</table>
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
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19EN613</td>
<td>German Advanced (GER)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CS302</td>
<td>Programming in C (PROG C)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19MA212</td>
<td>Algebra and Number Theory (MAT)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19PH205</td>
<td>Computational Physics (PHY)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19CS301P1</td>
<td>Computer Networks (CN)</td>
</tr>
<tr>
<td align="center">7.</td>
<td align="center">19EN102</td>
<td>Technical English (ENG)</td>
</tr>
</table>
</body>
</html>
```

# OUPUT
![OUTPUT](mypro/static/images/slot.png)


# HTML VALIDATOR
![HTML VALIDATOR](http://deeksha.student.saveetha.in:8000/static/images/out5.png?raw=true)

# RESULT
The program for creating slot time table is completed successfully
