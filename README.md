<!DOCTYPE html>
<html>
<head>
	<title>CGPA Calculator</title>
</head>
<body>
	<h1>CGPA Calculator</h1>
	<table>
		<tr>
			<th>Course</th>
			<th>Credit Hours</th>
			<th>Grade</th>
		</tr>
		<tr>
			<td><input type="text" id="course1"></td>
			<td><input type="number" id="credit-hours1" placeholder="Enter credit hours"></td>
			<td>
				<select id="grade1">
					<option value="A">A (4.0)</option>
					<option value="B">B (3.0)</option>
					<option value="C">C (2.0)</option>
					<option value="D">D (1.0)</option>
					<option value="F">F (0.0)</option>
				</select>
			</td>
		</tr>
		<tr>
			<td><input type="text" id="course2"></td>
			<td><input type="number" id="credit-hours2" placeholder="Enter credit hours"></td>
			<td>
				<select id="grade2">
					<option value="A">A (4.0)</option>
					<option value="B">B (3.0)</option>
					<option value="C">C (2.0)</option>
					<option value="D">D (1.0)</option>
					<option value="F">F (0.0)</option>
				</select>
			</td>
		</tr>
		<!-- Add more rows as needed -->
	</table>
	<button onclick="calculateCGPA()">Calculate CGPA</button>
	<p id="result"></p>

	<script src="script.js"></script>
</body>
</html>
```

<!---
MrCatastrophy/MrCatastrophy is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
