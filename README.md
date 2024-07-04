create simple registration form using html
<!DOCTYPE html>
<html>
    <head>
        <title>Registration Form</title>
        <style>
            body {
                background-image: url("train.jpg");
                background-repeat: no-repeat;
                background-size: cover;

            }
            h1{
                color:line:margin:10px
            }
            form {
                width:25%;
                background-color: skyblue;
                opacity:0.7;
            }
            input[type="text"],[type="password"],[type="number"],[type="date"] {
                width:70%;
                font-size:18px;
                margin:10px;
                outline:none;
                text-align: center;
            }
            input[type="submitt"]{
                width:70%;
                height:20px;
                color:whitesmoke;
                background: blue;
                cursor: pointer;
                outline:none;
                margin:10px;
                font-size:10px;
                text-align:center;
            }
        </style>

    
    </head>

    <body>

    </body>
    <center>
        <h1>Create Your Account</h1>
        <form method="post">  
            <input type="text" placeholder="Firstname"/></br>
            <input type="text" placeholder="Lastname"/></br>
            <input type="password" placeholder="Password"/></br>
            <input type="number" placeholder="Mobile number"/></br>
            <input type="Date"/> </br>
            <input type="submitt" value=" Register"/></br>


        </form>
    </center>
</html>
