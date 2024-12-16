# Ex.07 Restaurant Website
## Date: 16/12/2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
home.html

<!DOCTYPE html>
<html lang="en">

<head>
    <link rel="icon" href="images/logo.jpeg">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HOTEL SEVEN</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css"
        integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g=="
        crossorigin="anonymous" referrerpolicy="no-referrer">

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Caveat:wght@400..700&family=Dancing+Script:wght@400..700&family=Lobster&family=Orbitron:wght@400..900&family=Permanent+Marker&family=Sour+Gummy:ital,wght@0,100..900;1,100..900&display=swap"
        rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Caveat:wght@400..700&family=Dancing+Script:wght@400..700&family=Lobster&family=Orbitron:wght@400..900&family=Oswald:wght@200..700&family=Permanent+Marker&family=Sour+Gummy:ital,wght@0,100..900;1,100..900&display=swap"
        rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Caveat:wght@400..700&family=Dancing+Script:wght@400..700&family=Lobster&family=Nunito:ital,wght@0,200..1000;1,200..1000&family=Orbitron:wght@400..900&family=Oswald&family=Permanent+Marker&family=Sour+Gummy:ital,wght@0,100..900;1,100..900&display=swap"
        rel="stylesheet">
</head>

<body>
    <marquee> "NEW YEAR DHAMAKA" OFFER IS LIVE! BUY NOW!</marquee>
    <nav>
        <div class="logo">
            <img src="images/logo.jpeg" alt="">
        </div>
        <div class="homeh1">
            <h1>HOTEL 7</h1>

        </div>
        <div class="links">
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="admin.html">Administration</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="contact.html">Book Now</a></li>
            </ul>
        </div>
    </nav>
    <div class="main">
        <div class="text">
            <h1>GET <span>HOMELY FOODS </span>IN SECONDS</h1>
        </div>
        <div class="homeimg">
            <img src="images/home.png" alt="">
        </div>
    </div>
    <div class="btn">
        <a href="contact.html" class="order_btn">BOOK NOW</a>
    </div>
    <footer>
        Designed with <i class="fa-regular fa-heart"></i> by Venkatachalam S &copy;
    </footer>
</body>


</html>
```
```
about.html

<!DOCTYPE html>
<html lang="en">

<head>
    <link rel="icon" href="images/logo.jpeg">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us ~ Hotel 7</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css" integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g==" crossorigin="anonymous" referrerpolicy="no-referrer">

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Caveat:wght@400..700&family=Dancing+Script:wght@400..700&family=Lobster&family=Orbitron:wght@400..900&family=Permanent+Marker&family=Sour+Gummy:ital,wght@0,100..900;1,100..900&display=swap"
        rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Caveat:wght@400..700&family=Dancing+Script:wght@400..700&family=Lobster&family=Orbitron:wght@400..900&family=Oswald:wght@200..700&family=Permanent+Marker&family=Sour+Gummy:ital,wght@0,100..900;1,100..900&display=swap"
        rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Caveat:wght@400..700&family=Dancing+Script:wght@400..700&family=Lobster&family=Nunito:ital,wght@0,200..1000;1,200..1000&family=Orbitron:wght@400..900&family=Oswald&family=Permanent+Marker&family=Sour+Gummy:ital,wght@0,100..900;1,100..900&display=swap"
        rel="stylesheet">

</head>

<body>
    <nav>
        <div class="logo">
            <img src="images/logo.jpeg" alt="">
        </div>
        <div class="homeh">
            <h1>HOTEL 7</h1>

        </div>
        <div class="links1">
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="admin.html">Administration</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="contact.html">Book Now</a></li>
            </ul>
        </div>
    </nav>
    <div class="h1">
        <h1><span class="abt">ABOUT </span>US </h1></div>
    <div class="about">
        
        <div class="abt1">
            <h2>Why Choose Us?</h2>
            <p>Hotel 7 is a unique culinary destination that offers a diverse range of dining experiences. From the comfort of home-style Indian cuisine to the exotic flavors of international dishes, there's something for everyone. The restaurant boasts a separate section dedicated to authentic Indian delicacies, served in traditional style with a focus on regional specialties. For those seeking quick bites, the fast-food section offers a variety of tempting options. The presence of a world-class chef ensures that every dish is a masterpiece, elevating the dining experience without breaking the bank. Beyond the food, Hotel 7 provides a fun and relaxing atmosphere with games and chill zones, making it a perfect spot for families and friends to unwind.
            </p>
        </div>

        <div class="abtimg">
            <img src="images/about.jpeg" alt="">
        </div>
        <p></p>
    </div>
    <footer class="abtfo">
        Designed with  <i class="fa-regular fa-heart"></i>  by Venkatachalam S &copy;
    </footer>
