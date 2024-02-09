<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Document</title> 
<style>
  /* تحريك النص باستخدام CSS */
  @keyframes marquee {
    0% { transform: translateX(0); }
    100% { transform: translateX(100%); }
  }

  .marquee {
    display: inline-block;
    animation: marquee 10s linear infinite;
  }
</style>
</head>
<body>

<p align="center">  
    <img src="https://telegra.ph/file/4d347b0d92e12fc9c0774.jpg" alt="Johan's Image" width="560">
    <!-- استخدام الكلاس المعرف لتحريك النص -->
    <h1 align="center" class="marquee">Hi 👋 Johan Here</h1>
</p>

<h3 align="center">
    I'm a beginner developer 
</h3>

</body>
</html>
