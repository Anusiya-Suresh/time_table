# Ex04 Time Table
# Date: 23/11/2026
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
```
timetable.html

<html>
<head>
    <title>Student timetable</title>
    <style>
        
        table,tr,th,td{
            border: 3px, solid rgb(93, 11, 11);
            border-collapse: auto;
            padding: 5px;
        }
        table{
            margin-left: auto;
            margin-right: auto;
            height: 250px;
            width: 800px;
         
        }


    body {
        background-color: #897fb99e;
        font-family: Georgia;
    }

    h2 {
        color: #45205F;
        text-align: center;
    }

    table {
        background-color: white;
        border: 3px solid #45205F;
        border-collapse: separate;
        border-spacing: 3px;
        margin: auto;
    }

    th {
        background-color: #6C4AB6;
        color: white;
        padding: 12px;
    }

    td {
        background-color: #EDE7F6;
        color: #222;
        padding: 12px;
    }

    tr:nth-child(even) td {
        background-color: #DCD0F0;
    }

    td:first-child {
        background-color: #B39DDB;
        color: #24113D;
        font-weight: bold;
    }
    .image{
        text-align: center;
    }

    .logo{
        width: 700px;
        height: auto;
        mix-blend-mode: multiply;
        background: transparent;
    }

    </style>
</head>
<body>
    <div class="image"> 
        <img src="D:\web\html\images.png"  width="800"  height="300"  class="logo">
    </div>
    <table>
        <caption><h2><b>SLOT TIMETABLE - ANUSIYA S (26011141) </b></h2></caption>
        <tr>
            <th>Day/ Time</th>
            <th>8:00 to 9:30</th>
            <th>9:45 to 11:15</th>
            <th>11:30 to 12:15</th>
            <th>12:30 to 1:00</th>
            <th>1:15 to 2:45</th>
            <th>3:00 to 4:30</th>
        </tr>
        <tr>
            <td><b>Monday</b></td>
            <td>FWAD</td>
            <td>PP</td>
            <td>Free Slot</td>
            <td>LUNCH</td>
            <td>Free Slot</td>
            <td>DE</td>
        </tr>
        <tr>
            <td><b>Tuesday</b></td>
            <td>FWAD</td>
            <td>Free Slot</td>
            <td>Mentor meeting</td>
            <td>LUNCH</td>
            <td>Free Slot</td>
            <td>EDM</td>
        </tr>
        <tr>
            <td><b>Wednesday</b></td>
            <td>PP</td>
            <td>Free Slot</td>
            <td>Mentor meeting</td>
            <td>LUNCH</td>
            <td>Free Slot</td>
            <td>Free Slot</td>
        </tr>
        <tr>
            <td><b>Thursday</b></td>
            <td>PP</td>
            <td>SNM</td>
            <td>Mentor meeting</td>
            <td>LUNCH</td>
            <td>PS</td>
            <td>DE</td>
        </tr>
           <tr>
            <td><b>Friday</b></td>
            <td>SNM</td>
            <td>Free Slot</td>
            <td>Mentor meeting</td>
            <td>LUNCH</td>
            <td>Free Slot</td>
            <td>Free Slot</td>
        </tr>
        <tr>
            <td><b>Saturday</b></td>
            <td>PS</td>
            <td>Free Slot</td>
            <td>Mentor meeting</td>
            <td>LUNCH</td>
            <td>FWAD</td>
            <td>EDM</td>
        </tr>
    </table>
    <br>
    <br>
    <br>

    <table>
        <tr>
            <th>S.No</th>
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
            <td>Python Programming (PP)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19AI302</td>
            <td>Engineering Design and Modelling (EDM)</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>SH1105</td>
            <td>Public Speaking (PS)</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19EE404</td>
            <td>Digital Electronics (DE)</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>SH2211</td>
            <td>Statistics and Numerical Methods (SNM)</td>
        </tr>
    </table>
    <br>
    <br>
</body>
</html>
```
# OUTPUT

[alt text](<Screenshot 2026-11-23 213158.png>)

# RESULT!
The program for creating slot timetable using basic HTML tags is executed successfully.