</body>

</html>
```
```
admin.html

<!DOCTYPE html>
<html lang="en">

<head>
    <link rel="icon" href="images/logo.jpeg">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration ~ Hotel 7</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css"
        integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g=="
        crossorigin="anonymous" referrerpolicy="no-referrer">

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Caveat:wght@400..700&family=Dancing+Script:wght@400..700&family=Lobster&family=Orbitron:wght@400..900&family=Permanent+Marker&family=Sour+Gummy:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Caveat:wght@400..700&family=Dancing+Script:wght@400..700&family=Lobster&family=Orbitron:wght@400..900&family=Oswald:wght@200..700&family=Permanent+Marker&family=Sour+Gummy:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Caveat:wght@400..700&family=Dancing+Script:wght@400..700&family=Lobster&family=Nunito:ital,wght@0,200..1000;1,200..1000&family=Orbitron:wght@400..900&family=Oswald&family=Permanent+Marker&family=Sour+Gummy:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">

</head>

<body>
    <nav>
        <div class="logo">
            <img src="images/logo.jpeg" alt="">
        </div>
        <div class="homeh1">
            <h1>HOTEL 7</h1>

        </div>
        <div class="links">
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="admin.html">Administration</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="contact.html">Book now</a></li>
            </ul>
        </div>
    </nav>
    <div class="chefad">
        <div class="team">
            <h1>Meet <span>Our Team</span></h1>

            <div class="admin">
                <div class="admins">
                    <div class="admininfo">
                        <div class="imgad">
                            <img src="images/dhoni.jpg" alt="">
                        </div>
                        <h2>MS DHONI</h2>
                        

                    </div>
                </div>
                <div class="admins">
                    <div class="admininfo">
                        <div class="imgad">
                            <img src="images/vijay.jpg" alt="">
                        </div>
                        <h2>THALAPATHY VIJAY</h2>
                        
                    </div>
                </div>

            </div>
        </div>
        <div class="h1adm">
            <h1>Our <span>Premium Chef</span></h1>
        </div>
        <div class="chef">
            
            <div class="chefs">
                <img src="images/chefdamu.jpeg" class="imgg " alt="">
                <h1>Chef Damu</h1>
            </div>

            <div class="chefs">
                <img src="images/chefvenkateshbhat.jpg" alt="">
                <h1>Chef Venkatesh Bhat</h1>
            </div>
            <div class="chefs">
                <img src="images/chefkoushik.jpeg" alt="">
                <h1>Chef Koushik</h1>
            </div>

            <div class="chefs">
                <img src="images/chefgarima.jpeg" alt="">
                <h1>Chef Garima</h1>
            </div>

            <div class="chefs">
                <img src="images/chefsanjeev.jpeg" alt="">
                <h1>Chef Sanjeev Kapoor</h1>

            </div>
        </div>
    </div>






    <footer class="admf">
        Designed with <i class="fa-regular fa-heart"></i> by Venkatachalam S &copy;
    </footer>
</body>

</html>
```

```
menu.html

<!DOCTYPE html>
<html lang="en">

