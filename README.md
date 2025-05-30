✅ Navigation is now sticky and scrolls with the page.
✅ "About the Show" section has been added with a clear mission and voice.

Next options:

* 🎥 Add a **“Watch Now”** section (YouTube embed, teaser trailer, or episode thumbnails)?
* 📸 Embed social media (Instagram/TikTok grid)?
* 📧 Add a newsletter sign-up or “Contact Us”?

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mothers in the Making</title>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'DM Sans', sans-serif;
      margin: 0;
      background-color: #f9f5f0;
      color: #222;
    }
    nav {
      position: sticky;
      top: 0;
      background-color: #fff;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 1rem;
      z-index: 1000;
    }
    nav a {
      text-decoration: none;
      color: #222;
      font-weight: 700;
    }
    nav a:hover {
      color: #d946ef;
    }
    header {
      background-color: #000;
      color: #fff;
      padding: 2rem 1rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    .intro {
      text-align: center;
      padding: 1rem 2rem;
      font-size: 1.2rem;
      max-width: 700px;
      margin: auto;
    }
    .cast-section {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2rem;
      padding: 2rem;
    }
    .cast-card {
      background-color: #fff;
      padding: 1.5rem;
      border-radius: 1.5rem;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    .cast-card h2 {
      margin-top: 0;
      font-size: 1.4rem;
      color: #d946ef;
    }
    .cast-card h3 {
      margin: 0.25rem 0 1rem;
      font-size: 1.1rem;
      font-weight: normal;
      color: #666;
    }
    .cast-card p {
      font-size: 1rem;
      line-height: 1.5;
    }
    .cast-quote {
      margin-top: 1rem;
      font-style: italic;
      color: #444;
    }
    .about-section {
      padding: 2rem;
      background-color: #fff0fa;
      text-align: center;
    }
    .about-section h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }
    .about-section p {
      font-size: 1.1rem;
      max-width: 700px;
      margin: auto;
    }
    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }
      nav {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>
  <nav>
    <a href="#home">Home</a>
    <a href="#family">Family</a>
    <a href="#about">About the Show</a>
    <a href="#watch">Watch Now</a>
  </nav>

  <section id="home">
    <header>
      <h1>Mothers in the Making</h1>
      <p class="intro"><strong>Five voices. Five journeys. One unapologetic truth.</strong><br />
      <em>Mothers in the Making</em> brings together young parents and creators navigating motherhood, healing, and hustle in real time.</p>
    </header>
  </section>

  <section class="intro" style="text-align:center; padding: 0 2rem 2rem;">
    <h2 style="font-size: 2rem; margin-bottom: 0.5rem;">Meet the Family</h2>
    <p style="font-size: 1.1rem; max-width: 700px; margin: auto;">This isn't just a cast — it's a chosen family. United by resilience, creativity, and the love they have for their kids, these five show us what it means to mother on your own terms.</p>
  </section>

  <section id="family" class="cast-section">
    <div class="cast-card">
      <h2>Tee</h2>
      <h3>Digital Boss. New Mom. Spiritual Oracle.</h3>
      <p>Tee’s intuition runs deep — both online and off. With a newborn in one hand and a phone in the other, she’s building her platform while guiding her sisters through spiritual awakening and self-worth.</p>
      <p class="cast-quote">“Motherhood didn’t slow me down — it unlocked my purpose.”</p>
    </div>

    <div class="cast-card">
      <h2>Pedro</h2>
      <h3>Leo Dad. Stand-Up King. Father of a Teen.</h3>
      <p>Pedro’s presence is loud, proud, and full of punchlines — but his love runs even deeper. As the only dad in the crew, he’s redefining Black fatherhood while balancing gigs and guidance.</p>
      <p class="cast-quote">“I’m raising a man while becoming one — laugh with me or get left.”</p>
    </div>

    <div class="cast-card">
      <h2>Ro</h2>
      <h3>Hairstylist. Fashion CEO. Divine Vibes Only.</h3>
      <p>Ro’s chair is her therapy couch — and her clients leave feeling blessed. She’s crafting a legacy through hair, style, and softness, with a sharp eye for beauty and a heart full of intention.</p>
      <p class="cast-quote">“I don’t just style hair, I restore crowns.”</p>
    </div>

    <div class="cast-card">
      <h2>Big Za</h2>
      <h3>Gemini Energy. Influencer-in-Training. No Filter.</h3>
      <p>Big Za is raw, real, and rising. Whether she’s filming reels or calling out red flags, her voice hits hard and her vibe is unmatched. She’s learning the ropes of influence while staying true to herself.</p>
      <p class="cast-quote">“I’m not for everybody — but I’m definitely for <em>somebody</em>.”</p>
    </div>

    <div class="cast-card">
      <h2>Sed</h2>
      <h3>Capricorn Clown. Relentless Hustler. Healing Loudly.</h3>
      <p>Behind every joke is a truth Sed is still facing. She’s chasing bags, cracking jokes, and confronting trauma head-on — because being a mother doesn’t mean hiding your pain.</p>
      <p class="cast-quote">“If I don’t laugh, I’ll cry. And sometimes, I do both.”</p>
    </div>
  </section>

  <section id="about" class="about-section">
    <h2>About the Show</h2>
    <p><em>Mothers in the Making</em> is more than reality — it’s revelation. This show centers the stories of young Black and Brown parents choosing motherhood, creativity, and healing while rewriting the narrative. It's raw, funny, spiritual, and real — just like the community it represents.</p>
  </section>
</body>
</html>
