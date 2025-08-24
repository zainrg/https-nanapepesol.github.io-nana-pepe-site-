# https-nanapepesol.io
“Cozy homepage project for Nana Pepe.”
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Nana Pepe's Cozy Corner</title>
<meta name="description" content="Nana Pepe shares her cozy kitchen, baking delights, and knitting adventures.">

<style>
body {
  font-family: 'Georgia', serif;
  background: #fffaf5;
  margin: 0;
  padding: 0;
  color: #4b3b32;
}

header {
  background: linear-gradient(135deg, #f9d5d3, #f7c6a0);
  padding: 40px 20px;
  font-size: 2.8em;
  font-weight: bold;
  color: #3e2c24;
  text-shadow: 1px 1px #fff;
  border-bottom: 4px solid #e1a07a;
  border-bottom-left-radius: 20px;
  border-bottom-right-radius: 20px;
  text-align: center;
}

.container {
  max-width: 1000px;
  margin: 40px auto;
  padding: 20px;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 40px;
}

.card {
  background: #fffdfb;
  border-radius: 20px;
  padding: 20px;
  box-shadow: 0 6px 16px rgba(0,0,0,0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
}

.card:hover {
  transform: translateY(-8px);
  box-shadow: 0 12px 25px rgba(0,0,0,0.15);
}

.card img {
  width: 100%;
  border-radius: 16px;
  margin-bottom: 20px;
  transition: transform 0.3s ease;
}

.card img:hover {
  transform: scale(1.05);
}

.card h3 {
  margin: 0 0 10px;
  font-size: 1.6em;
  color: #5a4339;
}

.card p {
  font-size: 1em;
  line-height: 1.6;
  color: #5e4a3c;
}

footer {
  text-align: center;
  margin: 50px 0;
}

footer a {
  display: inline-block;
  text-decoration: none;
  background: #1DA1F2;
  color: white;
  padding: 14px 28px;
  border-radius: 12px;
  font-weight: bold;
  transition: background 0.3s ease, transform 0.2s ease;
}

footer a:hover {
  background: #0d8ddb;
  transform: scale(1.05);
}

@media (max-width: 768px) {
  .container {
    padding: 10px;
    gap: 25px;
  }

  header {
    font-size: 2.2em;
    padding: 30px 15px;
  }
}
</style>
</head>
<body>

<header>
  Nana Pepe's Cozy Corner
</header>

<div class="container">
  <div class="card">
    <img src="https://i.imgur.com/3v6P6G7.png" alt="Nana Pepe Baking">
    <h3>Baking Love</h3>
    <p>Nana Pepe always has something fresh in the oven. From pies to cookies, her kitchen is full of warmth, joy, and the smell of sweet treats. 🍪🥧</p>
  </div>

  <div class="card">
    <img src="https://i.imgur.com/0wHn6Lh.png" alt="Nana Pepe Knitting">
    <h3>Cozy Evenings</h3>
    <p>When the baking is done, Nana Pepe relaxes by the fireplace with her knitting. Every stitch is made with care, keeping hearts and homes warm. 🧶🔥</p>
  </div>
</div>

<footer>
  <a href="https://x.com/nanapepesol" target="_blank">Follow Nana Pepe on Twitter</a>
</footer>

</body>
</html>
