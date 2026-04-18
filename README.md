<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Oil Price Hike & OFW Crisis | Sojourner News</title>

  <!-- Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&family=Merriweather:ital,wght@0,300;0,400;0,700;0,900;1,400&display=swap" rel="stylesheet" />

  <!-- FontAwesome for Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

  <style>
    /* ===== Brand Palette ===== */
    :root {
      --primary: #252958;
      --accent:  #E2841C;
      --white:   #FDFDFD;
      --light-bg:#F6F7FA;
      --text-dark:#1A1A1A;
      --text-grey:#666A75;
      --border:  #E2E5EF;
    }

    .brand-logo { height: 60px; width: auto; }
    
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body { font-family: 'Inter', sans-serif; background-color: var(--white); color: var(--text-dark); line-height: 1.6; }
    h1, h2, h3, h4, h5 { font-family: 'Merriweather', serif; color: var(--primary); }
    a { text-decoration: none; color: inherit; }
    ul { list-style: none; }

    /* Top Bar */
    .top-bar { background-color: var(--primary); color: var(--white); font-size: 0.8rem; padding: 0.5rem 0; text-align: center; display: flex; justify-content: center; gap: 20px; }
    .top-bar span { cursor: pointer; }
    .top-bar span:hover { color: var(--accent); }

    /* Header */
    header { background: var(--white); padding: 1rem 0; border-bottom: 1px solid var(--border); position: sticky; top: 0; z-index: 1000; box-shadow: 0 2px 10px rgba(0,0,0,0.05); }
    .header-container { max-width: 1200px; margin: 0 auto; padding: 0 1rem; display: flex; justify-content: space-between; align-items: center; }
    .header-actions button { background: var(--primary); color: var(--white); border: none; padding: 0.6rem 1.2rem; font-weight: 600; cursor: pointer; border-radius: 4px; transition: background 0.3s; }
    .header-actions button:hover { background: var(--accent); }

    /* Navigation */
    nav { background: var(--white); border-bottom: 3px solid var(--accent); }
    .nav-container { max-width: 1200px; margin: 0 auto; display: flex; justify-content: center; position: relative; }
    .nav-links { display: flex; gap: 2rem; }
    .nav-links a { display: block; padding: 1rem 0; font-weight: 600; font-size: 0.9rem; text-transform: uppercase; color: var(--text-dark); position: relative; transition: color 0.3s; cursor: pointer; }
    .nav-links a::after { content: ''; position: absolute; bottom: 0; left: 0; width: 0; height: 2px; background: var(--accent); transition: width 0.3s; }
    .nav-links a:hover, .nav-links a.active { color: var(--primary); }
    .nav-links a:hover::after, .nav-links a.active::after { width: 100%; }

    /* Main Layout */
    .container { max-width: 1000px; margin: 2rem auto; padding: 0 1rem; display: grid; grid-template-columns: 1fr; gap: 2rem; }

    /* Article Header */
    .article-header { text-align: center; margin-bottom: 2rem; }
    .category-tag { color: var(--accent); font-weight: 700; text-transform: uppercase; font-size: 0.9rem; letter-spacing: 1px; margin-bottom: 1rem; display: block; }
    .article-header h1 { font-size: 2.5rem; line-height: 1.2; margin-bottom: 1rem; }
    .article-meta { color: var(--text-grey); font-size: 0.9rem; margin-bottom: 1.5rem; }
    .article-meta i { margin-right: 5px; color: var(--accent); }

    /* Hero Image */
    .article-hero-img { width: 100%; height: 500px; object-fit: cover; border-radius: 8px; margin-bottom: 2rem; box-shadow: 0 4px 15px rgba(0,0,0,0.1); }

    /* Article Content */
    .article-content { font-size: 1.1rem; line-height: 1.8; color: var(--text-dark); max-width: 800px; margin: 0 auto; }
    .article-content p { margin-bottom: 1.5rem; }
    .article-content strong { color: var(--primary); }
    .quote { border-left: 4px solid var(--accent); padding-left: 1.5rem; margin: 2rem 0; font-style: italic; color: var(--text-grey); font-size: 1.2rem; }
    .source { margin-top: 2rem; padding-top: 1rem; border-top: 1px solid var(--border); font-weight: 600; color: var(--primary); }

    /* Share Buttons */
    .share-buttons { margin-top: 2rem; display: flex; gap: 10px; }
    .share-btn { padding: 0.5rem 1rem; border: 1px solid var(--border); border-radius: 4px; cursor: pointer; transition: all 0.3s; font-size: 0.9rem; }
    .share-btn:hover { background: var(--primary); color: var(--white); border-color: var(--primary); }

    /* Newsletter */
    .newsletter-box { background: var(--primary); color: var(--white); padding: 2rem; border-radius: 8px; margin-top: 3rem; text-align: center; }
    .newsletter-box h4 { color: var(--white); margin-bottom: 0.5rem; }
    .newsletter-box p { font-size: 0.9rem; margin-bottom: 15px; }
    .newsletter-box input { width: 100%; max-width: 300px; padding: 0.6rem; margin-bottom: 0.5rem; border: none; border-radius: 4px; }
    .newsletter-box button { width: 100%; max-width: 300px; background: var(--accent); color: var(--white); border: none; padding: 0.6rem; font-weight: bold; border-radius: 4px; cursor: pointer; transition: background 0.3s; }
    .newsletter-box button:hover { background: #c87112; }

    /* SECOND ARTICLE - WHITE THEME */

      background: linear-gradient(135deg, var(--primary) 0%, #1e235a 100%) !important; 
      color: var(--white) !important; 
      padding: 3rem 2rem; 
      border-radius: 16px; 
      margin-top: 4rem; 
      box-shadow: 0 20px 40px rgba(37, 41, 88, 0.3);
    }
    .second-article .article-header h1,
    .second-article .article-content,
    .second-article .article-content p,
    .second-article .article-content strong { color: var(--white) !important; }
    .second-article .article-meta { color: rgba(200, 200, 200, 1) !important; }
    .second-article .quote { border-left-color: var(--accent); color: rgba(255,255,255,0.95) !important; }
    .second-article .source { color: rgba(255,255,255,0.9) !important; border-top-color: rgba(255,255,255,0.2); }

    /* Image Captions */
    .image-caption { margin-top: 1rem; padding: 0.8rem; background: rgba(255,255,255,0.1); border-radius: 6px; border-left: 4px solid var(--accent); }
    .image-caption p { font-size: 0.95rem; color: inherit; margin: 0; font-style: italic; }

    /* Footer */
    footer { background: var(--primary); color: var(--white); padding: 3rem 1rem; margin-top: 3rem; text-align: center; }
    .footer-grid { max-width: 1200px; margin: 0 auto; display: flex; justify-content: space-between; flex-wrap: wrap; gap: 2rem; }
    .footer-col h4 { color: var(--accent); margin-bottom: 1rem; }
    .footer-col a { color: #cfd5e6; display: block; margin-bottom: 0.5rem; }
    .footer-col a:hover { color: var(--accent); }
    .copyright { margin-top: 2rem; padding-top: 1rem; border-top: 1px solid rgba(255,255,255,0.1); font-size: 0.9rem; color: #cfd5e6; }

    /* Mobile */
    @media (max-width: 768px) {
      .menu-toggle { display: block; font-size: 1.5rem; cursor: pointer; color: var(--primary); }
      .nav-links { display: none; position: absolute; top: 100%; left: 0; width: 100%; background: var(--white); flex-direction: column; border-bottom: 1px solid var(--border); box-shadow: 0 5px 10px rgba(0,0,0,0.1); z-index: 999; }
      .nav-links.show { display: flex; }
      .nav-links a { padding: 1rem; border-bottom: 1px solid #eee; }
      .article-header h1 { font-size: 1.8rem; }
      .article-hero-img { height: 250px; }
    }
  </style>
</head>
<body>

  <!-- Top Info Bar -->
  <div class="top-bar">
    <span id="current-date"></span>
    <span>Manila, PH: 88°F</span>
    <span onclick="scrollToSubscribe()">Subscribe</span>
    <span>Login</span>
  </div>

  <!-- Header -->
  <header>
    <div class="header-container">
      <img src="sojourne.jpeg" alt="Sojourner News Logo" class="brand-logo">
      <div class="header-actions">
        <i class="fas fa-bars menu-toggle" onclick="toggleMenu()"></i>
        <button onclick="scrollToSubscribe()">Subscribe</button>
      </div>
    </div>
  </header>

  <!-- Navigation -->
  <nav>
    <div class="nav-container">
      <div class="nav-links" id="nav-links">
        <a href="#" onclick="filterCategory('all')" class="active">Home</a>
        <a href="#">World</a>
        <a href="#">Business</a>
        <a href="#">Economy</a>
        <a href="#">Politics</a>
        <a href="#">Community</a>
        <a href="#">Sports</a>
      </div>
    </div>
  </nav>

  <!-- Main Content -->
  <div class="container">
    
    <!-- 🔥 FIRST ARTICLE - Oil Price Hike 🔥 -->
    <header class="article-header">
      <span class="category-tag">Economy & Transportation</span>
      <h1> 5k fuel subsidy of LTFRB, DSWD vs. continues petroleum crisis</h1>
      <div class="article-meta">
        <span><i class="far fa-clock"></i> March 21, 2026</span> &nbsp;|&nbsp; 
        <span><i class="far fa-user"></i> By Princess Louise Gonzales and Micaela Cruz</span>
      </div>
    </header>

    <img src="GasStation.jpg" alt="Oil Price Hike Philippines" class="article-hero-img">

    <article class="article-content">
      <p>As gasoline prices continue to surge due to the ongoing petroleum crisis triggered by the war between Israel, Iran, and the United States, <strong>Public Utility Vehicle (PUV) drivers and commuters</strong> remain the most affected sectors in the Philippines.</p>

      <!-- Driver Image -->
      <div style="text-align: center; margin: 2rem 0;">
        <img src="TrycDriver.jpg" alt="PUV Driver Kenneth Medina" style="width: 100%; max-width: 600px; height: 350px; object-fit: cover; border-radius: 8px; box-shadow: 0 4px 15px rgba(0,0,0,0.1);">
        <div class="image-caption">
          <p><i class="fas fa-camera"></i> Kenneth Medina, VP of MXM Toda</p>
        </div>
      </div>

      <p>To ease the burden on motorists, the Land Transportation Franchising and Regulatory Board (LTFRB) has mandated PUV operators to list the names of their subordinates under their Regional Franchising and Regulatory Office (RFRO) to qualify them for a <strong>₱5,000 fuel subsidy</strong>.</p>

      <blockquote class="quote">"Pwede na rin. Kaya wala, malaking tulong na rin iyon para sa amin—pandagdag gastusin," said Kenneth Medina.</blockquote>

      <!-- Commuter Image -->
      <div style="text-align: center; margin: 2rem 0;">
        <img src="Commuter.jpg" alt="Student Commuter Raylee Sunga" style="width: 100%; max-width: 600px; height: 350px; object-fit: cover; border-radius: 8px; box-shadow: 0 4px 15px rgba(0,0,0,0.1);">
        <div class="image-caption">
          <p><i class="fas fa-camera"></i> Student commuter Raylee Sunga sharing his sentiments on oil price hikes</p>
        </div>
      </div>

      <p>According to Global Trading petroleum products, <strong>diesel prices are set to rise by up to ₱14.50 per liter next week</strong> from the current ₱14. Gasoline is also expected to increase from ₱7 to ₱7.50 per liter.</p>

      <div class="source">Sojourner News | Manila, Philippines</div>
      <div class="share-buttons">
        <div class="share-btn"><i class="fab fa-facebook-f"></i> Share</div>
        <div class="share-btn"><i class="fab fa-twitter"></i> Tweet</div>
        <div class="share-btn"><i class="fab fa-linkedin-in"></i> Share</div>
      </div>
    </article>

    <!-- Newsletter -->
    <div class="newsletter-box" id="newsletter">
      <h4>Subscribe to Sojourner News</h4>
      <p>Get breaking news on economy, community, and global affairs.</p>
      <form onsubmit="handleSubscribe(event)">
        <input type="email" placeholder="Your email address" required />
        <button type="submit">Subscribe Now</button>
      </form>
</div>

    <!-- 🔥 SECOND ARTICLE - WHITE THEME 🔥 -->
<h2 style="text-align:center; margin-top: 4rem; color: var(--text-grey); letter-spacing: 2px;">
  FEATURE STORY
</h2>
    <div class="second-article" style="margin-top: 4rem; padding-top: 3rem; border-top: 3px solid var(--accent);">
      <header class="article-header">
        <span class="category-tag">Community</span>
        <h1>Malolos Provides P10,000 Subsidy for Affected OFW Families in Middle East Conflict</h1>
       <div class="article-meta" style="color: rgba(80,80,80,1);">
  <span><i class="far fa-clock"></i> March 16, 2025</span> &nbsp;|&nbsp; 
  <span><i class="far fa-user"></i> By Jannes Magayon and Samantha Castillo</span>
</div>
    </header>
      </header>

      <img src="ofw.jpg" alt="Malolos OFW Help Desk" class="article-hero-img">

      <article class="article-content">
        <p>With the ongoing conflict in the Middle East, the city government of Malolos dispensed a <strong>₱10,000 financial subsidy</strong> for Overseas Filipino Workers (OFW) unable to return home or send money to their families.</p>

        <p>The city officials created a <strong>"Special Help Desk"</strong> serving as an office in Malolos Municipality for OFW beneficiaries, providing aid from the city's "Extraordinary funds" to more than <strong>127 OFW relatives</strong>.</p>

        <p>According to city Mayor Christian Natividad, aside from financial help, the Local Government Unit (LGU) will also assist OFWs wishing to return home but not covered by the national government's repatriation program.</p>

        <blockquote class="quote">"Talagang mahirap, hindi siya nakakalabas. Sa padala, mahirap. Sobrang hirap. Talagang, kaming pamilya, kami na lang gumagawa ng paraan."</blockquote>

        <!-- Roxanne Cruz Image -->
  <div style="text-align: center; margin: 2.5rem 0;">
  <img src="citizen.jpg" alt="Roxanne Cruz OFW Family" 
       style="width: 100%; max-width: 650px; height: 400px; object-fit: cover; border-radius: 12px; box-shadow: 0 6px 20px rgba(255,255,255,0.2);">
  
  <div class="image-caption">
    <p><i class="fas fa-quote-left"></i> 
      <strong>Roxanne Cruz, one of the affected families with the ongoing Middle East Crisis</strong><br>
      <small>Photo by Samantha Castillo</small>
    </p>
  </div>
</div>

        <p>Roxanne Cruz, a Malolos resident whose mother works in Riyadh, Saudi Arabia, shared the emotional and financial toll: <em>"Ayun nga po, masyadong nangangamba. Medyo natatakot din po kami bilang pamilya niya dito. Nag-aalert, ganon. Mismo narinig niya yung pinaka bomba… Siya lang mag-isa, talagang ngambang-ngamba na kami."</em></p>

        <p>Mayor Natividad reiterated the city's commitment to continue assistance as the OFW help desk remains operational for affected families.</p>

        <div class="source">Malolos, Bulacan | Sojourner News</div>

        <div class="share-buttons">
          <div class="share-btn"><i class="fab fa-facebook-f"></i> Share</div>
          <div class="share-btn"><i class="fab fa-twitter"></i> Tweet</div>
          <div class="share-btn"><i class="fab fa-linkedin-in"></i> Share</div>
        </div>
      </article>
    </div>

  </div> <!-- End Container -->

  <!-- Footer -->
  <footer>
    <div class="footer-grid">
      <div class="footer-col">
        <h4>SojournerNews</h4>
        <p style="color: #cfd5e6; font-size: 0.9rem;">
          Delivering global perspectives with integrity and depth.
        </p>
      </div>
      <div class="footer-col">
        <h4>Sections</h4>
        <a href="#">World</a>
        <a href="#">Business</a>
        <a href="#">Economy</a>
        <a href="#">Politics</a>
        <a href="#">Community</a>
      </div>
      <div class="footer-col">
        <h4>About</h4>
        <a href="#">Our Story</a>
        <a href="#">Careers</a>
        <a href="#">Contact</a>
      </div>
      <div class="footer-col">
        <h4>Follow Us</h4>
        <a href="#"><i class="fab fa-facebook"></i> Facebook</a>
        <a href="#"><i class="fab fa-twitter"></i> Twitter</a>
        <a href="#"><i class="fab fa-instagram"></i> Instagram</a>
      </div>
    </div>
    <div class="copyright">
      &copy; 2026 SojournerNews. All Rights Reserved.
    </div>
  </footer>

  <script>
    // Set Current Date
    const dateElement = document.getElementById('current-date');
    const options = { weekday: 'long', year: 'numeric', month: 'long', day: 'numeric' };
    dateElement.textContent = new Date().toLocaleDateString('en-US', options);

    // Toggle Mobile Menu
    function toggleMenu() {
      const navLinks = document.getElementById('nav-links');
      navLinks.classList.toggle('show');
    }

    // Scroll to Subscribe
    function scrollToSubscribe() {
      document.getElementById('newsletter').scrollIntoView({ behavior: 'smooth' });
    }

    // Handle Newsletter Subscribe
    function handleSubscribe(event) {
      event.preventDefault();
      const email = event.target.querySelector('input').value;
      alert('Thank you for subscribing to Sojourner News!\nYou\'ll receive breaking news updates straight to your inbox.\n\nEmail: ' + email);
      event.target.reset();
    }

    // Filter Category (placeholder)
    function filterCategory(category) {
      alert('Filtering ' + category + ' articles...');
    }
  </script>
