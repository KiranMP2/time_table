# Ex03 Time Table
# Date:31-3-2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```python
<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/photo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
    <caption><b>SLOT TIME TABLE - KIRAN.MP (24000839) </b></caption> -
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
        <td>ENGINEERING DESIGN AND MODELLING</td>
        <td>FREE SLOT</td>
        <td>PYTHON AND LINEAR ALGEBRA</td>
        <td>FUNDAMENTALS OF C PROGRAMMING</td>
        <td>FREE SLOT</td>
    </tr>
    <tr align="center">
        <th bgcolor="yellow">10-12</th>
        <td>FREE SLOT</td>
        <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
        <td>ENGINEERING DESIGN AND MODELLING</td>
        <td>COMMUNICATIVE ENGLISH</td>
        <td>COMMUNICATIVE ENGLISH</td>
    </tr>
    <tr>
        <th bgcolor="yellow">12-1</th>
        <td colspan="5" align="center">L U N C H</td>
    </tr>
    <tr align="center">
        <th bgcolor="yellow">1-3</th>
        <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT </td>
        <td>PYTHON AND LINEAR ALGEBRA</td>
        <td>FUNDAMENTALS OF C PROGRAMMING</td>
        <td>SOFT SKILLS</td>
        <td>PYTHON AND LINEAR ALGEBRA</td>
    </tr>
    <tr align="center">
        <th bgcolor="yellow">3-5</th>
        <td>FREE SLOT</td>
        <td>FREE SLOT</td>
        <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
        <td>PYTHON AND LINEAR ALGEBRA</td>
        <td>FREE SLOT</td>
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
        <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT (FWAD)</td>
    </tr>
    <tr>
        <td align="center">2.</td>
        <td align="center">19AI304</td>
        <td>FUNDAMENTALS OF C PROGRAMMING (C PROGRAM)</td>
    </tr>
    <tr>
        <td align="center">3.</td>
        <td align="center">19AI301C</td>
        <td>PYTHON AND LINEAR ALGEBRA (PYTHON & MATHS)</td>
    </tr>
    <tr>
        <td align="center">4.</td>
        <td align="center">19AI302</td>
        <td>ENGINEERING DESIGN AND MODELLING (EDM)</td>
    </tr>
    <tr>
        <td align="center">5.</td>
        <td align="center">19EN101</td>
        <td>COMMUNICATIVE ENGLISH (ENG)</td>
    </tr>
    <tr>
        <td align="center">6.</td>
        <td align="center">19EY701</td>
        <td>Soft Skills (SS)</td>
    </tr>
</table>
</body>
</html>
```
# OUTPUT
![Screenshot 2025-03-31 112936](https://github.com/user-attachments/assets/bde13833-727f-452b-8371-efc78ebabce7)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
