# Ex.07 Restaurant Website
## Date:15.12.2024

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
index.html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Suvaiyagam - Home</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="header-container">
            
            <img src="logo.jpg" alt="Suvaiyagam restaurant logo" class="logo">
            <div class="menu-bar">
                <a href="menu.html">Menu</a>
                <a href="members.html">Members</a>
                <a href="reviews.html">Reviews</a>
                <a href="order.html">Place Order</a>
            </div>
        </div>
    </header>
    
    
    <section class="main-heading">
        <h1>Suvaiyagam</h1>
    </section>
    
    
    <section class="offer-banner">
        <div class="offer-content">
            <h2>Flat 15% Off for Christmas!</h2>
            <p>Celebrate the festive season with a special discount at Suvaiyagam. Enjoy authentic and delicious dishes with a 15% discount!</p>
        </div>
    </section>
    
   
    <section class="about-restaurant">
        <h3>About Suvaiyagam</h3>
        <p>Suvaiyagam is a place where tradition meets taste. Our dishes are crafted with passion, offering a memorable dining experience. We specialize in authentic local cuisine made with fresh ingredients, providing an unforgettable experience for food lovers.</p>
    </section>
</body>
</html>

members.html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Members - Suvaiyagam</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="header-container">
            <img src="logo.jpg" alt="Suvaiyagam Logo" class="logo">
            <div class="menu-bar">
                <a href="menu.html">Menu</a>
                <a href="members.html">Members</a>
                <a href="reviews.html">Reviews</a>
                <a href="order.html">Place Order</a>
            </div>
        </div>
    </header>

    <section class="team">
        <h2>Meet Our Team</h2>
        <div class="team-members">
            <div class="member">
                <img src="member1.jpg" alt="Member 1">
                <p>Harini-CEO</p>
            </div>
            <div class="member">
                <img src="member2.jpg" alt="Member 2">
                <p>Sivakarthikeyan-Head chef</p>
            </div>
            <div class="member">
                <img src="member3.jpg" alt="Member 3">
                <p>Saipallavi-Manager</p>
            </div>
            <div class="member">
                <img src="member4.jpg" alt="Member 4">
                <p>Soori-Chef</p>
            </div>
            <div class="member">
                <img src="member5.jpg" alt="Member 5">
                <p>Nani-Customer care</p>
            </div>
            <div class="member">
                <img src="member6.jpg" alt="Member 6">
                <p>Vadivelu-Chef</p>
            </div>
        </div>
    </section>
</body>
</html>

