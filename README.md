Good Day!

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Sandbox</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

    <header class="main-header title" id="headermain">
        <div class="header">
          
        </div>
    </header>
    <section>
        <img src="data:image/jpeg;base64,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
        
        J+9ZEkgHMwXTBcGDMDkBtGmfrY8YkeUqdtIMva0gkCcJDhGohsgTpOfOU2O+kZ/Z7XDpqNLvJhg4RkXzlgMSCyZxTB0yjmwwyFf12Wu0WYsbUDamJ2WJzGuYAWtJdT8zXSGVMtDLcwuprJxptGRuu2BtMstEPbSLXYnOew1DicXEOBLh
        i8MSc8IMRKZQwzWbPemIA1aJBLcw3DhAbmXeUk57CJ2LE9EekWdwWa0U6ZZaXh7g44SC53lOYBLhJIzzJO2mi48dj1HPcs1w6EAQBAEAQBAEAQBAEAQBAEAQBAEAQBAEAQBAEAQBAEAQBAEAQBAEAQBAEAQBAEAQBAEAQBAEAQBAEAQB
        Af/9k=" alt="Welcome!img">
        <p>Welcome! This is the form where we check to see if you did the assignments or your Attendance. If you have any questions, ask "Soliyana", or "Meta"</p>
        
        <form>
            <label for="First Name">First Name</label>
            <input type="text" placeholder="Enter First Name">

            <label for="Last Name">Last name</label>
            <input type="text" placeholder="Enter Last Name">
            
            <label for="Age">Age</label>
            <input type="text" placeholder="Enter Age">

            <label for="Email">Email</label>
            <input type="email" placeholder="Enter Parents Email">
            <br>
            <br>
            <br><br>
            <p>How happy are you today?</p>
            <br>
            <select>
                <option value="" disabled selected>--Select</option>
                <option value="">Good! =)</option>
                <option value="">Okay =|</option>
                <option value="">Bad =(</option>
            </select>
           <nav>
               <ul>
                   <br>
                   <li><a href="hi.html">Submit</a></li>
               </ul>
           </nav>
        </form>
        <br>
        <br>
<hr>
<footer>

    
<br><br><br><br><br><br><br><br><br><br><br>
<h2>Created by: Nebiyu</h2>
<h4>Be sure to credit me if you want to use this webpage!</h4>
<br>
<hr>
<p>DISCLAIMER:</p>
<p>Please read and type everything correctly, this is an eraly form and I will update the website soon. Dont make any mistakes! </p>
<hr>
<br><br>
    <p>Copyright &copy; 2020; All Rights Reserved</p>
</footer>

