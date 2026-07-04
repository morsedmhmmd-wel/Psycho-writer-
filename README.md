<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Psycho Writer</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#111;
color:white;
}

header{
background:#000;
padding:20px;
text-align:center;
}

header h1{
color:#ff2d55;
font-size:40px;
}

nav{
margin-top:15px;
}

nav a{
color:white;
text-decoration:none;
margin:15px;
font-size:18px;
}

nav a:hover{
color:#ff2d55;
}

.hero{
padding:80px 20px;
text-align:center;
}

.hero h2{
font-size:45px;
margin-bottom:20px;
}

.hero p{
font-size:20px;
color:#ccc;
}

section{
padding:50px;
}

.cards{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:30px;
}

.card{
width:300px;
background:#222;
border-radius:10px;
padding:20px;
text-align:center;
transition:.3s;
}

.card:hover{
transform:scale(1.05);
}

.card img{
width:100%;
border-radius:10px;
}

.card h3{
margin:15px 0;
}

.btn{
display:inline-block;
margin-top:10px;
padding:10px 20px;
background:#ff2d55;
color:white;
text-decoration:none;
border-radius:5px;
}

footer{
background:#000;
text-align:center;
padding:20px;
margin-top:40px;
}
</style>

</head>
<body>

<header>
<h1>Psycho Writer</h1>

<nav>
<a href="#">Home</a>
<a href="#">Books</a>
<a href="#">Stories</a>
<a href="#">About</a>
<a href="#">Contact</a>
</nav>

</header>

<div class="hero">
<h2>Welcome to Psycho Writer</h2>
<p>বাংলা গল্প, হরর গল্প, উপন্যাস এবং সাহিত্যিক বইয়ের সংগ্রহ।</p>
</div>

<section>

<h2 align="center">Featured Books</h2>

<br><br>

<div class="cards">

<div class="card">

<img src="book.jpg">

<h3>অভিশপ্ত চোখ</h3>

<p>একটি ভয়ংকর হরর গল্প।</p>

<a href="books/abhisapto.pdf" class="btn">Read PDF</a>

</div>

<div class="card">

<img src="book2.jpg">

<h3>ও পরী?</h3>

<p>রহস্য ও ভালোবাসার গল্প।</p>

<a href="books/opori.pdf" class="btn">Read PDF</a>

</div>

<div class="card">

<img src="book3.jpg">

<h3>কল্পনাতে তুমি</h3>

<p>রোমান্টিক উপন্যাস।</p>

<a href="books/kolponate_tumi.pdf" class="btn">Read PDF</a>

</div>

</div>

</section>

<footer>

<h3>Psycho Writer</h3>

<p>© 2026 All Rights Reserved.</p>

</footer>

</body>
</html>
