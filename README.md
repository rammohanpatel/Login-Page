# Login-Page

//HTML CODE

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="login.css">
    <title>Login Page</title>
</head>
<body>
    <div class="loginbox">
        <img src="imgport/login2.png" class="avatar">
        <h1>Login Here</h1>
        <form >
            <p>Username</p>
            <input type="text" placeholder="Enter Username">
            <p>Password</p>
            <input type="password" placeholder="Enter Password">
            <input type="submit" value="Login"><br>
            <a href="#">Lost Your Password</a><br>
            <a href="#">Don't have an account</a>

        </form>
    
    </div>
    
</body>
</html>

//CSS


*{
    margin: 0;
    padding: 0;
    font-family: sans-serif,'Poppins';
}

body{
    background:url(imgport/login1.webp)
}
.loginbox{
    width: 320px;
    height: 420px;
    background: #000;
    color: #fff;
    top: 50%;
    left: 50%;
    position: absolute;
    transform: translate(-50%,-50%);
    box-sizing: border-box;
    padding: 70px 30px;
    border-radius: 30px;
}
.avatar{
    width: 100px;
    height:100px  ;
    position: absolute;
    top: -50px;
    left: calc(50% - 50px);   
}
h1{
    margin: 0;
    padding:0 0 20px;
    text-align: center;
    font-size: 28px;
}
.loginbox p{
    margin: 0;
    padding: 0;
    font-weight: bold;
}
.loginbox input{
    width: 100%;
    margin-bottom: 20px;
}
.loginbox input[type="text"],input[type="password"]
{
    border: none;
    border-bottom: 1px solid #fff;
    background: transparent;
    outline:none;
    height:40px;
    color: #fff;
    font-size: 16px;
}
.loginbox input[type="submit"]
{
    outline: none;
    border: none;
    height: 40px;
    background: #fb2525;
    color: #fff;
    font-size: 18px;
    border-radius: 20px;
}
.loginbox input[type="submit"]:hover{
    cursor: pointer;
    background: #ffc107;
    color: #000;
}
.loginbox a{
    font-size:15px;
    line-height:20px;
    color: darkgrey;
}
.loginbox a:hover{
    cursor: pointer;/*No need to write cursor because it's already an anchor tag*/
    color: #ffc107;
}