<head>
    <link rel="icon" href="images/logo.jpeg">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HOTEL SEVEN</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css"
        integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g=="
        crossorigin="anonymous" referrerpolicy="no-referrer">

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Caveat:wght@400..700&family=Dancing+Script:wght@400..700&family=Lobster&family=Orbitron:wght@400..900&family=Permanent+Marker&family=Sour+Gummy:ital,wght@0,100..900;1,100..900&display=swap"
        rel="stylesheet">
    <link
        href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Caveat:wght@400..700&family=Dancing+Script:wght@400..700&family=Lobster&family=Orbitron:wght@400..900&family=Oswald:wght@200..700&family=Permanent+Marker&family=Sour+Gummy:ital,wght@0,100..900;1,100..900&display=swap"
        rel="stylesheet">
    <link
        href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Caveat:wght@400..700&family=Dancing+Script:wght@400..700&family=Lobster&family=Nunito:ital,wght@0,200..1000;1,200..1000&family=Orbitron:wght@400..900&family=Oswald&family=Permanent+Marker&family=Sour+Gummy:ital,wght@0,100..900;1,100..900&display=swap"
        rel="stylesheet">
</head>

<body>

    <nav>
        <div class="logo">
            <img src="images/logo.jpeg" alt="">
        </div>
        <div class="homeh1">
            <h1>HOTEL 7</h1>

        </div>
        <div class="links">
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="admin.html">Administration</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="contact.html">Book Now</a></li>
            </ul>
        </div>
    </nav>
    <div class="menubar">
        <h1>Indian Cuisine</h1>
        <div class="indian">
            
            <div class="ind">
                <img src="images/ind1.jpg" alt="">
                <h2>Biriyani - ₹200</h2>
                <p>"Indulge in a symphony of flavors with our diverse biryani selection."</p>
            </div>
            <div class="ind">
                <img src="images/ind2.png" alt="">
                <h2>Mini South Indian Tiffin - ₹100</h2>
                <p>"A mini feast of South Indian flavors."</p>
            </div>
            <div class="ind">
                <img src="images/ind3.jpeg" alt="">
                <h2>Naan and Panner Butter Masala - ₹175</h2>
                <P>"Experience the magic of Naan and Paneer Butter Masala, our way."</P>
            </div>
            <div class="ind">
                
                <div class="view">
                <img src="images/ind4.jpg" alt="">
                <h3>View All</h3>
                </div>
                
            </div>
        </div>
        <h1>Fast foods</h1>
        <div class="fast">
            <div class="fastt">
                <img src="images/fast1.jpeg" alt="">
                <h2>Burger - ₹90</h2>
                <p>"Discover a burger for every craving."</p>
            </div>
            <div class="fastt">
                <img src="images/fast2.webp" alt="">
                <h2>French Fries - ₹90</h2>
                <p>"Elevate your fry game with our unique flavors."</p>
            </div>
            <div class="fastt">
                <img src="images/fast3.jpg" alt="">
                <h2>Pizza - ₹120</h2>
                <p>"A slice of heaven, every time."</p>
            </div>
            <div class="fastt">
                <div class="view">
                <img src="images/fast4.jpg" alt="">
                
                <h3>View All</h3></div>
            </div>
        </div>
        <h1>Other Cuisine</h1>
        <div class="other">
            <div class="otherr">
                <img src="images/other4.jpg" alt="">
                <h2>Tacos - ₹250</h2>
                <p>"Taco your way to flavor town."</p>
            </div>
            <div class="otherr">
                <img src="images/other2.webp" alt="">
                <h2>Pastry Dish - ₹275</h2>
                <p>"Pastry paradise."</p>
            </div>
            <div class="otherr">
                <img src="images/other3.jpeg" alt="">
                <h2>Shrimp dish - ₹300</h2>
                <p>"Shrimply delicious."</p>
            </div>
            <div class="otherr">
                <div class="view">
                <img src="images/other5.webp" alt="">
                <h3>View All</h3>
                </div>
            </div>
        </div>
    </div>










    <footer>
        Designed with <i class="fa-regular fa-heart"></i> by Venkatachalam S &copy;
    </footer>
</body>


</html>
```

```
contact.html

<!DOCTYPE html>
<html lang="en">

