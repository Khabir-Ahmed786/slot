# Ex03 Time Table
# DATE : 
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

## CODE
```
<!DOCTYPE html>
<meta name="viewport">
<img src="download.png" width="500" >

<html>
<head>
    <title>Time Table</title>
    <link rel="stylesheet" href="style.css">
</head>
<body style="background-color: rgb(173, 230, 221);">
    <p>Slot Time Table - Khabir Ahmed B (212221040083) </p>

<table border="1">
    <tr>
        <th style="background-color: violet;">Day/Time</th>
        <th style="background-color: violet;">Monday</th>
        <th style="background-color: violet;">Tuesday</th>
        <th style="background-color: violet;">Wednesday</th>
        <th style="background-color: violet;">Thursday</th>
        <th style="background-color: violet;">Friday</th>
        <th style="background-color: violet;">Saturday</th>
    </tr>
    
    <tr>
        <td style="background-color: yellow;">8-10</td>
        <td style="background-color: rgb(0, 255, 128);"> Free</td>
        <td style="background-color: rgb(0, 255, 128);">Web</td>
        <td style="background-color: rgb(0, 255, 128);">Free</td>
        <td style="background-color: rgb(0, 255, 128);" >Toc</td>
        <td style="background-color: rgb(0, 255, 128);">Free</td>
        <td style="background-color: rgb(0, 255, 128);">Free</td>
    </tr>
    <tr>
        <td style="background-color: yellow;">10-12</td>
        <td style="background-color: rgb(0, 255, 128);">Mern</td>
       <td style="background-color: rgb(0, 255, 128);">Free</td>
       <td style="background-color: rgb(0, 255, 128);">Mern</td>
       <td style="background-color: rgb(0, 255, 128);">TOC</td>
       <td style="background-color: rgb(0, 255, 128);">Mern</td>
       <td style="background-color: rgb(0, 255, 128);">Crypto</td>
    </tr>
    <tr>
        <td bgcolor="yellow">1-3 </td>
        <td style="background-color: rgb(0, 255, 128);">Free</td>
        <td style="background-color: rgb(0, 255, 128);">Mern</td>
        <td style="background-color: rgb(0, 255, 128);">Game</td>
        <td style="background-color: rgb(0, 255, 128);">Game</td>
        <td style="background-color: rgb(0, 255, 128);">Compiler</td>
        <td style="background-color: rgb(0, 255, 128);">Free</td>
    </tr>
    <tr>
        <td style="background-color: yellow;">3-5 </td>
        <td style="background-color: rgb(0, 255, 128);">Crypto</td>
        <td style="background-color: rgb(0, 255, 128);">Compiler</td>
        <td style="background-color: rgb(0, 255, 128);">Compiler</td>
        <td style="background-color: rgb(0, 255, 128);">Web</td>
        <td style="background-color: rgb(0, 255, 128);">Trainning</td>
        <td style="background-color: rgb(0, 255, 128);">Web</td>
    </tr>
    
</table>
<table border="1">
    <br>
<br>

    <tr>
   <td> Crypto - 19CS412 </td>
   </tr>
   <tr>
    <td>Java-19AI413</td>
</tr>
<tr>
    <td>Compiler-19CS409</td>
</tr>
<tr>
    <td>Web - 19AI414</td>
</tr>
<tr>

    <td>TOC-19CS309</td>
</tr>
<tr>
    <td>Game-19AI454</td>
</tr>
</table>


</body>
</html>
```

## OUTPUT
![Alt text](<exp3/ap/static/Screenshot 2023-10-14 154633.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
