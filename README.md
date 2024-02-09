<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Resetting Text Animation</title> 
<style>
/* تحريك النص بشكل أفقي باستخدام CSS */
@keyframes rewriteText {
    0% { content: "Hi 👋 Johan Here"; }
    20% { content: "H"; }
    40% { content: "Hi"; }
    60% { content: "Hi 👋 Johan"; }
    80% { content: "Hi 👋 Johan Here"; }
    100% { content: "Hi 👋 Johan Here"; }
}
.marquee::before {
    content: "Hi 👋 Johan Here";
    display: inline-block;
    animation: rewriteText 5s steps(20) infinite;
    white-space: nowrap; /* لمنع النص من الانتقال إلى سطر جديد */
}
</style>
</head>
<body>

<p align="center">  
    <img src="https://telegra.ph/file/4d347b0d92e12fc9c0774.jpg" alt="Johan's Image" width="200">
    <!-- النص المتحرك بشكل أفقي -->
    <div class="marquee"></div>
</p>

<h3 align="center">
    I'm a beginner developer 
</h3>

</body>
</html>
