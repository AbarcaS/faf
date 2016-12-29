
# Find A Friend
_Developers: Sam A., Cris G., Emilia and Mimi_

###Pages
* Home - Dashboard
* Profile
* GoHunting
* LetsPlan
* Make and share a playlist
* Sign Up
* Log In

### Techdetail
sams_lib.php 
$dbh //database
$_SESSION

### Work
* HomePage
* SignUp
* Sign

index.php
<signin form action="signup.php">
<signup form action="signup.php">
<PHP- Select * from profiles limit 10>


signup.php
<php check $_POST
check if someone used the email already using a select statement where email = ""
insert the info they gave you in the profile , insert statement
(redirect them to index.php) - header( 'Location: index.php' ) ;
>

signin.php
<php check $_POST
check if some email and password combination exists - select * from profiles where email = "" and password = "";
if the last statement comes back with 1 row you are loged in
save the session ( i will teach you this  $_SESSION)
(redirect them to index.php) - header( 'Location: index.php' ) ;






