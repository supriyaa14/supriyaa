# supriyaa
<html>
    <head>
        <title>REGISTERATION</title>
        <link rel="stylesheet" href="reg.css"> 
    </head>
    <body class="main">
      <div class="bg-img">
        <div class="container">
          <form action="connection.php" method="post">
            <h2><B>Register ACCOUNT</B></h2>
            <p><h3><b><i>||Please fill in this form to create an account||</i></h3></b></p>
            <label for="username"><b>User Name</b></label>
            <input type="text" id="UserName" name="UserName" class="form-control"  autofocus placeholder="required">          
            <label for="dateofbirth"><b>Date of Birth</b></label><br>
            <input type="date" name="DateofBirth" id="DateofBirth" placeholder="required" required >
            <label for="gender"><b>Gender</b><br></label>
            <div class="col-75">
              <select id="ft" name="gender">
                <option  value="male">male</option>
                <option value="female">female</option>
                <option value="other">other</option>
              </select>
            </div>
            <label for="state"><b>State</b></label>
            <input type="text" name="state" id="state" placeholder="required" required>
            <label for="district"><b>District</b></label>
            <input type="text" name="district" id="district" placeholder="required" required>
            <label for="address"><b>Address</b></label>
            <input type="text" name="address" id="address" placeholder="required" required>
            <label for="aadharno"><b>Aadhar Number</b></label>
            <input type="number" name="Aadharno" id="Aadharno" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}" required>
            <label for="mobileno"><b>Phone Number</b></label>
            <input type="number" name="Mobileno" id="Mobileno" placeholder="required" required>
            <label for="email"><b>Email</b></label>
            <input type="text" placeholder="Enter Email" name="email" id="email" required>
            <label for="psw"><b>New Password</b></label>