menu.html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Suvaiyagam - Menu</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="header-container">
            <img src="logo.jpg" alt="Suvaiyagam Logo" class="logo">
            <div class="menu-bar">
                <a href="index.html">Home</a>
                <a href="menu.html">Menu</a>
                <a href="members.html">Members</a>
                <a href="reviews.html">Reviews</a>
                <a href="order.html">Place Order</a>
            </div>
        </div>
    </header>
    
   
    <section class="menu">
        <h2>Our Menu</h2>
        <div class="menu-items">
            <div class="menu-row">
                <div class="menu-item">
                    <img src="biryani.jpg" alt="Dish 1">
                    <h4>Chicken biryani</h4>
                    <span>Rs.260/-</span>
                </div>
                <div class="menu-item">
                    <img src="chukka.jpg" alt="Dish 2">
                    <h4>Mutton chukka</h4>
                    <span>Rs.360/-</span>
                </div>
                <div class="menu-item">
                    <img src="prawn.jpg" alt="Dish 3">
                    <h4>Prawn Thokku</h4>
                    <span>Rs.400/-</span>
                </div>
            </div>
            <div class="menu-row">
                <div class="menu-item">
                    <img src="parotta.webp" alt="Dish 4">
                    <h4>Parotta</h4>
                    <span>Rs.40/-</span>
                </div>
                <div class="menu-item">
                    <img src="idli.jpg" alt="Dish 5">
                    <h4>Idli</h4>
                    <span>Rs.20/-</span>
                </div>
                <div class="menu-item">
                    <img src="dosai.jpg" alt="Dish 6">
                    <h4>Masala dosai</h4>
                    <span>Rs.50/-</span>
                </div>
            </div>
            <div class="menu-row">
                <div class="menu-item">
                    <img src="vadai.webp" alt="Dish 7">
                    <h4>Medhu vadai</h4>
                    <span>Rs.10/-</span>
                </div>
                <div class="menu-item">
                    <img src="paniyaram.jpg" alt="Dish 8">
                    <h4>Kuli paniyaram</h4>
                    <span>Rs.30/-</span>
                </div>
                <div class="menu-item">
                    <img src="payasam.jpg" alt="Dish 9">
                    <h4>Paal payasam</h4>
                    <span>Rs.55/-</span>
                </div>
            </div>
            <div class="menu-row">
                <div class="menu-item">
                    <img src="juice.jpg" alt="Dish 10">
                    <h4>Lemon juice</h4>
                    <span>Rs.10/-</span>
                </div>
                <div class="menu-item">
                    <img src="red velvet.webp" alt="Dish 11">
                    <h4>Red velvet pudding</h4>
                    <span>Rs.100/-</span>
                </div>
                <div class="menu-item">
                    <img src="moose.webp" alt="Dish 12">
                    <h4>Choclate moose</h4>
                    <span>Rs.85/-</span>
                </div>
            </div>
        </div>
    </section>
</body>
</html>

reviews.html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Reviews - Suvaiyagam</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="header-container">
            <img src="logo.jpg" alt="Suvaiyagam Logo" class="logo">
            <div class="menu-bar">
                <a href="menu.html">Menu</a>
                <a href="members.html">Members</a>
                <a href="reviews.html">Reviews</a>
                <a href="order.html">Place Order</a>
            </div>
        </div>
    </header>

    <section class="reviews">
        <h2>Customer Reviews</h2>
        <div class="review">
            <p>"Amazing food and great service!" - Customer 1</p>
        </div>
        <div class="review">
            <p>"Best restaurant in town!" - Customer 2</p>
        </div>
        <div class="review">
            <p>"Had a wonderful dining experience." - Customer 3</p>
        </div>
        <div class="review">
            <p>"Highly recommend the local dishes." - Customer 4</p>
        </div>
        <div class="review">
            <p>"Great ambiance and delicious food." - Customer 5</p>
        </div>
        <div class="review">
            <p>"A place worth visiting again and again." - Customer 6</p>
        </div>
        <div class="review">
            <p>"The flavors are incredible!" - Customer 7</p>
        </div>
        <div class="review">
            <p>"Would love to come back!" - Customer 8</p>
        </div>
        <div class="review">
            <p>"Perfect place for family dinners." - Customer 9</p>
        </div>
        <div class="review">
            <p>"Great experience overall." - Customer 10</p>
        </div>
    </section>
</body>
</html>

order.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Order - Suvaiyagam</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="header-container">
            <img src="logo.jpg" alt="Suvaiyagam Logo" class="logo">
            <div class="menu-bar">
                <a href="menu.html">Menu</a>
                <a href="members.html">Members</a>
                <a href="reviews.html">Reviews</a>
                <a href="order.html">Place Order</a>
            </div>
        </div>
    </header>

    <section class="order">
        <h2>Place Your Order</h2>
        <form>
            <label for="dish">Select Dish:</label>
            <select id="dish" name="dish">
                <option value="dish1">Dish 1</option>
                <option value="dish2">Dish 2</option>
                <option value="dish3">Dish 3</option>
                
            </select>
            <br>
            <label for="quantity">Quantity:</label>
            <input type="number" id="quantity" name="quantity" min="1" required>
            <br><br>
            <input type="submit" value="Place Order">
        </form>
    </section>
</body>
</html>

styles.css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}


body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    padding: 0;
    background-image:url(restaurant.jpg);
}


