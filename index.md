<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="landingPage/styles.css">
    <link rel="stylesheet" href="https://use.typekit.net/mua4zpm.css">
        <title>Synthesis</title>
</head>
<body>
    <div id="mainPageWrap">
        <div class="mainPageBg" id="secondVid"></div>
        <video playsinline autoplay muted loop id="introVid">
            <source src="Synthesis_LandingDraft1.mp4" type="video/mp4">
        </video>
        <div class="socialRow">
            <span class="socialWrap">
                <button id="instaBtn">
                    <img src="instaLogo.png" alt="Instagram">
                </button>
                <button id="fbBtn">
                    <img src="fbLogo.png" alt="Facebook">
                </button>
            </span>
            <span class="navWrap">
                <a href="#mainPageWrap" class="navLink main">Main</a>
                <a href="#aboutPageWrap" class="navLink about">About</a>
                <a href="#processPageWrap" class="navLink process">Process</a>
            </span>
        </div>
        <div class="countdownRow">
            <div class="countdownWrap">
                <h2 id="countdown">
                    <span id="days">
                        <h2>
                            <span id="dayCount"><!-- daysLeft --></span>
                            <span class="colon">:</span>
                        </h2>
                        <p class="timeLabel">Days</p>
                    </span>
                    <span id="hours">
                        <h2>
                            <span id="hourCount"><!-- hoursLeft --></span>
                            <span class="colon">:</span>
                        </h2>
                        <p class="timeLabel">Hours</p>
                    </span>
                    <span id="mins">
                        <h2>
                            <span id="minCount"><!-- minsLeft --></span>
                            <span class="colon">:</span>
                        </h2>
                        <p class="timeLabel">Minutes</p>
                    </span>
                    <span id="secs">
                        <h2>
                            <span id="secCount"><!-- secsLeft --></span>
                        </h2>
                        <p class="timeLabel">Seconds</p>
                    </span>
                </h2>
            </div>
        </div>
        <div class="notifyRow">
            <button id="notifyBtn">
                Notify Me
            </button>
        </div>
    </div>
    <div id="aboutPageWrap">
        <div class="aboutTitleRow">
            <h2>Who. What.</h2>
        </div>
        <div class="aboutBodyRow">
            <p>We are Penn State’s Graphic Design class of 2021, and as our college careers are coming to an end, we are preparing for our senior showcase Synthesis. The goal behind our showcase is to reflect on how we have grown as a class and discovered our individuality as designers. Our theme Synthesis comes from comparing our time of growth in college to evolutionary biology, and is stylistically  influenced by the structured form of mathematics.
            <br><br>
            Traditionally, our showcase would be held in-person, but in light of COVID we have decided to create an entirely virtual, web-based experience. This will include a virtual exhibition, along with some short films and information about us as both a class, and as individual designers.
            <br><br>
            We are so excited for what is to come and hope to see you there! Sign up to receive a link when our website goes live and follow us on social media for updates and behind the scenes!</p>
        </div>
    </div>
    <div id="processPageWrap">
        <div class="processTitleRow">
            <h2>Process</h2>
        </div>
        <div class="videoRow">
            <div id="carousel">
                <div class="carouselItem">
                    <video playsinline autoplay controls>
                        <source src="" type="video/mp4">
                    </video>
                </div>
                <div class="carouselItem">
                    <video playsinline autoplay controls>
                        <source src="" type="video/mp4">
                    </video>
                </div>
                <div class="carouselItem">
                    <video playsinline autoplay controls>
                        <source src="" type="video/mp4">
                    </video>
                </div>
                <div class="carouselItem">
                    <video playsinline autoplay controls>
                        <source src="" type="video/mp4">
                    </video>
                </div>
            </div>
            <p id="prevBtn">prev</p>
            <p id="nextBtn">next</p>
        </div>
    </div>
    <div id="modalBg">
        <div id="notifyModal">
            <span id="closeModal">&times;</span>
            <h2>Keep Me Posted</h2>
            <p>Enter your email to get notified (once!) when our full site and exhibition go live. Plus, we'll send you an exclusive digital gift as a thanks for supporting us.</p>
            <form action="" id="notifyForm">
                <input type="email" name="email" id="emailInput" placeholder="me123@gmail.com">
                <br>
                <button id="submitBtn">Notify Me!</button>
            </form>
        </div>
    </div>
    <script src="landingPage/index.js"></script>
</body>
</html> 