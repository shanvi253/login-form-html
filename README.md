# Html-form-layout
Sample HTML code showing how to build a user input form, including text fields, dropdowns, and buttons.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form action="submit.php" method="post">
        <fieldset>
<label for="username"> Name:</label>
<input type="text" id="username" name="username"
placeholder="Enter your name">
<br><br>


<label for="userage">Age:</label>
<input type="number" id="userage" name="age" min="1" max="100">
<br><br>


<label for="email">Email:</label>
<input type="email" id="email" age="email"
placeholder="Enter your email">
<br><br>


<input type="password" name="pwd" placeholder="Enter password" style="width:200px; height:200px;">
<br><br>


<input type="radio" name="gender" value="female">female
<input type="radio" name="gender" value="male">Male<br><br>
<input type="checkbox" name="subscribe">Subscribe to Newsletter <br><br>
<input  type="checkbox" name="Subscribe">Okay<br><br>
<input type="submit" value="Submit"><br><br>
<textarea name="message" rows="4" cols="50">
            Enter message 
</textarea><br><br>


<button type="submit">Submit Form</button><br><br>
<button type="reset">Reset</button><br><br>
<button type="button" onclick="alert('Custom Action!')">Click</button><br><br>


<select name="country" id="country"> <!--dropdown box-->
    <option value=""selected disabled>select a country</option>
    <option value="India">India</option>
    <option value="UK">UK</option>
    <option value="Australia">Australia</option>
    <option value="USA">USA</option>
</select><br><br>

 <select name="skills" multiple size="4">
    <option value="java">java script</option>
    <option value="html">Html</option>
    <option value="css">CSS</option>
    <option value="python">Python</option>
    <option value="php">Php</option>
    <option value="pl/sql">PL/SQL</option>
    </select><br><br>

    <select name="language" multiple size="4">
        <option value="hindi">Hindi</option>
    <option value="tamil">Tamil</option>
    <option value="telgu">Telgu</option>
    <option value="english">English</option>
    <option value="marathi">Marathi</option>
    <option value="punjabi">Punjabi</option>
    </select><br><br>

    <label for="resume">select a file:</label> <!--for choose a file-->
<input type="file" id="resume" name="resume"><br><br>
</body>
</html>
