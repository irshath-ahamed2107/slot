# Ex03 Time Table
## Date:19/11/24

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
        <title>Slot Timetable</title>
    </head>
    <body>
       <center><img src="/static/logo.png" height="100" width="540"></center>
       <br>
   <center><table border="5" cellpadding="20" cellspacing="10" bgcolor="">
    <TR>
        <TH>S.NO</TH>
        <TH>8 TO 10</TH>
        <TH>10 TO 12</TH>
        <TH>1 TO 3</TH>
        <TH>3 TO 5</TH>
    </TR>
    <TR>
        <TD bgcolor="red">MONDAY</TD>
        <TD></TD>
        <TD>WEB APP</TD>
        <TD>CDS</TD>
    </TR>
      <TR>  <TD bgcolor="violet">TUEDAY</TD>
            <TD></TD>
             <TD></TD>
            <TD>DE</TD></TR>
        <TR><TD bgcolor="yellow">WEDNESDAY</TD>
            <TD>DE</TD>
            <TD>WEB APP</TD>
            <TD>MENTOR MEET</TD>
            <TD>CHEMISTRY</TD>
        </TR>
       <TR> <TD bgcolor="orange">THURSDAY</TD>
            <TD></TD>
            <TD>EMPD</TD>
            <TD>COMM ENG</TD>
            <TD>CHEMISTRY</TD>
        </TR>
       <TR><TD bgcolor="green">FRIDAY</TD>
           <TD>PQM</TD>
           <TD>COMM ENG</TD>
           <TD>EMPD</TD>
       </TR>
       <TR>
        <TD bgcolor="brown"> SATURDAY </TD>
        <TD></TD>
        <TD>PQM</TD>
        <TD>WEB APP</TD>
        
       </TR>
    
        
</table>
</center>
<center><table>
<TR>
    <TH>S.NO</TH>
    <TH>Slot code</TH>
    <TH>Slot name</TH>
</TR>
<TR>
    <TD>1.</TD>
    <TD>19AI303</TD>
    <TD>Engineering Mechanics and Product Development</TD>
</TR>
<TR>
    <TD>2.</TD>
    <TD>19AI414</TD>
    <TD>Fundamentals of Web Application Development</TD>
</TR>
<TR>
    <TD>3.</TD>
    <TD>19CY205</TD>
    <TD>Principles of Chemistry in Engineering</TD>
<TR>
    <TD>4.</TD>
    <TD>19EE404</TD>
    <TD>Digital Electronics</TD>
</TR>
<TR>
    <TD>5.</TD>
    <TD>19EN101</TD>
    <TD>Communicative English</TD>
</TR>
<TR>
    <TD>6.</TD>
    <TD>19EY708</TD>
    <TD>Career Development Skills</TD>
</TR>
<TR>
    <TD>7.</TD>
    <TD>19MA222</TD>
    <TD>Probability and Queueing Models</TD>
</TR>

</table></center>
</body>
</html>             
```

## OUTPUT

![slot table](https://github.com/user-attachments/assets/e1abdc00-c6f3-44c4-82cc-121183bfe33e)




## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
