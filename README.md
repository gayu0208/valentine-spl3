
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Valentine Special</title>
<style>
body {
    text-align: center;
    font-family: Arial;
    background-color: #ffe6f2;
}

.box {
    background: white;
    width: 60%;
    margin: 80px auto;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0px 0px 10px gray;
}

input {
    padding: 8px;
    margin: 5px;
}

button {
    padding: 8px 15px;
    margin: 10px;
    font-size: 14px;
}

.page {
    display: none;
}
</style>

<script>
function showPage(pageId) {
    document.getElementById("page1").style.display = "none";
    document.getElementById("page2").style.display = "none";
    document.getElementById("page3").style.display = "none";
    document.getElementById("page4").style.display = "none";

    document.getElementById(pageId).style.display = "block";
}
</script>
</head>

<body onload="showPage('page1')">

<h1>💖 Valentine Special 💖</h1>

<!-- PAGE 1 -->
<div id="page1" class="page">
<div class="box">
<h2>Page 1 — Your Details</h2>
<p>Enter your Name:</p>
<input type="text" placeholder="Your Name"><br><br>

<p>Enter your Date of Birth:</p>
<input type="date"><br><br>

<button onclick="showPage('page2')">Next ➜</button>
</div>
</div>

<!-- PAGE 2 -->
<div id="page2" class="page">
<div class="box">
<h2>Page 2 — Questions</h2>

<p>1. Did she like food? 🍽️</p>
<button onclick="alert('Yes ❤️')">Yes</button>
<button onclick="alert('No 😢')">No</button>

<p>2. Did she like you? 💕</p>
<button onclick="alert('Yes ❤️')">Yes</button>
<button onclick="alert('No 😢')">No</button>

<p>3. Do you miss her? 😔</p>
<button onclick="alert('Yes ❤️')">Yes</button>
<button onclick="alert('No 😢')">No</button>

<p>4. Do you love her? 💖</p>
<button onclick="alert('Yes ❤️')">Yes</button>
<button onclick="alert('No 😢')">No</button>

<p>5. Do you marry her? 💍</p>
<button onclick="alert('Yes ❤️')">Yes</button>
<button onclick="alert('No 😢')">No</button>

<br>
<button onclick="showPage('page3')">Next ➜</button>
</div>
</div>

<!-- PAGE 3 -->
<div id="page3" class="page">
<div class="box">
<h2>Page 3 — My Love Message</h2>
<h3>To my Ennavan,</h3>
<p>
I love you so much, muu. You are the most important person in my life — without you, I am nothing. 
You are my sun in life. I am so blessed to have you in my life. You are my best friend, my family, 
and the love of my life. I am so happy with you. I cherish each and every moment with you. 
You are my strength and my backbone. You were there for me when no one else was. We have had many fights 
and faced struggles together — let’s have 100 years together and always have each other’s back. 
I am there for you whenever you need me. 💗
</p>

<button onclick="showPage('page4')">Next ➜</button>
</div>
</div>

<!-- PAGE 4 -->
<div id="page4" class="page">
<div class="box">
<h2>Page 4 — Final Question 💘</h2>
<p><b>Will you be my Valentine?</b></p>
<button onclick="alert('Yes, forever ❤️')">Yes</button>
<button onclick="alert('Think again 😢')">No</button>
</div>
</div>

</body>
</html>
