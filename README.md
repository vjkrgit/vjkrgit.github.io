<!DOCTYPE html>
<html>
  <head>
    <title>Welcome to My Website</title>
    <style>
      body {
        background-color: #fff; /* set initial background color */
      }
    </style>
  </head>
  <body>
    <h1>Welcome to My Website</h1>
    <p>Thank you for visiting my website. I hope you find it informative and enjoyable.</p>
    
    <script>
      setInterval(function() {
        var colors = ['#f00', '#0f0', '#00f', '#ff0', '#0ff', '#f0f'];
        var randomIndex = Math.floor(Math.random() * colors.length);
        document.body.style.backgroundColor = colors[randomIndex];
      }, 5000); /* change background color every 5 seconds */
    </script>
  </body>
</html>
