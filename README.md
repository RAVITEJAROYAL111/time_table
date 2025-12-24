# Ex02 Time Table
# Date:
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
h2 {
  color: #101011ff;
}
table {
  border-collapse: collapse;
  margin: 25px auto;
  width: 85%;
  background: white;
  box-shadow: 0px 0px 8px rgba(0, 0, 0, 0.2);
  border-radius: 10px;
}

th, td {
  border: 1px solid #555;
  padding: 10px;
  text-align: center;
}

th {
  background-color: #8bd6fcff;
  color: black;
}

td {
  font-weight: bold;
}

tr:nth-child(even) {
  background-color: #f7faf0ff;
}

tr:hover {
  background-color: #88d4f5ff;
}

.sub-table {
  width: 60%;
  margin-top: 30px;
}

.sub-table th {
  background-color: #0c0c0cff;
  color: white;
}

footer {
  margin-top: 20px;
  font-style: italic;
  color: #444;
}
# OUTPUT
<img width="807" height="408" alt="image" src="https://github.com/user-attachments/assets/bca33d7b-254c-425d-bbb7-4d44cf2bc6b9" />

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
