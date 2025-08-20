<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Dyota - Rass Ladi Dandiya Night</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: Arial, sans-serif; line-height: 1.6; color: #333; }
    header {
      background: url('dandiya-background.jpg') no-repeat center center/cover;
      color: white;
      text-align: center;
      padding: 100px 20px;
      background-blend-mode: multiply;
      background-color: rgba(255, 0, 0, 0.6);
    }
    header h1 { font-size: 3em; }
    header p { font-size: 1.3em; margin-top: 10px; }
    section { padding: 40px 20px; max-width: 1000px; margin: auto; }
    .tickets a {
      display: inline-block;
      margin: 10px;
      padding: 10px 20px;
      background: red;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }
    .sponsors { display: flex; gap: 20px; flex-wrap: wrap; justify-content: center; }
    .sponsor-card {
      border: 1px solid #ccc;
      padding: 20px;
      background: white;
      border-radius: 10px;
      text-align: center;
      width: 200px;
    }
    footer {
      background: #f1f1f1;
      padding: 20px;
      text-align: center;
      font-size: 0.9em;
    }
    @media (max-width: 600px) {
      header h1 { font-size: 2em; }
      .sponsors { flex-direction: column; align-items: center; }
    }
  </style>
</head>
<body>

  <header>
    <h1>Dyota – Rass Ladi</h1>
    <p>Karnataka’s Biggest Dandiya Night in Bangalore</p>
  </header>

  <section id="about">
    <h2>About the Event</h2>
    <p>Join us for a night of joy, music, and dance at Dyota’s Rass Ladi – the grandest Dandiya Night in Bangalore! With cultural performances, corporate engagement, and a vibrant musical fest, this is a celebration you won't want to miss.</p>
  </section>

  <section id="tickets" class="tickets">
    <h2>Get Your Tickets</h2>
    <a href="https://bookmyshow.com" target="_blank">Book via BookMyShow</a>
    <a href="https://your-custom-ticket-link.com" target="_blank">Book via Personal Link</a>
  </section>

  <section id="sponsors">
    <h2>Our Sponsors</h2>
    <div class="sponsors">
      <div class="sponsor-card">Indian Sweet House</div>
      <div class="sponsor-card">Aadishwara Home Appliances</div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>For inquiries or bulk bookings:</p>
    <p><strong>Phone:</strong> <a href="tel:+918861983428">+91 88619 83428</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Dyota Events. All Rights Reserved.</p>
  </footer>

</body>
</html>
