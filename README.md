<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vipul - Developer Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            background-color: rgb(0, 0, 33);
            color: white;
        }

        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 80px;
            background-color: rgb(18, 18, 62);
        }

        nav ul {
            display: flex;
            justify-content: center;
        }

        nav ul li {
            list-style: none;
            margin: 0 23px;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
        }

        nav ul li a:hover {
            color: rgb(153, 153, 226);
        }

        main hr {
            border: 0;
            background: #9c97f1;
            height: 1.2px;
            margin: 40px 84px;
        }

        .left {
            font-size: 1.5rem;
        }

        .firstSection {
            display: flex;
            justify-content: space-around;
            align-items: center;
            margin: 130px 0;
        }

        .firstSection>div {
            width: 30%;
        }

        .leftSection {
            font-size: 3rem;
        }
        .leftSection .buttons{
            padding: 50px 0;
        }

        .leftSection .btn{
            padding: 12px;
            background: #1e2167;
            color: white;
            border: 2px solid white;
            border-radius: 6px;
            font-size: 20px;
            cursor: pointer;

        }

        .rightSection img {
            width: 80%;
        }

        .purple {
            color: rgb(170, 107, 228);
        }

        .text-gray {
            color: gray;
        }

        #element {
            color: rgb(170, 107, 228);
        }

        .secondSection {
            max-width: 80vw;
            margin: auto;
            height: 80vh;
        }

        .secondSection h1 {
            font-size: 1.9rem;
        }

        .secondSection .box {
            background: white;
            width: 80vw;
            height: 2px;
            margin: 56px 0;
            display: flex;
        }

        .secondSection .vertical {
            height: 93px;
            width: 1px;
            background-color: white;
            margin: 0 120px;
        }

        .image-top {
            width: 23px;
            position: relative;
            top: -32px;
            left: -9px;
        }

        .vertical-title {
            position: relative;
            top: 75px;
            width: 150px;
            font-size: 14px;
        }

        .vertical-desc {
            position: relative;
            top: 86px;
            color: gray;
            width: 150px;
            font-size: 12px;

        }

        footer {
            background-color: #0e0e1a;
        }

        .footer {
            display: flex;
            padding: 23px 122px;
            justify-content: space-evenly;
        }

        .footer ul {
            list-style: none;
        }
        .footer > div{
            width: 223px;
        }
        footer .footer-rights{
           text-align: center; 
           color: gray;
           padding: 12px;
        }
    </style>
</head>

