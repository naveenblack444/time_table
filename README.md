# Ex03 Time Table
## Date:21-10-2024

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using <table.> tag in html.

### STEP 4
Add header row using <th.> tag.

### STEP 5
Add your timetable using <td.> tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```


<html><body>
    <center>
    <img src="download.png" width="800">
          <hr>
          <BR>
        
          <table border="1"  CELLPADDING="10">
            <tr>
              <th colspan="6" bgcolor="YELLOW">SLOT TIME TABLE-NAVEEN(24900811)</th>
            </tr>
            <tr>
              <th align="center" bgcolor="BLUE">Days\Time</th>
                <th align="center" bgcolor="BLUE">8am-10am</th>
                  <th align="center" bgcolor="BLUE">10am-12pm</th>
                   <th align="center" bgcolor="BLUE">12pm-1pm</th>
                   <th align="center" bgcolor="BLUE">1pm-3pm</th>
                    <th align="center" bgcolor="BLUE">3pm-5pm</th>
                    </tr>
  <tr>
    <th align="center" bgcolor="orange">Monday</th>
    <td align="center" bgcolor="green">  </td>
    <td align="center" bgcolor="green">Web App</td>
    <th rowspan="6" align="center" bgcolor="sky blue">Lunch</th>
    <td align="center" bgcolor="green" >BEEE</td>
    <td align="center" bgcolor="green">   </td>
    
     </tr>
     
      <tr>
        <th align="center" bgcolor="orange">Tuesday</th>
        <td align="center" bgcolor="green">  </td>
        <td align="center" bgcolor="green">EVS</td>
         <td align="center" bgcolor="green">BEEE</td>
         <td align="center" bgcolor="green">  </td>
         </tr>
  
         <tr>
         <th align="center" bgcolor="orange">Wednesday</th>
         <td align="center" bgcolor="green">  </th>
         <td align="center" bgcolor="green">C-prgm</td>
         <td align="center" bgcolor="green">M-meet</td>
         <td align="center" bgcolor="green">   </td>
         </tr>
         
         <tr>
           <th align="center" bgcolor="orange">Thursday</th>
           <td align="center" bgcolor="green">Qun-Phys</td>
           <td align="center" bgcolor="green">   </td>
           <td align="center" bgcolor="green">Web App</td>
           <td align="center" bgcolor="green">  </td>
           </tr>
  
           <tr>
            <th align="center" bgcolor="orange">Friday</th>
            <td align="center" bgcolor="green"></td>
            <td align="center" bgcolor="green">D-Elect</td>
            <td align="center" bgcolor="green">Qun-Phys</td>
            <td align="center" bgcolor="green"> </td>
           </tr>
           <tr>
            <th align="center" bgcolor="orange">Saturday</th>
            <td align="center" bgcolor="green">D-Elect</td>
            <td align="center" bgcolor="green">CD</td>
            <td align="center" bgcolor="green">C-prgm</td>
            <td align="center" bgcolor="green">Web App</td>
           </tr></table>
          <br>
      
         <table border="1"  CELLPADDING="5">
              <tr>
              <th>S.NO</th>
              <th>Subject Code</th>
              <th>Subject Name</th>
            </tr>
  
            <tr>
              <th>01.</th>
              <td>19EY708</td>
              <td>Career Development skills</td>
            </tr>
            <tr>
              <th>02.</th>
              <td>SH4801</td>
              <td>Environmental Sciences and Sustainability</td>
            </tr>
            <tr>
              <th>03.</th>
              <td>SH3214</td>
              <td>Physics for Quantum Computing</td>
            </tr>
            <tr>
              <th>04.</th>
              <td>ECA-M-SCOFT</td>
              <TD>Mentor Meet</TD>
            </tr>
            <tr>
              <th>05.</th>
              <td>19AI414</td>
              <td>Fundamentals of Web Application</td>
            </tr>
            <tr>
              <th>06.</th>
              <td>19AI304</td>
              <TD>Fundametals of C Programming</TD>
            </tr>
            <tr>
              <th>07.</th>
              <td>19EE404</td>
              <TD>Digital Electronics</TD>
            </tr>
            <tr>
              <th>08.</th>
              <td>19EE305</td>
              <TD>Basic Electrical,Electronics and Measurement Engineering</TD>
            </tr>
          </center>
            </body>
            </html>
          
          
        
```
## OUTPUT
![alt text](<Screenshot (14).png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
