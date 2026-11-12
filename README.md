 Uppgift 1
 #HTML


### Vad är HTML?
- programmeringsspråk
- Strukturera hemsidor med information genom organisera information på olika platser.

### Vad kan det användas till?
- Bygga hemsidor och skapa interface
- Kan skapa knappar och interaktiva objekt med hjälp av .css och js



 ## HTML i kod över en simpel websida
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <link rel="stylesheet" href="StyleSheet1.css">
</head>
<body>
    <h1>New MDU student</h1>
    <div id="navigation">
        <a href="sida1.html">Sida 1</a>
        <a href="sida2.html">Sida 2</a>
        <a href="sida3.html">Sida 3</a>
    </div>

   
    <h2>Everything you need to know:</h2>
    <ul>
        <li>Before you start</li>
        <li>What to expect</li>
        <li>How to succeed</li>
    </ul>

    <h3>Before you start:</h3>
    <p>Make yourself familiar with your enviroment.</p>

    <h3>What to expect:</h3>
    <p>Depending on your course your journey will be different.Don't worry too much about what will happen.</p>

    <h3>How to succeed:</h3>
    <p>Make sure to eat, sleep, and attend your class!</p>

    <button onclick="showVideo()">Watch video </button>
    <div id="video"></div>
    <script>
        function showVideo() {
            var videoContainer = document.getElementById("video").innerHTML =
                '<iframe width="560" height="315" src="https://www.youtube.com/watch?v=E_CnO8L4GQU" frameborder="0" allowfullscreen></iframe>';
        }
    </script>

    <p class="Viktigt">
        Important information for new students at MDU. Make sure to read all the guidelines and follow the instructions provided by the university.
    </p>
 
 
    <img src="MDU_logotyp.png" alt="MDU logo" />

</body>
</html>


## Extra tillägg med CSS


body {
   


    background-color: rgb(255, 216, 248);
    font-family: Arial, sans-serif;
}
a {
    color: black;
    font-weight: bold;
    font-family: Arial, sans-serif;
    font-size: 30px;
  
    margin-bottom: 60px;
    margin-top: 60px;
    margin-left: 400px;
}
h1 {
    color: black;
    font-size: 50px;
    margin-bottom: 60px;
    margin-left: 720px;
}
h2 {
    color: black;
    margin-top: 60px;
}
h3 {
    color: black;  
}
button {
    background-color: orangered;
    color: white;
    font-weight: bold;
    font-size: 20px;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    margin-top: 60px;
}
p {
    color: black;
    margin-bottom: 60px;
    margin-top: 15px;
}
.Viktigt {
    margin-top: 60px;
    margin-bottom: 60px;
    color: darkred;
    font-weight: bold;
}
img {
    width: 300px;
    height: auto;
    margin-top: 100px;
}