.header-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    color: white;
}

.logo {
    max-width: 150px;
    display: block;
    margin: 0 auto;
}

.menu-bar {
    display: flex;
    gap: 20px;
}

.menu-bar a {
    color: black;
    text-decoration:solid;
    font-size: 18px;
    padding: 10px;
}

.menu-bar a:hover {
    background-color: #575757;
    border-radius: 4px;
}


.main-heading {
    text-align: center;
    margin-top: 50px; 
    margin-bottom: 40px;
}

.main-heading h1 {
    font-size: 3rem;
    color: white;
    font-weight: bold;
}


.offer-banner {
    background-image:url(christmas.webp);
    padding: 40px 0;
    text-align: center;
    color: white;
}

.offer-banner h2 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

.offer-banner p {
    font-size: 1.2rem;
    max-width: 800px;
    margin: 0 auto;
}


.about-restaurant {
    text-align: center;
    padding: 40px 20px;
    background-color: #fff;
}

.about-restaurant h3 {
    font-size: 2rem;
    margin-bottom: 20px;
}

.about-restaurant p {
    font-size: 1.2rem;
    max-width: 900px;
    margin: 0 auto;
}


@media screen and (max-width: 768px) {
    .header-container {
        flex-direction: column;
        align-items: flex-start;
    }

    .menu-bar {
        margin-top: 15px;
        flex-direction: column;
        align-items: flex-start;
    }

    .menu-bar a {
        margin-left: 0;
        margin-bottom: 10px;
    }

    .offer-banner {
        height: 300px;
    }

    .offer-content h2 {
        font-size: 32px;
    }

    .offer-content p {
        font-size: 16px;
    }

    .about-restaurant {
        width: 90%;
    }
}

.menu {
    width: 80%;
    margin: 40px auto;
    text-align: center;
}

.menu h2 {
    font-size: 36px;
    margin-bottom: 20px;
}

.menu-items {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
}

.menu-row {
    display: flex;
    justify-content: space-between;
    margin-bottom: 20px;
    width: 100%;
}

.menu-item {
    width: 30%;
    background-color: #ffffff;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    text-align: center;
    padding: 15px;
    transition: transform 0.3s ease;
}

.menu-item:hover {
    transform: scale(1.05);
}

.menu-item img {
    width: 100%;
    height: auto;
    border-radius: 8px;
}

.menu-item h4 {
    font-size: 20px;
    color: #333;
    margin-top: 10px;
}

.menu-item p {
    font-size: 16px;
    color: #555;
}

.menu-item span {
    font-size: 18px;
    font-weight: bold;
    color: #e76f51;
    margin-top: 10px;
}


@media screen and (max-width: 768px) {
    .menu-items {
        flex-direction: column;
    }

    .menu-row {
        flex-direction: column;
        align-items: center;
    }

    .menu-item {
        width: 80%;
        margin-bottom: 20px;
    }
}



.team-members {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
}

.member img {
    width: 50%;
    border-radius:10%;
}

.member p {
    text-align: center;
    margin-top: 10px;
    color:white;
    text-style:bold;
}


.reviews {
    padding: 20px;
    color:black;
    background-color:orangered;
}

.review {
    margin-bottom: 20px;
}


.order {
    padding: 20px;
    text-align: center;
}

input[type="number"], select {
    padding: 10px;
    margin: 10px 0;
    font-size: 16px;
    border-radius: 5px;
    border: 1px solid #ccc;
}

input[type="submit"] {
    background-color: #f4a261;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

input[type="submit"]:hover {
    background-color: #e76f51;
}
```         


## OUTPUT:
![alt text](<Screenshot (38).png>)
![alt text](<Screenshot (39).png>)
![alt text](<Screenshot (40).png>)
![alt text](<Screenshot (41).png>)
![alt text](<Screenshot (42).png>)

## RESULT:
The program for designing restaurant website using HTML and CSS is completed successfully.
