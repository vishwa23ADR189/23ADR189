<html>
<head> <title> Register </title>  </head>
<style>
body{background: linear-gradient(orange,white,green);}
</style>
<body>
<h1> REGISTER </h1>
<form> 

<label for="fname">Name:</label> <br>
<input type = "text" id = "fname"Name = "fname"placeholder = "Enter your Name"><br><br>

<label for="dob">DOB:</label><br>
<input type = "date" id = "dob" name ="dob" required/><br><br>

<label for="email">Enter your Email: </label><br>
<input id="email" name="email" type="email"placeholder = "abc@gmail.com" required/><br><br>
<label for="Phone no">Enter your phone no: </label><br>
<input id="tel" name="phone no" type="phone no"placeholder = "+91" required/><br><br>
<label for="password">Enter your Password: </label><br>
<input id="password" name="password" type="password" placeholder = "Enter your Password" required/><br><br>
<label for="confirm password">Re-enter your Password: </label><br>
<input id="password" name="password" type="password"placeholder = "re-enter your Password " required/><br><br>
<label for="Address">Address:</label><br>
<textarea  id = "msg" id = "address" name ="address" rows = "3", cols = "20" placeholder = "1\a summerstreet,ocktown,New jersey" required></textarea><br>

<h4>GENDER: </h4>
<input type="radio" id = "male" name = "gender"  checked/></label>
<label  for ="male">Male</label><br>
<input type="radio" id = "female" name = "gender" ></label>
<label  for ="Gender">Female</label><br>
<input type="radio" id = "other" name = "gender" ></label>
<label  for ="Gender">Other</label><br>

<label for = "profile-picture">Upload a profile picture:
<input id ="Profile-picture" type="file" name ="file" />
</label><br><br>

<label for= "nation">Enter your nationality (native)
<select id="state" name="state"
<option value = "">(select one)</option>
<option value = "1">India</option>
<option value = "2">American</option>
<option value = "3">Africa</option>
<option value = "4">Austrila</option>
<option value = "5">Sri Lankan</option>
</select><br><br>

<h4>COURSE: </h4>
<input type="checkbox" id = "vehicle1" name = "course1"  required></label>
<label  for ="course1">MODE</label><br>
<input type="checkbox" id = "vehicle2" name = "course2"  required></label>
<label  for ="course2">EIT</label><br>
<input type="checkbox" id = "vehicle3" name = "course3"  required></label>
<label  for ="course3">PHY</label><br><br>


<input type="submit" value ="submit"/>

</form>


