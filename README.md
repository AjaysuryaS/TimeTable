#### Name : Kanmani U
#### Reg No : 212221040070

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
</head>
<body style="display: flex; flex-direction: column; align-items: center; font-size: 1.5rem;">
    <img src="saveethalogo.png" width="40%">
    <h1>KANMANI U (212221040070)</h1>
	<table border='3'  cellspacing="4" cellpadding='4'   style="width: 50%;"  >
		<tr bgcolor="purple">
			<th>Day/Time</th>
			<th>Monday</th>
			<th>Tuesday</th>
			<th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
		</tr>
		<tr>
			<td bgcolor="purple">8-10</td>
			<td>MAD</td>
			<td>WEB</td>
            <td>MPMC</td>
            <td>MAD</td>
            <td>CE</td>
		</tr>

		<tr>
            <td bgcolor="purple">10-12</td>
			<td>FREE</td>
			<td>MPMC</td>
			<td>IOT</td>
            <td>CE</td>
			<td>MPMC</td>
		</tr>

		<tr>
            <td bgcolor="purple">12-1</td>
			<td colspan="5" align="center" bgcolor="yellow">LUNCH</td>
			
		</tr>
		<tr>
            <td bgcolor="purple">1-3</td>
			
			<td>IOT</td>
			<td>IPR</td>
			<td>WEB</td>
			<td>CNS</td>
			<td>CNS</td>
		</tr>
		<tr>
            <td bgcolor="purple">3-5</td>
			<td>FREE</td>
			<td>FREE</td>
			<td>IPR</td>
			<td>FREE</td>
			<td>WEB</td>
		</tr>
	</table>
    <br>
    <table border='3' cellspacing="4" cellpadding='4' style="width: 50%;">
		<tr bgcolor="purple">
			<th>S.NO</th>
			<th>Subject code</th>
			<th>Subject Name</th>
			
		</tr>
		<tr>
			<td>1.</td>
			<td>19AI414</td>
            <td>Fundamentals of Web Apllication Development(WEB)</td>
		</tr>

		<tr>
            <td>2.</td>
			<td>19CS412</td>
            <td>Cryptography and Network Security(CNS)</td>
		</tr>

		<tr>
            <td>3.</td>
			<td>19EC408</td>
            <td>Microprocessor and Microcontroller(MPMC)</td>
			
		</tr>
		<tr>
            <td>4.</td>
			<td>19EC307</td>
            <td>Communication Engineering(CE)</td>
		</tr>
		<tr>
            <td>5.</td>
			<td>19ME531</td>
            <td>Intellectual Property Rights(IPR)</td>
		</tr>
        <tr>
            <td>6.</td>
			<td>19CS420</td>
            <td>Prototyping of IOT Systems(IOT)</td>
		</tr>
        <tr>
            <td>7.</td>
			<td>19CS420</td>
            <td>Mobile Application Development(MAD)</td>
		</tr>
	</table>
	</body>
</body>
</html>
```

## OUTPUT
![Screenshot (20)](https://github.com/kanmanikannu/slot/assets/114866367/046b456a-797b-4bc5-a95f-718c36224f36)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