<head>
    <link rel="icon" href="images/logo.jpeg">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us ~ Hotel 7</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css" integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g==" crossorigin="anonymous" referrerpolicy="no-referrer">

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Caveat:wght@400..700&family=Dancing+Script:wght@400..700&family=Lobster&family=Orbitron:wght@400..900&family=Permanent+Marker&family=Sour+Gummy:ital,wght@0,100..900;1,100..900&display=swap"
        rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Caveat:wght@400..700&family=Dancing+Script:wght@400..700&family=Lobster&family=Orbitron:wght@400..900&family=Oswald:wght@200..700&family=Permanent+Marker&family=Sour+Gummy:ital,wght@0,100..900;1,100..900&display=swap"
        rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Caveat:wght@400..700&family=Dancing+Script:wght@400..700&family=Lobster&family=Nunito:ital,wght@0,200..1000;1,200..1000&family=Orbitron:wght@400..900&family=Oswald&family=Permanent+Marker&family=Sour+Gummy:ital,wght@0,100..900;1,100..900&display=swap"
        rel="stylesheet">

</head>

<body>

    <nav>
        <div class="logo">
            <img src="images/logo.jpeg" alt="">
        </div>
        <div class="homeh1">
            <h1>HOTEL 7</h1>

        </div>
        <div class="links">
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="admin.html">Administration</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="contact.html">Book Now</a></li>
            </ul>
        </div>
    </nav>
    <div class="book">
        
        <div class="bookimg">
            <h1><span>Order</span> Now</h1>
            <div class="bimg">
            <img src="images/other1.webp" alt=""></div>
        </div>
        <div class="order">
            <form>
                <div class="inp">
                    <label> Enter Your Name:</label><br>
                    <input type="text" minlength="3" placeholder="Enter Name" required>
                </div>
                <div class="inp">
                    <label> Enter Your Mobile Number:</label><br>
                    <input type="text" minlength="10" maxlength="10" placeholder="Enter Mobile No." required>
                </div>
                <div class="inp">
                    <label> Enter Your Email:</label><br>
                    <input type="email" placeholder="Enter email">
                </div>
                <div class="inp">
                    <label> Enter tables to be booked:</label><br>
                    <input type="number" placeholder="Enter no. of tables" required>
                </div>
                <div class="inp">
                    <label>Select Date</label><br>
                    <select name="Date" required>
                        <option value="16-12-2024">16-12-2024</option>
                        <option value="17-12-2024">17-12-2024</option>
                        <option value="18-12-2024">18-12-2024</option>
                        <option value="19-12-2024">19-12-2024</option>
                        <option value="20-12-2024">20-12-2024</option>
                    </select>
                </div>
                <div class="inp">
                    <label>Select Time</label><br>
                    <select name="Date" required>
                        <option value="1PM">1PM</option>
                        <option value="2PM">2PM</option>
                        <option value="3PM">3PM</option>
                        <option value="7PM">7PM</option>
                        <option value="9PM">9PM</option>
                    </select>
                </div>
                <div class="sub">
                <input type="submit" class ="submit" value="Book">
                    </div>

            </form>
        </div>
    </div>

    <footer class="conf">
        Designed with <i class="fa-regular fa-heart"></i> by Venkatachalam S &copy;
    </footer>
</body>


</html>
```

```
style.css
body {
    font-family: sans-serif;
    background-color: white;
    box-sizing: border-box;
}

marquee {
    font-size: 24px;
    color: rgb(245, 174, 30);
    background: rgba(0, 0, 0, 0.5);
    word-spacing: 12px;
}


nav {
    display: flex;
    padding: 2%;
    justify-content: space-between;
    align-items: center;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);


}

nav ul li {
    display: inline-block;
    margin: 12px 15px;
    flex: 1;
    list-style-type: none;
    position: relative;
    text-align: right;
    padding: 12px 24px;
    padding-bottom: 0;
    transition: 0.5s;
}

nav ul li a {
    color: rgb(245, 162, 37);

    font-size: 28px;
    font-family: "Nunito", sans-serif;
    text-decoration: none;

    font-weight: 500;
    font-size: 20px;
    transition: 0.5s;
}

nav ul li a::after {
    content: '';
    width: 0;
    height: 2px;
    background: black;
    display: block;
    transition: 0.2s linear;
}

nav ul :hover {
    transform: scale(1.3);

}

