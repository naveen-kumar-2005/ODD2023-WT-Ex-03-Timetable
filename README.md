# Ex-04-Timetable
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
<!DOCTYPE html>
<html>
 
<body>
    <centre>
    <img align="centre" src="logo.png" width="700"height="100" border="5" >

    <h1 align="centre">TIME TABLE</h1>
    <table border="10" cellspacing="2" >
        <!--<caption>Timetable</caption>-->
        <tr align = "center" height="50" width="100">
            <td><b>REFERENCE NUMBER:</b></td>
            <td><b>23013536</b></td>
            <td><b>NAME</b></td>
            <td><b>Naveen Kumar</b></td>
            <td><b>DEPARTMENT</b></td>
            <td><b>AI&DS</b></td>
        </tr>
        
        <tr >
            <td align="center" height="50"
                width="100"><br>
                <b>Day/Period</b></br>
            </td>
            <td align="center" height="50"
                width="110">
                <b>I<br>8:00-10:00</b>
            </td>
            <td align="center" height="50"
                width="110">
                <b>II<br>10:00-12:00</b>
            </td>
            <td align="center" height="50"
                width="110">
                <b>12:00-1:00</b>
            </td>
            <td align="center" height="50"
                width="110">
                <b>III<br>1:00-3:00</b>
            </td>
            <td align="center" height="50"
                width="110">
                <b>IV<br>3:00-5:00</b>
            </td>
           
        </tr>
        <tr >
            <td align="center" height="50" >
                <b>Monday</b></td>
            <td align="center" height="50">Pythoon and Linear Algebra
            </td>
            <td align="center" height="50">---</td>
            <td rowspan="6" align="center" height="50">
                <h2>L<br>U<br>N<br>C<br>H</h2></td>
            <td align="center" height="50">Physics for Quantum Computing</td>
            <td align="center" height="50">---</td>

        
            
        </tr>
        <tr>
            <td align="center" height="50" >
                <b>Tuesday</b>
            </td>
            
            <td align="center" height="50">Principles of Chemistry</td>
            <td align="center" height="50">Probability for Queuing models</td>
            <td align="center" height="50">Python and Linear Algebra</td>
            <td align="center" height="50">---</td>
        </tr>
        <tr>
            <td align="center" height="50" >
                <b>Wednesday</b>
            </td>
            <td align="center" height="50">---</td>
            <td align="center" height="50">Fundamental of Web Application Development</td>
            <td align="center" height="50">Python and Linear Algebra</td>
            <td align="center" height="50">---</td>
            
        
        </tr>
        <tr  >
            <td align="center" height="50" >
                <b>Thursday</b>
            </td>
            <td align="center" height="50">Fundamental of Web Application Development</td>
            <td align="center" height="50">---</td>
            <td align="center" height="50">Python and Linear Algebra</td>
            <td align="center" height="50">---</td>
        </tr>
        <tr>
            <td align="center" height="50">
                <b>Friday</b>
            </td>
            <td align="center" height="50">Principles of Chemistry</td>
            <td align="center" height="50">Fundamental of Web Application Development</td>
            <td align="center" height="50">Python and Linear Algebra</td>
            <td align="center" height="50">Physics for Quantum Computing</td>
        </tr>
        
    </table>
</body>
 
</html>
```
# OUPUT
![Alt text](<Screenshot (2).png>)

# RESULT
Thus we display the timetable of us using HTML webpage successfully.
