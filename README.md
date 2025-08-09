<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Sifat Bhatia - About Me</title>
  <style>
    /* Minimal but slightly convoluted styles */
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #111, #444);
      color: #eee;
      display: grid;
      grid-template-columns: minmax(200px, 1fr) 3fr;
      height: 100vh;
      gap: 2rem;
      padding: 2rem;
    }
    aside {
      background: #222;
      border-radius: 12px;
      padding: 1.5rem;
      display: flex;
      flex-direction: column;
      gap: 1rem;
      text-align: center;
      filter: drop-shadow(0 0 6px #56CCF2);
    }
    aside img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 3px solid #56ccf2;
      filter: drop-shadow(0 0 10px #56ccf2);
      margin: 0 auto;
      object-fit: cover;
    }
    aside h2 {
      margin: 0;
      font-weight: 600;
      letter-spacing: 2px;
      color: #56ccf2;
      text-transform: uppercase;
    }
    main {
      background: #222;
      border-radius: 12px;
      padding: 2rem;
      box-shadow: 0 0 15px #222 inset;
      overflow-y: auto;
      line-height: 1.6;
      font-size: 1.15rem;
      position: relative;
    }
    main h1 {
      font-weight: 700;
      border-bottom: 2px solid #56ccf2;
      padding-bottom: 0.5rem;
      margin-top: 0;
      text-transform: uppercase;
      letter-spacing: 1.5px;
    }
    main p {
      margin-top: 1rem;
    }
    main .highlight {
      color: #56ccf2;
      font-weight: 700;
      font-style: italic;
      background: rgba(86, 204, 242, 0.3);
      padding: 0 4px;
      border-radius: 4px;
    }
    /* subtle floating cat emoji animation */
    .cat-emoji {
      position: absolute;
      right: 1rem;
      bottom: 1rem;
      font-size: 3rem;
      animation: float 4s ease-in-out infinite;
      filter: drop-shadow(1px 1px 2px #000);
    }
    @keyframes float {
      0%, 100% { transform: translateY(0) rotate(0deg);}
      50% { transform: translateY(-10px) rotate(10deg);}
    }
  </style>
</head>
<body>
  <aside>
    <img src="https://avatars.githubusercontent.com/u/yourGitHubID?v=4" alt="Sifat Bhatia"/>
    <h2>SIFAT BHATIA</h2>
    <div>Full-stack Developer</div>
    <div>React, Tailwind, UI Animation</div>
    <div>Based in East LA 🌴</div>
  </aside>
  <main>
    <h1>About Me</h1>
    <p>Hey there! I'm <span class="highlight">Sifat Bhatia</span>, a casual but passionate full-stack web developer diving deep into <span class="highlight">React</span> and <span class="highlight">Tailwind CSS</span>. I’m on a journey to up my UI animation skills while embracing my love for <span class="highlight">tech</span>, <span class="highlight">cats</span> 🐱, and the quirky side of <span class="highlight">UX psychology</span>.</p>
    <p>Currently studying at Los Angeles City College (not too seriously 😅) and looking for a steady front-end role where I can bring ideas to life with smooth, appealing interfaces.</p>
    <p>When not coding, you’ll find me pondering user behavior or chilling with my feline friends.</p>
    <p>Let’s connect and make the web a more delightful place!</p>
    <div class="cat-emoji" aria-label="cat emoji" role="img">🐈‍⬛</div>
  </main>
</body>
</html>
