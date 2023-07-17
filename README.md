# Melanie-Hua.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>START BOOTSTRAP</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>
        body {
            margin: 0;
            padding: 0;
        }

        .fa-star {
            font-size: 30px;
            margin: 0 10px;

        }

        hr {
            display: inline-block;
            width: 100px;
            height: 5px;
            border-radius: 5px;
            background-color: white;
            border: none;
        }

        #navbar {
            position: fixed;
            font-size: 16px;
            background-color: #2C3E50;
            color: white;
            width: 100%;
            padding-top: 7px;
            padding-bottom: 7px;
            padding-left: 6.25%;
        }

        #navbar p {
            font-family: sans-serif;
            font-size: 20px;
            font-weight: 600;

        }

        #navbar button {
            background-color: #1abc9c;
            width: 84.7px;
            height: 42.4px;
            color: white;
            border-radius: 8px;
            float: right;
            margin-top: -52px;
            margin-right: 12.5%;
            border: none;
        }

        #header {
            padding-top: 207px;
            background-color: #1abc9c;
            width: 100%;
            margin: 0;
            text-align: center;
            color: white;

        }

        #header p {
            text-align: center;
            color: white;
            background-color: #1abc9c;
            padding-bottom: 96px;
            font-family: sans-serif;
            font-size: 20px;
        }

        #header img {
            width: 240px;
            background-color: #1abc9c;


        }

        #header h1 {
            margin-top: 48px;
            display: block;
            font-size: 40px;
            font-family: sans-serif;
        }

        #separator {
            display: block;
            margin: 24px;
        }

        #separator hr {
            background-color: white;

        }

        #portfolio h2 {
            color: #2C3E50;
            text-align: center;
            font-family: sans-serif;
            font-size: 35px;
            margin: 20px 0px 24px;
            padding-top: 96px;
        }


        #portfolio h2 icon hr {
            background-color: #2C3E50;

        }

        #portfolio icon {
            display: block;
            margin-top: 24px;
        }

        #portfolio picture {
            display: inline-block;
            /*
                        margin: 40px;
*/
            margin-bottom: 70px;
            text-align: center;

        }

        #portfolio picture img {
            /*     width: 47.3%;*/
            border-radius: 4%;
            /*
            margin-bottom: 20px;
*/
            margin: 7px;
            height: 220px;
            margin-top: 30px;
            transition: 0.01s;

        }

        #portfolio picture img:hover {
            /*
           filter: opacity(50%)
*/
            filter: opacity(50%)
        }

        #about {
            background-color: #1ABC9C;
            padding: 96px;
        }

        #about #text {
            margin: 12px;
            color: white;
        }

        #about h2 {
            color: white;
            text-align: center;
            font-family: sans-serif;
            font-size: 35px;
            margin: 20px 0px 24px;
            background-color: #1ABC9C;
        }

        #about #icon {
            text-align: center;
            color: white;
            margin-top: 20px;
            margin-bottom: 24px;
        }

        #about #text p {
            text-align: center;
            float: none;
            font-family: sans-serif;
            margin: 16px;
            font-size: 20px;
        }

        #about #button {
            text-align: center;
            margin-top: 24px;
        }

        #about #button button {
            height: 65.2px;
            width: 237.1px;
            border-radius: 8px;
            border: solid white;
            background-color: #1ABC9C;
            color: white;
            font-size: 20px;
            transition: 0.2s;

        }

        #about #button button i {
            margin-right: 6px;
        }

        #about #button button:hover {
            background-color: white;
            color: black
        }

        #contact {
            padding: 96px;
            color: #2C3E50;
        }

        #contact h1 {
            text-align: center;
            font-family: sans-serif;
            font-size: 36px;

        }

        #contact #icon hr {
            background-color: #2C3E50;
        }

        #contact #icon {
            text-align: center;
        }

        #contact #input {

            padding: 12px;
        }

        #contact #input input {
            font-size: 24px;
            width: 100%;
            border-top: none;
            border-left: none;
            border-right: none;
            padding-top: 40px;
            padding-bottom: 27px;
            border-bottom: solid 1px #ced4da;
        }


        #contact button {
            background-color: #1abc9c;
            color: white;
            border: none;
            width: 90px;
            height: 60px;
            border-radius: 8px;
            font-size: 16px;
            margin-left: 12px;
        }

        #footer {
            background-color: #2c3e50;
            color: white;
            padding: 80px;
            text-align: center;

        }

        #footer h4 {
            font-family: sans-serif;
            margin-bottom: 24px;
            font-size: 24px;
        }

        #footer p {
            font-family: sans-serif;
            font-size: 20px;
        }

        #footer i {
            border: solid white 1px;
            border-radius: 50%;
            width: 52px;
            height: 38px;
            margin: 4px;
            padding-top: 14px;
            font-size: 24px;
            transition: 0.2s;
        }

        #footer i:hover {
            background-color: white;
            color: black;
        }

        #footer u {
            color: #1abc9c;
        }

        #footer u:hover {
            filter: opacity(70%);
        }

        #footer #part1,
        #footer #part2 {
            margin-bottom: 48px;
        }

        #copyright {
            color: white;
            background-color: #1a252f;
            text-align: center;
            font-size: 14px;
            padding: 24px;
            font-family: sans-serif;
        }
    </style>
