<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>OnlyFans Manager | Grow & Monetize Your Content</title>
<style>
  /* Reset */
  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }

  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    background: #121212;
    color: #f0f0f0;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
  }

  a {
    color: #1dd1a1;
    text-decoration: none;
  }
  a:hover {
    text-decoration: underline;
  }

  header {
    background: #1e272e;
    padding: 2rem 1rem;
    text-align: center;
  }
  header h1 {
    font-size: 2.5rem;
    margin-bottom: 0.5rem;
  }
  header p {
    font-size: 1.25rem;
    color: #70a1ff;
  }

  main {
    flex: 1;
    padding: 2rem 1rem;
    max-width: 900px;
    margin: 0 auto;
  }

  section {
    margin-bottom: 3rem;
  }

  h2 {
    color: #54a0ff;
    margin-bottom: 1rem;
    border-bottom: 2px solid #54a0ff;
    padding-bottom: 0.3rem;
  }

  ul.services-list {
    list-style: none;
    padding-left: 0;
  }
  ul.services-list li {
    background: #222f3e;
    padding: 1rem;
    margin-bottom: 1rem;
    border-radius: 6px;
  }

  blockquote.testimonial {
    background: #222f3e;
    border-left: 5px solid #10ac84;
    padding: 1rem 1.5rem;
    margin-bottom: 1rem;
    font-style: italic;
  }
  blockquote.testimonial footer {
    margin-top: 0.5rem;
    font-weight: bold;
    color: #10ac84;
  }

  .calendly-container {
    background: #222f3e;
    padding: 2rem 1rem;
    border-radius: 8px;
    max-width: 500px;
    margin: 0 auto;
  }

  footer {
    background: #1e272e;
    text-align: center;
    padding: 1rem;
    font-size: 0.9rem;
  }

  footer a.social-link {
    margin: 0 0.5rem;
    color: #70a1ff;
  }

  @media (max-width: 600px) {
    header h1 {
      font-size: 2rem;
    }
    main {
      padding: 1rem;
    }
  }
</style>
</head>
<body>

<header>
  <h1>Unlock Your OnlyFans Potential</h1>
  <p>Expert Management, Promotion & Content Strategy to Maximize Your Earnings</p>
</header>

<main>
  <section id="services">
    <h2>Our Services</h2>
    <ul class="services-list">
      <li><strong>DM Management:</strong> We handle your messages professionally to keep your fans engaged 24/7.</li>
      <li><strong>Promotion Strategy:</strong> Custom marketing plans tailored to grow your audience fast and sustainably.</li>
      <li><strong>Content Advice:</strong> Tips and ideas on what content sells best and how to keep your subscribers happy.</li>
    </ul>
  </section>

  <section id="testimonials">
    <h2>What Clients Say</h2>
    <blockquote class="testimonial">
      "Thanks to this management team, my subscriber count doubled in just 2 months!" 
      <footer>– Alex P.</footer>
    </blockquote>
    <blockquote class="testimonial">
      "Professional, reliable, and always there when I need help with promo or ideas."
      <footer>– Jamie R.</footer>
    </blockquote>
    <!-- Add more testimonials here -->
  </section>

  <section id="contact">
    <h2>Book a Free Consultation</h2>
    <div class="calendly-container" id="calendly-inline-widget"></div>
  </section>
</main>

<footer>
  <p>Contact us: <a href="mailto:contact@onlyfansmanager.com">contact@onlyfansmanager.com</a></p>
  <p>
    Follow us:
    <a href="https://twitter.com/OnlyFansMgr" class="social-link" target="_blank" rel="noopener">Twitter</a> | 
    <a href="https://instagram.com/OnlyFansMgr" class="social-link" target="_blank" rel="noopener">Instagram</a> | 
    <a href="https://tiktok.com/@OnlyFansMgr" class="social-link" target="_blank" rel="noopener">TikTok</a>
  </p>
  <p>© 2025 OnlyFans Manager. All rights reserved.</p>
</footer>

<!-- Calendly widget script -->
<script src="https://assets.calendly.com/assets/external/widget.js" type="text/javascript" async></script>
<script>
  window.onload = function() {
    Calendly.initInlineWidget({
      url: 'https://calendly.com/your-calendly-username/consultation',
      parentElement: document.getElementById('calendly-inline-widget'),
      prefill: {},
      utm: {}
    });
  };
</script>

</body>
</html>
