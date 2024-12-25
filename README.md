# Ex03 Time Table
# Date: 12.10.2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using ```<table>``` tag in html.

## STEP 4
Add header row using ```<th>``` tag.

## STEP 5
Add your timetable using``` <td>``` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<html> 
    <head>
        <title>My CAMU Schedule</title>
        </head>
    
           
    <body style="background-color: rosybrown">
        <center>
            <img src="logo.png" width="800" height="100">
        </center>
        <br>
        <br>
            
                <center>
              <caption>SLOT TIME TABLE-YUVASHREE (24900809) </caption>
        <style>
            table,th,td{
                text-align: center;
                border-color: yellowgreen;
                border: 3px solid black;    
                height: 30px;
                width: auto;
                vertical-align: center;
                scroll-behavior: smooth;
            }
        </style>
        <table>
            <tr>
            <th style="background-color: tan;">Day/Time</th>
            <th style="color: rgb(226, 226, 43); background-color: brown;">MON</th>
            <th style="color: rgb(226, 226, 43); background-color: brown;">TUE</th>
            <th style="color: rgb(226, 226, 43); background-color: brown;">WED</th>
            <th style="color: rgb(226, 226, 43); background-color: brown;">THU</th>
            <th style="color: rgb(226, 226, 43); background-color: brown;">FRI</th>
            <th style="color: rgb(226, 226, 43); background-color: brown;">SAT</th>
        </tr>
        <tr>
            <th style="color: aqua; background-color: blueviolet;">8-10</th>
            <td style="background-color: olivedrab;">FREE SLOT</td>
            <td style="background-color: olivedrab;">Evs</td>
            <td style="background-color: olivedrab;" colspan="4">FREE SLOT</td>

        </tr>
        <tr>
            <th style="color: aqua; background-color: blueviolet;">10-12</th>
            <td style="background-color: olivedrab;">Web</td>
            <td style="background-color: olivedrab;">Maths</td>
            <td style="background-color: olivedrab;">English</td>
            <td style="background-color: olivedrab;">Career</td>
            <td style="background-color: olivedrab;">Python</td>
            <td style="background-color: olivedrab;">Maths</td>
        </tr>
        <tr>
            <th style="color: aqua; background-color: blueviolet;">12-1</th>
            <td style="background-color: olivedrab;" colspan="6">LUNCH</td>
        </tr>
        <tr>
            <th style="color: aqua; background-color: blueviolet;">1-3</th>
            <td style="background-color: olivedrab;">python</td>
            <td style="background-color: olivedrab;">English</td>
            <td style="background-color:olivedrab;">FREE SLOT</td>
            <td style="background-color: olivedrab;">Web</td> 
            <td style="background-color: olivedrab;">FREE SLOT</td>
            <td style="background-color: olivedrab;">Chemistry</td>
        </tr>
        <tr>
            <th style="color: aqua; background-color: blueviolet;">3-5</th>
            <td style="background-color: olivedrab;" colspan="2">FREE SLOT</td>
            <td style="background-color: olivedrab;">Chemistry</td>
            <td style="background-color: olivedrab;" colspan="2">FREE SLOT</td>
            <td style="background-color: olivedrab;">Web</td>
        </tr>
        </table>


</center>

<br>
<br>


            <center>
          
            <table>
                <tr>
                    <th style="background-color: lightcoral;">CODE</th>
                    <th style="background-color: khaki;">DESCRIPTION</th>
                </tr>
                <tr>
                    <th style="background-color: gold;">19CY205</th>
                    <td style="background-color: sienna;">Principal of Chemistry in Engineering</td>
                </tr>
                <tr>
                    <th style="background-color: gold;">19A1301</th>
                    <td style="background-color: sienna;">Python Programming</td>
                </tr>
                <tr>
                    <th style="background-color: gold;">19MA201</th>
                    <td style="background-color: sienna;">Calculus and Matrix Algebra</td>
                </tr>
                <tr>
                    <th style="background-color: gold;">19EY708</th>
                    <td style="background-color: sienna;">Career Development Skills</td>
                </tr>
                <tr>
                    <th style="background-color: gold;">19EN101</th>
                    <td style="background-color: sienna;">Communicative English</td>
                </tr>
                <tr>
                    <th style="background-color: gold;">SH4801</th>
                    <td style="background-color: sienna;">Environmental Science and Sustainability</td>
                </tr>
                <tr>
                    <th style="background-color: gold;">19A1301</th>
                    <td style="background-color: sienna;">Fundamental of Web Application Development</td>
                </tr>
                
            </table>
        </center>
           
        </body>
    </head>
</html>

```
# OUTPUT
![alt text](<Screenshot (13).png>)
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
