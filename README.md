# Ex03 Time Table
## Date:4/10/24

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
</html>

```

## OUTPUT

![Slot Timetable](https://github.com/user-attachments/assets/4f4b4666-a675-40ee-a811-fba6a7ed333e)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
