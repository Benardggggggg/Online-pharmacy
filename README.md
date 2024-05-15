# Online-pharmacy
<!DOCTYPE html>
<html>
<head>
  <title>ONLINE PHERMACY</title>
  <style>
     {
      font-family: Arial, sans-serif;
    }
 
    h1 {
      color: blue;
      text-align: center;
    }
    
  h2{
    color:green;
    text-align:center;
    
  }
    .menu {
      background-color: green;
      padding: 8px;
      text-align: center;
      
    }
    
    .menu ul {
      list-style-type: none;
      margin: 0;
      padding: 0;
    }
    
    .menu li {
      display: inline-block;
      margin-right: 10px;
    }
    
    .menu a {
      color: #333;
      text-decoration: none;
      padding: 5px 10px;
      border-radius: 5px;
    }
    
    .menu a:hover {
      background-color: green;
      color: red;
    }
    
    .content-section {
      display: none;
      padding: 20px;
    }
    
    .recycling {
      color: #ff7f50;
    }
    
  
  
  .reuse {
      color: green;
    }
    
    .services {
      color: blue;
    }
  </style>
  <script>
    // JavaScript to toggle display of content sections
    function showSection(sectionId)

{
      var sections = document.getElementsByClassName('content-section');
      for (var i = 0; i < sections.length; i++) {
        sections[i].style.display = 'none';
      }
      
      var section = document.getElementById(sectionId);
      section.style.display = 'block';
    }
  </script>
</head>
 
<body>
  <h1>ONLINE PHAMACY</h1>

   <p></p>
  <img src="ki.jpg"alt="img"style="width:50%";height:auto;">
    
  <div class="menu">
    <ul>
      <p>
      <li><a href="#" onclick="showSection('login')">LOGIN</a></li>
      <li><a href="#" onclick="showSection('home')"> HOME</a></li>
       <li><a href="#" onclick="showSection('user feedback')">USER FEEDBACK</a></li>
      <li><a href="#" onclick="showSection('categories of medicine')">CATEGORIES OF MEDICINE</a></li>
      </p>
    </ul>
  </div>
  <main>
    <section id="login" class="content-section">
      
      <h3>LOG IN</h3>

   <html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Login Form</title>
  
</head>
<body>
  <form action="process_login.php" method="post">
    
   
   <title>Login Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
    }
    
    .login-container {
      background-color: orangered;
      padding: 20px;
      border-radius: 5px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      max-width: 400px;
      margin: 0 auto;
      margin-top: 50px;
    }
    
    input[type=text], input[type=password] {
      width: 100%;
      padding: 12px 20px;
      margin: 8px 0;
      display: inline-block;
      border: 1px solid #ccc;
      border-radius: 4px;
      box-sizing: border-box;
    }
    
    button {
      background-color: #4CAF50;
      color: white;
      padding: 14px 20px;
      margin: 8px 0;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      width: 100%;
    }
    
    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>
  <div class="login-container">
    <h2>Login</h2>
    <form>
      <label for="username">Username:</label>
      <input type="text" id="username" name="username" placeholder="Enter your username" required>
      
      <label for="password">Password:</label>
      <input type="password" id="password" name="password" placeholder="Enter your password" required>
      
      <button type="submit">Login</button>
    </form>Forgot password
  </div>
  </form>
</body>
     
    
   

  <title>Create Account</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
    }
    
    .signup-container {
      background-color: orangered;
      padding: 20px;
      border-radius: 5px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      max-width: 400px;
      margin: 0 auto;
      margin-top: 50px;
    }
    
    input[type=text], input[type=email], input[type=password] {
      width: 100%;
      padding: 12px 20px;
      margin: 8px 0;
      display: inline-block;
      border: 1px solid #ccc;
      border-radius: 4px;
      box-sizing: border-box;
    }
    
    button {
      background-color: #4CAF50;
      color: white;
      padding: 14px 20px;
      margin: 8px 0;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      width: 100%;
    }
    
    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>
  <div class="signup-container">
    <h2>Create Account</h2>
    <form>
      <label for="first_name">First Name:</label>
      <input type="text" id="first_name" name="first_name" placeholder="Enter your first name" required>
      
      <label for="last_name">Last Name:</label>
      <input type="text" id="last_name" name="last_name" placeholder="Enter your last name" required>
      
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" placeholder="Enter your email" required>
      
      <label for="password">Password:</label>
      <input type="password" id="password" name="password" placeholder="Enter your password" required>
      
      <button type="submit">Create Account</button>
    </form>
  </div>
