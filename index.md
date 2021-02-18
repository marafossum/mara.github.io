
<!DOCTYPE html>
<html lang="en">
   <head>
    <link rel="stylesheet" href="/Users/marafossum/Desktop/CSSExercise2/css/main.css">
       <meta charset="utf-8">
       <title>CSS Exercise Week 2</title>
       <meta name="description" content="css exercise for comm 261 at ndsu  ">
       <meta name="keywords" content="css, exercise, web, development   ">
      <script>
        src="http://html5shiv.googlecode.com/svn/trunk/html5.js">
      </script>
<title>CSS Exercise Week 2</title>

</head>
<style>

    div#breakfast {
        border-style: solid;
    }
    div#lunch {
        border-style: solid;
    }
    div#dinner {
        border-style: solid;
    }

    ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover {
  background-color: #111;
}
    </style>
<body>
<header>
<h1>Dakota Bistro</h1>
</header>
<section>
<p>At the Dakota Bistro, you decide what will be included in your meal by choosing from our varied list of fresh ingredients. Then your meal is custom made for you - no dry meals sitting under heat lamps! You'll receive exactly the meal you want, fresh and hot.</p>

<p>
<img src="/Users/marafossum/Desktop/CSSExercise2/img/breakfast.jpg" alt="breakfast example" height="100px" />
<img src="/Users/marafossum/Desktop/CSSExercise2/img/lunch.jpg" alt="lunch example" height="100px" />
<img src="/Users/marafossum/Desktop/CSSExercise2/img/dinner.jpg" alt="dinner example" height="100px" />
</p>

<ul>
    <li><a class="active" href="#home">Home</a></li>
    <li><a href="#news">News</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#about">About</a></li>
  </ul>
  

<div#breakfast>
<h2>Breakfast Menu</h2>
<ul>
<li>Design your own omelet</li>
<li>Have a country breakfast</li>
<li>Lighten up with all things healthy</li>
</ul>
</div>

<div#lunch>
<h2>Lunch Menu</h2>
<ul>
<li>Design your own burger</li>
<li>Design your own sandwich</li>
<li>Design your own salad</li>
</ul>
</div>

<div#dinner>
<h2>Dinner Menu</h2>
<ul>
<li>Made from scratch home-styled dinner</li>
<li>Meat and potatoes please</li>
<li>Try a signature dish</li>
</ul>
</div>

</section>
<footer>
<h3>Our Mission</h3>
<blockquote><p>To feed you what you're hungry for, done the way you want it, using only the freshest ingredients.</p></blockquote>
</footer>
</body>
</html>
