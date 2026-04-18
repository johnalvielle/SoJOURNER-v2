<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>My Newsroom</title>

<!-- Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&family=Merriweather:wght@300;400;700&display=swap" rel="stylesheet"/>

<!-- Icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

<style>
:root {
  --primary:#252958;
  --accent:#E2841C;
  --bg:#ffffff;
  --text:#1a1a1a;
  --grey:#666;
  --border:#e2e5ef;
}

*{margin:0;padding:0;box-sizing:border-box;}
body{font-family:Inter,sans-serif;background:var(--bg);color:var(--text);line-height:1.6;}

header{
  position:sticky;top:0;
  background:#fff;
  border-bottom:1px solid var(--border);
  padding:1rem;
  z-index:1000;
}

.brand{font-family:Merriweather;font-weight:700;color:var(--primary);font-size:1.5rem;}

nav{
  display:flex;
  gap:1rem;
  justify-content:center;
  padding:0.8rem;
  border-bottom:3px solid var(--accent);
  flex-wrap:wrap;
}

nav a{
  text-decoration:none;
  color:var(--primary);
  font-weight:600;
  font-size:0.9rem;
}

.container{
  max-width:1000px;
  margin:2rem auto;
  padding:0 1rem;
}

.article{
  margin-bottom:4rem;
  padding-bottom:2rem;
  border-bottom:1px solid var(--border);
}

.tag{
  color:var(--accent);
  font-weight:700;
  text-transform:uppercase;
  font-size:0.8rem;
}

h1{
  font-family:Merriweather;
  color:var(--primary);
  margin:0.5rem 0 1rem;
}

.meta{color:var(--grey);font-size:0.9rem;margin-bottom:1rem;}

img{
  width:100%;
  border-radius:8px;
  margin:1rem 0;
}

p{margin-bottom:1rem;}

.quote{
  border-left:4px solid var(--accent);
  padding-left:1rem;
  font-style:italic;
  color:var(--grey);
  margin:1.5rem 0;
}

footer{
  background:var(--primary);
  color:#fff;
  text-align:center;
  padding:2rem 1rem;
  margin-top:3rem;
}
</style>
</head>

<body>

<header>
  <div class="brand">MY NEWSROOM</div>
</header>

<nav>
  <a href="#feature">Feature</a>
  <a href="#opinion">Opinion</a>
  <a href="#breaking1">Breaking 1</a>
  <a href="#breaking2">Breaking 2</a>
</nav>

<div class="container">

<!-- ================= FEATURE ARTICLE ================= -->
<section class="article" id="feature">
  <div class="tag">Feature Article</div>
  <h1>Malolos Provides Financial Aid to OFW Families Amid Middle East Crisis</h1>
  <div class="meta">March 2026 • By Your Name</div>

  <img src="ofw.jpg">

  <p>
    The city government of Malolos has released financial assistance to support families of Overseas Filipino Workers affected by the ongoing Middle East conflict.
  </p>

  <p>
    Officials confirmed that more than 100 families have received aid through a special assistance program funded by local government resources.
  </p>

  <div class="quote">
    “Talagang mahirap ang sitwasyon, pero malaking tulong ang ibinigay ng LGU,” one beneficiary shared.
  </div>
</section>

<!-- ================= OPINION ================= -->
<section class="article" id="opinion">
  <div class="tag">Opinion Writing</div>
  <h1>Rising Fuel Prices: A Burden That Keeps Growing</h1>
  <div class="meta">March 2026 • Editorial Staff</div>

  <p>
    The continuous increase in fuel prices has placed enormous pressure on both commuters and transport workers.
  </p>

  <p>
    While government subsidies provide temporary relief, they do not address the long-term instability of global oil dependence.
  </p>

  <div class="quote">
    Real solutions must go beyond subsidies and focus on sustainable transport alternatives.
  </div>
</section>

<!-- ================= BREAKING 1 ================= -->
<section class="article" id="breaking1">
  <div class="tag">Breaking News</div>
  <h1>LTFRB Announces ₱5,000 Fuel Subsidy for PUV Drivers</h1>
  <div class="meta">April 2026 • Live Update</div>

  <img src="gas.jpg">

  <p>
    The LTFRB has officially announced a fuel subsidy program aimed at assisting public utility vehicle drivers affected by rising petroleum costs.
  </p>

  <p>
    The subsidy is expected to benefit thousands of registered drivers nationwide.
  </p>
</section>

<!-- ================= BREAKING 2 ================= -->
<section class="article" id="breaking2">
  <div class="tag">Breaking News</div>
  <h1>Oil Prices Expected to Increase Again Next Week</h1>
  <div class="meta">April 2026 • Live Update</div>

  <img src="oil.jpg">

  <p>
    Global petroleum markets are signaling another round of fuel price hikes due to ongoing international tensions.
  </p>

  <p>
    Diesel and gasoline prices may increase significantly depending on global trading movements.
  </p>
</section>

</div>

<footer>
  <p>© 2026 My Newsroom. All rights reserved.</p>
</footer>

</body>
</html>
