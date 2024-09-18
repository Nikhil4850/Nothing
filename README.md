<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CAREER HELPER</title>
    
</head>

<body>
    
    <header>
        <!-- <img src="c:\Users\Nikhil\Downloads\.shorts\logo.jpg.jpeg" alt="CAREER HELPER" class="logo"> -->
        <nav>
            <ul>
                <li><a id="logo" href="https://nikhil4850.github.io/carrier/">CAREERHELPER.com</a></li>
                <li><a href="https://nikhil4850.github.io/carrier/"> Home</a></li>
                <li><a href="https://nikhil4850.github.io/carrier/">Courses</a></li>
                <li><a href="https://nikhil4850.github.io/IQ-test/">IQ Test</a></li>
                <li><a href="https://nikhil4850.github.io/carrier/">consultant</a></li>
                <li><a href="https://nikhil4850.github.io/carrier/">Contact</a></li>
                <li><a href="https://nikhil4850.github.io/carrier/">Login</a></li>
            </ul>
        </nav>
    </header>
    
    <div class="hamburger">
        <div class="line"></div>
        <div class="line"></div>
        <div class="line"></div>
    </div>
</nav>

</script>



<style>
    .evnt-noti{
        background-color: #F23F36;
        margin: 0;
        align-items: center;
        justify-content: center;
        display: flex;
        padding: 1rem;
        z-index: 1;
    }
    .notiVoteBtn{
        background-color: white;
        color: #754485;
        border-radius: 3px;
        padding: 3px 12px;
        margin-left: 15px;
        border: none;
        height: 30px;
    }
    .notiVoteBtn:hover{
        background-color: #754485;
        color: white;
    }
    .noti-txt{
        color: white !important;
        font-size:15px !important;
        margin:0 !important;
    }
    .carousel{ 
         /*z-index:-1;*/ 
        margin-top: -50px;
    }
    .image_sliderHome {
        height:60h;
        position:relative;
        background-image:url(https://images.hdqwalls.com/wallpapers/blue-blur-color-4k-wp.jpg);
        background-repeat:no-repeat;
        background-position:center;
        background-size:cover;
        transition:0.3s;
    }
    .image_sliderHome {
        margin-top:7vh;
        position:relative;
        z-index:99;
    }
    .sliderBanner {
        width:100%;
        height:65vh;
        overflow:hidden;
        position:relative;

    }
    .imageBanner_container{
        position:absolute;
        width:700%;
        height:100%;
        left:0;
        top:0;
        display:flex;
        transition:0.4s ease-in-out
    }
    .imageBanner_container .imageBanner {
        width:100%;
        background-size:cover !important;
    }
    .bannerCaption {
        gap: 1rem;
        width: max(40%, 550px);
        background: linear-gradient(to right, rgba(0,0,0,0.8), rgba(0,0,0,0.3), transparent);
        height: 100%;
        left: 0;
        flex-direction: column;
        display: flex;
        justify-content: center;
        color: white;
        bottom: 0;
        position: absolute;
        padding: 1em 1em 0.5em 3em;
        letter-spacing: 1px;
    }
    .bannerCaption h2 {
        color: white;
        font-size:40px;
        font-weight: 700;
    }
    .bannerCaption a {
        color: white;
        background-color: #FF3B3B;
        width: fit-content;
        font-weight: 600;
        box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
        padding: 0.5rem 1rem;
        transition: color 0.3s, background-color 0.3s;
        border-radius: 0.5rem;
    }
    .bannerCaption a:hover{
        color: #FF3B3B;
        background-color: white;
    }
    .imageBanner:nth-child(1) {
        background:url(https://www.careerguide.com/images_new/banner_1.png);
    }
    .imageBanner:nth-child(2) {
        background:url(https://www.careerguide.com/images_new/banner_2.png);
    }
    .imageBanner:nth-child(3) {
        background:url(https://www.careerguide.com/images_new/banner_3.png);
    }
    .imageBanner:nth-child(4) {
        background:url(https://www.careerguide.com/images_new/banner_4.png);
    }
    .imageBanner:nth-child(5) {
        background:url(https://www.careerguide.com/images_new/banner_5.png);
    }
    .imageBanner:nth-child(6) {
        background:url(https://www.careerguide.com/images_new/banner_6.png);
    }
    .imageBanner:nth-child(7) {
        background:url(https://www.careerguide.com/images_new/banner_7.png);
    }
    .pagination {
        width: 100%;
        position: absolute;
        bottom: 3em;
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 1em;
    }
    .pagination span{
        background:#111;
        box-shadow: 
            inset -1px 1px #555,
            inset 1px 1px #000;
        width:1em;
        height:1em;
        border-radius:50%;
        cursor:pointer;
    }
    .pagination .activeBanner {
        background:#fff;
        box-shadow:0 0 0.5em #000;
    }
    .searchbox  {
        z-index:0;
    }
    #section-counter {
        inset:-4rem 0 0 0 !important; 
        padding: 2rem 0;
        z-index: 99;
        display: flex;
        max-width: 1320px !important; 
        height: auto;
        margin:0 auto 0 auto !important;
    }
    #section-counter>.cg-img {
        display: flex;
        padding: 0 0 0 11px;
        margin:0; 
        width:100%; 
        margin-left: -14px;
    }
    #section-counter>.cg-img>.container {max-width:1247px !important;}
    #section-counter>.cg-img>span {
        bottom: 94px; 
        position: absolute;
        right: 28px;
        font-size: 17px; 
        font-weight: 600;
    }
    #section-counter>.cg-img>span a {color:#4E59AD; text-decoration:none;}
    @keyframes textChangeBanner {
        50% {left:-35em;}
        100% {left:0;}
    }
    @media screen and (min-width: 576px) {
        section#section-counter {margin-top:0 !important;}
    }
    @media screen and (max-width:1000px) {
        .pagination {bottom:0em;}
        #section-counter {inset:0 0 0 0 !important;}
    }
    @media only screen and (max-width: 914px) {
        .noti-txt{
            margin-bottom: 0px; 
            color: white !important;
            line-height:2;
        }
        .carousel{
            /*z-index:-1;*/ 
            margin-top: 0px;
        }
    }
    @media screen and (max-width:501px) {
        .imageBanner:nth-child(1) {
            background-position: 70% !important;
        }
        .imageBanner:nth-child(2) {
            background-position: 80% !important;
        }
        .imageBanner:nth-child(3) {
            background-position: 90% !important;
        }
        .imageBanner:nth-child(4) {
            background-position: 90% !important;
        }
        .imageBanner:nth-child(5) {
            background-position: 80% !important;
        }
        .imageBanner:nth-child(6) {
            background-position: 85% !important;
        }
        .imageBanner:nth-child(7) {
            background-position: 85% !important;
        }
        .bannerCaption {
            gap:0;
            width: 100%;
            justify-content:flex-end;
            padding: 1em 1em 4em 1em;
            background: linear-gradient(to right, rgba(0,0,0,0.8), rgba(0,0,0,0.5), transparent);
        }
        .bannerCaption h2 {
            font-size:30px;
        }
        .bannerCaption p {
            font-size: 14px;
            color: white;
            font-weight: 400;
        }
        .bannerCaption a {
            font-size:15px;
        }
        
    }
    @media screen and (max-width:420px) {
        .bannerCaption a {
            font-size:13px;
        }
    }
</style>



<section class="image_sliderHome">
    <div class="evnt-noti" align="center" style="display:none;">
        <p class="noti-txt">
        <b>LIVE Master Career Guide Counsellor's Certification Course</b>
            
            <a id="ctl00_ctContentMiddle_alrt" class="notiVoteBtn" target="_blank" href="file:///C:/Users/Nikhil/consultant.html">Join Now</a>
        </p>
    </div>
    <div class="sliderBanner">
        <div class="imageBanner_container" style="left: 0%;">
            <div class="imageBanner"></div>
            <div class="imageBanner"></div>
            <div class="imageBanner"></div>
            <div class="imageBanner"></div>
            <div class="imageBanner"></div>
            <div class="imageBanner"></div>
            <div class="imageBanner"></div>
        </div>
        <div class="bannerCaption" style="animation: auto ease 0s 1 normal none running none;">
            <h2>CLASS 10th</h2>
            <p>Miss Nikita for 10th class</p>
            <a id="bannerLink" href="file:///C:/Users/Nikhil/OneDrive/Desktop/Career%20helper/10th%20class.html">Explore services for Class 10th</a>
        </div>
        
        <div class="pagination">
            <span class="activeBanner"></span>
            <span class=""></span>
            <span class=""></span>
            <span class=""></span>
            <span class=""></span>
            <span class=""></span>
            <span class=""></span>
        </div>
    </div>
</section>
<script>
    const sliderBanner = document.querySelector('.sliderBanner');
    const imageContainer = document.querySelector('.imageBanner_container');
    const pagination = document.querySelectorAll('.pagination span');
    const captionBanner = document.querySelector('.bannerCaption');
    const captionHeading = document.querySelector('.bannerCaption h2');
    const captionText = document.querySelector('.bannerCaption p');
    const captionLink = document.querySelector('.bannerCaption a');
    const bannerLink = document.querySelector('#bannerLink');

    const captionHeadings = [
         "CLASS 10th", "CLASS 11th & 12th", "College Students", "CAREER COUNSELLORS", "CET Exam", "Working Professionals", "Explore Colleges"
     ];

     const captionTexts = [
         "Miss Nikita","Miss maithili","Miss Rakhi","Mr. Nikhil","Mr. Harshadip","Miss Ashwini","Miss Rutuja"
     ];

     const captionLinks = [
         "Explore services for Class 10th", "Explore services for Class 11th & 12th", "Explore services for College Students", "Explore services for Career Counsellors", "Explore services for CET Exam", "Explore services for Working Professional", "Explore more Colleges to get enrolled"
     ];

     const bannerLinks = [
        "file:///C:/Users/Nikhil/OneDrive/Desktop/Career%20helper/10th%20class.html","file:///C:/Users/Nikhil/OneDrive/Desktop/Career%20helper/11%2612th.html"
     ]
    
    function slideBanner(slideId) {
        imageContainer.style.left = -100 * slideId + "%";

        pagination.forEach(pag => {
            pag.classList.remove('activeBanner')
        });

        pagination[slideId].classList.add('activeBanner');

        captionBanner.style.animation = "textChangeBanner 1s ease-in-out";

        setTimeout(() => {
            captionBanner.style.animation = "none";
        }, 1000);

        setTimeout(() => {
            captionHeading.innerText = captionHeadings[slideId];
            captionText.innerText = captionTexts[slideId];
            captionLink.innerText = captionLinks[slideId];
            bannerLink.href = bannerLinks[slideId];
        }, 500);
    }

    let bannerInterval = setInterval(autoSlideBanner, 3000);

    let bannerImgId = 1;

    function autoSlideBanner() {

        if (bannerImgId > pagination.length - 1) {

            bannerImgId = 0;
        }

        slideBanner(bannerImgId);

        bannerImgId++;
    }

    for (let i = 0; i < pagination.length; i++) {

        pagination[i].addEventListener('click', () => {
            clearInterval(bannerInterval);

            slideBanner(i);

            bannerImgId = i + 1;

            bannerInterval = setInterval(autoSlideBanner, 3000);
        });
    }

</script>
    <!-- Background page -->
    <section id="home">
        <h2>Home</h2>
        <p>Welcome to the best place for Guide</p>
    </section>
    <body>
        <section class="test-section">
            <div class="container">
                <div class="test-card">
                    <img src="C:\Users\Nikhil\OneDrive\Desktop\Career helper\IQ TEST.png" alt="IQ Test">
                    <h3>IQ TEST™</h3>
                    <ul class="test-info">
                        <li>180 Questions</li>
                        <li>1 Hour</li>
                    </ul>
                    <div class="price">
                        <span class="old-price">₹1000</span>
                        <span class="new-price">Free</span>
                    </div>
                    <a href="file:///C:/Users/Nikhil/OneDrive/Desktop/Career%20helper/free_iq_test.html"><button class="test-button">For All Age Groups</button></a>
                </div>
    
                <div class="test-card">
                    <img src="C:\Users\Nikhil\OneDrive\Desktop\Career helper\IQ for 10.jpeg" alt="IQ Test For 9th">
                    <h3>IQ TEST FOR 9TH</h3>
                    <ul class="test-info">
                        <li>40 Questions</li>
                        <li>30 Minutes</li>
                    </ul>
                    <div class="price">
                        <span class="old-price">₹1000</span>
                        <span class="new-price">₹200</span>
                    </div>
                    <button class="test-button">For Class 9th</button>
                </div>
    
                <div class="test-card">
                    <img src="C:\Users\Nikhil\OneDrive\Desktop\Career helper\iqs.jpeg" alt="IQ Test For 10th">
                    <h3>IQ TEST FOR 1OTH</h3>
                    <ul class="test-info">
                        <li>50 Questions</li>
                        <li>40 Minutes</li>
                    </ul>
                    <div class="price">
                        <span class="old-price">₹1000</span>
                        <span class="new-price">₹200</span>
                    </div>
                    <button class="test-button">For Class 10th</button>
                </div>
    
                <div class="test-card">
                    <img src="C:\Users\Nikhil\OneDrive\Desktop\Career helper\iq 11th.jpeg" alt="IQ Test For 11th & 12th">
                    <h3>IQ TEST FOR 11TH & 12TH</h3>
                    <ul class="test-info">
                        <li>100 Questions</li>
                        <li>60 Minutes</li>
                    </ul>
                    <div class="price">
                        <span class="old-price">₹1000</span>
                        <span class="new-price">₹200</span>
                    </div>
                    <button class="test-button">IQ Test For 11th & 12th</button>
                </div>

                <div class="test-card">
                    <img src="C:\Users\Nikhil\OneDrive\Desktop\Career helper\iq 12th.jpeg"alt="Psychometric Engineering Selector">
                    <h3>IQ ENGINEERING SELECTOR</h3>
                    <ul class="test-info">
                        <li>100 Questions</li>
                        <li>60 Minutes</li>
                    </ul>
                    <div class="price">
                        <span class="old-price">₹1000</span>
                        <span class="new-price">₹200</span>
                    </div>
                    <button class="test-button">For ENGINEERING SELECTOR</button>
                </div>
            </div>
        </section>
    </body>
    <style>
        * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
    
    body {
        font-family: Arial, sans-serif;
        background-color: #f9f9f9;
    }
    
    .container {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        padding: 20px;
        gap: 20px;
    }
    
    .test-card {
        background-color: #fff;
        border-radius: 10px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        width: 250px;
        padding: 20px;
        text-align: center;
        transition: transform 0.3s;
    }
    
    .test-card img {
        width: 100%;
        border-radius: 10px;
        margin-bottom: 15px;
    }
    
    .test-card h3 {
        font-size: 18px;
        color: #333;
        margin-bottom: 10px;
    }
    
    .test-info {
        list-style: none;
        margin-bottom: 15px;
    }
    
    .test-info li {
        font-size: 14px;
        color: #777;
    }
    
    .price {
        margin-bottom: 15px;
    }
    
    .old-price {
        text-decoration: line-through;
        color: #999;
        font-size: 14px;
    }
    
    .new-price {
        color: #e74c3c;
        font-size: 18px;
        margin-left: 10px;
    }
    
    .test-button {
        background-color: #ff7f50;
        color: white;
        border: none;
        padding: 10px 20px;
        border-radius: 5px;
        cursor: pointer;
        transition: background-color 0.3s;
    }
    
    .test-button:hover {
        background-color: #ff5733;
    }
    
    .test-card:hover {
        transform: translateY(-10px);
    }
    
    </style>
    <footer>
    <p id="contact">
        <h2>Contact Us</h2>
        <p>Email: carrierhelper@gmail.com</p>
        <p>Phone: 9766323998</p>
    </p>
    </footer>
    <div class="whatsapp-icon-container">
        <div class="whatsapp-icon"><a href="https://chat.whatsapp.com/HPAbPV1dKmrCb7n1c674gq"><img src="C:\Users\Nikhil\OneDrive\Desktop\Career helper\whatsapp logo.png" alt="whatsapp" width="50px"></a></div>
        <div class="whatsapp" id="whatsapp">
            <div id="whatsapp">
                <p></p>
            </div>
        </div>
    </div>
    <style>
        .whatsapp-icon-container {
        position: fixed;
        bottom: 80px;
        right: 20px;
        z-index: 1000;
    }
        .whatsapp-container {
        display: none;
        position: fixed;
        bottom: 80px;
        right: 20px;
        width: 300px;
        background-color: white;
        background-image: url('https://th.bing.com/th/id/OIP.zs6ycwcSD15SnbzbvFAgRwHaLH?rs=1&pid=ImgDetMain');
        box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        border-radius: 8px;
        padding: 10px;
        z-index: 1000;
    }
    
    #whatsappbox {
        max-height: 200px;
        overflow-y: auto;
        margin-bottom: 10px;
    }
    .whatsapp-icon {

        border-radius: 50%;
        width: 50px;
        height: 50px;
        display: flex;
        align-items: center;
        justify-content: center;
        cursor: pointer;
        box-shadow: 10px 10px 10px rgba(0, 0, 0, 0.1);
    }
    </style>
    <div class="chat-icon-container">
        <div class="chat-icon">💬</div>
        <div class="chat-container" id="chat-container">
            <div id="chatbox">
                <p><strong>Nikhil :</strong> Hi! My Name is Nikhil. How can I help you today?</p>
            </div>
            <input type="text" id="userInput" placeholder="Type your message here...">
            <button id="sendBtn">Send</button>
        </div>
    </div>
    <script>
        document.querySelector('.chat-icon').addEventListener('click', function() {
    const chatContainer = document.getElementById('chat-container');
    if (chatContainer.style.display === 'none' || chatContainer.style.display === '') {
        chatContainer.style.display = 'block';
    } else {
        chatContainer.style.display = 'none';
    }
});

document.getElementById('sendBtn').addEventListener('click', function() {
    let userInput = document.getElementById('userInput').value.trim();
    let chatbox = document.getElementById('chatbox');
    
    if (userInput !== "") {
        chatbox.innerHTML += `<p><strong>You:</strong> ${userInput}</p>`;
        document.getElementById('userInput').value = '';

        // Simulate AI response
        setTimeout(() => {
            let aiResponse = getAIResponse(userInput);
            chatbox.innerHTML += `<p><strong>Nikhil:</strong> ${aiResponse}</p>`;
            chatbox.scrollTop = chatbox.scrollHeight;
        }, 1000);
    }
});

function getAIResponse(input) {
    // Simple AI response logic (you can replace this with an actual AI API)
    const responses = {
        "hello": "Hello! How can I assist you today?",
        "how are you": "I'm just a guide to help!",
        "what is your name": "I am your friendly Nikhil",
        "nikhil": "Bol n",
        "jevan zal": "Ho tuz",
        "j1 zal": "Nahi karnar aata",
        "nahi": "kadhi jevnar aahes",
        "what i can do after 10th": "You may go to the consultants and then select 10th class for the information.",
        "what i can do after tenth": "You may go to the consultants and then select 10th class for the information.",
        "what i can do after ten": "You may go to the consultants and then select 10th class for the information.",
        "what i can do after 12th": "You may go to the consultants and then select 12th class for the information.",
        "what i can do after twelveeth": "You may go to the consultants and then select 12th class for the information.",
        "what i can do after twelvee": "You may go to the consultants and then select 12th class for the information.",
        "what i do after 10th": "You may go to the consultants and then select 10th class for the information.",
        "mi ya website la pahu kashi":"Please Home var click kara"
    };

    let lowerInput = input.toLowerCase();
    return responses[lowerInput] || "Sorry, I don't understand that.";
}

    </script>
    <style>.chat-icon-container {
        position: fixed;
        bottom: 20px;
        right: 20px;
        z-index: 1000;
    }
    
    .chat-icon {
        background-color: #FF3B3B;
        color: white;
        border-radius: 50%;
        width: 50px;
        height: 50px;
        display: flex;
        align-items: center;
        justify-content: center;
        cursor: pointer;
        box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
    }
    
    .chat-container {
        display: none;
        position: fixed;
        bottom: 80px;
        right: 20px;
        width: 300px;
        background-color: white;
        background-image: url('https://www.theaccountant-online.com/wp-content/uploads/sites/10/2021/07/Code.jpg');
        box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        border-radius: 8px;
        padding: 10px;
        z-index: 1000;
    }
    
    #chatbox {
        max-height: 200px;
        overflow-y: auto;
        margin-bottom: 10px;
    }
    
    #userInput {
        width: calc(100% - 60px);
        padding: 5px;
        margin-right: 10px;
        
        border: 1px solid #ccc;
        border-radius: 5px;
    }
    
    #sendBtn {
        padding: 5px 10px;
        background-color: #FF3B3B;
        color: white;
        border: none;
        border-radius: 5px;
        cursor: pointer;
    }
    
    #sendBtn:hover {
        background-color: #cc3232;
    }
    </style>
