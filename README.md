<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Task Login Form</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="container">
        <form action="" id="form">
            <h1>REGISTER FORM</h1>
            <div class="input-group">
                <label for="username">Username</label>
                <input type="text" id="username" name="username">
                <div class="error"></div>
            </div>
            <div class="input-group">
                <label for="password">Password</label>
                <input type="password" id="password" name="password" autocomplete="current-password">
                <div class="error"></div>
            </div>
            <button type="submit" value="button">Login</button>
            <a href="todolist.htm"></a>
            <p>Create your account!If u don't have!</p>
            <a href="signup.htm"><button type="button" target="_blank"> SignUp</button></a>
        </form>
    </div>
    <script src="script.js"></script>
</body>

</html>
