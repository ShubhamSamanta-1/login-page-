# login-page-
login page for my farmers portal project 
<!doctype html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>AGRICULTURE  LOGIN</title>
    <style>
        body{
            margin: 0;
            padding: 0;
        }
        body:before{
            content: '';
            position: fixed;
            width: 100vw;
            height: 100vh;
            background-image: url("5.jpg");
            background-position: center center;
            background-repeat: no-repeat;
            background-attachment: fixed;
            background-size: cover;
            -webkit-filter: blur(10px);
            -moz-filter: blur(10px);
            -o-filter: blur(10px);
            -ms-filter: blur(10px);
            filter: blur(10px);
        }
        .contact-form
        {
            position: absolute;
            top: 50%;
            left: 70%;
            transform: translate(-50%,-50%);
            width: 400px;
            height: 500px;
            padding: 80px 40px;
            box-sizing: border-box;
            background: rgba(0,0,0,.5);
        }
        .avatar {
            position: absolute;
            width: 80px;
            height: 80px;
            border-radius: 30%;
            overflow: hidden;
            top: calc(-80px/2);
            left: calc(50% - 40px);
        }
        .contact-form h2 {
            margin: 0;
            padding: 0 0 20px;
            color: #ffffff;
            text-align: center;
            text-transform: uppercase;
        }
        .contact-form p
        {
            margin: 0;
            padding: 0;
            font-weight: bold;
            color: #ffffff;
        }
        .contact-form input
        {
            width: 100%;
            margin-bottom: 20px;
        }
        .contact-form input[type="text",color="white"],
        .contact-form input[type="password",color="white"]
        {
            border: none;
            border-bottom: 1px solid #ffffff;
            background: transparent;
            outline: none;
            height: 20px;
            color: #fff;
            font-size: 16px;
        }
        .contact-form input[type="submit"] {
            height: 40px;
            color: #ffffff;
            font-size: 15px;
            background: red;
            cursor: pointer;
            border-radius: 25px;
            border: none;
            outline: none;
            margin-top: 05%;
        }
 .contact-form input[type="reset"] {
            height: 40px;
            color: #fff;
            font-size: 15px;
            background: blue;
            cursor: pointer;
            border-radius: 25px;
            border: none;
            outline: none;
            margin-top: 05%;
        }

        .contact-form a
        {
            color: #fff;
            font-size: 14px;
            font-weight: bold;
            text-decoration: none;
        }
        input[type="checkbox"] {
            width: 20%;
        }
    </style>
</head>
<body>
    <div class="contact-form">
        <img src="2.jpg" class="avatar">
        <h2> AGRICULTURE LOGIN</h2>
        <form>
            <p>Email</p>
            <input type="text" name="" placeholder="Enter Email">
            <p>Password</p>
            <input type="password" name="" placeholder="Enter Password">
            <input type="submit" name="" value="FARMER LOGIN">
             <input type="reset" name="" value="CUSTOMER LOGIN">
            <p><input type="checkbox"> Remember Me</p>
        </form>
    </div>
<div>
<br />
<table width="80%" border="20" align="center" cellpadding="0" cellspacing="0">
  <tr>
    <td>
<marquee direction="up" scrollamount="3" onmouseover="this.stop()" onmouseout="this.start()" class="blink" height="600px;">
 <a href="https://www.betterhealth.vic.gov.au/health/healthyliving/farm-safety-and-handling-agrichemicals" target="_blank"><ul><li><h1><font color="black" ><b>INFORMATION CONTENTS</b></h1></font></a></il></ul>
<ul><li><h3><font color="#fff" >Common agrichemicals</ul></li>
<ul><li><h3><font color="#fff" >Side effects of exposure to agrichemicals</h3></ul></li>
<ul><li><h3><font color="#fff" >SDS information for agrichemicals</h3></ul></li>
<ul><li><h3><font color="#fff" >Safe storage of agrichemicals</h3></ul></li>
<ul><li><h3><font color="#fff" >Safe transport of agrichemicals</h3></ul></li>
<ul><li><h3><font color="#fff" >Safe use of agrichemicals</h3></ul></li>
<ul><li><h3><font color="#fff" >Seek medical help for ill-effects of agrichemical exposure</h3></ul></li>   </marquee>
</font> 

</td>
  </tr>
  <tr>
    <td>&nbsp;</td>
  </tr>
 
</table>
</div>

</body>
</html>
