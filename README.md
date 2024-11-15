# Ex.07 Restaurant Website
## Date: 15-11-2024

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
Index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Restaurant</title>
</head>
<body>
    <div class="container">
        <header>
            <h1>Lan Delight Restaurent</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="administration.html">Administration</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <h2>Discover Delicious Meals!</h2>
            <section class="menu-items">
                <div class="food-item">
                    <img src="images/pasta.jpeg" alt="Delicious Pasta">
                    <h4>Italian Pastas</h4>
                    <p>A creamy delight with fresh herbs and parmesan cheese.</p>
                </div>
                <div class="food-item">
                    <img src="images/burger.jpeg" alt="Juicy Burger">
                    <h4>Burgers</h4>
                    <p>Juicy beef patty with lettuce, tomato, and our special sauce.</p>
                </div>
                <div class="food-item">
                    <img src="images/salad.jpeg" alt="Fresh Salad">
                    <h4>Garden Salads</h4>
                    <p>A mix of fresh greens and seasonal vegetables.</p>
                </div>
                <div class="food-item">
                    <img src="images/dessert.jpeg" alt="Dessert">
                    <h4>Chocolate Cakes</h4>
                    <p>Rich and moist chocolate cake with a creamy frosting.</p>
                </div>
            </section>
        </main>
        
        
        <footer>
            <p>Sai Sruthi.V</p>
            <p>212223100061</p>
        </footer>
    </div>
</body>
</html>
```
Menu.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Menu</title>
</head>
<body>
    <div class="container">
        <header>
            <h1>Sangeetha Restaurant</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="administration.html">Administration</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <h2>Delicious Food Items</h2>
            <section class="menu-items">
                <div class="food-item">
                    <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\5BD7F2FEFF1F11170A507FCD0C0E9734\WhatsApp Image 2024-11-07 at 10.45.08_a1a202da.jpg" alt=" Chicken Wings">
                    <h4> Chicken Wings</h4>
                </div>
                <div class="food-item">
                    <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\5C6EF67E6079F0CDD640A5AD7C288E36\WhatsApp Image 2024-11-07 at 10.46.57_d40efb00.jpg" alt="Cheese noodles">
                    <h4>Cheese noodles</h4>
                </div>
                <div class="food-item">
                    <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\CCD986D2DE4C75133C049E26005B3DBC\WhatsApp Image 2024-11-07 at 10.48.22_4ea050ed.jpg" alt="Pimento cheese">
                    <h4>Pimento cheese</h4>
                </div>
                <div class="food-item">
                    <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\0BC58258E6F3C040A65FA2BFC9D0C907\WhatsApp Image 2024-11-07 at 10.51.15_4355b887.jpg" alt="Beef Tacos">
                    <h4>Beef Tacos</h4>
                </div>
                <div class="food-item">
                    <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\C6C209418814B5CEE2107E6E744BB737\WhatsApp Image 2024-11-07 at 10.49.39_fd114a58.jpg" alt="chocolate cake">
                    <h4>chocolate cake</h4>
                </div>
                <div class="food-item">
                    <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\37AFE5DE7AFBFC1D2C5B27FC33D82A5F\WhatsApp Image 2024-11-07 at 10.21.03_304bffa7.jpg" alt="Cesar Salad">
                    <h4>Cesar Salad</h4>
                </div>
                <div class="food-item">
                    <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\3A647FF6D4D2328A51836AE6AB9600EB\WhatsApp Image 2024-11-07 at 10.32.26_d472edab.jpg" alt="Cheeseburger">
                    <h4>Cheeseburger</h4>
                </div>
                <div class="food-item">
                    <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\90A9BEEC2356E3613F667E20704C953D\WhatsApp Image 2024-11-07 at 10.34.21_399b5f9c.jpg" alt="Chicken Tikka Masala">
                    <h4>Chicken Tikka Masala</h4>
                </div>
                <div class="food-item">
                    <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\5824AA83D1AE73B56A67273714B57843\WhatsApp Image 2024-11-07 at 10.36.05_53c1f82e.jpg" alt="Mutton Soup">
                    <h4>Mutton Soup</h4>
                </div>
                <div class="food-item">
                    <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\5BD7F2FEFF1F11170A507FCD0C0E9734\WhatsApp Image 2024-11-07 at 10.45.08_54090e60.jpg" alt="Paneer Kurkure">
                    <h4>Paneer Kurkure</h4>
                </div>
                <div class="food-item">
                    <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\CCD986D2DE4C75133C049E26005B3DBC\WhatsApp Image 2024-11-07 at 10.48.22_43f32e6d.jpg" alt="Tortillas">
                    <h4>Tortillas</h4>
                </div>
                <div class="food-item">
                    <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\3D0E9613972282A4E53F300F804C1B4F\WhatsApp Image 2024-11-07 at 10.19.10_75985bd8.jpg" alt="Ice cream">
                    <h4>Ice cream</h4>
                </div>
            </section>
        </main>
        
        <footer>
            <p>Sai Sruthi.V</p>
            <p>212223100061</p>
        </footer>
    <div>
    
</body>
</html>
```
Administration.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Administration</title>
</head>
<body>
    <div class="container">
        <header>
            <h1>Sangeetha Restaurant</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="administration.html">Administration</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <h2>Meet Our Team</h2>
            <div class="team">
                <div class="member">
                    <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\CAD5A325C48A0E53242EE2079A4BBCA2\WhatsApp Image 2024-11-07 at 11.02.22_d656e42d.jpg" alt="Admin 1">
                    <p>Martin - Manager</p>
                </div>
                <div class="member">
                    <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\F2904D6B4000D5402B14177A4F8704F3\WhatsApp Image 2024-11-07 at 11.04.16_11f90609.jpg" alt="Admin 2">
                    <p>Andrea - Chef</p>
                </div>
                <div class="member">
                    <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\ADCA3FBBC686891075A97939F99EACFB\WhatsApp Image 2024-11-07 at 11.06.44_9a9a09ea.jpg" alt="Admin 3">
                    <p>John  - Waiter</p>
                </div>
                <div class="member">
                    <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\216DB3E862DF3FB6D8B3EFA5B09A8A59\WhatsApp Image 2024-11-07 at 11.09.43_565ce680.jpg" alt="Admin 4">
                    <p>Trump - Bartender</p>
                </div>
                <div class="member">
                    <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\1989D2D0108AF415AC8A9A3B13090A95\WhatsApp Image 2024-11-07 at 11.12.34_ec2aa0ce.jpg" alt="Admin 5">
                    <p>Bailu - Hostess</p>
                </div>
                <div class="member">
                    <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\976782D3370C14312A65F6C9F6B2A7CB\WhatsApp Image 2024-11-07 at 11.14.16_e48f63a8.jpg" alt="Admin 6">
                    <p>Dylan - Accountant</p>
                </div>
            </div>
        </main>
        <footer>
            <p>Sai Sruthi.V</p>
            <p>212223100061</p>
        </footer>

    </div>
    
