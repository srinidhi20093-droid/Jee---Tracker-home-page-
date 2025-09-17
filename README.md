# Jee---Tracker-home-page-
I ve built a homepage for Jee-Tracker as my grade 12 and I am working on it.
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>JEE Tracker</title>
    <style>
      body {
        margin: 0;
        font-family: Arial, sans-serif;
      }

      .Sign-in {
        position: absolute;
        top: 10px;
        right: 120px;
        font-family: arial;
        background-color: rgb(252, 245, 245);
        color: rgb(0, 0, 0);
        width: 100px;
        height: 36px;
        border-color: rgb(0, 0, 0);
        cursor: pointer;
        transition: opacity 0.5s;
      }
      .Sign-in:hover {
        opacity: 0.5;
      }
      .Get-roadmap {
        position: absolute;
        top: 10px;
        right: 10px;
        font-family: arial;
        background-color: rgb(252, 245, 245);
        color: rgb(0, 0, 0);
        width: 100px;
        height: 36px;
        border-color: rgb(0, 0, 0);
        cursor: pointer;
        transition: opacity 0.5s;
      }
      .Get-roadmap:hover {
        opacity: 0.5;
      }

      .side {
        position: absolute;
        top: 0px;
        left: 0px;
        height: 50px;
        width: 50px;
        background-color: rgb(252, 245, 245);
        transition: opacity 0.5s;
        cursor: pointer;
      }
      .side:hover {
        opacity: 0.5;
      }
      .imag {
        height: 400px;
        width: 640px;
        object-fit: cover;
        position: absolute;
        top: 55px;
        left: 50px;
        object-position: bottom;
        margin-right: 40px;
        transition: opacity 0.5s;
      }
      .imag:hover {
        width: 600px;
        height: 380px;
        opacity: 0.8;
      }
      .intro {
        font-size: 23px;
        font-weight: bolder;
        font-family: Arial;
        position: absolute;
        top: 75px;
        right: 90px;
      }
      .sol {
        font-size: 16px;
        width: 500px;
        line-height: 24px;
        font-family: Arial;
        position: absolute;
        top: 135px;
        right: 100px;
      }
      .join {
        font-size: 18px;
        width: 500px;
        line-height: 24px;
        font-family: arial;
        position: absolute;
        top: 300px;
        right: 95px;
        font-weight: bold;
      }

      /* YOU GOT THIS message */
      .you-got-this {
        position: absolute;
        top: 470px; /* directly below the image */
        left: 50px;
        font-size: 2.5em;
        font-weight: bold;
        background: linear-gradient(90deg, #665c5a, #070506);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        opacity: 0;
        transform: scale(0.8);
        animation: fadeInScale 3s ease-out forwards;
      }

      @keyframes fadeInScale {
        0% {
          opacity: 0;
          transform: scale(0.8);
        }
        50% {
          opacity: 1;
          transform: scale(1.1);
        }
        100% {
          opacity: 1;
          transform: scale(1);
        }
      }

      /* About section */
      .about-title {
        position: absolute;
        top: 600px;
        left: 50px;
        font-size: 26px;
        font-weight: bold;
        color: #333;
      }
      .about-text {
        position: absolute;
        top: 640px;
        left: 50px;
        width: 80%;
        max-width: 700px;
        font-size: 16px;
        line-height: 24px;
        color: #444;
      }
    </style>
  </head>
  <body>
    <button class="side">&#9776; Menu</button>
    <button class="Sign-in">Sign-in</button>
    <button class="Get-roadmap">Get roadmap</button>
    <img class="imag" src=https://images.unsplash.com/photo-1522202176988-66273c2fd55f?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=60" 
     alt="Indian student stressed" />

    <!-- Animated YOU GOT THIS message -->
    <div class="you-got-this">YOU GOT THIS!</div>

    <p class="intro">“Every AIR 1 starts with a plan. What&#39;s yours?”</p>
    <p class="sol">
      The endless chapters, the backlogs, the fear of forgetting everything
      before the exam — it’s overwhelming. The confusion & fear of failing in
      game now has come to an end. Track your syllabus. Build discipline. Crack
      JEE with clarity.
    </p>
    <p class="join">
      Sign-in and get our Free Roadmap to your success journey. Turn your
      efforts into marks — with the right strategies and tools. Remember "You
      got this!".
    </p>

    <!-- About section -->
    <h2 class="about-title">About</h2>
    <p class="about-text">
      JEE preparation is not just about hard work — it iss about clarity,
      consistency, and confidence. This website is built to help students track
      their syllabus, manage backlogs, and study smarter. Instead of feeling
      lost in endless chapters, you will know exactly where you stand and what
      to focus on next. Trust me,I've been in there,but now has come to an end.
      <br /><br />
      Our mission is simple: to turn your daily efforts into visible progress,
      and progress into marks. Because with the right plan and the right
      mindset,
      <b>you got this</b>.
    </p>
  </body>
</html>
