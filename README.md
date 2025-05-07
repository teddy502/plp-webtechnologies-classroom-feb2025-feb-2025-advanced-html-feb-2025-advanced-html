# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body style="background-image: url('pexels-maz-tik-122922125-30445795 (1).jpg'); 
             background-size: cover; 
             background-repeat: no-repeat;
             background-position: center;">
 <!--this is an ordered list-->
<ol type=i>
<li>Teddy</li>
<li>Brian</li>
<li>Samwel</li>
<li>Henk</li>
<li>Alex</li> 
</ol>
 <!--table containing 5 contacts and their information-->
 <table border="1">
  <caption>Teachers' Details</caption>
  <tr>
   <th>name</th>
   <th>Address</th>
   <th>Mobile No</th>
   <th>Email</th> 
  </tr>
  <tr>
   <td>Teddy</td>
   <td>N230</td>
   <td>+254718963042</td>
   <td>teddn230@gmail.com</td>
  </tr>
   <tr>
   <td>Brian</td>
   <td>M24</td>
   <td>+254790245782</td>
   <td>brianm24@gmail.com</td>
  </tr>
   <tr>
   <td>Samwel</td>
   <td>2N8</td>
   <td>+254764729332</td>
   <td>samwel2n8@gmail.com</td>
  </tr>
   <tr>
   <td>Henk</td>
   <td>534U</td>
   <td>+254725798340</td>
   <td>henk534u@gmail.com</td>
  </tr>
   <tr>
   <td>Alex</td>
   <td>N238</td>
   <td>+254718963042</td>
   <td>henkn238@gmail.com</td>
  </tr>  
 </table>
 <form>
 <h3>This is a registration form </h3>
<!--name-->
<label>Name</label>
<input type="text" placeholder="enter your name">
<br>
<!--email-->
<label>email</label>
<input type="email" placeholder="enter your email">
<br>
<!--password-->
<label>password</label>
<input type="password" placeholder="insert your password">
<br>
 <!--date-->
<input type="date">
<br>
<!--dropdown-->
<label for="langages">Language</label>
<select name="languages" id="languages" multiple>
  <option value="english">English</option>
  <option value="swahili">swahili</option>
  <option value="french">French</option>
</select>
<br>
<!--radio-buttons-->
<p>please select your gender></p>
<input type="radio" name="gender" value="Male">
Male <br>
<input type="radio" name="gender" value="Female">
Female <br>
<input type="radio" name="gender" value="Others">
Others <br>
<!--checkboxes-->
<p>Choose your hobbies:</p>
<label><input type="checkbox" name="hobby" value="reading"> Reading</label><br>
<label><input type="checkbox" name="hobby" value="sports"> Sports</label><br>
<label><input type="checkbox" name="hobby" value="music"> Music</label><br>

 <!--button-->
 <button>submit</button>
</form>
</body>
</html>