</body>
</head>

     <style>
     body {
         position: relative;
     }

     nav {
         position: fixed;
         width: 100%;
         height: 7vh;
         top: 0;
         left: 0;
         display: flex;
         align-items: center;
         font-family: 'Poppins', sans-serif;
         font-size: 14px;
         z-index: 100;
         background-color: rgb(255, 245, 245);
         box-shadow: 0px 0px 20px 0px #e81a1a;
     }

     .nav-ul {
         display: flex;
         list-style: none;
         width: 75%;
         align-items: center;
         background-color: rgb(96, 47, 160);
         margin: 1vh 0;
         text-overflow: clip;
         white-space: nowrap;
         justify-content: space-around; 
         font-size: 9px;
     }
     </style>
<style>
    body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
}
#logo{
    color: #000;
    line-height: 200%;
}

#sd{
    text-align: center;
}
header {
    background: #ccc;
    color: #000000;
    padding: 10px 0;
    text-align: center;
}

header h1 {
    margin: 0;
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
    color: #010000;
    text-decoration: none;
    
}

nav ul li a:hover {
    color: #1e00ff; /* Change text color on hover */
} 

section {
    padding: 20px;
    margin: 20px 0;
}

section h2 {
    margin-top: 0;
}

form {
    max-width: 400px;
    margin: 0 auto;
}

