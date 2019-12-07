1. First ordered list item
2. Another item
⋅⋅* Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
⋅⋅1. Ordered sub-list
4. And another item.
# [Home](homepage.md)

<!DOCTYPE html>
<html>
<body>
	<h1>Demo: JavaScript function parameters</h1>
	
	<script>
		function ShowMessage(firstName, lastName) {
			alert("Hello " + firstName + " " + lastName);
		}

		ShowMessage("Steve", "Jobs");
		ShowMessage("Bill", "Gates");
		ShowMessage(100, 200);

    </script>
</body>
</html>
