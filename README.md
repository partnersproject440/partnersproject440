<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <title>GARUDIC Title</title>
    <link
      href="https://fonts.googleapis.com/css2?family=Cinzel:wght@700&display=swap" rel="stylesheet">


    

  <style>
     body {
      background: linear-gradient(135deg, #0f0f0f, #1f1f1f, #3f3f3f);
      color: white;
      font-family: 'Sanas', sans-serif;

    }
   
    .brand-title {
      font-size: 60px; 
      font-weight: bold;
      text-align: center; 
      color: goldenrod; 
      margin-top: 50px;
      letter-spacing: 3px; 
      text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
       font-family: Cinzel, serif;
       transition: color 0.3s ease;
    }

    
     </style>
  </head>
  <body>

  <h1 class="brand-title">GARUDIC</h1>
    
    <title>LOGIN & SIGNUP</title>
  </head>
  <body>
  

    <div style="max-width: 400px; margin: 50px auto; padding: 20px; border: 1px solid #e0e0e0; border-radius: 10px;">
        
        <h2 style="text-align: center;">LOGIN</h2>

        <form action="login.php" method="POST" onsubmit="returnvalidateForm">

            <!-- Email input -->
            <label for="userInput">Username:</label><br>
            <input type="text" id="userInput" name="userInput" placeholder="Username, email address or mobile number" required style="width: 100%; padding: 12px; margin: 8px 0; border: 1px solid #ccc; border-radius: 10px; box-sizing:border-box; font-size: 16px;">
            <div id="error"></div>

                       
            <!-- Password input -->
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required style="width: 100%; padding: 12px; margin: 8px 0; border: 1px solid #ccc; border-radius: 10px; box-sizing: border-box; font-size: 16px;">

            <!-- Submit button -->
            <button type="submit" style="width: 100%; padding: 10px; background-color: #007BFF; color: white; border: none; border-radius: 25px;/* 🎯 Rounded button */">LOGIN</button>
        </form>
        
        <p style="text-align: center; margin-top: 15px;">Don't have an account? <a href="#" style="color: #007BFF;">Sign up here</a></p>
    </div>

    <!-- Signup Page -->
    <div style="max-width: 400px; margin: 50px auto; padding: 20px; border: 1px solid #e0e0e0; border-radius: 10px;">
        
        <h2 style="text-align: center;">SIGNUP</h2>

        <form action="#" method="POST">
            <!-- Name input -->
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required style="width: 100%; padding: 12px; margin: 8px 0; border: 1px solid #ccc; border-radius: 10px; box-sizing: border-box; font-size: 16px;">

            <!-- Email input -->
            <label for="email">Username:</label>
            <input type="Username, email address or mobile number" id="Username, email address or mobile number" name="Username, email address or mobile number" placeholder="Username, email address or mobile number" required style="width: 100%; padding: 12px; margin: 8px 0; border: 1px solid #ccc; border-radius: 10px; box-sizing: border-box; font-size: 16px;">
            
            <!-- Password input -->
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required style="width: 100%; padding: 12px; margin: 8px 0; border: 1px solid #ccc; border-radius: 10px; box-sizing: border-box; font-size: 16px;">
            
            <!-- Confirm password input -->
            <label for="confirm-password">Confirm Password:</label>
            <input type="password" id="confirm-password" name="confirm-password" placeholder="Confirm your password" required style="width: 100%; padding: 12px; margin: 8px 0; border: 1px solid #ccc; border-radius: 10px; box-sizing: border-box; font-size: 16px;">
            
            <!-- Submit button -->
            <button type="submit" style="width: 100%; padding: 10px; background-color: #007BFF; color: white; border: none; border-radius: 25px; /* 🎯 Rounded button */">SIGN UP</button>
        </form>

        <p style="text-align: center; margin-top: 15px;">Already have an account? <a href="#" style="color: #007BFF;">Login here</a></p>
    </div>

</body>
</html>




