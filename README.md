# Ex03 Time Table
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
```C
<html>
    <head>
        <title>Slot Timetable</title>
    </head>
    <body>
        <center>
            <img src="C:\Users\screenshot\Pictures\4.png"height="100" width="500">
        </center>
        <br>
        <table align="center" width="500" cellspacing="3" cellpadding="2" border="3" bgcolor="lightgreen">
            <caption><b>SLOT TIMETABLE INDRAJA S (212222043003)</b></caption> 
            <tr align="center">
                <th bgcolor="pink">Day/Time</th>
                <th bgcolor="pink">Monday</th>
                <th bgcolor="pink">Tuesday</th>
                <th bgcolor="pink">Wednesday</th>
                <th bgcolor="pink">Thursday</th>
                <th bgcolor="pink">Friday</th>
            </tr>
            <tr align="center">
                <th bgcolor="blue">8-10</th>
                <td bgcolor="red">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
                <td bgcolor="red">ETHICAL HACKING TECHNIQUES</td>
                <td bgcolor="red">INTRODUCTION TO IOT</td>
                <td bgcolor="red">FREE SLOT</td>
                <td bgcolor="red">INTRODUCTION TO IOT</td>
            </tr>
            <tr align="centre">
                <th bgcolor="blue">10-12</th>
                <td bgcolor="cyan">FREE SLOT</td>
                <td bgcolor="red">COMPUTER NETWORKS</td>
                <td bgcolor="cyan">FREE SLOT</td>
                <td bgcolor="red">COMPUTER NETWORKS</td>
                <td bgcolor="cyan">FREE SLOT</td>
            </tr>
            <tr bgcolor="orange" align="center">
                <th bgcolor="blue">12-1</th>
                <td colspan="5" align="center"> L U N C H </td>
            <tr align="centre">
                <th bgcolor="blue">1-3</th>
                <td bgcolor="cyan">FREE SLOT</td>
                <td bgcolor="cyan">FREE SLOT</td>
                <td bgcolor="red">Programming in C</td>
                <td bgcolor="red">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
                <td bgcolor="red">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
            </tr>
            <tr align="centre">
                <th bgcolor="blue">1-3</th>
                <td bgcolor="cyan">FREE SLOT</td>
                <td bgcolor="cyan">FREE SLOT</td>
                <td bgcolor="red">SOFT SILLS</td>
                <td bgcolor="cyan">FREE SLOT</td>
                <td bgcolor="cyan">FREE SLOT</td>
        </table>
        <br>
        <table align="center" cellspacing="2" cellpadding="4" border="2">
            <tr align="center">
                <th>S.No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr> 
            <tr>
                <td align="center">1.</td>
                <td align="center"><b><font color = blue>19AI414</font></b></td>
                <td><b><font color = blue>Fundamentals of Web Application Development (FWAD)</font></b></td>
                </tr>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19AM508</td>
                <td>INTRODUCTION TO IOT(IOT)</td>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19CS417</td>
                <td>ETHICAL HACKING TECHNIQUES(EHT)</td>
            </tr>
            <tr>
                <td align="center">4.</td>
                <td align="center">19CS406</td>
                <td>COMPUTER NETWORKS(CN)</td>
            </tr>
            <tr>
                <td align="center">5.</td>
                <td align="center">19CS302</td>
                <td>C PROGRAMMING(C)</td>
            </tr>
            <tr>
                <td align="center">6.</td>
                <td align="center">19EY701</td>
                <td>SOFT SKILLS (SS)</td>
            </tr>
        </table>
    </body>
</html>
```
## OUTPUT
![Screenshot (31)](https://github.com/indrajasukumar/slot/assets/145115195/dd90a570-1e89-476b-9dff-5440152e4872)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
