# Login-page
A sample of login page using Html/Css

 ```
# Login Basic

This is a simple login form built using HTML and CSS. It includes fields for username, password, and phone number, as well as a submit button and a link to a registration page.

## Getting Started

To use this login form, you will need to create a new HTML file and add the following code:

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Login basic</title>
        <link href="style.css" rel="stylesheet"/>
    </head>
    <body>
        <!-- <div class="navbar_Menu">
            <ul>
                <li>About Us</li>
                <li>Help</li>
                <li>Services</li>
                <li>Contact Us</li>
                </div> -->
        
            <h1>Login form using HTML and CSS</h1>
    <form action="">
        <!-- Headings for the form -->
        <div class="headingsContainer">
            <h3>Sign in</h3>
        </div>

        <!-- Main container for all inputs -->
        <div class="mainContainer">
            <!-- Username -->
            <label for="username">Your username</label>
            <input type="text" placeholder="Enter Username" name="username" required>

            <br><br>

            <!-- Password -->
            <label for="pswrd">Your password</label>
            <input type="password" placeholder="Enter Password" name="pswrd" required>

            <br><br>
            <label for="number">Enter Your Phone Number</label>
            <input type="number" placeholder="Enter Your Number" name="Number" required > <br>

            <!-- Submit button -->
            <label for="Click"> Click Here For </label>
             <button type="submit">Login</button>

            <!-- Sign up link -->
            <p class="register">Not a member?  <a href="#">Register here!</a></p>
        </div>
        
            
           
        </form>
        
    </
