# student-survey
<!DOCTYPE HTML>
<html>
<head>
<title>Student Interest Survey</title>
  <style>
    body{
        background-color: brown;
    }
    h1 {
        color: royalblue;
    }
</style>
</head>
<body>
<div align="center">
<h1>Student Interest Survey form</h1>
Enter your name:
<input type="text" name="UserName" size=35 maxlength=35 value="">
</br></br>
Enter your department:
<input type="text" name="Dept" size=35 maxlength=35 value=""> </br> </br>
Tell us a little about yourself:
<textarea name="Comments" cols=30 rows=4></textarea> </br> </br>
Do you exercise at home?
<input type="radio" name="exe" value=1>Yes
<input type="radio" name="exe" value=2>No
</p>
How do you like to read about your favorite topics?
<p>
<input type="checkbox" name="Books">Books
<input type="checkbox" name="Online resources">Online resources
<input type="checkbox" name="Phone apps">Phone apps
<input type="checkbox" name="Magazines">Magazines
</p>
What genre of movies do you like?
<select name="moviepref" ><option>
<option value=1 selected = "true">comedy 
<option value=2 >romance
<option value=3 >thriller
<option value=4 >horror
<option value=5 >biopic
</select>
</br></br>
<input type=submit value="Submit form">
</div>
</form>
</body>
</html>
