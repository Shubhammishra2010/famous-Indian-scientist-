<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Famous Indian Scientists</title>

<style>
body{
    font-family: Arial, sans-serif;
    margin:0;
    padding:0;
    box-sizing:border-box;
}

h1{
    background-color: lightgreen;
    color: green;
    text-align:center;
    padding:15px;
}

.main{
    display:flex;
    justify-content:space-around;
    flex-wrap:wrap;
    padding:20px;
}

.scientist-card{
    border:1px solid #ddd;
    border-radius:8px;
    margin:10px;
    padding:15px;
    width:300px;
    box-shadow:0 0 8px gray;
    text-align:center;
}

.scientist-card img{
    width:100%;
    height:250px;
    object-fit:cover;
    border-radius:4px;
}

h2{
    margin-top:10px;
}
</style>
</head>

<body>

<h1>Famous Indian Scientists</h1>

<div class="main">

<div class="scientist-card">
<img src="kalam.jpg" alt="A.P.J. Abdul Kalam">
<h2>A. P. J. Abdul Kalam</h2>
<p>Contribution: Missile Technology and Aerospace Engineering.</p>
</div>

<div class="scientist-card">
<img src="raman.jpg" alt="C. V. Raman">
<h2>C. V. Raman</h2>
<p>Contribution: Raman Effect in Physics.</p>
</div>

<div class="scientist-card">
<img src="bose.jpg" alt="Jagadish Chandra Bose">
<h2>Jagadish Chandra Bose</h2>
<p>Contribution: Plant Science and Radio Science.</p>
</div>

</div>

</body>
</html>
