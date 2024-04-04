#### Name : Ajay Surya S
#### Reg No : 212221040009

# Ex03 Time Table
## Date: 04.04.2024

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
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Timetable</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        h1 {
            color: #333;
            text-align: center;
            margin-top: 20px;
        }
        table {
            width: 80%;
            margin: 20px auto;
            border-collapse: collapse;
            border: 2px solid #444;
            border-radius: 8px;
        }
        th, td {
            padding: 12px;
            text-align: center;
            border: 1px solid #ddd;
        }
        th {
            background-color: #FF5733;
            color: white;
        }
        td {
            background-color: #FFF;
        }
        td.lunch {
            background-color: #FFFF00;
        }
        img {
            display: block;
            margin: 20px auto;
            max-width: 300px;
        }
    </style>
</head>
<body>
    <img src="saveethalogo.png" alt="Saveetha Logo">
    <h1>SLOT TIME TABLE - AJAY SURYA S (21222104009)</h1>
    <table>
        <tr>
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr>
            <td>8-10</td>
            <td>MAD</td>
            <td>WEB</td>
            <td>MPMC</td>
            <td>MAD</td>
            <td>CE</td>
        </tr>
        <tr>
            <td>10-12</td>
            <td>FREE</td>
            <td>MPMC</td>
            <td>IOT</td>
            <td>CE</td>
            <td>MPMC</td>
        </tr>
        <tr>
            <td class="lunch" colspan="6">LUNCH</td>
        </tr>
        <tr>
            <td>1-3</td>
            <td>IOT</td>
            <td>IPR</td>
            <td>WEB</td>
            <td>CNS</td>
            <td>CNS</td>
        </tr>
        <tr>
            <td>3-5</td>
            <td>FREE</td>
            <td>FREE</td>
            <td>IPR</td>
            <td>FREE</td>
            <td>WEB</td>
        </tr>
    </table>

    <table>
        <tr>
            <th>S.NO</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (WEB)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19CS412</td>
            <td>Cryptography and Network Security (CNS)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19EC408</td>
            <td>Microprocessor and Microcontroller (MPMC)</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19EC307</td>
            <td>Communication Engineering (CE)</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19ME531</td>
            <td>Intellectual Property Rights (IPR)</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19CS420</td>
            <td>Prototyping of IoT Systems (IOT)</td>
        </tr>
        <tr>
            <td>7.</td>
            <td>19CS420</td>
            <td>Mobile Application Development (MAD)</td>
        </tr>
    </table>
</body>
</html>

```

## OUTPUT

![Screenshot 2024-04-04 220810](https://github.com/AjaysuryaS/TimeTable/assets/114158396/3f50e498-2e75-41be-a598-d05d7ea32ce4)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
