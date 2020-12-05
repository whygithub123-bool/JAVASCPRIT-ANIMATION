# JAVASCPRIT-ANIMATION
animation html CSS3 JAVASCPRIT CODE

<!DOCTYPE html>
<html lang="en">
<style>
  .demo {
    display: block;
    position: fixed;
    top: 30%;
    left: 20%;
    margin: auto;
    width: 350px;
    height: 300px;
    border: 3px solid rgb(29, 126, 253);
    box-shadow: 0 0 35px cyan;
    outline: none;
    background-color: rgb(9, 15, 24);
    transition: all 1s;
    opacity: 1;
    border-radius: 50px;
}

body {
    background-color: rgb(22, 21, 21);
    background-repeat: no-repeat;
    opacity: 1;
}

.demo a {
    opacity: 2;
    text-decoration: none;
    display: block;
    position: relative;
    text-align: center;
    align-items: center;
    top: 20%;
    padding: 40px;
    font-size: 55px;
    font-weight: bold;
    font-family: 'Times New Roman', Times, serif;
    font-variant: normal;
    text-transform: uppercase;
    text-shadow: 0 0 35px cyan;
    opacity: 1;
    color: rgb(64, 145, 250);
}

.demo:hover {
    transform: scale(1.77, 1.77);
}

.msg {
    display: none;
    position: fixed;
    text-align: center;
    align-items: center;
    justify-content: center;
    font-size: 10px;
    color: cyan;
    top: 76%;
    left: 25%;
}
 </style>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>transform</title>
    <link rel="stylesheet" href="./style.css">
</head>

<body>
    <span class="demo" onmouseover="over('hey sir')" onmouseout="out()" id="jarvis">
        <a href="#">
            <strong>JARVIS</strong>
        </a>
    </span>
    <br>
    <h1 id="mymsg" class="msg">HELLOW SIR</h1>
    <script>
        var m = document.getElementById("mymsg");

        function over(text) {
            m.style.display = "block";
            m.style.fontSize = 45 + "px";
        }

        function out() {
            m.style.display = "none";
        }
    </script>
</body>

</html>
