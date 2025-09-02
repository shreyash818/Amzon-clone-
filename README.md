# Amzon-clone-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amzon</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="stayle.css"> 
   <style>
       *{
    margin: 0px;
    font-family: Arila;
    border: border-box;
}
.navbar{
    height: 60px;
    background-color: #0f1111;
    color: white;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
}
.nav-log{
    height: 50px;
    width: 100px;
}
.logo{
    background-image: url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTcLQm5ZfijEFU2hg5IzsdqpdW-y72wrNa4fw&s");
    background-size: cover;
    height: 50px;
    width: 100%;
}
.border{
    border: 1.5px solid transparent;
}
.border:hover{
    border: 1.5px solid white;
}

/** box 2 **/

.add-first{
    color: #cccccc;
    font-size: 0.85rem;
    margin-left: 15px;
}
.add-second{
    font-size: 1rem;
    margin-left: 3px;
}
.add-icon{
    display: flex;
    align-items: center;
}

/** box 3 **/
.nav-search{
    display: flex;
    justify-content: space-evenly;
    background-color: pink;
    width: 620px;
    height: 40px;
    border-radius: 4px;
}
.search-select{
    background-color: #f3f3f3;
    width: 50px;
    text-align: center;
    border-top-left-radius: 4px;
    border-bottom-left-radius: 4px;
    border: none;
}
.search-input{
    width: 100%;
    font-size: 1rem;
    border: none;
}
.search-icon{
    width: 45px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1.2rem;
    background-color: #febd68;
    border-top-right-radius: 4px;
    border-bottom-right-radius: 4px;
    color: #0f1111;
}
.nav-search:hover{
    border: 2px solid orange;
}

/** box4 **/

span{
    font-size: 0.85rem;
}
.nav-second{
    font-size: 0.85rem;
    font-weight: 700;
}

/** box5 **/

.nav-cart i{
    font-size: 30px;
}

.nav-cart{
    font-size: 0.85rem;
    font-weight: 700;
}

/** panel **/

.panel{
    height: 40px;
    background-color: #222f3d;
    display: flex;
    color: white;
    align-items: center;
    justify-content: space-evenly;
}
.panel-ops p{
    display: inline;
    margin-left: 15px;
}
.panel-ops{
    width: 70%;
    font-size: 0.85rem;
}
.panel-deals{
    font-size: 0.9rem;
    font-weight: 700;
}

/** hero section **/

.hero-section{
    background-image: url("https://images-eu.ssl-images-amazon.com/images/G/31/lap/aurart/gw/Laptops-Category-Hero---Asin-PC._CB804837928_.jpg");
    background-size: cover;
    height: 450px;
    display: flex;
    justify-content: center;
    align-items: flex-end;
}
.hero-msg{
    background-color: white;
    color: black;
    height: 40px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1rem;
    width: 80%;
    margin-bottom: 25px;
}

/** shop section **/

.shop-section{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    background-color: rgb(180, 218, 233);
}
.box{
    height: 400px;
    width: 23%;
    background-color: white;
    padding: 20px 0px 15px ;
    margin-top: 15px;
}
.box-img{
    height: 300px;
    background-size: cover;
    margin-top: 1rem;
    margin-bottom: 1rem;
}
.box-content{
    margin-left: 1rem;
    margin-right: 1rem;
}
.box-content p{
    color: #007185;
}

/** footer panel **/

footer{
    margin-top: 15px;
}
.foot-panel1{
    background-color: #375758;
    color: white;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1rem;
}

.foot-panel2{
    background-color: #222f3d;
    color: white;
    height: 300px;
    display: flex;
    justify-content: space-evenly;
}
ul {
    margin-top: 20px;
}
ul a {
    display: block;
    font-size: 0.85px;
    margin-top: 10px;
    color: #dddddd;
}
.foot-panel3{
    background-color: #222f3d;
    color: white;
    border-top: 0.5px solid white;
    height: 70px;
    display: flex;
    justify-content: center;
    align-items: center;
}
.logo{
    background-image: url("amzonlogo.png"); 
    background-size: cover;
    height: 50px;
    width: 100px;
}

.foot-panel4{
    background-color: #0f1111;
    color: white;
    height: 80px;
    font-size: 0.7rem;
    text-align: center;
} 

.pages{
    padding-top: 25px;
}
.copyright{
    padding-top: 5px;
}
   </style>
