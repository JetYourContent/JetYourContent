<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>ContentJet — AI-Powered Content for Small Business</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background: #f8f9fa;
      color: #222;
    }
    header {
      background: #0c4a6e;
      color: #fff;
      padding: 60px 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    header p {
      font-size: 1.2rem;
      margin-top: 10px;
    }
    section {
      max-width: 800px;
      margin: 40px auto;
      padding: 0 20px;
    }
    .cta-button {
      display: inline-block;
      margin-top: 20px;
      padding: 15px 30px;
      background-color: #10b981;
      color: white;
      text-decoration: none;
      font-weight: bold;
      border-radius: 6px;
    }
    .plans {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    .plan {
      background: white;
      border: 1px solid #ddd;
      padding: 20px;
      border-radius: 8px;
      width: 300px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    }
    .plan h3 {
      margin-top: 0;
      color: #0c4a6e;
    }
    form {
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    }
    input, select, textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0 20px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    footer {
      background: #0c4a6e;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 60px;
    }
  </style>
</head>
<body>

  <header>
    <h1>ContentJet</h1>
    <p>AI-Powered Content. Human Quality.</p>
    <a class="cta-button" href="#form">Get 3 Free Samples</a>
  </header>

  <section>
    <h2>What We Do</h2>
    <p>We create weekly blogs, social media captions, and emails for small businesses — powered by AI, tailored to your industry, and edited by humans. Save time and grow your online presence.</p>
  </section>

  <section>
    <h2>Our Plans</h2>
    <div class="plans">
      <div class="plan">
        <h3>Starter</h3>
        <p>4 blog posts or 8 social posts per month</p>
        <p><strong>£99/month</strong></p>
      </div>
      <div class="plan">
        <h3>Pro</h3>
        <p>4 blogs + 8 social posts + 1 email newsletter + SEO</p>
        <p><strong>£199/month</strong></p>
      </div>
    </div>
  </section>

  <section id="form">
    <h2>Get Free Samples</h2>
    <p>Fill in your details and we’ll send you a free content pack within 24 hours.</p>
    <form action="https://formsubmit.co/YOUR-EMAIL@example.com" method="POST">
      <input type="hidden" name="_captcha" value="false">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="text" name="business" placeholder="Business Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <input type="text" name="industry" placeholder="Industry (e.g. fitness, coaching)" required>
      <select name="tone" required>
        <option value="">Preferred Tone</option>
        <option value="Casual">Casual</option>
        <option value="Professional">Professional</option>
        <option value="Friendly">Friendly</option>
        <option value="Energetic">Energetic</option>
      </select>
      <textarea name="extras" placeholder="Anything specific you'd like? (optional)"></textarea>
      <button type="submit" class="cta-button">Send Me Free Content</button>
    </form>
  </section>

  <footer>
    © 2025 ContentJet. Powered by OpenAI. Built for small business owners.
  </footer>

</body>
</html>
