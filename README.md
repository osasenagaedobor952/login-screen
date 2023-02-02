<!DOCTYPE html>
<html>
<head>
   <title>Bolt login page</title>
</head>
</html>
<style>
  /*CSS styles for the page*/
  body{
    text-align: center;
    margin: 20px;
  }
  input[type="number"], input[type="number"] {
      width: 50%;
      padding: 12px 20px;
      margin: 0px;
      box-sizing: border-box;
      border-radius: 5px;
      background-color: rgb(239, 238, 238);
      border: none;
    }
  button{
        background: #ffffff;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        width: 55%;
        height: 36px;
        margin: 7px;
        border: 1px solid rgb(215, 215, 215);
        outline: none;
        color: #000000;
        font-size: 0.8rem;
        cursor: pointer;
        box-shadow: inset 0 0 0 #23c403;
        transition: ease-out 0.6s;
        border-radius: 16px;
        opacity: 50%;
      }
      button:hover{
        box-shadow: inset 500px 0 0 0 #ffffff;
        color: #000;
        opacity: 100%;
      }
      p{
        font-size: 11px;
        opacity: 60%;
      }
      input[type="submit"] {
      width: 55%;
      height: 36px;
      font-size: 0.7rem;
      color: white;
      padding: 14px 20px;
      margin: 7px;
      border: none;
      border-radius: 16px;
      cursor: pointer;
      background: #21b603;
      }
      .container{
        font-size: larger;
        font-family: copperplate;
      }
</style>
<body>
<div class="container">
    <h4>Enter your number</h4>
</div>
    <form>
        <label for="number"></label>
        <input type="number" id="number" name="number" placeholder="+234 8023456789" required>
        <input type="submit" value="Sign in">
    </form>
    <p>OR</p>
    <a href="www.google.com">
    <button>Sign in with Google</button>
    </a>

    <a href="www.facebook.com">
    <button>Sign in with Facebook</button>
    </a>

    <a href="www.apple.com">
      <button>Sign in with Apple</button>
      </a>

    <p>if you are creating a new account,Terms & conditions and<br> privacy policy will apply</p>
</body>
</div>
