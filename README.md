<!DOCTYPE html>
<html lang="en">

<head>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RANJEET-PORTFOLIO</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;

        }

        body {
            background-color: rgb(7, 7, 182);
            color: white;
            font-family: 'Poppins', sans-serif;
        }

        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 80px;
            background-color: rgb(12, 223, 212);
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
            color: rgb(218, 11, 11)
        }

        nav ul li a:hover {
            text-decoration: hover;
            color: lavender
        }

        main hr {
            border: 2;
            background: rgb(7, 7, 182);
            height: 1.2px;
            margin: 40px 84px;
        }

        .left {
            font-size: 2re;
        }

        .firstSection {
            display: flex;
            justify-content: space-around;
            margin: -70px 0;

        }

        .firstSection>div {
            width: 30%;
            margin: 60px 0;

        }

        .leftSection {
            margin: 30px 0;

            font-size: 3rem;

        }

        .rightSection img {
            width: 40%;
            margin: 50px 0;
            background-color: rgb(7, 7, 182);
            border-radius: 50%;
            background: #ff1d96;
            padding: 20px; 
            width: 200px;
            height: 150px;
          } 


        

        .leftSection .buttons {
            padding: 16pxpx;

        }

        .leftSection .btn {
            padding: 12px;
            background: #d604d6;
            border: 2px solid white;
            border-radius: 10px;
            font-size: 20px;
            cursor: pointer;

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
            font-size: 2rem;
        }

        .secondSection .box {
            background: white;
            width: 76vw;
            height: 2px;
            margin: 56px 0;
            display: flex;
        }

        .secondSection .vertical {
            height: 93px;
            width: 1px;
            background: white;
            margin: 0 140px;
        }

        .image-top {
            width: 23px;
            position: relative;
            top: -32px;
            left: -9px;


        }

        .vertical-title {
            position: relative;
            top: 80px;
            width: 150px;
            color: rgb(206, 215, 218);
            font-size: 20px;

        }

        .vertical-desc {
            position: relative;
            top: 80px;
            color: rgb(251, 234, 234);
            width: 150px;
            font-size: 20px;

        }

        footer {
            background-color: rgb(1, 64, 118)
        }

        .footer {
            display: flex;
            padding: 23px 122px;
            justify-content: space-evenly;
        }

        .footer ul {
            list-style: none;
        }

        .footer>div {
            width: 233px;
        }

        footer .footer-rights {

            text-align: center;

            color: rgb(214, 210, 210);


        }
    </style>
</head>

<body>
    <script>
        window.watsonAssistantChatOptions = {
            integrationID: "1516d4f2-1af9-416c-abd4-a84faafd9d49", // The ID of this integration.
            region: "au-syd", // The region your integration is hosted in.
            serviceInstanceID: "e20fcba0-6a5c-4562-a809-a6bfcf574092", // The ID of your service instance.
            onLoad: async (instance) => { await instance.render(); }
        };
        setTimeout(function () {
            const t = document.createElement('script');
            t.src = "https://web-chat.global.assistant.watson.appdomain.cloud/versions/" + (window.watsonAssistantChatOptions.clientVersion || 'latest') + "/WatsonAssistantChatEntry.js";
            document.head.appendChild(t);
        });
    </script>
    <header>
        <nav>
            <div class="left">Ranjeet's portfolio</div>
            <div class="right">
                <ul>
                    <li><a href="/">home</a></li>
                    <li><a href="https://www.facebook.com/profile.php?id=100006877421653&mibextid=kFxxJD">about</a></li>
                    <li><a href="/">qualification</a></li>

                    <li><a href="https://wa.me/8804015370">contact me</a></li>


                </ul>
            </div>
        </nav>
    </header>
    <main>
        <section class="firstSection">
            <div class="leftSection">
                Hi,I am <span class="purple">Ranjeet</span>
                <div>from Nsti(w) Patna
                </div>
                <span id="element"></span>
                <div class="buttons">
                    <button class="btn"><a href="resume.pdf"> Download Resume</a></button>
                    <button class="btn"><a href="https://github.com/Ranjeetpatna"> Visit Github</a></button>
                </div>
            </div>
            <div class="rightSection">
                <img src="rt.png" alt="photo">
            </div>
</body>
</section>
<hr>
<section class="secondSection">
    <span class="text-gray">what I have done so far</span>
    <h1>past qualification</h1>
    <div class="box">
        <div class="vertical">
            <img class="image-top" src="bg.png" alt="">
            <div class="vertical-title">
                10th (2013)
            </div>
        </div>

        <div class="vertical">
            <img class="image-top" src="bg.png" alt="">
            <div class="vertical-desc">
                intermediate(2015)
            </div>
        </div>
        <div class="vertical">
            <img class="image-top" src="bg.png" alt="">
            <div class="vertical-title">
                Graduation (2021)
            </div>
        </div>

        <div class="vertical">
            <img class="image-top" src="bg.png" alt="">
            <div class="vertical-desc">
                ITI(2020)
            </div>
        </div>

    </div>

    </div>

</section>
</main>
<footer>
    <div class="flex">
        <div class="footer">
            <div class="footer-first">
                <h3>Ranjeet portfolio</h3>
            </div>
            <div class="footer-second">
                <ul>
                    <li>HTML
                    </li>
                    <li>CSS
                    </li>
                    <li>Javascript
                    </li>
                    <li>Bootstrap
                    </li>
                </ul>
            </div>
            <div class="footer-third">
                <ul>
                    <li>PHP</li>
                    <li>Wordpress</li>
                    <li>MySQL</li>
                    <li>Laravel</li>
                </ul>

            </div>
            <div class="footer-fourth">
                <ul>
                    <li>MongoDB</li>
                    <li>Web Design</li>
                    <li>Graphic Design</li>
                    <li>Github</li>
                </ul>

            </div>

        </div>
        <div class="footer-rights">
            copyright &#169; wwww.ranjeetkumartiwarichp123@gmail.com | All rights reserved
        </div>







</footer>

<script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
<script>
    var typed = new Typed('#element', {
        strings: ['web developer', 'Graphic designer'],
        typeSpeed: 100,
    });
</script>


</body>

</html>

