- Create a forms according to the layout shown below.

![Building HTML forms Assignment level 1](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/building-html-forms/ex-1.jpg)

- Using CSS resets is necessary.

- Use semantic tags and keep the nesting and indentation proper.
<!DOCTYPE html>
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
<body>
    <main>
        <div class="box1">
        <article>
            <h1>Learn to code by watching others</h1>
            <p>See how experienced developers solve problem in real time.<br>
                Watching scripted tutorials is great,but understanding how <br> developers think invaluable
            </p>
        </article>
        <div class="form">
             <div class="trial">
                 <h2> <b>Try it free 7 days</b> then &#36;20/mo. thereafter </h2>
             </div>
             <form action="index.html" method="POST">
                 <fieldset>
                 <input type="text" name="firstname" placeholder="Name">
                 <input type="text" name="lastname" placeholder="Last Name">
                 <input type="email" name="email" placeholder="Email-Address">
                 <input type="password" name="password" placeholder="Password">
                 <button>
                     Claim your free trial
                 </button>
                 <p>By clicking to the following you are agreeing to our <span>Terms and Services</span></p>
                 </fieldset>
             </form>
        </div>
        </div>

    </main>
</body>
</html>
