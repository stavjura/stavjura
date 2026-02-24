## Hi there 👋

<!--
**stavjura/stavjura** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html lang="cs">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>STAV JURA</title>
<style>
body { margin:0; font-family: Arial, sans-serif; }
header { background: url('https://via.placeholder.com/1200x600.png?text=House+Banner') center/cover no-repeat; height: 100vh; color: white; display:flex; flex-direction:column; justify-content:center; align-items:center; text-align:center; }
header h1 { font-size:4em; margin:0; text-shadow:2px 2px 5px rgba(0,0,0,0.7); opacity:0; animation: fadeIn 2s forwards 1s; transform: scale(0.8); }
header img { width:120px; margin-bottom:20px; opacity:0; transform:translateY(-50px); animation: slideFadeScale 2s forwards; }
@keyframes fadeIn { to { opacity:1; transform: scale(1); } }
@keyframes slideFadeScale { to { opacity:1; transform: translateY(0) scale(1); } }
nav { background:#003366; padding:10px 0; text-align:center; }
nav a { color:white; margin:0 15px; text-decoration:none; font-weight:bold; }
section { padding:50px 20px; max-width:1200px; margin:auto; }
.services { display:flex; flex-wrap:wrap; justify-content:space-around; }
.service { flex:1 1 250px; margin:20px; padding:20px; background:#f2f2f2; border-radius:10px; text-align:center; }
footer { background:#003366; color:white; text-align:center; padding:20px; }
.contact-info { line-height:1.8; }
@media(max-width:768px){ .services { flex-direction:column; } }
</style>
</head>
<body>

<header>
  <img src="https://via.placeholder.com/120.png?text=Logo" alt="STAV JURA">
  <h1>STAV JURA</h1>
  <p>Příjemný domov s profesionálním přístupem</p>
</header>

<nav>
  <a href="#about">O nás</a>
  <a href="#services">Služby</a>
  <a href="#projects">Projekty</a>
  <a href="#contact">Kontakt</a>
</nav>

<section id="about">
  <h2>O nás</h2>
  <p>Jura – váš super-zedník s dlouholetou zkušeností v budování domů a komerčních projektů.</p>
</section>

<section id="services">
  <h2>Služby</h2>
  <div class="services">
    <div class="service"><h3>Stavba domů</h3><p>Kvalitní rodinné i moderní domy.</p></div>
    <div class="service"><h3>Rekonstrukce</h3><p>Profesionální renovace a přestavby.</p></div>
    <div class="service"><h3>Design a projekty</h3><p>Navrhneme moderní interiér i exteriér.</p></div>
    <div class="service"><h3>Komerční stavby</h3><p>Budovy pro podnikání a investice.</p></div>
  </div>
</section>

<section id="projects">
  <h2>Projekty</h2>
  <p>Ukázky našich dokončených staveb a realizací.</p>
</section>

<section id="contact">
  <h2>Kontakt</h2>
  <div class="contact-info">
    <p>Telefon: 608922114</p>
    <p>Email: <a href="mailto:jurastav@seznam.cz" style="color:#003366;">jurastav@seznam.cz</a></p>
    <p>IČO: 06537472</p>
  </div>
</section>

<footer>
  &copy; 2026 STAV JURA | Všechna práva vyhrazena
</footer>

</body>
</html>
