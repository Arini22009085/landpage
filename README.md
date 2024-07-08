# landpage
index.html
```
<!DOCTYPE html>
<html>
    <head>
        <title>landpage</title>
        <link rel="stylesheet" href="index.css">
    </head>
    <body>
        <div class="main">
            <div class="navbar">
                <div class="icon">
                    <h2 class="logo">Arivalli</h2>
                </div>
                <div class="menu">
                    <ul>
                        <li><a href="#">HOME</a></li>
                        <li><a href="#">ABOUT</a></li>
                        <li><a href="#">SERVICE</a></li>
                        <li><a href="#">DESIGN</a></li>
                        <li><a href="#">CONTACT</a></li>
                    </ul>
                </div>
                <div class="search">
                    <input class="srch" type="search" name="" placeholder="Type to text">
                    <a href="#"><button class="btn">search</button></a>
                </div>
            </div>
            <div class="content">
                <h1>Web Design & <br><span>Development</span> <br>Course</h1>
                <p class="par">Lorem, ipsum dolor sit amet consectetur adipisicing elit. <br>
                    Id quibusdam recusandae aut dignissimos quia quidem, iste impedit fugiat<br> 
                    officiis maxime deserunt non repellendus, ipsum praesentium ex. Accusantiu<br> 
                    atque sunt non id eaque unde inventore veniam ipsa modi dignissimos illo<br> 
                    sequi perferendis nulla, maiores cum tenetur cupiditate quam, hic soluta<br> 
                    error doloribus vel at vitae voluptas! Natus, aperiam accusantium? Porro<br> 
                    sequi ipsa ab, tempora architecto optio deleniti ex est ratione. Repellendus?</p>
                    <button class="cn"><a href="#">JOIN US</a></button>
                     <div class="form">
                        <h2>Login Here</h2>
                        <input type="email" name="email" placeholder="Enter Email Here">
                        <input type="Password" name="" placeholder="Enter password Here">
                        <button class="btnn"><a href="#">Login</a></button>
                        <p class="link">Don't have an account
                        <a href="#">Sign up</a> here</a></p>
                        <p class="liw">Log in with</p>
                     </div>
            </div>
        </div>    
    </body>
</html>
```
index.css
```
*{
    margin:0;
    padding:0;
}
.main
{
    width:100%;
    background: linear-gradient(to top,rgba(0,0,0,0.5)50%,rgba(0,0,0,0.5)50%),url("./image.jpg");
    background-position: center;
    background-size:cover;
    height:109vh;
}
.navbar
{
    width:1200px;
    height:75px;
    margin:auto;
}
.icon
{
    width:200px;
    float:left;
    height:70px;
}
.logo
{
    color:blueviolet;
    font-size: 30px;
    font-family: arial;
    padding-left: 20px ;
    float: left;
    padding-top:10px;
}
.menu
{
    width:400px;
    float:left;
    height:70px;
}
ul{
    float:left;
    display:flex;
    justify-content:center;  
    align-items: center; 
}
ul li 
{
    list-style: none;
    margin-left: 62px;
    margin-top: 27px;

}

ul li a{
    text-decoration: none;
    color: aliceblue;
    font-family: Arial;
    font-weight: bold;
    transition: 0.4s ease-in-out;
}
ul li a:hover
{
    color:blueviolet;

}
.search
{
    width:330px;
    float:left;
    margin-left:270px;
}
.srch{
    font-family: 'Times new roman';
    width: 200px;
    height:40px;
    background:transparent;
    border:1px solid blueviolet;
    margin-top: 13px;
    color: aliceblue;
    border-right: none;
    font-size: 16px;
    float: left;
    padding:10px;
    border-bottom-left-radius: 5px;
    border-top-left-radius: 5px;
}
.btn
{
    width: 100px;
    height: 40px;
    background:blueviolet;
    border:2px solid blueviolet;
    margin-top: 13px;
    color: aliceblue;
    font-size: 15px;
    border-bottom-right-radius: 5px;
    border-bottom-right-radius: 5px;

}
.btn:focus{
    outline:none;
}
.srch:focus{
    outline:none;
}
.content
{
    width: 1200px;
    height: auto;
    margin: auto;
    color: aliceblue;
    position:relative;
}
.content h1{
    font-family: 'times new roman';
    font-size: 50px;
    padding-left: 20px;
    margin-top: 9%;
    letter-spacing:2px;
}
.content .cn
{
    width: 160px;
    height: 40px;
    background: blueviolet;
    border:none;
    margin-bottom: 10px;
    margin-left: 20px;
    font-size:18px;
    border-radius:10px;
    cursor:pointer;
}
.content .cn a{
    text-decoration: none;
    color: #000;
    transition: .3s ease;
}
.cn{
    margin-top: 20px;
}
.cn:hover{
    background-color: white;
}
.content span
{
    color:blueviolet;
    font-size: 60px;
}
.form
{
    width: 250px;
    height: 380px;
    background: linear-gradient(to top,rgba(0,0,0,0.8)50%,rgba(0,0,0,0.8)50%);
    position: absolute;
    top:-20px;
    left:870px;
    border-radius: 10px;
    padding: 25px;

}
.form h2{
    width: 220px;
    font-family: sans-serif;
    text-align: center;
    color: blueviolet;
    font-size: 22px;
    background-color: aliceblue;
    border-radius: 10px;
    margin: 2px;
    padding: 8px;
}
.form input{
    width: 240px;
    height: 35px;
    background: transparent;
    border-bottom: 1px solid blueviolet;
    border-top: none;
    border-right: none;
    border-left: none;
    color: aliceblue;
    font-size: 15px;
    letter-spacing: 1px;
    margin-top: 30px;
    font-family: sans-serif;
}
.form input:focus
{
    outline: none;
}
::placeholder
{
    color: aliceblue;
    font-family: Arial;
}
.btnn
{
    width: 240px;
    height: 40px;
    background: blueviolet;
    border:none;
    margin-top: 30px;
    font-size: 18px;
    border-radius: 10px;
    cursor: pointer;
    color:aliceblue;
}

.btnn:hover{
    background: white;
    color:blueviolet;

}
.btnn a{
    text-decoration: none;
    color:#000;
    font-weight: bold;
}
.form .link
{
    font-family: Arial, Helvetica, sans-serif;
    font-size: 17px;
    padding-top: 20px;
    text-align: center;
}
.form .link a{
    text-decoration: none;
    color:blueviolet;
}
.liw
{
    padding-top: 15px;
    padding-bottom: 10px;
    text-align: center;
}

```
###output:
![landpage](https://github.com/Arini22009085/landpage/assets/119643315/b68c2422-bf6b-4805-a37b-41b396bd9c67)