nav ul li a:hover::after {
    width: 100%;
}

nav ul li a:hover {
    color: black;


}

nav .logo :hover {
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
}

nav h1 {
    font-size: 32px;

    color: rgb(250, 192, 49);
    margin: 0 5px;
    cursor: pointer;
    margin-left: -175%;
    transition: 0.5s;
}

nav h1:hover {
    color: black;
}

nav .logo img {
    width: 100px;
    cursor: pointer;
    margin: 7px 0;
    margin-left: 10%;
    transition: 0.5s;
}

.main {
    display: flex;
    align-items: center;
    justify-content: space-around;
    position: relative;
    top: 130px;
}

.main .text h1 {
    font-size: 60px;
    position: relative;
    top: -90px;
    left: 20px;
}

.main .text h1 span {
    margin-left: 15px;
    color: rgb(250, 192, 49);
    font-family: Papyrus;
    line-height: 1.5;
    font-size: 70px;
}

.main .homeimg img {
    width: 650px;
    position: relative;
    right: 10%;
    margin-top: -20%;
    margin-left: 10%;
    transition: 0.5s;
}

.main .homeimg :hover {
    transform: scale(1.1);
}

.order_btn {
    background: #fac031;
    padding: 15px 18px;
    font-size: 24px;
    text-decoration: none;
    color: #fff;
    position: relative;
    left: 1.5%;
    bottom: 30px;
    transition: 0.5s;
}

.btn :hover {
    color: rgb(250, 192, 49);
    background-color: white;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
}

footer {
    text-align: center;
    margin-top: 5%;
    background-color: rgba(250, 192, 49, 0.5);
    color: black;
    font-family: "Nunito", sans-serif;
    font-size: 28px;
}

footer i {
    margin: 0 5px;
    transition: 0.5s;
    color: red;
}

footer i:hover {
    color: yellow;
    transform: scale(1.2);

}

/*about*/
.about {
    display: flex;
    align-items: center;
    justify-content: space-between;
    position: relative;

}

.h1 h1 {
    font-size: 60px;
    position: relative;

    left: 7%;
}

.h1 h1 span {
    margin-left: 15px;
    color: rgb(250, 192, 49);
    font-family: Papyrus;
    line-height: 1.5;
    font-size: 70px;
}

.about .abtimg img {
    width: 400px;
    position: relative;
    right: 20%;
    margin-top: -20%;
    transition: 0.5s;
}

.about .abtimg :hover {
    box-shadow: 0 0 15px rgba(0, 0, 0, 0.5);
}

.abt1 h2 {
    margin-left: 10%;
    font-size: 42px;
}

.about .abt1 p {
    font-size: 24px;
    width: 80%;
    margin-left: 10%;
    line-height: 1.5;
    word-spacing: 10px;
}

.homeh {
    font-size: 32px;

    color: rgb(250, 192, 49);
    margin: 0 5px;
    cursor: pointer;
    margin-left: -10%;
    transition: 0.5s;
}

.homeh :hover {
    color: black;
}

.abtfo {
    margin-top: 5%;
}

/* Admin*/

.team {
    width: 100%;
    padding: 70px 0;
    height: 90vh;
    margin: auto;
}

.team h1 {
    margin-left: 15%;
    justify-content: left;
    align-items: left;
    font-size: 60px;
    margin-top: -2%;
}

h3 {
    margin-left: 22%;
}

.team h1 span {
    color: #fac031;
    margin-left: 15px;
    font-family: mv boli;
}



.admin {
    display: flex;
}

.admins {
    width: 300px;
    display: flex;
    height: 400px;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.5);
    border-radius: 10%;
    padding: 10px 12px;
    margin: 0 8px;
    justify-content: center;
    text-align: center;

}

.admins .admininfo .imgad {
    transition: 0.5s;
}
.admininfo .imgad img {
    transition: 0.5s;
}
.admininfo .imgad :hover {
    transform: scale(1.4);
}

.admininfo p {
    font-size: 18px;
}

.admins img {
    width: 200px;
    border-radius: 100%;
    margin-top: 20%;
}