</body>
</html>
```
contact.html
```
style.css
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Contact Us</title>
</head>
<body>
    <div class="container">
        <header>
            <h1>Sangeetha Restaurant</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="administration.html">Administration</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <h2>Get in Touch</h2>
            <p>Address: Old no 16, new 86, 3rd Ave, W Block, Anna Nagar, Chennai, Tamil Nadu 600102</p>
            <p>Phone: 089399 94114</p>
            <p>Reservations: eazydinner.com, zomato.com</p>
            <p>Open Hours: 6–11 pm</p>
        </main>
        <footer>
            <p>ETTA SUPRAJA</p>
            <p>212223220022</p>
        </footer>

    </div>
    
</body>
</html>
```
Style.css
```
* {
    box-sizing: border-box;
}

html, body {
    height: 100%;
    margin: 0;
}

body {
    font-family: Arial, sans-serif;
    background-color: #ecf0f1;
    color: #2c3e50;
}

.container {
    display: flex;
    flex-direction: column;
    min-height: 50vh;
}

header {
    background-color:rgb(4, 8, 68);
    color: white;
    padding: 20px;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

h1, h2 {
    margin: 10px 0;
}

main {
    flex: 1; 
    padding: 20px;
}

.team {

    display: flex;
    flex-wrap: wrap;
}

.member {
    width: 30%;
    margin: 10px;
    text-align: center;
}

.member img {
    width: 50%;
    height: auto;
    border-radius: 50%;
}

footer {
    text-align: center;
    padding: 20px;
    background-color:rgb(4, 8, 68);
    color: white;
}
.member
{
    border-radius:50%;
    width: 10%;
    height: 10%;
}
.menu-items {
    display: flex;
    flex-wrap: wrap; 
    justify-content: space-between; 
    margin: 20px 0; 
}

.food-item {
    flex: 1 1 200px; 
    margin: 10px; 
    text-align: center; 
}

.food-item img {
    width: 80%; 
    height: 80%; 
    border-radius: 8px; 
}
.menu-items {
    display: flex;
    flex-wrap: wrap; 
    justify-content: space-between; 
    margin: 20px 0; 
}

.food-item {
    width:10%;
    height: 10%;
    flex: 1 1 200px;
    margin: 10px; 
    text-align: center; 
}

.food-item img {
    width: 50%; 
    height: 5%; 
    border-radius: 8px; 
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/3542a78b-d923-4535-9c5b-a9e070939a71)
![image](https://github.com/user-attachments/assets/4cb7d3d5-340e-4d97-9c67-c9926b8dc946)
![image](https://github.com/user-attachments/assets/693bcc3c-c14c-415a-ac60-9bbd050c4ce0)
![image](https://github.com/user-attachments/assets/afc1718b-a00f-4c23-8174-c9fc36bd2744)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