</head>
<body>
    <header>
        <div class="navbar">
            <div class="nav-log border">
                <div class="logo"></div>
            </div>

            <div class="nav-address border">
                <p class="add-first">Deliver to</p>
                <div class="add-icon">
                    <i class="fa-solid fa-location-dot"></i>
                    <p class="add-second">India</p>
                </div>
            </div>
            <div class="nav-search">
                <select class="search-select">
                    <option>All</option>
                </select>
                <input placeholder="Search Amazon" class="search-input">
                <div class="search-icon">
                     
                    <i class="fa-solid fa-magnifying-glass"></i>
                </div>
            </div>
        
        <div class="nav-singin border">
            <p><span>Hello, sign in</span></p>
            <p class="nav-second">Account & Lists</p>
        </div>

        <div class="nav-return border">
            <p><span>Return</span></p>
            <p class="nav-second">& Oreders</p>
        </div>

        <div class="nav-cart border">
            <i class="fa-solid fa-cart-shopping"></i>
            Cart
        </div>
    </div>
    <div class="panel">
        <div class="panel-all border">
            <i class="fa-solid fa-bars"></i>
            All
        </div>
        <div class="panel-ops">
            <p>Today's Deals</p>
            <p>Customer Service</p>
            <p>Registry</p>
            <p>Gift Cards</p>
            <p>Sell</p>
        </div>
        <div class="panel-deals border">
            Shop deals in Electronice
        </div>
    </div>
    </header>

    <div class="hero-section">
        <div class="hero-msg">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus, fugiat ? <a href=""> Click here to go to amazon.in </a> </div>
    </div>

    <div class="shop-section">
        <div class="
        box">
            <div class="box-content">
             <h2>Buy 2 Get 10% off, freebies & more offers</h2>
            <div class="box-img" style="background-image: url('face.jpg');"></div>
            <p>See more</p>
            </div>
        </div>
        <div class="box">
            <div class="box-content">
             <h2>Up to 70% off | International brands</h2>
            <div class="box-img" style="background-image: url('cliner.jpg');"></div>
            <p>See more</p>
        </div>
        </div>
        <div class="box">
            <div class="box-content">
             <h2>Up to 60% off | Amazon Renewed</h2>
            <div class="box-img" style="background-image: url('i pad.jpg');"></div>
            <p>See more</p>
            </div>
        </div>
        <div class="box">
            <div class="box-content">
             <h2>Up to 75% off | Electronics & Accessories</h2>
            <div class="box-img" style="background-image: url('laptop.jpg');"></div>
            <p>See more</p>
            </div>
        </div>
       <div class="box">
            <div class="box-content">
             <h2>More & More Unisex-Adult Hooded Sweatshirt</h2>
            <div class="box-img" style="background-image: url('laptop.jpg');"></div>
            <p>See more</p>
            </div>
        </div>
        <div class="box">
            <div class="box-content">
             <h2>Built for Apple Intelligence.iPhone 16.</h2>
            <div class="box-img" style="background-image: url('iphone.jpg');"></div>
            <p>See more</p>
        </div>
        </div>
        <div class="box">
            <div class="box-content">
             <h2>Up to 70% off | International brands</h2>
            <div class="box-img" style="background-image: url('cliner.jpg');"></div>
            <p>See more</p>
            </div>
        </div>
        <div class="box">
            <div class="box-content">
             <h2>Buy 2 Get 10% off, freebies & more offers</h2>
            <div class="box-img" style="background-image: url('face.jpg');"></div>
            <p>See more</p>
            </div>
        </div> 
    </div>
    <footer>
        <div class="foot-panel1">
            Back to Top
        </div>
        <div class="foot-panel2">
            <ul>
                <h3>Get to Know Us</h3>
                <br>
                <p>About Amazon</p>
                <p>Careers</p>
                <p>Press Releases</p>
                <p>Amazon Science</p>
            </ul>
            <ul>
                <h3>Connect with Us</h3>
                <br>
                <p>Facebook</p>
                <p>Twitter</p>
                <p>Instagram</p>	
            </ul>
            <ul> 	
                <h3>Make Money with Us</h3>
                <br>
                <p>Sell on Amazon</p>
                <p>Sell under Amazon Accelerator</p>
                <p>Protect and Build Your Brand</p>
                <p>Amazon Global Selling</p>
                <p>Supply to Amazon</p>
                <p>Become an Affiliate</p>
                <p>Fulfilment by Amazon</p>
                <p>Advertise Your Products</p>
                <p>Amazon Pay on Merchants</p>
            </ul>
            <ul>
                <h3>Let Us Help You</h3>
                <br>
                <p>Your Account</p>
                <p>Returns Centre</p>
                <p>Recalls and Product Safety Alerts</p>
                <p>100% Purchase Protection</p>
                <p>Amazon App Download</p>
                <p>Help</p>	
            </ul>
        </div>
        <div class="foot-panel3">
            <div class="logo"></div>
        </div>
        <div class="foot-panel4">
            <div class="pages">
                <a>Conditions of Use</a>
                <a>Privacy Notice</a>
                <a>Interest-Based Ads</a>
            </div>
            
            <div class="copyright">
                © 1996-2025, Amazon.com, Inc. or its affiliates
            </div>
        </div>
    </footer>
</body>
</html>
