# gym.point
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gym Point </title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: gray;
    }
    header {
      background: linear-gradient(to right, #ff512f, #dd2476);
      color: white;
      text-align: center;
      padding: 0px 0px;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
    }
    nav {
      background: #333;
      display: flex;
      justify-content: center;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
      display: inline-block;
    }
    nav a:hover {
      background: #555;
    }
    section {
      padding: 40px 20px;
      text-align: center;
    }
    .classes {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }
    .class-card {
      background: #ffecec;
      border-radius: 10px;
      padding: 20px;
      width: 220px;
      box-shadow: 0px 4px 6px rgba(0,0,0,0.1);
    }
    .class-card h3 {
      margin-bottom: 10px;
      color: #dd2476;
    }
    /* About collapsible */
    .collapsible {
      background: #dd2476;
      color: white;
      cursor: pointer;
      padding: 14px;
      width: 200px;
      border: none;
      border-radius: 5px;
      text-align: center;
      outline: none;
      font-size: 16px;
      margin: 10px auto;
      display: block;
    }
    .active, .collapsible:hover {
      background-color: #ff512f;
    }
    .content {
      padding: 15px;
      display: none;
      background-color: #f9f9f9;
      border: 1px solid #ddd;
      border-radius: 8px;
      width: 80%;
      margin: auto;
    }
  </style>
</head>
<body>
  <header>
    <h1>Gym Point</h1>
    <p>Owned & Managed by Ankit Vishwakarma</p>
    <p>Train Hard, Stay Fit, Live Strong</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#classes">Classes</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- About Section with collapsible -->
  <section id="about">
    <h2>About Us</h2>
      <p>Welcome to Gym Point! We provide world-class fitness training programs 
      including Strength Training, Cardio, Yoga, Zumba, and CrossFit. 
      Our certified trainers ensure that you stay motivated, disciplined, 
      and achieve your fitness goals effectively.</p>
      <p>We believe in holistic fitness combining physical strength, stamina, and mental peace.</p>

  </section>

  <!-- Classes -->
  <section id="classes">
    <h2>Our Classes & Timings</h2>
    <div class="classes">
      <div class="class-card">
        <h3>Strength Training</h3>
        <p>Build muscles and improve endurance.</p>
        <p><b>Time:</b> 6:00 AM - 8:00 AM</p>
      </div>
      <div class="class-card">
        <h3>Cardio</h3>
        <p>Boost stamina and burn calories.</p>
        <p><b>Time:</b> 8:00 AM - 9:00 AM</p>
      </div>
      <div class="class-card">
        <h3>Yoga</h3>
        <p>Increase flexibility and peace of mind.</p>
        <p><b>Time:</b> 5:00 PM - 6:00 PM</p>
      </div>
      <div class="class-card">
        <h3>Zumba</h3>
        <p>Enjoy fitness with fun music beats.</p>
        <p><b>Time:</b> 6:00 PM - 7:00 PM</p>
      </div>
      <div class="class-card">
        <h3>CrossFit</h3>
        <p>Challenge your body with dynamic exercises.</p>
        <p><b>Time:</b> 7:00 PM - 8:00 PM</p>
      </div>
    </div>
  </section>

  <!-- Gallery -->
  <section id="gallery">
    <h2>Gallery</h2>
    <p>Photos of our gym, trainers, and fitness events will be showcased here.</p>
    <img src="image1.jpeg" alt="image1" style="width: 200px; margin:20px; border-radius:10px;">
    <img src="image2.jpeg" alt="image2" style="width: 200px; margin:20px; border-radius:10px;">
    <img src="image3.jpeg" alt="image3" style="width: 200px; margin:20px; border-radius:10px;">
  </section>

  <!-- Contact -->
  <section id="contact">
    <h2>Contact Us</h2>
    <p><b>Email:</b> ankitvishwakarma6181@aksuniversity.com</p>
    <p><b>Phone:</b>+91 8349715412</p>
    <p><b>Address:</b> Satna, Pateri, Madhya Pradesh, India</p>
  </section>

  
    
  </script>
</body>
</html>