<body>
    <header>
        <nav>
            <div class="left">Vipul's Portfolio</div>
            <div class="right">
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="/">Services</a></li>
                    <li><a href="http://localhost/VIPUL/index.html">Projects</a></li>
                    <li><a href="#Contact">Contact Me</a></li>
                </ul>
            </div>
        </nav>
    </header>
    <main>
        <section class="firstSection">
            <div class="leftSection">
                Hi, My name is <span class="purple"> Vipul</span>
                <div>and I am a Passionate</div>

                <span id="element"></span>
                <div class="buttons">
                    <button class="btn"><a href="https://www.linkedin.com/in/vipul-pawar-2b7a29252/" style=" text-decoration: none; color: inherit">My linked in profile</a></button>
                    <button class="btn"><a href="https://github.com/vippawar1104" style=" text-decoration: none; color: inherit"> Visit Github</a></button>
                </div>
            </div>
            <div class="rightSection">
                <img src="https://www.pngitem.com/pimgs/m/112-1127587_software-hire-developers-hd-png-download.png"
                    alt="">
            </div>
        </section>
        <hr>
        <section class="secondSection">
            <span class="text-gray">What I have done so far</span>
            <h1>Work Experience</h1>
            <div class="box">

                <div class="vertical">
                    <img class="image-top" src="https://w7.pngwing.com/pngs/201/90/png-transparent-logo-html-html5.png"
                        alt="">
                    <div class="vertical-title">
                        HTML Developer (2022-2023)
                    </div>
                    <div class="vertical-desc">
                    I have studied HTML in 7th standard . But properly i have studied HTML inn my college.
                    and now i know everything about HTML.  About it's attributes which are used to define aditional 
                    characteristics or the behaviour of HTML elemments. They provide instructions and information to the browser about how an element should be displayed or behave.
                    I have made various projects using HTML,CSS,JS
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top"
                        src="https://w7.pngwing.com/pngs/56/223/png-transparent-node-js-javascript-computer-icons-github-angle-text-logo.png"
                        alt="">
                    <div class="vertical-title">
                        Node.js Developer (2022-2023)
                    </div>
                    <div class="vertical-desc">
                   I have also studied node.js but at a small level. i have not studied it fully. 
                   Node.js is a powerful JavaScript runtime that allows you to build various types of applications.
                   Node.js is well-suited for building web applications, both on the server-side and the client-side. 
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="https://upload.wikimedia.org/wikipedia/commons/1/19/C_Logo.png" alt="">
                    <div class="vertical-title">
                        C language coder (2022-2023)
                    </div>
                    <div class="vertical-desc">
                        I have studied C language for the first time in  my College. and Now i am coding on c language only.
                        I have studied C language inmy first semester and i am giving contests on codechef,codeforces in 
                        c language only. I know its a low level programming language thats why i have also studied python language
                        which is a high level programming language.
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top"
                        src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/1869px-Python-logo-notext.svg.png"
                        alt="">
                    <div class="vertical-title">
                        Python (2022-2023)
                    </div>
                    <div class="vertical-desc">
                    I have mainly studied python from the online courses from youtube such as code with harry which helped me a lot.
                    I have also studied it in my College. It is a high -level programming language which is known for it's
                    simplicity, readability, and versatility.
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top"
                        src="https://w7.pngwing.com/pngs/609/813/png-transparent-web-development-html-php-cascading-style-sheets-javascript-world-wide-web-blue-text-logo.png"
                        alt="">
                    <div class="vertical-title">
                        php,My Sql,javascript(2022-2023)
                    </div>
                    <div class="vertical-desc">
                    These languages php,My Sql,javascript are also very important for a Web Developer. I have also studied 
                    these languages in my second semester. through php we can create a connection between our frontend project and 
                    our backend languages . Through javascript we can create animations in our webiste.
                    </div>
                </div>
            </div>

        </section>
    </main>
    <footer>
        <div class="footer" id="Contact">
            <div class="footer-first">
                <h3>Vipul's Developer Portfolio</h3>
            </div>
            <div class="footer-second">
                <ul>
                    <!-- <li>Home</li>
                    <li>About Me</li> -->
                    <li><a href="https://www.linkedin.com/in/vipul-pawar-2b7a29252/" style=" text-decoration: none; color: inherit">My linked in profile</a</li>
                    <li><a href="https://www.instagram.com/vippawar1104/" style=" text-decoration: none; color: inherit" >Follow Me On Instagram</a></li>
                    <li>vipulpawar81077@gmail.com</li>

                </ul>
            </div>
            <!-- <div class="footer-third">
                <ul>
                    <li>Home</li>
                    <li>About</li>
                    <li>Services</li>
                    <li>Projects</li>
                    <li>Contact</li>

                </ul>
            </div>
            <div class="footer-fourth">
                <ul>
                    <li>Home</li>
                    <li>About</li>
                    <li>Services</li>
                    <li>Projects</li>
                    <li>Contact</li>

                </ul> -->
            </div>
        </div>
        <div class="footer-rights">
            Copyright &#169; www.vipul'sportfolio.com | All rights reserved
        </div>
    </footer>
    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
    <script>
        var typed = new Typed('#element', {
            strings: ['Web Developer', 'Coder', 'Web Designer', 'Video Editor'],
            typeSpeed: 50,
        });
    </script>
</body>

</html>
