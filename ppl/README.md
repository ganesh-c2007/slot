# Ex03 Time Table
## Date:21.09.2025

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
<!DOCTYPE html>
<html>
<head>
    <title align="center">Slot Time Table - YOUR NAME</title>
</head>
<body>
    <div style="text-align:center;">
    <IMG SRC="C:\Users\acer\ppl\pplapp\static\PHOTO 1.jpg"HEIGHT="150"WIDTH="500"BORDER=6>
    </div>    
    <h2 align="center">Saveetha Engineering College</h2>
    <h3 align="center">SLOT TIME TABLE - Ganesh.c (25017481)</h3>

    <table align="center" border="1">
        <tr BGCOLOR="YELLOW">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">8-10</td>
            <td align="center">free slot</td>
            <td>Python programming </td>
            <td>Python programming</td>
            <td align="center">free slot</td>
            <td align="center">free slot</td>
            <td align="center">free slot</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">10-12</td>
            <td align="center"> FWAD</td>
            <td align="center">free slot</td>
            <td align="center">FWAD</td>
            <td align="center">free slot</td>
            <TD align="center">FWAD</TD>
            <td align="center">free slot</td>
        </tr>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">12-1</td>
            <td COLSPAN=6 ALIGN="CENTER">LUNCH</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">1-3</td>
            <td align="center">free slot</td>
            <td>Python programming</td>
            <td>Menter meet</td>
            <td align="center">free slot</td>
            <td>Python programming</td>
            <td align="center">FWAD</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">3-5</td>
            <td>Python programming</td>
            <td align="center">free slot</td>
            <td align="center">FWAD</td>
            <td align="center">free slot</td>
            <td align="center">free slot</td>
            <td align="center">free slot</td>
        </tr>
        
    </tr>
    </table>

    <h3 align="center">Subjects</h3>
    <table align="center" border="1">
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19AI301</td>
            <td>Python programming </td>
        </tr>
    </table>
</body>
</html>
```


## OUTPUT



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
