App to help our elderly
<html>
<head>
<title>Society App Admin Page</title>
</head>
<body>
<form action="Rkanagaraj19.github.io">
<!-- If we remove this, every thing will move to the left of the page-->
<div align="center">
<!--Adds a heading to the form-->
<h1>Society App Admin Page</h1>
Enter your name:
<!-- Input type text for small texts, specify size -->
<input type="text" name="UserName" size=35 maxlength=35 value="">
<!--Adds spaces - remove and see what happens -->
</br></br>
Enter your Flat number:
<input type="text" name="Deptt" size=35 maxlength=35 value=""> </br> </br>
Tell us a little about yourself:
<!-- For writing lot of text like descriptions with text wrapping,
if you dont want text wrapping, you can add wrap = "off" (horizontal scrollbar -->
<textarea name="Comments" cols=30 rows=4></textarea> </br> </br>
Do you exercise at home?
<!-- Radio buttons help you choose one out of the many values -->
<input type="radio" name="exe" value=1>Yes
<input type="radio" name="exe" value=2>No
</p>
How do you like to read about your favorite topics?
<p>
<!--Checkbox lets you select multiple options -->
<input type="checkbox" name="Books">Books
<input type="checkbox" name="Web">Online resources
<input type="checkbox" name="Phone">Phone apps
<input type="checkbox" name="Magazines">Magazines
</p>
What genre of movies do you like?
<!--Select box lets you choose one of the multiple dropdown options-->
<select name="moviepref" ><option>
<option value=1 selected = "true">comedy
<option value=2 >romance
<option value=3 >thriller
<option value=4 >horror
<option value=5 >biopic
</select>
</br></br>
<!--submits the information entered in the form by the user -->
<input type=submit value="Submit form">
</div>
</form>
</body>
</html>