form label {
    display: block;
    margin-top: 10 px;
}

form input, form select {
    width: 100%;
    padding: 5px;
    margin-top: 5px;
}

form input[type="submit"] {
    background: #646161;
    color: #fff;
    border-radius: 10px;
    cursor: pointer;
}

form input[type="submit"]:hover {
    background: #555;
}

footer {
    h2 {
        color: #ecedf8;
    }
    background: #333;
    color: #fff;
    text-align: center;
    padding: 8px 0;
}
body {
    font-family: Arial, sans-serif;
    background-color: #ecedf8;
    /* background-image: url('https://th.bing.com/th/id/OIP.pqLd4QuF4HnV7_8ZiZ-ZaQHaEo?pid=ImgDet&w=474&h=296&rs=1'); */
    height: 100vh;
    margin: 0;
}

.chat-container {
    width: 350px;
    background-color: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

#chatbox {
    height: 300px;
    overflow-y: auto;
    margin-bottom: 10px;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
    background-color: #e9e9e9;
}

#chatbox p {
    margin: 5px 0;
}

#userInput {
    width: calc(100% - 60px);
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

#sendBtn {
    width: 50px;
    padding: 10px;
    border: none;
    background-color: #007bff;
    color: white;
    border-radius: 5px;
    cursor: pointer;