</body>
</html>
    </section>
     
    
    <section id="categories of medicine" class="content-section">
  <h2>CATEGORIES OF MEDICINE</h2>
  <div class="services"> 
    <p><a href="#antipyretics">1. ANTIPYRETICS</a></p>
    <p><a href="#analgesics">2. ANALGESICS</a></p>
    <p><a href="#antibiotics">3. ANTIBIOTICS</a></p>
    <p><a href="#mood-stabilizers">4. MOOD STABILISERS</a></p>
  
    
    
    
    
    <section id="antipyretics">
   <img src="c+.jpg" alt="First Image" class="image" alt="img"style="width:40%";height:auto;">
  
</section>

<section id="analgesics">
   <img src="c++.jpg" alt="First Image" class="image" alt="img"style="width:40%";height:auto;">
  
</section>

<section id="antibiotics">
   <img src="c+++.jpg" alt="First Image" class="image" alt="img"style="width:40%";height:auto;">
  
</section>

<section id="mood-stabilizers">
   <img src="d+.jpg" alt="First Image" class="image" alt="img"style="width:40%";height:auto;">
  
</section>
    
    
    
    
    
    <div class="container">
 
  <img src="c++.jpg" alt="Second Image" class="image" alt="img"style="width:40%";height:auto;">
    <img src="c+++.jpg" alt="First Image" class="image" alt="img"style="width:40%";height:auto;">
  
  <img src="d+.jpg" alt="Second Image" class="image" alt="img"style="width:40%";height:auto;">
    
      
      </div>
    </section>
    
    
    <section id="user feedback" class="content-section">
     <img src="kii.jpg" alt="First Image" class="image" alt="img"style="width:40%";height:auto;">
  
      <h2>user feedback</h2>
    
      <div class="services"> 
  <p>Many people have tried and now believe

we are doing the best of this kind .

<p>Have many witnesses across the world:
</p>
<p>Mbarara
</p>
  <p>Jinja
</p>
<p>Kampala
</p>
<p>Masaka.</p>
      </d>
   </section>
    
    <section id="home" class="content-section">
      <h2>HOME</h2>
      <div class="services">
    <form action="/search" method="get">
  <input type="search" name="q" placeholder="Search...">
  <input type="submit" value="Search">

  <button>Add to Cart</button>
  <img src="med.jpg" alt="222">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Payment Methods</title>
</head>
<body>
    <h1>Choose your payment method:</h1>
    <ul>
        <li><a href="https://example.com/airtel money"><img src="air.jpg" alt="222"></a></li>
        <li><a href="https://example.com/mtn money"><img src="ttn.png" alt="444"></a></li>
        <li><a href="https://example.com/mastercard/VISA"><img src="msv.jpg" alt="333"></a></li>
        
        
        <!-- Add more payment methods as needed -->
    </ul>
</body>
</form>

     <img src="ki.jpg"alt="img"style="width:40%";height:auto;">
    
 
  <section id="user feed back" class="content-section">
      <h2>USER FEED BACK</h2>
      <div class="services">
        <p>Many people have tried and now believe

we are doing the best of this kind .

Have many witnesses across the world:

Mbarara

Jinja

Kampala

Masaka.</p>
        <img src="b+.jpg"alt="img"style="width:100%";height:auto;">
      
  
  </main>
  <footer>
    <section id="contact">
    <h2>Contact Us</h2>
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required><br>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required><br>
        <label for="message">Message:</label><br>
        <textarea id="message" name="message" rows="4" required></textarea><br>
        <input type="submit" value="Submit">
    </form>
</section>
    <p>&copy; 24/7 Online Pharmacy. All rights reserved.</p>
    <p>ephamarcy@tweet</P>
    <p>ephamarcy@gmail.com</p>
</footer>
</body>
</html>
