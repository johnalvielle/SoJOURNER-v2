
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Campus & Community Newsroom</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&family=Merriweather:wght@300;400;700&display=swap" rel="stylesheet"/>

<style>
:root{
  --primary:#252958;
  --accent:#E2841C;
  --text:#1a1a1a;
  --grey:#666;
  --border:#e2e5ef;
}

*{margin:0;padding:0;box-sizing:border-box;}

body{
  font-family:Inter,sans-serif;
  background:#fff;
  color:var(--text);
  line-height:1.7;
}

header{
  padding:1rem;
  text-align:center;
  border-bottom:3px solid var(--accent);
}

header h1{
  font-family:Merriweather;
  color:var(--primary);
}

nav{
  display:flex;
  justify-content:center;
  gap:1rem;
  padding:1rem;
  flex-wrap:wrap;
  border-bottom:1px solid var(--border);
}

nav a{
  text-decoration:none;
  color:var(--primary);
  font-weight:600;
  font-size:0.9rem;
}

.container{
  max-width:900px;
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
  font-size:0.8rem;
  font-weight:700;
  text-transform:uppercase;
  letter-spacing:1px;
}

h2{
  font-family:Merriweather;
  color:var(--primary);
  margin:0.5rem 0 1rem;
  line-height:1.3;
}

.meta{
  font-size:0.85rem;
  color:var(--grey);
  margin-bottom:1rem;
}

img{
  width:100%;
  border-radius:8px;
  margin:1rem 0;
}

p{
  margin-bottom:1rem;
}

.quote{
  border-left:4px solid var(--accent);
  padding-left:1rem;
  font-style:italic;
  color:var(--grey);
  margin:1.5rem 0;
}

footer{
  text-align:center;
  padding:2rem;
  background:var(--primary);
  color:#fff;
}
</style>
</head>

<body>

<header>
  <h1>Campus & Community Newsroom</h1>
</header>

<nav>
  <a href="#feature">Feature</a>
  <a href="#opinion">Opinion</a>
  <a href="#news1">Breaking 1</a>
  <a href="#news2">Breaking 2</a>
</nav>

<div class="container">

<!-- ================= FEATURE ARTICLE ================= -->
<section class="article" id="feature">
  <div class="tag">Feature Article</div>
  <h2>Under the Blazing Sun: Robin's Fight for Survival and Dreams</h2>
  <div class="meta">By Your Team</div>

  <img src="robin.jpg" alt="Robin Street Vendor">

  <p>
    Robin, a 20-year-old construction worker and street vendor, stands beside his pushcart selling pineapple juice in Malolos, Bulacan.
  </p>

  <p>
    He started working at 16 in Iloilo to support his studies but financial struggles forced him to stop schooling and leave his dream of becoming a soldier.
  </p>

  <p>
    Seeking better opportunities, he moved to Bulacan where he now works under extreme heat in construction and small street vending.
  </p>

  <div class="quote">
    “Survival comes first, even if it means leaving my dreams behind,” Robin shared.
  </div>

  <p>
    Despite hardships, he continues working daily, helping his aunt’s friend sell pineapple juice as gratitude for shelter and support.
  </p>
</section>

<!-- ================= OPINION ================= -->
<section class="article" id="opinion">
  <div class="tag">Opinion Writing</div>
  <h2>Resilience Shall Never Be the Answer</h2>
  <div class="meta">Editorial</div>

  <img src="hagonoy.jpg" alt="Flooded Hagonoy Protest">

  <p>
    In Bulacan, resilience is often praised—but for many residents, it has become a cycle of endurance rather than progress.
  </p>

  <p>
    Communities in Hagonoy continue to suffer from chest-deep floods, not as temporary disasters, but as recurring conditions of life.
  </p>

  <p>
    Infrastructure projects meant to solve flooding have raised roads but left homes below water level, worsening vulnerability.
  </p>

  <div class="quote">
    “Kapag nilapit pa namin sa gobyerno, wala… pangangakuan ka lang,” a resident lamented.
  </div>

  <p>
    True resilience should not mean accepting failure, but demanding accountability and long-term solutions.
  </p>
</section>

<!-- ================= BREAKING 1 ================= -->
<section class="article" id="news1">
  <div class="tag">Breaking News</div>
  <h2>Heat Index in Bulacan Reaches Danger Zone; Jeepney Drivers Struggle</h2>
  <div class="meta">April 18, 2026 • Micaela Cruz</div>

  <img src="jeepney.jpg" alt="Jeepney Driver Heat">

  <p>
    Bulacan has officially reached the “Danger Zone” heat index level, posing health risks such as heat stroke and exhaustion.
  </p>

  <p>
    Despite extreme conditions, jeepney drivers continue working to provide for their families.
  </p>

  <div class="quote">
    “Kailangan magtiyaga, para sa pamilya,” said driver Francisco Domingo.
  </div>

  <p>
    Drivers endure long trips from Meycauayan to Malolos despite hours of exposure to extreme heat.
  </p>
</section>

<!-- ================= BREAKING 2 ================= -->
<section class="article" id="news2">
  <div class="tag">Breaking News</div>
  <h2>BulSU Students Struggle With Extreme Heat Inside Campus</h2>
  <div class="meta">Millie Bordaje</div>

  <img src="bulsu.jpg" alt="BulSU Students Heat">

  <p>
    Students at Bulacan State University are experiencing severe heat conditions affecting focus and health.
  </p>

  <p>
    Limited cooling facilities and overcrowded classrooms worsen the situation.
  </p>

  <div class="quote">
    “Kahit naka-aircon, hindi sapat kasi sobrang dami namin,” a student shared.
  </div>

  <p>
    Some students have reported dizziness and even fainting due to extreme heat inside classrooms.
  </p>
</section>

</div>

<footer>
  <p>© 2026 Campus & Community Newsroom</p>
</footer>

</body>
</html>
