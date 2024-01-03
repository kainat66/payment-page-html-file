<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ONLINE PAYMENT</title>
    <link rel="icon" href="Vector (2).png">
    <style>
                
                nav{
    height: 60px;
    width: 1530px;
    background: white;
    padding: 20px;
    position:sticky;
    top: 0;
}
nav ul{
    float: right;
    margin-right: 40px;
}
nav li{
    display: inline-block;
    margin: 0 30px;
    line-height: 50px;

}
nav a{
    font-size: 25px;
    text-decoration: none;
    color: #005E98;
}
nav a :hover{
    border: 4px solid #005E98;
    background-color: #005E98;
    color: white;
    padding: 5px;
    border-radius: 25px;
}
form{
    font-size: 35px;
    color: #005E98;
    
}
fieldset{
    width: 1480px;
    height: 610px;
    padding-left: 50px;

    
}
legend{
    font-size: 50px;
}
.item{
    border: 2px solid #005E98;
}
.button{
    height: 40px;
    width: 140px;
    background-color: #005E98;
    color: aliceblue;
    border: 2px solid #005E98;
}
.item2{
    border: 2px solid #005E98;
}
    </style>

</head>
<body>
    <nav>
        <img src="Vector (3).png" height="70PX"/>
        <UL>
            <li > <a href="DELTA.HTML" ><b>HOME</b></a></li> 
            <li > <a href="booking.html" ><b>BOOKING</b></a></li> 
            <li> <a href="services.html" ><b>SERVICES</b></a></li> 
            <li> <a href="login.html" ><b>LOGIN</b></a></li> 
            <li> <a href="about us.html" ><b>ABOUT US</b></a></li> 
         
        </UL>  
    </nav>
    <form>
        <fieldset class="item2">
            <legend><b>PAYMENT</b></legend>
            Name: <input class="item" type="text"/><br/>
            <br/>
            Credit card No: <input class="item" type="number"/><br/>
            <br/>
            <input  class="button"     type="submit" value="SUBMIT PAYMENT"/>
            </fieldset>
            </form>
    
</body>
</html>
