- Create a page according to the layout shown below.

![Building HTML forms Assignment level 2](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/building-html-forms/ex-2.png)

- Using CSS resets is necessary.

- Use semantic tags and keep the nesting and indentation proper.
- <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Building-forms assignment1</title>
    <link rel="stylesheet" href="assets/style.css">
    <script src="https://kit.fontawesome.com/ef43d9bbc3.js" crossorigin="anonymous"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;500;600;700;800&display=swap" rel="stylesheet"> 
</head>
<body class="container">
    <header class="flex">
        <div class="logo flex">
            <img src="assets/logo.png" alt="logo">
            <h2><strong>JOURNEY</strong></h2>
        </div>
        <nav>
            <ul class="header-logo flex">
                <li><a href="#">Home</a></li>
                <li><a href="#">Top Destinations</a></li>
                <li><a href="#">Recommended Places</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="begin">
            <h1>LET'S BEGIN</h1>
            <div class="circles">
            <figure class="circ1"></figure>
            <figure class="circ2 circ1"></figure>
            <figure class="circ3 circ1"></figure>
            </div>
            <h6>We assist you to choose the best.</h6>
            <button class="begin-btn">
                &#x2304;
            </button>
            <form class="begin-form flex" action="index.html" method="POST">
                <fieldset class="begin-form-left">
                    <legend class="destination">
                    <label for="destination">
                        Choose your destination
                        <input type="text" name="destination" placeholder="Type your destination" id="destination"> 
                    </label>
                    </legend>
                    <legend class="dates flex">
                    <label for="Checkin">
                        Check In Date
                        <input type="text" name="Checkin" placeholder="Check In" id="Checkin"> 
                    </label>
                    <label for="Checkout">
                        Check Out Date
                        <input type="text" name="Checkout" placeholder="Check In" id="Checkout"> 
                    </label>
                    </legend>
                </fieldset>
                <fieldset class="begin-form-right">
                    <legend class="flex">
                        <label for="rooms">
                            How many rooms?
                            <input type="number" name="rooms" placeholder="" id="rooms" value="1"> 
                        </label>
                        <label for="adult">
                            Adult<br>
                            <input type="number" name="adult" placeholder="" id="adult" value="1"> 
                        </label>
                        <label for="child">
                            Children<br>
                            <input type="number" name="child" placeholder="" id="child" value="0"> 
                        </label>
                    </legend>
                    <legend class="btn">
                            <input type="button" name="destination" placeholder="Type your destination" id="destination" value="Check Availability" > 
                    </legend>
                </fieldset>
            </form>
        </section>
        <section class="begin your-journey">
            <article>
            <h2>YOUR <strong>JOURNEY </strong>IS OUR PRIORITY</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris urna nibh, maximus ac sapien sed, egestas ultrices urna.
                 Vestibulum dolor elit, tempor faucibus urna ut, ullamcorper feugiat nisl. Etiam vel fringilla nibh.
            </p>
            <button>
                CONTINUE EXPLORE
            </button>
            </article>
        </section>
        <section class="europe">
            <img class="euro-img" src="assets/tm-img-01.jpg" alt="1">
            <div class="nav-euro flex">
                <button class="nav1">
                    <i class="fas fa-chevron-circle-left"></i>
                </button>
                <button class="nav1">
                    <i class="fas fa-chevron-circle-right"></i>
                </button>
            </div>
            <article class="art">
                <h2>Europe's most visited places</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris urna nibh, maximus ac sapien sed, egestas ultrices urna.
                    Vestibulum dolor elit
                </p>
                <button>
                    CONTINUE READING
                </button>
            </article>
            </div>
            </article>
        </section>
        <section class="europe asia">
            <img class="asia-img" src="assets/tm-img-02.jpg" alt="1">
            <div class="nav-euro nav-asia flex">
                <button class="nav1">
                    <i class="fas fa-chevron-circle-left"></i>
                </button>
                <button class="nav1">
                    <i class="fas fa-chevron-circle-right"></i>
                </button>
            </div>
            <article class="art asia-art">
                <h2>Asia's most visited places</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris urna nibh, maximus ac sapien sed, egestas ultrices urna.
                    Vestibulum dolor elit
                </p>
                <button>
                    CONTINUE READING
                </button>
            </article>
            </div>
            </article>
        </section>
        <section class="europe america">
            <img class="euro-img" src="assets/tm-img-03.jpg" alt="1">
            <div class="nav-euro flex">
                <button class="nav1">
                    <i class="fas fa-chevron-circle-left"></i>
                </button>
                <button class="nav1">
                    <i class="fas fa-chevron-circle-right"></i>
                </button>
            </div>
            <article class="art">
                <h2>America's most visited places</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris urna nibh, maximus ac sapien sed, egestas ultrices urna.
                    Vestibulum dolor elit
                </p>
                <button>
                    CONTINUE READING
                </button>
            </article>
            </div>
            </article>
        </section>
        <section class="world flex">
            <div class="world-1">
                <img src="assets/north-america.png" alt="america">
                <h5>NORTH AMERICA</h5>
            </div>
            <div class="world-1">
                <img src="assets/south-america.png">
                <h5>SOUTH AMERICA</h5>
            </div>
            <div class="world-1">
                <img src="assets/europe.png">
                <h5>EUROPE</h5>
            </div>
            <div class="world-1 asia-1">
                <img src="assets/north-america.png">
                <h5>ASIA</h5>
            </div>
            <div class="world-1">
                <img src="assets/north-america.png">
                <h5>AFRICA</h5>
            </div>
            <div class="world-1">
                <img src="assets/north-america.png">
                <h5>AUSTRALIA</h5>
            </div>
            <div class="world-1">
                <img src="assets/north-america.png">
                <h5>ANTARCTICA</h5>
            </div>
        </section>
        <section class="more-places">
            <article class="more-places1 flex">
                <img src="assets/tm-img-07.jpg">
                <article class="round">
                    <h5>ASIA RESORT HOTEL</h5>
                    <p class="pink">Singapore</p>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris urna nibh, maximus ac sapien sed</p>
                </article>
                <div class="money">
                    <h2>$450</h2>
                    <h4>CONTINUE READING</h4>
                </div>
            </article>
            <article class="more-places1 flex">
                <img src="assets/tm-img-04.jpg">
                <article class="round">
                    <h5>ASIA RESORT HOTEL</h5>
                    <p class="pink">Singapore</p>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris urna nibh, maximus ac sapien sed</p>
                </article>
                <div class="money">
                    <h2>$450</h2>
                    <h4>CONTINUE READING</h4>
                </div>
            </article>
            <article class="more-places1 flex">
                <img src="assets/tm-img-05.jpg">
                <article class="round">
                    <h5>ASIA RESORT HOTEL</h5>
                    <p class="pink">Singapore</p>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris urna nibh, maximus ac sapien sed</p>
                </article>
                <div class="money">
                    <h2>$450</h2>
                    <h4>CONTINUE READING</h4>
                </div>
            </article>
            <article class="more-places1 flex">
                <img src="assets/tm-img-06.jpg">
                <article class="round">
                    <h5>ASIA RESORT HOTEL</h5>
                    <p class="pink">Singapore</p>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris urna nibh, maximus ac sapien sed</p>
                </article>
                <div class="money">
                    <h2>$450</h2>
                    <h4>CONTINUE READING</h4>
                </div>
            </article>
            <button>
                SHOW MORE PLACES
            </button>
        </section>
        <section class="contact-form">
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2483.5406050415136!2d-0.12174238389824883!3d51.503297279634445!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x487604b900d26973%3A0x4291f3172409ea92!2slastminute.com%20London%20Eye!5e0!3m2!1sen!2sin!4v1635327273185!5m2!1sen!2sin" width="1400" height="650" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
                <form class="contact-form1" action="index.html" method="POST">
                    <fieldset>
                            <div class="flex">
                            <input type="text" name="name" placeholder="Name">
                            <input type="email"  name="email" placeholder="Email">
                            </div>
                            <input type="text" name="subject" placeholder="Subject">
                            <textarea name="message" placeholder="Message" cols="80" rows="10"></textarea>
                            <input class="button2" type="button" name="send message" value="SEND MESSAGE NOW">
                    </fieldset>
                </form>
        </section>
    </main>
    <footer>
        <p>Copyright &#xA9; 2021,Your Company. Designed by Template Mo</p>
    </footer>
</body>
</html>