.admins h2 {
    font-size: 20px;
    margin-top: 50%;
    color: #fac031;
}
.admf{
    margin-top: -17%;
}


/*-----------------*/
.chefad {
    display: flex;
}

.h1adm {
    margin-left: -75%;
    width: 100%;
    justify-content: right;
    align-items: right;
    font-size: 32px;
    margin-left: 15px;
    margin-top: 1%;
}

.h1adm span {
    color: #fac031;
    font-family: mv boli;
    
}

.chef {
    width: 90%;
    margin-top: 12%;
    display: grid;
    margin-left: -40%;
    grid-template-columns: 330px 330px 330px;
    grid-template-rows: 220px;
}

.chefs {
    width: 270px;
    height: 170px;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.5);
    border-radius: 10%;
    padding: 10px 12px;
    margin-left: 30px;
    
}

.chefs img {
    display: flex;
    transition: 0.5s;
    justify-content: center;
    width: 150px;
    border-radius: 100%;
    margin-left: 20%;
    
}

.chef .chefs:hover img {
    opacity: 0.4;
}

.chefs h1 {
    position: absolute;
    font-size: 28px;
    font-family: "Nunito",sans-serif;
    margin-bottom: 130px;
    color: #fac031;
    font-family: polo;
    z-index: 5;
    opacity: 0;
    transition: 0.3s;
}

.chefs:hover h1 {
    opacity: 2;
    transform: translateY(-100px);
}

span {
    color: #fac031;
}

/*Order*/
.book {
    width: 90%;
    margin: auto;
    display: flex;
}

.book h1 span {
    color: #fac031;
    margin-left: 15px;
    font-family: mv boli;
}

.bookimg img {
    width: 400px;
    height: 500px;
    transition: 0.5s;
    margin-top: -3%;
}

.bimg :hover {
    box-shadow: 0 0 15px rgba(0, 0, 0, 0.5);
}

.book h1 {
    font-size: 48px;
}

.order {
    line-height: 2;
    justify-content: right;
    margin-top: 8%;
    margin-left: 7%;
}

form {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-gap: 10px 30px;
}

.inp {
    font-size: 32px;

}

input, select {
    font-size: 32px;
    width: 300px;
    background-color: rgba(0, 0, 0, 0.2);
    color: black;
}

.submit {
    color: white;
    padding-left: 2%;
    padding-right: 2%;
    padding-top: 0.5%;
    padding-bottom: 0.5%;
    background-color: #fac031;
    cursor: pointer;
    margin-left: 50%;
    margin-top: 2%;
}

.conf {
    margin-top: 2%;
}
/*Menu*/
.menubar{
    width: 90%;
    margin: auto;
    padding: auto;
}
.indian, .fast, .other{
    display: flex;    
}
.ind, .fastt, .otherr{
    background-color: peachpuff;
    margin: 25px;
    width: 400px;
    transition: 0.5s;
    border-radius: 25px;
}
.ind:hover, .fastt:hover, .otherr:hover{
    box-shadow: 0 0 15px rgba(0, 0, 0, 0.5);
}
.menubar h1{
    font-family: "Papyrus";
    color: #fac031;
    font-size: 48px;
}
.menubar img{
    width: 250px;
    height: 250px;
    padding: 25px;
    border-top-right-radius: 25%;
    border-bottom-left-radius: 25%;
    margin-left: 4%;
}

.menubar h2{
    text-align: center;
    font-size: 18px;
    margin: auto;
    width: 80%;
}
.menubar p{
    font-size: 15px;
    width: 80%;
    margin: auto;
    padding: 10px;
    text-align: center;
}
.view img{
    opacity: 0.3;
}
.view h3{
    font-size: 20px;
    margin-left: 40%;
    cursor: pointer;
}

```

## OUTPUT:
![alt text](<Screenshot 2024-12-16 145942.png>)
![alt text](<Screenshot 2024-12-16 150007.png>)
![alt text](<Screenshot 2024-12-16 150046.png>)
![alt text](<Screenshot 2024-12-16 150055.png>)
![alt text](<Screenshot 2024-12-16 150116.png>) 

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
