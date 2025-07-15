<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Zyxion Interactive</title>
  <style>
    :root {
      --dark-blue: #183b56;
      --medium-blue: #2a71a0;
      --light-blue: #81c3e6;
      --white: #ffffff;
      --text-dark: #0f2437;
      --bg-light: #f0f6fb;
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: var(--bg-light);
      color: var(--text-dark);
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }

    header {
      background: linear-gradient(90deg, var(--dark-blue), var(--medium-blue));
      padding: 1rem 2rem;
      color: var(--white);
      font-weight: bold;
      font-size: 1.5rem;
      text-align: center;
      box-shadow: 0 2px 6px rgba(24, 59, 86, 0.7);
    }

    main {
      flex-grow: 1;
      max-width: 900px;
      margin: 2rem auto;
      padding: 0 1rem 3rem 1rem;
    }

    h1, h2, h3 {
      color: var(--dark-blue);
      margin-bottom: 0.6rem;
      text-align: center;
    }

    h1 {
      font-size: 2.8rem;
    }

    h2 {
      font-size: 2rem;
      margin-top: 2rem;
    }

    p {
      font-size: 1.15rem;
      line-height: 1.7;
      max-width: 700px;
      margin: 1rem auto;
      color: var(--text-dark);
      text-align: center;
    }

    ul {
      max-width: 700px;
      margin: 1rem auto 2rem auto;
      padding-left: 1.3rem;
      color: var(--text-dark);
    }

    a.button {
      display: inline-block;
      background-color: var(--medium-blue);
      color: var(--white);
      padding: 0.8rem 2.2rem;
      border-radius: 9999px;
      text-decoration: none;
      font-weight: 600;
      font-size: 1.15rem;
      transition: background-color 0.3s ease;
      margin: 2rem auto;
    }

    a.button:hover {
      background-color: var(--light-blue);
    }

    footer {
      text-align: center;
      padding: 1rem 2rem;
      font-size: 0.9rem;
      color: var(--dark-blue);
      background-color: var(--bg-light);
      border-top: 1px solid var(--medium-blue);
    }
  </style>
</head>
<body>

<header>
  Zyxion Interactive
</header>

<main>
  <h1>Hello! Welcome on the Zyxion page.</h1>

  <h2>About us</h2>
  <p>Zyxion Interactive is an independent game studio on a mission to create worlds that leave a mark. We craft games that aren’t just played—they’re experienced. From pulse-pounding action to rich storytelling and unique multiplayer adventures, our goal is to build games that stick with you.</p>
  <p>Powered by a passionate team of developers, designers, and storytellers, we push boundaries and blur genres to deliver fresh, next-gen experiences to players around the world. We love to experiment, innovate, and—above all—play.</p>
  <p>Whether it’s an intense shooter, a captivating RPG, or a creative sandbox, gameplay always comes first at Zyxion Interactive.</p>
  <p>We’re gamers who make games. For the community, with the community.</p>
  <p><strong>Play different. Play Zyxion.</strong></p>

  <h2>Projects</h2>
  <p>Here are some projects we are working on.</p>
  <ul>
    <li><strong>Shadow Roleplay:</strong> Our first FiveM made in a dutch theme.</li>
    <li>…:</li>
    <li>…:</li>
  </ul>

  <h2>Join the Discussion</h2>
  <p>Have questions or want to discuss something? Join the conversation in our Discord!</p>

  <h2>Contact</h2>
  <p>Feel free to reach out to us via <a href="https://x.com/Zyxionofficial" target="_blank" rel="noopener noreferrer" style="color: var(--medium-blue); font-weight: 600;">X (Twitter)</a></p>
</main>

<footer>
  &copy; 2025 Zyxion Interactive – All rights reserved.
</footer>

</body>
</html>
