# Ex03 Time Table
## Date: 19.05.25

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
<<html>
<head>
<title>slot Timetable</title>    
</head>    
<body>
<center>
<img src="/static/logo.png"height="100"width="540">
</center>
<br>
<table align="center"width="540" cellspacing="2" cellpadding="4"border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - AHAMED JASEER SHA E (212224040015)</b></caption>
<tr align="center">
<th bgcolor="green">Day/Time</th>    
<th bgcolor="green">Monday</th>
<th bgcolor="green">Tuesday</th>
<th bgcolor="green">Wednesday</th>
<th bgcolor="green">Thursday</th>
<th bgcolor="green">Friday</th>
</tr>
<tr align="center">
<th bgcolor="green">8-10</th>    
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>JAPANESE LANGUAGE</td>
<td>DIGITAL ELECTRONICS</td>
<td>STATISTICS AND NUMERICAL METHODS</td>
<td>FUNDAMENTAL OF C PROGRAMMING</td>
</tr>
<tr align="center">
<th bgcolor="green">10-12</th>    
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>INTRODUCTION TO DATA SCIENCE</td>
<td>FREE SLOT</td>
<td>STATSTICS AND NUMERICAL METHODS</td>
<td>FREE SLOT</td>
</tr>
<tr>
<th bgcolor="green">12-1</th>
<td colspan="5" align="center">- - - L U N C H - - -</td>
</tr>
<tr align="center">
<th bgcolor="green">1-3</th> 
<td>FREE SLOT</td>
<td>DIGITAL ELECTRONICS</td>
<td>FUNDAMENTALS OF WEB APPLICATION</td>
<td>STUDY HOURS</td>
<td>JAPANESE LANGUAGE</td>   
</tr>
<tr align="center">
<th bgcolor="green">3-5</th> 
<td>STATISTICS AND NUMERICAL METHODS</td> 
<td>JAPANESE LANGUAGE</td>
<td>INTRODUCTION TO DATA SCIENCE</td>
<td>STUDY HOURS</td>
<td>FUNDAMETALS OF C PROGRAMMING</td>  
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. NO.</th>  
<th>SUBJECT CODE</th>
<th>SUBJECT NAME</th>  
</tr>   
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI304</td>    
<td>FUNDAMENTALS OF C PROGRAMMING (C PROGRAMMING)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI403</td>    
<td>INTRODUCTION TO DATA SCIENCE (DS)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19EE404</td>
<td>DIGITAL ELECTRONICS (DE)</td>    
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MA211</td>
<td>STATISTICS AND NUMERICAL METHODS (STAT)</td>    
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19TD603</td>
<td>JAPANESE LANGUAGE</td>    
</tr>
</table>
</body>
</html>
```

## OUTPUT
![alt text](time.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