</head>

<body>

    <div id="navbar">
        <p>START BOOTSTRAP</p> <button>MENU</button>
    </div>

    <section id="header">

        <img src="https://startbootstrap.github.io/startbootstrap-freelancer/assets/img/avataaars.svg" alt="">
        <h1>START BOOTSTRAP</h1>
        <div id=separator>
            <hr>
            <i class="fa-solid fa-star"></i>
            <hr>
        </div>
        <p>
            Graphic Artist - Web Designer - Illustrator
        </p>
    </section>

    <section id=portfolio>
        <h2>PORTFOLIO
            <icon>
                <hr>
                <i class="fa-solid fa-star"></i>
                <hr>
            </icon>
        </h2>
        <picture>
            <img src="https://startbootstrap.github.io/startbootstrap-freelancer/assets/img/portfolio/cabin.png
" alt="">
            <img src="https://startbootstrap.github.io/startbootstrap-freelancer/assets/img/portfolio/cake.png" alt="">
            <img src="https://startbootstrap.github.io/startbootstrap-freelancer/assets/img/portfolio/circus.png" alt="">
            <img src="https://startbootstrap.github.io/startbootstrap-freelancer/assets/img/portfolio/game.png
" alt="">
            <img src="https://startbootstrap.github.io/startbootstrap-freelancer/assets/img/portfolio/safe.png" alt="">
            <img src="https://startbootstrap.github.io/startbootstrap-freelancer/assets/img/portfolio/submarine.png" alt="">
        </picture>
    </section>

    <section id=about>

        <h2>ABOUT</h2>

        <div id="icon">
            <hr>
            <i class="fa-solid fa-star"></i>
            <hr>
        </div>
        <section id="text">
            <p>Freelancer is a free bootstrap theme created by Start Bootstrap. The download includes the complete source files including HTML, CSS, and JavaScript as well as optional SASS stylesheets for easy customization.</p>
            <p>You can create your own custom avatar for the masthead, change the icon in the dividers, and add your email address to the contact form to make it fully functional!</p>
        </section>


        <div id="button">
            <button>
                <i class="fa-solid fa-download"></i> Free Download!
            </button>

        </div>

    </section>


    <section id="contact">

        <h1>CONTACT ME</h1>
        <div id="icon">
            <hr>
            <i class="fa-solid fa-star"></i>
            <hr>
        </div>

        <div id="input">
            <input type="Name" placeholder="Full Name">
            <input type="Email" placeholder="Email address">
            <input type="Phone" placeholder="Phone number">
            <input type="msg" placeholder="Message">
        </div>


        <button>
            Send
        </button>
    </section>

    <section id="footer">
        <div id="part1">
            <h4>LOCATION</h4>

            <p>2215 John Daniel Drive Clarc, MO 65243</p>

        </div>

        <div id="part2">
            <h4>AROUND THE WEB</h4>

            <div id="icon">
                <i class="fa-brands fa-facebook-f"></i>
                <i class="fa-brands fa-twitter"></i>
                <i class="fa-brands fa-linkedin-in"></i>
                <i class="fa-brands fa-dribbble"></i>
            </div>

        </div>


        <div id="part3">
            <h4>ABOUT FREELANCER</h4>


            <p>Freelance is a free to use, MIT licensed Bootstrap theme created by <u>Start Bootstrap</u>.</p>
        </div>

    </section>

    <div id="copyright">
        Copyright © 华晟杉 / Melanie Sheng Shan Hua
    </div>

</body></html>



