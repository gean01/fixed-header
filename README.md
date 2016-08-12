# fixed-header
A jQuery plugin to create tables with fixed header.

```html
<html>
<head>
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
	<script src="./fixedHeader.js"></script>
</head>
<body>
	<div id="box">
		<table id="my_table">
			<tr>
				<th>Header 1</th>
				<th>Header 2</th>
			</tr>
			<tr>
				<td>Row 1, Column 1</td>
				<td>Row 1, Column 2</td>
			</tr>
    </table>
	</div>
	<script>
	$("#my_table").fixedHeader(100);// 100 px of height for the table
	</script>
</body>
</html>
```
