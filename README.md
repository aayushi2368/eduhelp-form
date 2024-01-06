<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>EDU HELP</title>
    <link rel="stylesheet" href="style.css">
    <link rel="icon" href="https://media.licdn.com/dms/image/C511BAQG-PFkwuM_s3w/company-background_10000/0/1583926892097/iitism_cover?e=2147483647&v=beta&t=RBGRoORbLHALLZzFZtLp0r8HKeul8j47mPcRJIgerLI">
    <link rel="" href="<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display:ital@1&family=Montserrat:ital,wght@1,900&family=Sacramento&family=Ubuntu:ital,wght@1,300&display=swap" rel="stylesheet">

  </head>
  <body>
    <center>
   <img src="https://d2lk14jtvqry1q.cloudfront.net/media/small_Department_of_Management_Studies_IIT_Dhanbad_ae040bdd59_00524faa81_587e594e98_3dd33e6e60_8561d0e94d.png">

 </center>

 <div class="Container">
 <h1>Sign Up</h1>


   <form action="action_page.php" style="border:1px solid #ccc">
   <label for="email"><b>Email</b></label>
   <input type="text" placeholder="Email" class="text-field" name="email" required>
   <h2> </h2>
   <label for="password"><b>Password</b1></label>
   <input type="text" placeholder="Password" name>
   <h3></h3>
   <label for="Confirm password"><b>Confirm Password</b></label>
   <input type="text" placeholder="Confirm Password">
   <label>
     <h3></h3>
      <button type="submit" class="Signup">Sign up</button>
   </form>
   </div>
<script type="module">
  // Import the functions you need from the SDKs you need
  import { initializeApp } from "https://www.gstatic.com/firebasejs/10.7.1/firebase-app.js";
  import{
    getauth,
    createUserwithEmailandPassword,
    SignUpwithEmailandPassword,
    onAuthStateChanged,
  }
    "https://www.gstatic.com/firebasejs/10.7.1/firebase-authentication.js";

  // TODO: Add SDKs for Firebase products that you want to use
  // https://firebase.google.com/docs/web/setup#available-libraries

  // Your web app's Firebase configuration
  const firebaseConfig = {
    apiKey: "AIzaSyBWygcJ-PcwshCxfhoKLoM9mOEtVCddgJY",
    authDomain: "authentication-a3190.firebaseapp.com",
    databaseURL: "https://authentication-a3190-default-rtdb.firebaseio.com",
    projectId: "authentication-a3190",
    storageBucket: "authentication-a3190.appspot.com",
    messagingSenderId: "345435982311",
    appId: "1:345435982311:web:5aa0a5e90e85a3e8c45542"
  };

  // Initialize Firebase
  const app = initializeApp(firebaseConfig);
  const auth=getAuth(app);

  const userEmail=document.querySelecto("#userEmail");
  const userPassword=document.querySelector("#userPassword");
  const authenticationForm=document.querySelector("#authenticationForm");
  const secretContent=document.querySelector("#secretContent");
  const signUpButton=document.querySelector("#signUpButton");

  secretContent.style.display='none';



</script>


 </body>

</html>