/* } */

#sendBtn:hover {
    background-color: #0056b3;
}
/* hello */
.banner button {
    background-color: white;
    color: #007bff;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
    border-radius: 5px;
    position: absolute;
    top: 20px;
    right: 20px;
}

/* for banner */
.image_sliderHome {
    margin-top:7vh;
    position:relative;
    z-index:99;
}
.sliderBanner {
    width:100%;
    height:65vh;
    overflow:hidden;
    position:relative;

}
.imageBanner_container{
    position:absolute;
    width:700%;
    height:100%;
    left:0;
    top:0;
    display:flex;
    transition:0.4s ease-in-out
}
.imageBanner_container .imageBanner {
    width:100%;
    background-size:cover !important;
}
.bannerCaption {
    gap: 1rem;
    width: max(40%, 550px);
    background: linear-gradient(to right, rgba(0,0,0,0.8), rgba(0,0,0,0.3), transparent);
    height: 100%;
    left: 0;
    flex-direction: column;
    display: flex;
    justify-content: center;
    color: white;
    bottom: 0;
    position: absolute;
    padding: 1em 1em 0.5em 3em;
    letter-spacing: 1px;
}
.bannerCaption h2 {
    color: white;
    font-size:40px;
    font-weight: 700;
}
.bannerCaption a {
    color: white;
    background-color: #FF3B3B;
    width: fit-content;
    font-weight: 600;
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
    padding: 0.5rem 1rem;
    transition: color 0.3s, background-color 0.3s;
    border-radius: 0.5rem;
}
.bannerCaption a:hover{
    color: #FF3B3B;
    background-color: white;
}
.imageBanner:nth-child(1) {
    background:url(https://www.careerguide.com/images_new/banner_1.png);
}
.imageBanner:nth-child(2) {
    background:url(https://www.careerguide.com/images_new/banner_2.png);
}
.imageBanner:nth-child(3) {
    background:url(https://www.careerguide.com/images_new/banner_3.png);
}
.imageBanner:nth-child(4) {
    background:url(https://www.careerguide.com/images_new/banner_4.png);
}
.imageBanner:nth-child(5) {
    background:url(https://www.careerguide.com/images_new/banner_5.png);
}
.imageBanner:nth-child(6) {
    background:url(https://www.careerguide.com/images_new/banner_6.png);
}
.imageBanner:nth-child(7) {
    background:url(https://www.careerguide.com/images_new/banner_7.png);
}
.chat-icon-container {
    position: fixed;
    bottom: 20px;
    right: 20px;
    z-index: 1000;
}

.chat-icon {
    background-color: #FF3B3B;
    color: white;
    border-radius: 50%;
    width: 50px;
    height: 50px;
    display: flex;
    align-items: center;
    justify-content: center;
    cursor: pointer;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
}

.chat-container {
    display: none;
    position: fixed;
    bottom: 80px;
    right: 20px;
    width: 300px;
    background-color: white;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    padding: 10px;
    z-index: 1000;
}

#chatbox {
    max-height: 200px;
    overflow-y: auto;
    margin-bottom: 10px;
}

#userInput {
    width: calc(100% - 60px);
    padding: 5px;
    margin-right: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

#sendBtn {
    padding: 5px 10px;
    background-color: #FF3B3B;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

#sendBtn:hover {
    background-color: #cc3232;
}
#register {
    border: 2px solid #333; /* Border color and thickness */
    padding: 20px; /* Space inside the box */
    margin: 20px auto; /* Centering the box and adding space around it */
    width: 500px; /* Width of the box */
    background-color: #ffffff; /* Background color of the box */
    background-image: url('https://www.theaccountant-online.com/wp-content/uploads/sites/10/2021/07/Code.jpg');
    box-shadow: 0px 0px 10px rgba(61, 216, 9, 0.1); /* Adding a subtle shadow for depth */
    border-radius: 10px; /* Rounding the corners */
}

#register h2 {
    text-align: center; /* Centering the heading inside the box */
    margin-bottom: 15px; /* Space below the heading */
}

#registrationForm label,
#registrationForm input,
#registrationForm select {
    display: block; /* Ensures that each label and input/select occupies a new line */
    width: 100%; /* Makes the inputs and selects fill the box width */
    margin-bottom: 10px; /* Adds space below each form element */
}

#registrationForm input[type="submit"] {
    width: auto; /* Allows the submit button to have a smaller width */
    margin: 10px auto 0; /* Centers the submit button */
    display: block; /* Ensures the submit button is centered */
    padding: 10px; /* Adds padding inside the submit button */
    background-color: #333; /* Background color of the submit button */
    color: #fff; /* Text color of the submit button */
    border: none; /* Removes the border of the submit button */
    border-radius: 5px; /* Rounds the corners of the submit button */
    cursor: pointer; /* Changes the cursor to a pointer when hovering over the button */
}

#registrationForm input[type="submit"]:hover {
    background-color: #555; /* Changes the button color on hover */
}
/* #contact{
    background-color: #555;
    color: #ffffff;
}
} */
</style>
