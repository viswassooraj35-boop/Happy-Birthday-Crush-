# Happy-Birthday-Crush-

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday Rakhi ❤️</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Great+Vibes&family=Playfair+Display:ital,wght@0,400;0,600;1,400&family=Poppins:wght@300;400;500&display=swap');

* { box-sizing:border-box; margin:0; padding:0; }

body {
  background:linear-gradient(145deg,#fff0f5,#fce1eb,#fff7f9);
  color:#82465e;
  font-family:'Poppins',sans-serif;
  overflow-x:hidden;
  min-height:100vh;
}

.heart {
  position:fixed;
  bottom:-30px;
  animation:floatUp linear infinite;
  opacity:.6;
  pointer-events:none;
  z-index:0;
}

@keyframes floatUp {
  to { transform:translateY(-110vh) rotate(360deg); opacity:0; }
}

.hero {
  min-height:100vh;
  display:flex;
  align-items:center;
  justify-content:center;
  text-align:center;
  padding:30px 20px;
  position:relative;
  z-index:1;
}

.content { max-width:650px; }

.small {
  letter-spacing:5px;
  font-size:11px;
  color:#c47c9b;
  text-transform:uppercase;
}

h1 {
  font-family:'Great Vibes',cursive;
  font-size:clamp(65px,13vw,110px);
  color:#d66c99;
  font-weight:400;
  margin:20px 0;
  text-shadow:0 5px 20px #eeb4ca;
}

.subtitle {
  font-family:'Playfair Display',serif;
  font-size:clamp(17px,4vw,23px);
  font-style:italic;
  line-height:1.8;
  color:#946078;
}

button {
  margin-top:38px;
  border:none;
  border-radius:50px;
  padding:16px 32px;
  background:linear-gradient(120deg,#e88daf,#ce648e);
  color:white;
  font-family:'Poppins',sans-serif;
  font-size:14px;
  letter-spacing:1px;
  cursor:pointer;
  box-shadow:0 8px 25px #d889a966;
  transition:.3s;
}

button:hover { transform:translateY(-4px) scale(1.03); }

.decoration {
  font-size:30px;
  margin:20px;
  animation:pulse 2s infinite;
}

@keyframes pulse {
  50% { transform:scale(1.15); }
}

#surprise {
  display:none;
  position:relative;
  z-index:1;
  padding:75px 20px;
  text-align:center;
  animation:appear 1.5s ease;
}

@keyframes appear {
  from {opacity:0;transform:translateY(35px)}
  to {opacity:1;transform:translateY(0)}
}

.letter {
  max-width:650px;
  margin:35px auto;
  padding:40px 28px;
  background:#ffffffb8;
  border:1px solid #f3c9d8;
  border-radius:24px;
  box-shadow:0 15px 50px #d58aa522;
  line-height:2.1;
  font-size:14px;
}

.letter h2 {
  font-family:'Great Vibes',cursive;
  font-size:53px;
  color:#d66c99;
  font-weight:400;
  margin-bottom:22px;
}

.krishna {
  margin:35px auto;
  max-width:600px;
  font-family:'Playfair Display',serif;
  font-size:19px;
  line-height:2;
  font-style:italic;
  color:#a65e80;
}

footer {
  padding:35px 15px 50px;
  text-align:center;
  font-size:12px;
  color:#ba7b96;
  position:relative;
  z-index:1;
}

#celebration {
  position:fixed;
  inset:0;
  pointer-events:none;
  z-index:5;
  overflow:hidden;
}

@media(max-width:500px) {
  .letter {padding:28px 20px;}
}
</style>
</head>
<body>

<div class="hero">
  <div class="content">
    <div class="decoration">🌷 ✨ 🦋</div>
    <p class="small">A little surprise for someone special</p>
    <h1>Happy Birthday<br>Rakhi</h1>
    <p class="subtitle">
      Today, the world celebrates your existence,<br>
      and somewhere, someone is wishing<br>
      for your happiness. ❤️
    </p>
    <button onclick="openSurprise()">
      Open Your Little Surprise 💌
    </button>
    <p style="margin-top:30px;font-size:12px;color:#bd8ba0">
      Made with warm wishes & a little magic
    </p>
  </div>
</div>

<section id="surprise">
  <div style="font-size:35px">💗 🌸 💗</div>

  <p class="small">A message from the heart</p>

  <div class="letter">
    <h2>Dear Rakhi,</h2>

    <p>
      Wishing you a very Happy Birthday! 🎂
    </p>

    <p>
      May your days be painted with beautiful colours,
      your heart always find reasons to smile,
      and your dreams find their way into reality.
    </p>

    <p>
      You deserve all the happiness and joy in the world.
      Never stop being the wonderful person you are.
      Keep shining, keep smiling, and keep making
      the world a little more beautiful just by being you.
    </p>

    <p style="margin-top:20px;color:#d66c99">
      Some people make ordinary moments feel special.
      May life give you countless moments worth remembering.
    </p>

    <p style="margin-top:25px;font-family:'Great Vibes',cursive;font-size:35px;color:#d66c99">
      Stay beautiful, always. ❤️
    </p>
  </div>

  <div class="krishna">
    🦚

    <h2 style="font-family:'Great Vibes',cursive;font-size:48px;font-weight:400;color:#c56d91;margin:15px">
      A little blessing for you
    </h2>

    May Lord Krishna's flute always fill your life
    with the sweetest melodies, endless smiles,
    and peace.

    May His blessings guide your steps,
    protect your happiness, and bring light
    to every chapter of your life.

    <p style="margin-top:25px;font-weight:500">
      Hare Krishna 🙏💙
    </p>
  </div>

  <div style="font-size:27px;margin:30px">
    🌹 🦋 🌹
  </div>

  <button onclick="celebrate()">
    One More Birthday Hug! 💕
  </button>
</section>

<div id="celebration"></div>

<footer>
  Made with a little extra love for Rakhi ❤️<br><br>
  May your year be as beautiful as your smile.
</footer>

<script>
function openSurprise() {
  document.getElementById('surprise').style.display='block';
  document.getElementById('surprise').scrollIntoView({
    behavior:'smooth'
  });
  celebrate();
}

function celebrate() {
  const area=document.getElementById('celebration');
  const symbols=['💗','💕','✨','🌸','🦋','💖'];

  for(let i=0;i<35;i++){
    const item=document.createElement('span');
    item.innerText=symbols[Math.floor(Math.random()*symbols.length)];
    item.style.position='absolute';
    item.style.left=Math.random()*100+'%';
    item.style.top='-30px';
    item.style.fontSize=(15+Math.random()*20)+'px';
    item.style.transition='transform 3s ease-in, opacity 3s';
    area.appendChild(item);

    requestAnimationFrame(()=>{
      item.style.transform=`translateY(${window.innerHeight+80}px) rotate(${Math.random()*500}deg)`;
      item.style.opacity='0';
    });

    setTimeout(()=>item.remove(),3200);
  }
}

for(let i=0;i<22;i++){
  const h=document.createElement('div');
  h.className='heart';
  h.innerText=['♡','♥','✧','🌸'][i%4];
  h.style.left=Math.random()*100+'%';
  h.style.animationDuration=(7+Math.random()*10)+'s';
  h.style.animationDelay=(Math.random()*10)+'s';
  h.style.fontSize=(14+Math.random()*20)+'px';
  document.body.appendChild(h);
}
</script>
</body>
</html>
